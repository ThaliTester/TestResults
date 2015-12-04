#### Test 52539314a265f91_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2977): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2977):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2977):   adb logcat -s GAv4
W/GAv4    ( 2977): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2977): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2977): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2977): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2482): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  758): Killing 2198:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 2977): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2977): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 3021): 
D/AndroidRuntime( 3021): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3021): CheckJNI is OFF
W/libprocessgroup(  758): failed to open /acct/uid_1000/pid_2198/cgroup.procs: No such file or directory
V/JNIHelp ( 2977): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/AndroidRuntime( 3021): Calling main entry com.android.commands.am.Am
W/System  ( 2977): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2977): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  758): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  758): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3048 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3021): Shutting down VM
V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  758): Display changed displayId=0
I/Icing   ( 1600): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1600): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1600): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 3048): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3048): Time to load native libraries: 2 ms (timestamps 5732-5734)
I/LibraryLoader( 3048): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3048): Binding Chromium to main looper Looper (main, tid 1) {1b1feeb2}
I/LibraryLoader( 3048): Expected native library version number "",actual native library version number ""
I/chromium( 3048): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3048): Initializing chromium process, singleProcess=true
W/art     ( 3048): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3048): ApplicationContext is null in ApplicationStatus
W/chromium( 3048): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3048): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3048): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3048): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3048): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27a74347:true
D/BluetoothAdapter( 3048): 294306421: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3048): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3048): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3048): CordovaWebView is running on device made by: LGE
W/art     ( 3048): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3048): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3048): Render dirty regions requested: true
D/Atlas   ( 3048): Validating map...
W/chromium( 3048): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3048): Initialized EGL, version 1.4
D/OpenGLRenderer( 3048): Enabling debug mode 0
I/Keyboard.Facilitator( 1060): onFinishInput()
I/ActivityManager(  758): Displayed com.test.thalitest/.MainActivity: +449ms (total +53s988ms)
W/IInputConnectionWrapper( 3048): showStatusIcon on inactive InputConnection
W/BindingManager( 3048): Cannot call determinedVisibility() - never saw a connection for the pid: 3048
D/JsMessageQueue( 3048): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3048): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1546737536
D/JX-Cordova( 3048): jxcore cordova android initializing
I/ActivityManager(  758): Killing 2312:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10080/pid_2312/cgroup.procs: No such file or directory
,W/jxcore-log( 3048): Initializing JXcore engine
W/jxcore-log( 3048): JXcore engine is ready
,W/jxcore-log( 3048): Starting JXcore engine
,W/.test.thalitest( 3048): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6555]" dev="sockfs" ino=6555 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3048): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3048): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8436]" dev="sockfs" ino=8436 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3048): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18304]" dev="sockfs" ino=18304 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3048): Platform android
W/jxcore-log( 3048): 
W/jxcore-log( 3048): Process ARCH arm
W/jxcore-log( 3048): 
,I/jxcore-log( 3048): JXcore Cordova bridge is ready!
I/jxcore-log( 3048): 
,W/jxcore-log( 3048): JXcore engine is started
I/chromium( 3048): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3048): Toggling radios to true
I/jxcore-log( 3048): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  758): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  758): Message: 1
D/BluetoothManagerService(  758): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  758): New client listening to asynchronous messages
,D/WifiService(  758): setWifiEnabled: true pid=3048, uid=10270
,E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  178): Softap fwReload - Ok
D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring down wlan0
,I/ActivityManager(  758): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3118 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 3048): Radios toggled
I/jxcore-log( 3048): 
D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/WifiMonitor(  758): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  758): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3125 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3124): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3118): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3124): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3318541a:true
,D/BluetoothAdapter( 3125): 455077554: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  758): Message: 30
,D/BluetoothManagerService(  758): Message: 30
,D/AdapterServiceConfig( 3118): Adding HeadsetService
D/AdapterServiceConfig( 3118): Adding A2dpService
D/AdapterServiceConfig( 3118): Adding HidService
D/AdapterServiceConfig( 3118): Adding HealthService
D/LocalBluetoothProfileManager( 3125): Adding local MAP profile
D/AdapterServiceConfig( 3118): Adding PanService
D/AdapterServiceConfig( 3118): Adding GattService
D/AdapterServiceConfig( 3118): Adding BluetoothMapService
,D/BluetoothMap( 3125): Create BluetoothMap proxy object
,D/BluetoothManagerService(  758): Message: 30
,D/BluetoothManagerService(  758): Message: 30
,D/LocalBluetoothProfileManager( 3125): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3125): 455077554: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3125): 455077554: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  758): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3166 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 2401:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/BluetoothAdapterState( 3118): make
D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14aa3c58:true
,I/bluedroid( 3118): init
,I/BluetoothAdapterState( 3118): Entering OffState
,I/bte_conf( 3118): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3118): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3118): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3118): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3118): get_profile_interface socket
I/bluedroid( 3118): get_profile_interface map_client
,I/GKI_LINUX( 3118): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3118): Address is:34:FC:EF:11:AE:67
,W/libprocessgroup(  758): failed to open /acct/uid_10038/pid_2401/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  758): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  758): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 3118): Name is: Nexus 5
,D/BluetoothManagerService(  758): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  758): Message: 40
,D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3118): config_hci_snoop_log
,D/BluetoothManagerService(  758): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  758): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 3118): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3118): Setting state to 11
I/BluetoothAdapterState( 3118): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  758): Message: 60
,D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3118): make
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,D/BluetoothHeadset( 1162): Proxy object connected
,D/HeadsetService( 3118): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3118): classInitNative: succeeds
,D/BluetoothHeadset( 1162): Proxy object connected
,D/BluetoothHeadset(  758): Proxy object connected
,D/BluetoothHeadset( 1191): Proxy object connected
,D/HeadsetStateMachine( 3118): make
,I/BluetoothAdapterState( 3118): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3118): max_hf_connections = 1
I/bluedroid( 3118): get_profile_interface handsfree
,D/HeadsetStateMachine( 3118): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/BluetoothA2dp(  758): Proxy object connected
D/A2dpService( 3118): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3118): classInitNative: succeeds
,I/bluedroid( 3118): get_profile_interface avrcp
,E/RemoteController( 3118): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3118): classInitNative: succeeds
D/A2dpStateMachine( 3118): make
I/bluedroid( 3118): get_profile_interface a2dp
I/GKI_LINUX( 3118): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/A2dpStateMachine( 3118): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3118): classInitNative: succeeds
,D/BluetoothInputDevice( 3125): Proxy object connected
,D/HidService( 3118): Received start request. Starting profile...
I/bluedroid( 3118): get_profile_interface hidhost
D/BluetoothAdapterService( 3118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/HidProfile( 3125): Bluetooth service connected
,I/BluetoothHealthServiceJni( 3118): classInitNative: succeeds
,D/HealthService( 3118): Received start request. Starting profile...
,I/bluedroid( 3118): get_profile_interface health
D/BluetoothAdapterService( 3118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,I/BluetoothPanServiceJni( 3118): classInitNative(L105): succeeds
,D/PanService( 3118): Received start request. Starting profile...
D/BluetoothPan( 3125): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 3118): initializeNative(L110): pan
I/bluedroid( 3118): get_profile_interface pan
D/PanProfile( 3125): Bluetooth service connected
,D/BluetoothAdapterService( 3118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,I/BtGatt.JNI( 3118): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3118): handleDebugAction() action=null
D/BtGatt.GattService( 3118): Received start request. Starting profile...
D/BtGatt.GattService( 3118): start()
I/bluedroid( 3118): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3118): advertise manager created
,D/BluetoothAdapterService( 3118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,V/BluetoothMapService( 3118): BluetoothMapBinder()
,D/BluetoothMap( 3125): Proxy object connected
D/BluetoothMapService( 3118): Received start request. Starting profile...
D/BluetoothMapService( 3118): start()
D/MapProfile( 3125): Bluetooth service connected
D/BluetoothMap( 3125): getConnectedDevices()
,D/BluetoothMap( 3125): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3118): Found 0 applications
D/BluetoothMapEmailAppObserver( 3118): createReceiver()
D/BluetoothMapEmailAppObserver( 3118): initObservers()
D/BluetoothMapEmailAppObserver( 3118): getEnabledAccountItems()
,D/BluetoothAdapterService( 3118): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/HeadsetStateMachine( 3118): Proxy object connected
,D/HeadsetStateMachine( 3118): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3118): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,V/BluetoothMapService( 3118): Handler(): got msg=1
D/HeadsetStateMachine( 3118): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3118): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3118): enable
I/GKI_LINUX( 3118): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3118): btu_task pending for preload complete event
I/bt_hci_bdroid( 3118): init
I/bt_vendor( 3118): init
I/bt_vnd_conf( 3118): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3118): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3118): userial_init
,I/bt_userial_vendor( 3118): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3118): device fd = 53 open
,D/bt_userial( 3118): Entering userial_read_thread()
,I/art     ( 1298): Explicit concurrent mark sweep GC freed 9975(586KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 19MB/32MB, paused 520us total 22.357ms
,I/bt_hwcfg( 3118): bt vendor lib: set UART baud 4000000
,I/art     (  758): Explicit concurrent mark sweep GC freed 14052(721KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.862ms total 75.296ms
,D/bt_hwcfg( 3118): Chipset BCM4335C0
D/bt_hwcfg( 3118): Target name = [BCM4335C0]
I/bt_hwcfg( 3118): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  758): Killing 2451:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10069/pid_2451/cgroup.procs: No such file or directory
,D/Tethering(  758): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 3118): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3118): Settlement delay -- 100 ms
I/bt_hwcfg( 3118): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3124): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3124): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  758): Loading config and enabling all networks 
,D/WifiService(  758): New client listening to asynchronous messages
,I/bt_hwcfg( 3118): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3118): Setting local bd addr to 34:FC:EF:11:AE:67
E/WifiConfigStore(  758): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/Settings( 1856): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  758): Setting external_sim to 1
D/WifiStateMachine(  758): Setting OUI to DA-A1-19
I/WifiNative-HAL(  758): startHal
D/wifi    (  758): setting scan oui 0x9c1e1790
D/WifiHAL (  758): Sending mac address OUI
E/WifiHAL (  758): failed to set scanning mac OUI; result = -95
,E/native  (  758): do suspend true
,D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring up p2p0
D/WifiMonitor(  758): startMonitoring(p2p0) with mConnected = true
D/WifiNative-HAL(  758): p2pGetDeviceAddress
D/WifiNative-HAL(  758): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3118): vendor lib fwcfg completed
I/bt-btu  ( 3118): btu_task received preload complete event
D/WifiScanningService(  758): SCAN_AVAILABLE : 3
D/RttService(  758): SCAN_AVAILABLE : 3
D/WifiScanningService(  758): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  758): startHal
D/wifi    (  758): getting scan capabilities on interface[1] = 0x9c1e1790
D/WifiHAL (  758): Creating message to get scan capablities; iface = 21
D/WifiHAL (  758): In GetCapabilities::handleResponse
D/WifiHAL (  758): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  758): StartedState
D/RttService(  758): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3118): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3118): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3118): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3118): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3118): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3118): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3118): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3118): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3118): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3118): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3118): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3118): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3118): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3118): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3118): BTE_InitTraceLevels -- TRC_BTIF
,I/wpa_supplicant( 3124): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/bt-btm  ( 3118): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3bd99d5 
E/bt-btm  ( 3118): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3bd99d5 
,E/bt-btif ( 3118): Calling BTA_HhEnable
,E/bt-btif ( 3118): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3118): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3118): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3118): Scan Mode:20
D/BluetoothAdapterProperties( 3118): Discoverable Timeout:120
,D/BluetoothManagerService(  758): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  758): Stored Bluetooth name: Nexus 5
,D/bte_conf( 3118): Device ID record 1 : primary
D/bte_conf( 3118):   vendorId            = 000f
D/bte_conf( 3118):   vendorIdSource      = 0001
D/bte_conf( 3118):   product             = 1200
D/bte_conf( 3118):   version             = 1436
D/bte_conf( 3118):   clientExecutableURL = 
D/bte_conf( 3118):   serviceDescription  = 
D/bte_conf( 3118):   documentationURL    = 
D/bte_conf( 3118): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3118): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 3118): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3118): ScanMode =  20
D/BluetoothAdapterProperties( 3118): State =  11
D/BluetoothAdapterProperties( 3118): Setting state to 12
I/BluetoothAdapterState( 3118): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  758): Broadcasting onBluetoothStateChange(true) to 9 receivers.
I/BluetoothAdapterState( 3118): Entering On State
D/BluetoothPbap( 3125): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 3118): Scan Mode:21
D/BluetoothAdapterProperties( 3118): Discoverable Timeout:120
,D/BluetoothMap( 3125): onBluetoothStateChange: up=true
D/BluetoothHeadset(  758): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3125): onBluetoothStateChange: up=true
D/BluetoothPan( 3125): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1191): onBluetoothStateChange: up=true
D/BluetoothA2dp(  758): onBluetoothStateChange: up=true
D/BluetoothManagerService(  758): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 11 -> 12
D/BluetoothMapService( 3118): onReceive
D/BluetoothMapService( 3118): STATE_ON
V/BluetoothMapService( 3118): Handler(): got msg=1
W/bt-smp  ( 3118): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = 7d fe 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = b3 d0 47 21 ee cb 5a 85 df 86 02 5c 63 cf a1 8c 
W/bt-btm  ( 3118): Stopping oneshot timer
D/BluetoothMapMasInstance( 3118): Map Service startRfcommSocketListener
E/bt_h4   ( 3118): vendor lib postload completed
,D/BluetoothManagerService(  758): Message: 40
,D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3118): MAS initSocket()
D/BluetoothMapMasInstance( 3118):   masId = 00
D/BluetoothMapMasInstance( 3118):   msgTypes = 0e
D/BluetoothMapMasInstance( 3118):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3118):   SDP string = 000eSMS/MMS
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3118): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-smp  ( 3118): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = 3f c5 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = 28 41 8c f9 11 09 88 38 41 96 3b d2 de 01 1f 22 
W/bt-btm  ( 3118): Stopping oneshot timer
,I/Telecom ( 1162): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,V/BluetoothMapMasInstance( 3118): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3118): Accepting socket connection...
,D/HeadsetStateMachine( 3118): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 3118): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3118): mNumber:  mType: 128
W/bt-smp  ( 3118): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = aa ea 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = e1 af 69 83 a4 1f 44 71 43 70 43 90 b9 24 48 95 
W/bt-btm  ( 3118): Stopping oneshot timer
,D/HeadsetStateMachine( 3118): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3118): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/bt-smp  ( 3118): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = 4a fd 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = 5f d0 70 af 1f 17 8d 52 5b 2c 63 d1 6a 58 95 19 
W/bt-btm  ( 3118): Stopping oneshot timer
,W/bt-smp  ( 3118): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = 89 d5 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = 6e 61 51 65 c3 ef c4 a4 66 8d 5d a9 3b c5 2c da 
W/bt-btm  ( 3118): Stopping oneshot timer
,W/bt-smp  ( 3118): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = a0 fb 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = 15 c4 ba 61 08 e0 e3 2f 4a b3 ea bb d6 3d ed de 
W/bt-btm  ( 3118): Stopping oneshot timer
,W/bt-smp  ( 3118): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3118): Plain text(LSB ~ MSB) = c8 9c 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3118): Encrypted text(LSB ~ MSB) = ac 91 01 96 ad a0 15 e0 6c bc 69 41 28 58 f1 1f 
W/bt-btm  ( 3118): Stopping oneshot timer
,D/LocalBluetoothProfileManager( 3125): Adding local A2DP profile
,D/BluetoothManagerService(  758): Message: 30
,D/LocalBluetoothProfileManager( 3125): Adding local HEADSET profile
,D/BluetoothManagerService(  758): Message: 30
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3125): Proxy object connected
D/A2dpProfile( 3125): Bluetooth service connected
,D/BluetoothHeadset( 3125): Proxy object connected
,D/HeadsetProfile( 3125): Bluetooth service connected
,D/DockEventReceiver( 3125): finishStartingService: stopping service
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3118): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbap( 3125): Proxy object connected
,D/PbapServerProfile( 3125): Bluetooth service connected
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3118): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3118): Accept thread started.
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3048): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3048): 
I/jxcore-log( 3048): my name is : LGE-Nexus 5_PT5146
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): attempting to connect to test coordinator
I/jxcore-log( 3048): 
I/jxcore-log( 3048): check test folder
I/jxcore-log( 3048): 
I/jxcore-log( 3048): found test : ./testFindPeers.js
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): found test : ./testReConnect.js
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): found test : ./testSendData.js
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): Test app app.js loaded
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  758): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  758): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  758): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  758): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  758): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  758): will read network variables netId=1
,E/WifiStateMachine(  758): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  758): will read network variables netId=1
,I/wpa_supplicant( 3124): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  758): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3124): PNO: In assoc process
,I/wpa_supplicant( 3124): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3124): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3124): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  758): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
,E/WifiStateMachine(  758): Start Dhcp Watchdog 1
,E/native  (  758): do suspend false
,E/WifiStateMachine(  758): scanCount==0 - aborting
,I/dhcpcd  ( 3302): version 5.5.6 starting
,E/dhcpcd  ( 3302): get_duid: Read-only file system
,I/dhcpcd  ( 3302): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/dhcpcd  ( 3302): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3302): wlan0: leased 192.168.1.114 for 86400 seconds
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1381): OkHttp exception
W/EventLoggerService( 1381): Unable to send logs Error code: 262146
,W/Search.LoginHelper( 1381): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1381): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/native  (  758): do suspend true
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  758): Adding iface wlan0 to network 100
,E/ConnectivityService(  758): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  758): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  758): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  758): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,E/WifiStateMachine(  758): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  758): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  758): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  758): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Connected
D/ConnectivityService(  758):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  758): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  758): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 04 Dec 2015 08:03:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449216229399], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449216229381]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Validated
,D/ConnectivityService(  758): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  758): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  758): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  758): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1191): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3048): 
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  758): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  758): Setting time of day to sec=1449216232
,W/AlarmManagerService(  758): Unable to set rtc to 1449216232: Invalid argument
,I/NetworkMonitor( 2569): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2569): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.SyncManager( 1600): SYNC; picasa accounts
,D/NetworkLogImpl( 1600): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1600): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1600): num queued entries: 0
,I/iu.UploadsManager( 1600): num updated entries: 0
,I/iu.SyncManager( 1600): NEXT; no task
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1600): Checkin interval check for package: unspecified last checkin: 1449151177473 min interval config: 0 actual interval: 65055139
,I/SystemUpdateService( 1600): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SystemUpdateService( 1600): onCreate
,D/SystemUpdateService( 1600): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/CheckinService( 1600): Checking schedule, now: 1449216232624 next: 1449193344430
I/CheckinService( 1600): active receiver: enabled
,I/CheckinService( 1600): Preparing to send checkin request
I/SystemUpdateService( 1600): active receiver: enabled
,I/EventLogService( 1600): Accumulating logs since 1449215641447
,E/GpsLocationProvider(  758): No APN found to select.
,I/SystemUpdateService( 1600): showing system update notification
,I/ValidateNoPeople(  758): skipping global notification
,V/SystemUpdateService( 1600): retry (wakeup: false) in 3599974 ms
,I/ActivityManager(  758): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3386 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  758): NTP server returned: 1449216229474 (Fri Dec 04 09:03:49 GMT+01:00 2015) reference: 82677 certainty: 7 system time offset: -3227
E/LocSvc_eng(  758): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/art     (  193): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 385us total 15.845ms
,I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 182us total 15.025ms
,I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 171us total 7.534ms
,D/SystemUpdateService( 1600): onDestroy
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1856): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1600): [CredentialSyncAdapter] Unknown sync event.
,I/CheckinRequestBuilder( 1600): Checkin reason type: 12 attempt count: 1
,D/WifiService(  758): New client listening to asynchronous messages
,E/ActivityThread( 1600): Failed to find provider info for com.google.android.wearable.settings
,I/GCM     ( 1298): GCM config loaded
,I/GAv4    ( 3386): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3386):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3386):   adb logcat -s GAv4
,W/GAv4    ( 3386): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  758): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  758): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  758): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524290
,W/GAv4    ( 3386): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3386): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1298): Explicit concurrent mark sweep GC freed 16481(883KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 19MB/32MB, paused 732us total 55.361ms
,I/art     (  758): Explicit concurrent mark sweep GC freed 46454(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 1.078ms total 58.289ms
,W/AbstractGoogleClient( 2088): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2088): PlayLogger.onLoggerConnected
,W/DriveInitializer( 1600): Awaiting to be initialized
,W/DriveInitializer( 1600): Background init thread started
,I/WebViewFactory( 3386): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3386): Time to load native libraries: 1 ms (timestamps 6419-6420)
,I/LibraryLoader( 3386): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3386): Binding Chromium to main looper Looper (main, tid 1) {1c4e68d4}
I/LibraryLoader( 3386): Expected native library version number "",actual native library version number ""
I/chromium( 3386): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3386): Initializing chromium process, singleProcess=true
,W/art     ( 3386): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3386): ApplicationContext is null in ApplicationStatus
,W/chromium( 3386): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3386): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3386): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3386): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1600): Background init thread ended
,W/AudioManagerAndroid( 3386): Requires BLUETOOTH permission
,I/NSApplication( 3386): Starting up...
,W/art     ( 2718): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  758): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3497 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3497): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449216233469
,D/        ( 3497): TimeServiceNative: User Time to be set is 1449216233469
,D/QC-time-services( 3497): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3497): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3497): Lib:time_genoff_operation: pargs->ts_val = 1449216233469
D/QC-time-services(  196): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3497): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  196): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449216233469
D/QC-time-services(  196): Daemon:genoff_opr: Base = 2, val = 1449216233469, operation = 0
D/QC-time-services(  196): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/7/70 13:54:39
D/QC-time-services(  196): Daemon:Value read from RTC seconds = 8344479000
D/QC-time-services(  196): Daemon:new time 1449216233469 
D/QC-time-services(  196): Daemon: delta 1440871754469 genoff 1440871754469 
D/QC-time-services(  196): Daemon:genoff_persistent_update: Writing genoff = 1440871754469 to memory
D/QC-time-services(  196): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  196): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  196): Updating the TOD offset
D/QC-time-services(  196): Daemon:genoff_persistent_update: Writing genoff = 1440871754469 to memory
D/QC-time-services(  196): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  196): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  196): Daemon:Update to modem bit set
D/QC-time-services(  196): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  196): Daemon: Base = 2, Value being sent to MODEM = 1133251433469
,E/QC-time-services( 3497): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  196): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  196): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/art     ( 1600): Explicit concurrent mark sweep GC freed 13808(967KB) AllocSpace objects, 19(304KB) LOS objects, 24% free, 22MB/29MB, paused 510us total 38.404ms
,I/CheckinService( 1600): Checkin interval check for package: unspecified last checkin: 1449151177473 min interval config: 0 actual interval: 65056077
,I/ActivityManager(  758): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3517 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  758): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3534 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/ResourcesManager( 3517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3517): VM with version 2.1.0 has multidex support
I/MultiDex( 3517): install
I/MultiDex( 3517): VM has multidex support, MultiDex support library is disabled.
,I/CalendarSyncAdapter( 2088): Found no pending settings
,I/GAv4    ( 3534): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3534):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3534):   adb logcat -s GAv4
,I/ActivityManager(  758): Killing 1838:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10045/pid_1838/cgroup.procs: No such file or directory
,W/GAv4    ( 3534): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/JNIHelp ( 3517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/GAv4    ( 3534): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3534): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 3517): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@23780ea4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3517): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  758): Killing 2546:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/art     ( 3517): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3517): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/NativeLibraryUtils( 3517): Install completed successfully. count=13 extracted=0
,W/libprocessgroup(  758): failed to open /acct/uid_10003/pid_2546/cgroup.procs: No such file or directory
,D/WearableService( 1344): callingUid 10008, callindPid: 1344
,D/WVCdm   (  182): Instantiating CDM.
,I/WVCdm   (  182): CdmEngine::OpenSession
I/WVCdm   (  182): Level3 Library Sep 25 2014 17:10:03
,E/MDM     ( 1344): [149] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/WVCdm   (  182): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/GCM     ( 1298): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1298): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 1600): Restart initialization of location
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1600): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GoogleURLConnFactory( 3517): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  182): Service_Initialize: starts!
D/QSEECOMAPI: (  182): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  182): App is not loaded in QSEE
,D/QSEECOMAPI: (  182): Loaded image: APP id = 3
,D/DrmWidevineDash(  182): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5934000
E/DrmWidevineDash(  182): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5934000
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
D/DrmWidevineDash(  182): tz api version =  9
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  182): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession: starts! SID=0xb19ff940
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  182): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_GetRandom: starts! randomData=0xb50e60a8, dataLength=8
,D/DrmWidevineDash(  182): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1ae0000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  182): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  182): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  182): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  182): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: starts! deviceID=0xb3fbc440, idLength=0xb439a710
,D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
D/DrmWidevineDash(  182): tz api version =  9
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  182): PrepareKeyRequest: nonce=1053438925
D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d01600
D/DrmWidevineDash(  182): message_length=1597, signature=0xb411c140, signature_length=3023677172
,I/art     (  758): Explicit concurrent mark sweep GC freed 18594(814KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.568ms total 117.903ms
,W/GCoreFlp( 1344): No location to return for getLastLocation()
W/FusedLocationProvider( 1298): location=null
,I/art     ( 1298): Explicit concurrent mark sweep GC freed 13905(894KB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 19MB/32MB, paused 736us total 49.216ms
,D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  182): CdmEngine::CloseSession
D/DrmWidevineDash(  182): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  182): L3 Terminate.
D/DrmWidevineDash(  182): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  182): Service_Uninitialize: starts!
D/QSEECOMAPI: (  182): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  182): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  182): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  182): OEMCrypto_Terminate: ends! returns 0
,I/CalendarSyncAdapter( 2088): Found no pending settings
,I/ActivityManager(  758): Killing 2425:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10070/pid_2425/cgroup.procs: No such file or directory
,I/dex2oat ( 3585): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=35 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3585): dex2oat took 30.687ms (threads: 4)
,I/Adreno-EGL( 3517): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3517): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3517): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/WVCdm   (  182): CdmEngine::OpenSession
I/WVCdm   (  182): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  182): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  182): Service_Initialize: starts!
D/QSEECOMAPI: (  182): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  182): App is not loaded in QSEE
,D/QSEECOMAPI: (  182): Loaded image: APP id = 3
,D/DrmWidevineDash(  182): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  182): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5934000
E/DrmWidevineDash(  182): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5934000
,D/DrmWidevineDash(  182): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
D/DrmWidevineDash(  182): tz api version =  9
,D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  182): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  182): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  182): OEMCrypto_OpenSession: starts! SID=0xbee80500
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  182): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_GetRandom: starts! randomData=0xb4a21070, dataLength=8
,D/DrmWidevineDash(  182): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb61aa600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  182): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  182): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  182): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  182): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  182): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: starts! deviceID=0xb3fbc480, idLength=0xb439a710
,D/DrmWidevineDash(  182): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  182): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  182): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  182): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  182): hlos api version =  9
D/DrmWidevineDash(  182): tz api version =  9
,D/DrmWidevineDash(  182): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  182): PrepareKeyRequest: nonce=3045045399
,D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d01600
D/DrmWidevineDash(  182): message_length=1632, signature=0xb411c140, signature_length=3023677172
,D/DrmWidevineDash(  182): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  182): CdmEngine::CloseSession
D/DrmWidevineDash(  182): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  182): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  182): L3 Terminate.
D/DrmWidevineDash(  182): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  182): Service_Uninitialize: starts!
D/QSEECOMAPI: (  182): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  182): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  182): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  182): OEMCrypto_Terminate: ends! returns 0
,I/CheckinRequestBuilder( 1600): Classify the device as Phone.
,I/CheckinTask( 1600): Sending checkin request (9752 bytes)
,I/CheckinRequestBuilder( 1600): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1600): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 1600): Classify the device as Phone.
,I/CheckinTask( 1600): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1600): Checking schedule, now: 1449216236105 next: 1449258403101
I/CheckinService( 1600): active receiver: disabled
,D/CheckinService( 1600): Recording last checkin time for package unspecified as 1449216236131
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1298): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,D/Finsky  ( 2482): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2482): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  758): Killing 1464:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10013/pid_1464/cgroup.procs: No such file or directory
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,W/SQLiteConnectionPool( 1600): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1381): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1243): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@16ff0e03 new=com.google.android.velvet.VelvetApplication@16ff0e03
,D/PackageBroadcastService( 1600): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1600): Null package name or gms related package.  Ignoreing.
,D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  758): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  758): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  758): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  758): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3cb26742
,I/Icing   ( 1600): updateResources: need to parse f{com.google.android.gms}
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,V/GmsNetworkLocationProvi( 1344): DISABLE
,I/GCoreNlp( 1344): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1243): Deferring update until onResume
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1243): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1381): UpdateCorporaTask done [took 233 ms] updated apps [took 233 ms] 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/ActivityManager(  758): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3668 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3668): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3668): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3668): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/art     (  758): Explicit concurrent mark sweep GC freed 24630(1107KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 886us total 51.354ms
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,W/System  ( 3668): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3668): Installed default security provider GmsCore_OpenSSL
,I/VacuumService( 1298): Vacuum at: now=1449216266513 tag=VacuumService
,E/YouTube MDX( 3668): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3717): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-208356727.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-208356727.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3717): dex2oat took 50.011ms (threads: 4)
,W/InstanceID/Rpc( 3668): Found 10008
,I/ActivityManager(  758): Killing 2948:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10015/pid_2948/cgroup.procs: No such file or directory
,D/UdcCache:FPQuery( 1600): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1298): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1298): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1298):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1298): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1060): run()
,I/Keyboard.Facilitator( 1060): flushDynamicLanguageModels()
,I/ConfigService( 1298): onCreate
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/ConfigService( 1298): onDestroy
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/ClearcutLoggerApiImpl( 1344): disconnect managed GoogleApiClient
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,E/DataBuffer( 1298): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@179b06bf)
,E/DataBuffer( 1298): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3fca418c)
E/DataBuffer( 1298): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@75ec0d5)
E/DataBuffer( 1298): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3bd730ea)
,E/DataBuffer( 1298): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a834fdb)
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/ClearcutLoggerApiImpl( 1298): disconnect managed GoogleApiClient
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector connect called
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Coordinator is now connected to the server!
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1298): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  758): Killing 2977:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10040/pid_2977/cgroup.procs: No such file or directory
,I/jxcore-log( 3048): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector command called
I/jxcore-log( 3048): 
I/jxcore-log( 3048): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"58:3F:54:73:64
I/jxcore-log( 3048): Start now : testSendData.js
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): check server
I/jxcore-log( 3048): 
I/jxcore-log( 3048): serverPort is 38668
I/jxcore-log( 3048): 
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stop Bluetooth
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3048): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3048):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3048): All stuff available and enabled
I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stop Bluetooth
I/        ( 3048): Starting All
I/        ( 3048): Stopping services
I/        ( 3048): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3982bae9
I/        ( 3048): Stopping services
I/        ( 3048): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}
I/        ( 3048): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3048): peerDiscoveryTimer timeout value:9422
,I/        ( 3048): Stop Bluetooth
I/        ( 3048): StartBluetooth listener
I/        ( 3048): StartBluetooth listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): StartBroadcasting started ok
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:27.714Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:27.714Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:27.714Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: B0:C5:59:3F:75:69, name: null
,I/        ( 3048): Connecting to null, at B0:C5:59:3F:75:69
I/jxcore-log( 3048): 2015-12-04T08:09:27.720Z SendDataTCPServer.js: TCP/IP server is bound to port: 38668
I/jxcore-log( 3048): 
I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3048): We already were running, thus doing nothing
,I/        ( 3048): Added local service
I/        ( 3048): Cleared service requests
I/        ( 3048): Stopped peer discovery
I/        ( 3048): Started peer discovery
I/        ( 3048): Discovery state changed to Started.
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3118): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BTListenerThread( 3048): starting to listen
,I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3118): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 3118): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 1 peers.
,I/SS      ( 3048): Peer(1): Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,W/bt-btif ( 3118): info:x10
D/        ( 3118): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3118): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
,W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 3118): process_service_search_attr_rsp
,I/        ( 3048): Started service discovery
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2828, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2828, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:09:31.380Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-LG-D722_PT9142
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:09:32.031Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.648Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.684Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.698Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.703Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.747Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.753Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.793Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.828Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:32.864Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.057Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.153Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.184Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.208Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.218Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.223Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.265Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.287Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.321Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.343Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:33.345Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.364Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.399Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.421Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.436Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.442Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.452Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.460Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.479Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.486Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.496Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.505Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.515Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.522Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.549Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.578Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.588Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3048): 
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/jxcore-log( 3048): 2015-12-04T08:09:33.618Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.714Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.721Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.759Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.765Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.780Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.787Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.834Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.849Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.884Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.890Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:33.964Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.106Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.114Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.183Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.219Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.394Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.402Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.408Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.471Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.482Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.513Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.540Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.553Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.565Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.574Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.599Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.622Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.648Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3048): 
I/        ( 3048): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/jxcore-log( 3048): 2015-12-04T08:09:34.685Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.722Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.785Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:34.817Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3118): invalid rfc slot id: 6
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:09:34.836Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3048): 2015-12-04T08:09:34.882Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
E/BluetoothRemoteDevices( 3118): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,I/jxcore-log( 3048): 2015-12-04T08:09:35.041Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3048): 
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,I/jxcore-log( 3048): 2015-12-04T08:09:35.049Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3048): 
,E/BluetoothEventManager( 3125): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:09:35.104Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:35.199Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:35.206Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:35.216Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:35.539Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:09:35.601Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:35.608Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:35.616Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2034694b:true
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,I/BTListenerThread( 3048): we got incoming connection,
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-LG-D802_PT5431
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:09:39.067Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:09:40.461Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:40.650Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:40.758Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/BTConnectToThread( 3048): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT807
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT807
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT807
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 37393
I/BtConnectorHelper( 3048): Request socket is using : 37393
,I/jxcore-log( 3048): 2015-12-04T08:09:40.823Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:40.829Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:40.836Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): Now accepting connections
,I/jxcore-log( 3048): 2015-12-04T08:09:40.845Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:40.900Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:09:40.976Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.035Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.121Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3048): 
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :37393
,I/jxcore-log( 3048): 2015-12-04T08:09:41.156Z SendDataConnector.js: CLIENT connected to 37393, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:41.156Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 37393
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:09:41.198Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.209Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.787Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.795Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.855Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.888Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.934Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.938Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:41.949Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:09:42.558Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:42.566Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:42.663Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:42.699Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:42.711Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:42.723Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:42.831Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:43.463Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:43.536Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:43.626Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:43.734Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:43.814Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,W/bt-btif ( 3118): invalid rfc slot id: 4
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:09:45.525Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3048): Found 3 peers.
I/SS      ( 3048): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(3): G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3118): dm_pm_timer expires
W/bt-btif ( 3118): dm_pm_timer expires 1
W/bt-btif ( 3118): proc dm_pm_timer expires
,I/        ( 3048): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): invalid rfc slot id: 7
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:09:53.132Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 3048): 2015-12-04T08:09:53.815Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:53.816Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:53.823Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:53.824Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:53.835Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G900F_PT807
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3118): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/jxcore-log( 3048): 2015-12-04T08:09:57.702Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:09:58.290Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:58.357Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:58.385Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:58.440Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:09:58.476Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3048): 2015-12-04T08:09:58.834Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:09:58.834Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [34:fc:ef:9d:93:0b]: 7, f, 610c
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:10:03.842Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:03.842Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:03.843Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:03.844Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 3048): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3118): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-LG-D802_PT5431
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:10:03.901Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:10:04.714Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:10:04.845Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/SS      ( 3048): Found 7 peers.
I/SS      ( 3048): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3048): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3048): Peer(7): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/jxcore-log( 3048): 2015-12-04T08:10:04.966Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [b0:c5:59:3f:75:69]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3118): process_service_search_attr_rsp
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 3118): invalid rfc slot id: 8
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:10:08.485Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3048): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT807
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT807
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT807
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 35371
I/BtConnectorHelper( 3048): Request socket is using : 35371
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :35371
,I/jxcore-log( 3048): 2015-12-04T08:10:09.970Z SendDataConnector.js: CLIENT connected to 35371, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:09.971Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 35371
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:10:09.994Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,I/        ( 3048): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): invalid rfc slot id: 9
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:10:14.431Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x41
,W/bt-btif ( 3118): dm_pm_timer expires
W/bt-btif ( 3118): dm_pm_timer expires 0
W/bt-btif ( 3118): proc dm_pm_timer expires
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:10:19.556Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:10:19.984Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:19.993Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:20.002Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:20.011Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:20.082Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:20.083Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:20.084Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:20.085Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:20.086Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G900F_PT807
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3118): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 9 peers.
I/SS      ( 3048): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/jxcore-log( 3048): 2015-12-04T08:10:25.087Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:25.089Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-LG-D802_PT5431
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:10:27.288Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:10:27.955Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:28.194Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:28.231Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:28.236Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:30.096Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:30.096Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:30.100Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:30.103Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 3048): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 3048): Starting to connect
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3118): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): invalid rfc slot id: 10
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Stop ReceivingThread
,I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:10:30.413Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,W/bt-btif ( 3118): invalid rfc slot id: 12
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:10:37.850Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x4b
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 11 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3048): Peer(3): Note4-1 92:b6:86:43:73:1c
,I/SS      ( 3048): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,W/bt-btm  ( 3118): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=2
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:10:42.261Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:10:42.681Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:42.690Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:42.698Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): invalid rfc slot id: 13
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Stop ReceivingThread
,I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:10:52.860Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-LG-D802_PT5431
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:10:52.970Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:10:53.700Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:53.756Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:10:53.841Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 3048): 2015-12-04T08:10:54.033Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,W/bt-sdp  ( 3118): SDP - Rcvd conn cnf with error: 0x8  CID 0x4a
E/bt-btif ( 3118): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3118): invalid rfc slot id: 14
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3048): 2015-12-04T08:10:54.341Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:54.342Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:54.343Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 10 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2,
I/SS      ( 3048): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3048): 2015-12-04T08:10:59.344Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:10:59.345Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,W/bt-btif ( 3118): invalid rfc slot id: 15
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:11:03.955Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3048): 2015-12-04T08:11:04.346Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:04.347Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:04.347Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:04.347Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 3048): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3118): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x43
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT4577
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:11:06.094Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3048): 2015-12-04T08:11:06.551Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:06.555Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:06.558Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:06.595Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:06.599Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3118): process_service_search_attr_rsp
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT807
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT807
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT807
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 35279
I/BtConnectorHelper( 3048): Request socket is using : 35279
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :35279
I/jxcore-log( 3048): 2015-12-04T08:11:09.159Z SendDataConnector.js: CLIENT connected to 35279, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:09.159Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:09.162Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 35279
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3118): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): peer should have initiated security process by now (SM4 to SM4)
,W/bt-btif ( 3118): dm_pm_timer expires
W/bt-btif ( 3118): dm_pm_timer expires 1
W/bt-btif ( 3118): proc dm_pm_timer expires
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3118): L2CAP got sec_comp for unknown BD_ADDR
,E/BluetoothRemoteDevices( 3118): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3118): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3118): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3118): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3118): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3118): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3118): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-LG-D802_PT5431
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-LG-D802_PT5431
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/jxcore-log( 3048): 2015-12-04T08:11:15.286Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:11:15.697Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:15.730Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:15.821Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:15.864Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:15.939Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:15.950Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): invalid rfc slot id: 16
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT4577
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:11:17.207Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3118): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3118): RFCOMM_DisconnectInd LCID:0x40
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=0
,W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:11:19.247Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:19.249Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:19.251Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:19.251Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:19.253Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G900F_PT807
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51084 rs_disc_pending=1
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3118): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5mini-1
,I/jxcore-log( 3048): 2015-12-04T08:11:24.253Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:24.253Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,W/bt-btm  ( 3118): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=2
E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3118): invalid rfc slot id: 18
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:11:26.282Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:11:29.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:29.258Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:29.259Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:11:29.259Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 3048): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3118): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3118): info:x10
,D/        ( 3118): remote version info [b0:c5:59:3f:75:69]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3118): process_service_search_attr_rsp
,W/bt-btif ( 3118): new conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3118): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,D/btif_config_util( 3118): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3118): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
E/bt-btm  ( 3118): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3118): bta_dm_check_av:0
,W/bt-btif ( 3118): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3118): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 5 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 6 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3048): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/BtConnection( 3048): connectionTimeoutTimer
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/CONNEC  ( 3048): Error: Cancelled
I/jxcore-log( 3048): 2015-12-04T08:12:29.296Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:29.297Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:29.320Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:29.321Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:29.324Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): Connect to fake peer: 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:29.342Z SendDataConnector.js: Start called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:29.345Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:29.348Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 38:94:96:B5:06:DC, name: null,
I/        ( 3048): Connecting to null, at 38:94:96:B5:06:DC
I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: Connection to B0:C5:59:3F:75:69 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3118): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3118): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Cleared service requests
,I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 6 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3048): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/BTLD    ( 3118): ######################################################################
E/BTLD    ( 3118): #
E/BTLD    ( 3118): # WARNING : BTU HCI(id=0) command timeout. opcode=0x405
E/BTLD    ( 3118): #
E/BTLD    ( 3118): ######################################################################
W/bt-sdp  ( 3118): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4c
E/bt-btif ( 3118): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
W/bt-hci  ( 3118): HCI Cmd timeout counter 1
,W/bt-btif ( 3118): invalid rfc slot id: 21
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:12:36.406Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 38:94:96:B5:06:DC failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:36.406Z SendDataConnector.js: CLIENT Can not Connect: Connection to 38:94:96:B5:06:DC failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:36.410Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3048): 2015-12-04T08:12:41.413Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:41.414Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:46.420Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:46.420Z SendDataConnector.js: Connect (retry count 1) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:46.421Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:46.421Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 38:94:96:B5:06:DC, name: null
,I/        ( 3048): Connecting to null, at 38:94:96:B5:06:DC
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3118): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 8 peers.
I/SS      ( 3048): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3048): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3048): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,E/BTLD    ( 3118): ######################################################################
E/BTLD    ( 3118): #
E/BTLD    ( 3118): # WARNING : BTU HCI(id=0) command timeout. opcode=0x405
E/BTLD    ( 3118): #
E/BTLD    ( 3118): ######################################################################
W/bt-sdp  ( 3118): SDP - Rcvd conn cnf with error: 0x1f  CID 0x42
E/bt-btif ( 3118): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
E/bt-hci  ( 3118): Num consecutive HCI Cmd tout =2 Restarting BT process
,W/bt-btif ( 3118): invalid rfc slot id: 22
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothHeadset( 1162): Proxy object disconnected
D/BluetoothHeadset( 1162): Proxy object disconnected
,D/BluetoothHeadset( 1191): Proxy object disconnected
,D/BluetoothHeadset(  758): Proxy object disconnected
D/BluetoothManagerService(  758): BluetoothServiceConnection, disconnected: com.android.bluetooth.btservice.AdapterService
D/BluetoothA2dp(  758): Proxy object disconnected
D/BluetoothManagerService(  758): BluetoothServiceConnection, disconnected: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  758): Message: 41
E/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 1
D/BluetoothManagerService(  758): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  758): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothManagerService(  758): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothHeadset( 3125): Proxy object disconnected
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3048): 2015-12-04T08:12:54.492Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 38:94:96:B5:06:DC failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:12:54.493Z SendDataConnector.js: CLIENT Can not Connect: Connection to 38:94:96:B5:06:DC failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:54.493Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,D/HeadsetProfile( 3125): Bluetooth service disconnected
D/BluetoothA2dp( 3125): Proxy object disconnected
D/A2dpProfile( 3125): Bluetooth service disconnected
D/BluetoothInputDevice( 3125): Proxy object disconnected
D/HidProfile( 3125): Bluetooth service disconnected
D/BluetoothPan( 3125): BluetoothPAN Proxy object disconnected
D/PanProfile( 3125): Bluetooth service disconnected
,D/BluetoothMap( 3125): Proxy object disconnected
D/MapProfile( 3125): Bluetooth service disconnected
D/BluetoothPbap( 3125): Proxy object disconnected
D/PbapServerProfile( 3125): Bluetooth service disconnected
,I/BTListenerThread( 3048): accept socket failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/LISTEN  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/BTListenerThread( 3048): Stopped
I/        ( 3048): StartBluetooth listener
,I/ActivityManager(  758): Process com.android.bluetooth (pid 3118) has died
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.map.BluetoothMapService in 1000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.hfp.HeadsetService in 1000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.hdp.HealthService in 1000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.hid.HidService in 1000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.a2dp.A2dpService in 11000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.gatt.GattService in 11000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.pbap.BluetoothPbapService in 21000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.opp.BluetoothOppService in 21000ms
W/ActivityManager(  758): Scheduling restart of crashed service com.android.bluetooth/.pan.PanService in 21000ms
,D/BluetoothManagerService(  758): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3125): onBluetoothStateChange: up=false
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothSocket( 3048): bindListen fail, reason: bluetooth is off
W/System.err( 3048): java.io.IOException: Error: -1
W/System.err( 3048): 	at android.bluetooth.BluetoothAdapter.createNewRfcommSocketAndRecord(BluetoothAdapter.java:1196)
W/System.err( 3048): 	at android.bluetooth.BluetoothAdapter.listenUsingInsecureRfcommWithServiceRecord(BluetoothAdapter.java:1143)
W/System.err( 3048): 	at org.thaliproject.p2p.btconnectorlib.BTListenerThread.<init>(BTListenerThread.java:40)
W/System.err( 3048): 	at org.thaliproject.p2p.btconnectorlib.BTConnector_BtConnection.StartListening(BTConnector_BtConnection.java:93)
W/System.err( 3048): 	at org.thaliproject.p2p.btconnectorlib.BTConnector_BtConnection$6.run(BTConnector_BtConnection.java:237)
W/System.err( 3048): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3048): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3048): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3048): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
W/System.err( 3048): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3048): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3048): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
W/System.err( 3048): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/BluetoothHeadset( 3125): onBluetoothStateChange: up=false
D/BluetoothMap( 3125): onBluetoothStateChange: up=false
D/BluetoothHeadset(  758): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3125): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1191): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3125): onBluetoothStateChange: up=false
D/BluetoothA2dp(  758): onBluetoothStateChange: up=false
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 13 -> 10
D/BluetoothManagerService(  758): Message: 41
E/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED: 2
W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  758): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=3932 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/DockEventReceiver( 3125): finishStartingService: stopping service
D/BluetoothAdapter( 1344): 782594929: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1344): 782594929: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1344): 782594929: getState() :  mService = null. Returning STATE_OFF
E/BluetoothDevice( 1344): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1344): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1344): BT not enabled. Cannot get Remote Device Alias
E/BluetoothDevice( 1344): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1344): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1344): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1344): BT not enabled. Cannot get Remote Device Alias
D/BluetoothAdapter( 1344): 782594929: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1344): 782594929: getState() :  mService = null. Returning STATE_OFF
,W/ResourcesManager( 3932): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3932): Adding HeadsetService
D/AdapterServiceConfig( 3932): Adding A2dpService
D/AdapterServiceConfig( 3932): Adding HidService
D/AdapterServiceConfig( 3932): Adding HealthService
D/AdapterServiceConfig( 3932): Adding PanService
D/AdapterServiceConfig( 3932): Adding GattService
D/AdapterServiceConfig( 3932): Adding BluetoothMapService
,D/BluetoothManagerService(  758): Message: 20
D/BluetoothManagerService(  758): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bde4f27:true
,D/BluetoothAdapterState( 3932): make
,I/bluedroid( 3932): init
I/BluetoothAdapterState( 3932): Entering OffState
,I/bte_conf( 3932): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3932): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3932): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3932): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3932): get_profile_interface socket
I/bluedroid( 3932): get_profile_interface map_client
I/GKI_LINUX( 3932): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  758): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothAdapterProperties( 3932): Address is:34:FC:EF:11:AE:67
D/BluetoothManagerService(  758): Message: 40
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  758): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  758): Stored Bluetooth name: Nexus 5
I/BtGatt.JNI( 3932): classInitNative(L863): classInitNative: Success!
,D/BluetoothAdapterProperties( 3932): Name is: Nexus 5
I/bluedroid( 3932): config_hci_snoop_log
D/BluetoothManagerService(  758): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  758): Broadcasting onBluetoothServiceUp() to 11 receivers.
,D/BluetoothManagerService(  758): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothAdapterState( 3932): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3932): Setting state to 11
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3932): make
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/HeadsetService( 3932): Received start request. Starting profile...
I/BluetoothAdapterState( 3932): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/BluetoothHeadsetServiceJni( 3932): classInitNative: succeeds
D/HeadsetStateMachine( 3932): make
,D/DockEventReceiver( 3125): finishStartingService: stopping service
,D/HeadsetStateMachine( 3932): max_hf_connections = 1
I/bluedroid( 3932): get_profile_interface handsfree
,D/HeadsetStateMachine( 3932): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/A2dpService( 3932): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3932): classInitNative: succeeds
I/bluedroid( 3932): get_profile_interface avrcp
,E/RemoteController( 3932): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3932): classInitNative: succeeds
,D/A2dpStateMachine( 3932): make
,I/bluedroid( 3932): get_profile_interface a2dp
I/GKI_LINUX( 3932): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/A2dpStateMachine( 3932): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3932): classInitNative: succeeds
,D/HidService( 3932): Received start request. Starting profile...
,I/bluedroid( 3932): get_profile_interface hidhost
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
I/BluetoothHealthServiceJni( 3932): classInitNative: succeeds
D/HealthService( 3932): Received start request. Starting profile...
,I/bluedroid( 3932): get_profile_interface health
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,I/BluetoothPanServiceJni( 3932): classInitNative(L105): succeeds
,D/PanService( 3932): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3932): initializeNative(L110): pan
I/bluedroid( 3932): get_profile_interface pan
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/BtGatt.DebugUtils( 3932): handleDebugAction() action=null
,D/BtGatt.GattService( 3932): Received start request. Starting profile...
D/BtGatt.GattService( 3932): start()
I/bluedroid( 3932): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3932): advertise manager created
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,V/BluetoothMapService( 3932): BluetoothMapBinder()
,D/BluetoothMapService( 3932): Received start request. Starting profile...
D/BluetoothMapService( 3932): start()
,D/BluetoothMapEmailSettingsLoader( 3932): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3932): createReceiver()
,D/BluetoothMapEmailAppObserver( 3932): initObservers()
D/BluetoothMapEmailAppObserver( 3932): getEnabledAccountItems()
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/HeadsetStateMachine( 3932): Proxy object connected
,D/HeadsetStateMachine( 3932): Disconnected process message: 10, size: 0
,V/BluetoothMapService( 3932): Handler(): got msg=1
,D/HeadsetPhoneState( 3932): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3932): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3932): enable
,I/bt_hci_bdroid( 3932): init
,I/bt_vendor( 3932): init
I/GKI_LINUX( 3932): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3932): btu_task pending for preload complete event
I/bt_vnd_conf( 3932): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3932): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3932): userial_init
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_userial_vendor( 3932): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3932): device fd = 53 open
D/bt_userial( 3932): Entering userial_read_thread()
,I/bt_hwcfg( 3932): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3932): Chipset BCM4335C0
D/bt_hwcfg( 3932): Target name = [BCM4335C0]
,I/bt_hwcfg( 3932): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/bt_hwcfg( 3932): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3932): Settlement delay -- 100 ms
I/bt_hwcfg( 3932): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3932): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3932): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3932): vendor lib fwcfg completed
,I/bt-btu  ( 3932): btu_task received preload complete event
,I/        ( 3932): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3932): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3932): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3932): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3932): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3932): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3932): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3932): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3932): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3932): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3932): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3932): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3932): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3932): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3932): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3932): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3bd99d5 
E/bt-btm  ( 3932): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3bd99d5 
,E/bt-btif ( 3932): Calling BTA_HhEnable
E/bt-btif ( 3932): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3932): Address is:34:FC:EF:11:AE:67
,W/bt-smp  ( 3932): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3932): Plain text(LSB ~ MSB) = 34 c3 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3932): Encrypted text(LSB ~ MSB) = 08 83 33 26 fe 5c 17 56 44 af 67 39 b3 7b 8c 12 
,W/bt-btm  ( 3932): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3932): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3932): Scan Mode:20
D/BluetoothAdapterProperties( 3932): Discoverable Timeout:120
,D/bte_conf( 3932): Device ID record 1 : primary
D/bte_conf( 3932):   vendorId            = 000f
D/bte_conf( 3932):   vendorIdSource      = 0001
D/bte_conf( 3932):   product             = 1200
D/bte_conf( 3932):   version             = 1436
D/bte_conf( 3932):   clientExecutableURL = 
D/bte_conf( 3932):   serviceDescription  = 
D/bte_conf( 3932):   documentationURL    = 
D/bte_conf( 3932): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3932): ScanMode =  20
D/BluetoothAdapterProperties( 3932): State =  11
D/BluetoothAdapterProperties( 3932): Setting state to 12
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 11-> 12
,D/BluetoothPanServiceJni( 3932): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothManagerService(  758): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  758): Stored Bluetooth name: Nexus 5
,I/BluetoothAdapterState( 3932): Entering On State
,D/BluetoothAdapterProperties( 3932): Scan Mode:21
,D/BluetoothAdapterProperties( 3932): Discoverable Timeout:120
I/BT      ( 3048): Bluetooth DISABLED, stopping
I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stopping services
,E/bt_h4   ( 3932): vendor lib postload completed
,I/        ( 3048): Stop Bluetooth
I/        ( 3048): Stop Bluetooth
,I/BT      ( 3048): Bluetooth enabled, re-starting
I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stop Bluetooth
I/        ( 3048): Starting All
I/        ( 3048): Stopping services
I/        ( 3048): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3982bae9
I/        ( 3048): Stopping services
I/        ( 3048): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3048): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3048): peerDiscoveryTimer timeout value:9320
,I/        ( 3048): Stop Bluetooth
I/        ( 3048): StartBluetooth listener
I/        ( 3048): StartBluetooth listener
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3048): Discovery state changed to Started.
,I/BTListenerThread( 3048): starting to listen
I/BTListenerThread( 3048): waiting to accept incoming Connection
,D/BluetoothManagerService(  758): Sending off request.
,D/BluetoothAdapterState( 3932): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3932): Setting state to 13
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3932): onBluetoothDisable()
I/BluetoothAdapterState( 3932): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3932): Scan Mode:20
D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/BluetoothManagerService(  758): Message: 40
,D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 10 -> 11
D/BluetoothManagerService(  758): Message: 42
D/BluetoothManagerService(  758): MESSAGE_RESTART_BLUETOOTH_SERVICE: Restart IBluetooth service
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
I/BT      ( 3048): Bluetooth DISABLED, stopping
I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stopping services
I/BTListenerThread( 3048): accept socket failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = USER_TURN_ON, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING: Deferring request USER_TURN_ON
D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  758): Broadcasting onBluetoothStateChange(true) to 11 receivers.
D/BluetoothPbap( 3125): onBluetoothStateChange: up=true
D/BluetoothMapService( 3932): onReceive
D/BluetoothHeadset( 3125): onBluetoothStateChange: up=true
D/BluetoothMap( 3125): onBluetoothStateChange: up=true
D/BluetoothHeadset(  758): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=true
D/BluetoothHeadset(  758): Proxy object connected
D/BluetoothHeadset( 1162): Proxy object connected
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1162): Proxy object connected
D/BluetoothInputDevice( 3125): onBluetoothStateChange: up=true
D/BluetoothPan( 3125): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1191): onBluetoothStateChange: up=true
I/        ( 3048): Stop Bluetooth
I/        ( 3048): Stop Bluetooth
I/BTListenerThread( 3048): Stopped
I/LISTEN  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/        ( 3048): StartBluetooth listener
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 3932): Socket listen failed: 2
E/BluetoothAdapterService(385814019)( 3932): Failed to create socket channel
W/System.err( 3048): java.io.IOException: Error: -1
W/System.err( 3048): 	at android.bluetooth.BluetoothAdapter.createNewRfcommSocketAndRecord(BluetoothAdapter.java:1196)
W/System.err( 3048): 	at android.bluetooth.BluetoothAdapter.listenUsingInsecureRfcommWithServiceRecord(BluetoothAdapter.java:1143)
W/System.err( 3048): 	at org.thaliproject.p2p.btconnectorlib.BTListenerThread.<init>(BTListenerThread.java:40)
W/System.err( 3048): 	at org.thaliproject.p2p.btconnectorlib.BTConnector_BtConnection.StartListening(BTConnector_BtConnection.java:93)
W/System.err( 3048): 	at org.thaliproject.p2p.btconnectorlib.BTConnector_BtConnection$6.run(BTConnector_BtConnection.java:237)
W/System.err( 3048): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3048): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3048): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3048): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
W/System.err( 3048): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3048): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3048): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
W/System.err( 3048): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/BluetoothHeadset( 1191): Proxy object connected
D/BluetoothA2dp( 3125): onBluetoothStateChange: up=true
D/BluetoothA2dp(  758): onBluetoothStateChange: up=true
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 12 -> 13
D/BluetoothA2dp(  758): Proxy object connected
I/Telecom ( 1162): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
W/BluetoothHeadset( 1162): Proxy not attached to service
D/BluetoothHeadset( 1162): java.lang.Throwable
D/BluetoothHeadset( 1162): 	at android.bluetooth.BluetoothHeadset.phoneStateChanged(BluetoothHeadset.java:826)
D/BluetoothHeadset( 1162): 	at com.android.server.telecom.BluetoothPhoneService.updateHeadsetWithCallState(BluetoothPhoneService.java:775)
D/BluetoothHeadset( 1162): 	at com.android.server.telecom.BluetoothPhoneService.access$800(BluetoothPhoneService.java:51)
D/BluetoothHeadset( 1162): 	at com.android.server.telecom.BluetoothPhoneService$2.handleMessage(BluetoothPhoneService.java:299)
D/BluetoothHeadset( 1162): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BluetoothHeadset( 1162): 	at android.os.Looper.loop(Looper.java:135)
D/BluetoothHeadset( 1162): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
D/BluetoothHeadset( 1162): 	at java.lang.reflect.Method.invoke(Native Method)
D/BluetoothHeadset( 1162): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BluetoothHeadset( 1162): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
D/BluetoothHeadset( 1162): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
D/BluetoothMapService( 3932): onReceive
D/BluetoothMapService( 3932): STATE_ON
V/BluetoothMapService( 3932): Handler(): got msg=1
D/BluetoothMapService( 3932): onReceive
D/BluetoothMapService( 3932): STATE_TURNING_OFF
V/BluetoothMapService( 3932): Handler(): got msg=4
D/BluetoothMapService( 3932): MAP Service closeService in
D/BluetoothMapMasInstance( 3932): MAP Service shutdown
V/BluetoothMapService( 3932): MAP Service closeService out
,D/BluetoothHeadset( 3125): Proxy object connected
D/HeadsetProfile( 3125): Bluetooth service connected
,D/BluetoothMap( 3125): Proxy object connected
D/MapProfile( 3125): Bluetooth service connected
D/BluetoothMap( 3125): getConnectedDevices()
,D/BluetoothMap( 3125): Bluetooth is Not enabled
D/BluetoothInputDevice( 3125): Proxy object connected
D/HidProfile( 3125): Bluetooth service connected
,D/BluetoothPan( 3125): BluetoothPAN Proxy object connected
D/PanProfile( 3125): Bluetooth service connected
D/BluetoothA2dp( 3125): Proxy object connected
D/A2dpProfile( 3125): Bluetooth service connected
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/bt_userial( 3932): RX termination
W/bt_userial( 3932): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3932): Leaving userial_read_thread()
,D/bt_userial( 3932): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 3932): hw_epilog_process
W/bt-btif ( 3932): ag scb idx 1 not allocated
E/bt-btif ( 3932): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
I/bt_userial_vendor( 3932): device fd = 53 close
I/GKI_LINUX( 3932): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3932): GKI_exit_task 0 done
I/GKI_LINUX( 3932): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/HeadsetService( 3932): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/HeadsetStateMachine( 3932): Exit Disconnected: -1
D/BluetoothHeadset( 1162): Proxy object disconnected
,D/DockEventReceiver( 3125): finishStartingService: stopping service
,D/BluetoothHeadset( 1191): Proxy object disconnected
D/BluetoothHeadset(  758): Proxy object disconnected
D/BluetoothHeadset( 1162): Proxy object disconnected
,D/A2dpService( 3932): Received stop request...Stopping profile...
D/A2dpStateMachine( 3932): Exit Disconnected: -1
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/BluetoothA2dp(  758): Proxy object disconnected
,D/HidService( 3932): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/BluetoothAdapterState( 3932): Stopping profile services that were post enabled
,D/HealthService( 3932): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/PanService( 3932): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/HeadsetStateMachine( 3932): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3932): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3932): Cleaning up Bluetooth Handsfree callback object
D/BtGatt.DebugUtils( 3932): handleDebugAction() action=null
,D/BtGatt.GattService( 3932): Received stop request...Stopping profile...
D/BtGatt.GattService( 3932): stop()
D/BtGatt.AdvertiseManager( 3932): advertise clients cleared
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,I/GKI_LINUX( 3932): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3932): GKI_exit_task 2 done
I/GKI_LINUX( 3932): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BluetoothMapService( 3932): Received stop request...Stopping profile...
D/BluetoothMapService( 3932): stop()
,D/BluetoothMapEmailAppObserver( 3932): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3932): removeReceiver()
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,W/BluetoothHidServiceJni( 3932): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3932): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3932): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3932): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 3932): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3932): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3932): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3932): Handler(): got msg=4
D/BluetoothMapService( 3932): MAP Service closeService in
V/BluetoothMapService( 3932): MAP Service closeService out
,D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3932): Setting state to 10
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3932): cleanup()
D/BluetoothMapService( 3932): MAP Service closeService in
V/BluetoothMapService( 3932): MAP Service closeService out
,D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  758): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothPbap( 3125): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 3932): Entering OffState
D/BluetoothAdapterState( 3932): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3932): Setting state to 11
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3932): make
D/BluetoothHeadset( 3125): onBluetoothStateChange: up=false
,D/BluetoothMap( 3125): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  758): onBluetoothStateChange: up=false
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1162): onBluetoothStateChange: up=false
,D/HeadsetService( 3932): Received start request. Starting profile...
D/HeadsetStateMachine( 3932): make
D/BluetoothInputDevice( 3125): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3125): Proxy object disconnected
D/A2dpProfile( 3125): Bluetooth service disconnected
D/BluetoothPan( 3125): BluetoothPAN Proxy object disconnected
D/PanProfile( 3125): Bluetooth service disconnected
,D/HeadsetStateMachine( 3932): max_hf_connections = 1
I/bluedroid( 3932): get_profile_interface handsfree
D/BluetoothHeadset( 1191): onBluetoothStateChange: up=false
D/HeadsetStateMachine( 3932): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/BluetoothA2dp( 3125): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  758): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  758): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  758): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothAdapterState( 3932): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/A2dpService( 3932): Received start request. Starting profile...
I/bluedroid( 3932): get_profile_interface avrcp
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3125): finishStartingService: stopping service
,I/art     (  758): Explicit concurrent mark sweep GC freed 39708(1731KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 808us total 87.845ms
,E/RemoteController( 3932): Cannot set synchronization mode on an unregistered RemoteController
D/A2dpStateMachine( 3932): make
,I/bluedroid( 3932): get_profile_interface a2dp
I/GKI_LINUX( 3932): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/A2dpStateMachine( 3932): Enter Disconnected: -2
,D/HidService( 3932): Received start request. Starting profile...
I/bluedroid( 3932): get_profile_interface hidhost
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/HeadsetStateMachine( 3932): Proxy object connected
,D/HealthService( 3932): Received start request. Starting profile...
,I/bluedroid( 3932): get_profile_interface health
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/PanService( 3932): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3932): initializeNative(L110): pan
,I/bluedroid( 3932): get_profile_interface pan
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/HeadsetStateMachine( 3932): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3932): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3932): Disconnected process message: 11, size: 0
,D/BtGatt.DebugUtils( 3932): handleDebugAction() action=null
,D/BtGatt.GattService( 3932): Received start request. Starting profile...
D/BtGatt.GattService( 3932): start()
D/BtGatt.AdvertiseManager( 3932): advertise manager created
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
V/BluetoothMapService( 3932): BluetoothMapBinder()
D/BluetoothMapService( 3932): Received start request. Starting profile...
D/BluetoothMapService( 3932): start()
,D/BluetoothMapEmailSettingsLoader( 3932): Found 0 applications
D/BluetoothMapEmailAppObserver( 3932): createReceiver()
,D/BluetoothMapEmailAppObserver( 3932): initObservers()
,D/BluetoothMapEmailAppObserver( 3932): getEnabledAccountItems()
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,V/BluetoothMapService( 3932): Handler(): got msg=1
,D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 3932): enable
I/bt_hci_bdroid( 3932): init
I/GKI_LINUX( 3932): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3932): btu_task pending for preload complete event
,I/bt_vendor( 3932): init
I/bt_vnd_conf( 3932): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3932): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3932): userial_init
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3125): finishStartingService: stopping service
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_userial_vendor( 3932): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3932): device fd = 64 open
D/bt_userial( 3932): Entering userial_read_thread()
,I/bt_hwcfg( 3932): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3932): Chipset BCM4335C0
D/bt_hwcfg( 3932): Target name = [BCM4335C0]
,I/bt_hwcfg( 3932): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/bt_hwcfg( 3932): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3932): Settlement delay -- 100 ms
I/bt_hwcfg( 3932): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3932): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3932): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3932): vendor lib fwcfg completed
,I/bt-btu  ( 3932): btu_task received preload complete event
,I/        ( 3932): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3932): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3932): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3932): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3932): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3932): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3932): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3932): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3932): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3932): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3932): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3932): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3932): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3932): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3932): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3932): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3bd99d5 
E/bt-btm  ( 3932): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3bd99d5 
,E/bt-btif ( 3932): Calling BTA_HhEnable
E/bt-btif ( 3932): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3932): Address is:34:FC:EF:11:AE:67
,W/bt-smp  ( 3932): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3932): Plain text(LSB ~ MSB) = 3b 96 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3932): Encrypted text(LSB ~ MSB) = c0 e9 43 7e 91 fb d2 b4 5d 68 05 9d e3 7a 46 01 
,W/bt-btm  ( 3932): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3932): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3932): Scan Mode:20
D/BluetoothAdapterProperties( 3932): Discoverable Timeout:120
,D/bte_conf( 3932): Device ID record 1 : primary
D/bte_conf( 3932):   vendorId            = 000f
D/bte_conf( 3932):   vendorIdSource      = 0001
D/bte_conf( 3932):   product             = 1200
D/bte_conf( 3932):   version             = 1436
D/bte_conf( 3932):   clientExecutableURL = 
D/bte_conf( 3932):   serviceDescription  = 
D/bte_conf( 3932):   documentationURL    = 
D/bte_conf( 3932): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3932): ScanMode =  20
D/BluetoothAdapterProperties( 3932): State =  11
,D/BluetoothAdapterProperties( 3932): Setting state to 12
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  758): Broadcasting onBluetoothStateChange(true) to 11 receivers.
,I/BluetoothAdapterState( 3932): Entering On State
,D/BluetoothPbap( 3125): onBluetoothStateChange: up=true
,D/BluetoothPanServiceJni( 3932): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,E/bt_h4   ( 3932): vendor lib postload completed
,D/BluetoothAdapterProperties( 3932): Scan Mode:21
D/BluetoothAdapterProperties( 3932): Discoverable Timeout:120
,D/BluetoothManagerService(  758): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  758): Stored Bluetooth name: Nexus 5
,D/BluetoothHeadset( 3125): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 3125): Proxy object connected
D/HeadsetProfile( 3125): Bluetooth service connected
,D/BluetoothMap( 3125): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  758): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  758): Proxy object connected
,D/BluetoothHeadset( 1162): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1162): Proxy object connected
,D/BluetoothHeadset( 1162): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1162): Proxy object connected
,D/BluetoothInputDevice( 3125): onBluetoothStateChange: up=true
,D/BluetoothPan( 3125): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset( 1191): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1191): Proxy object connected
,D/BluetoothA2dp( 3125): onBluetoothStateChange: up=true
,D/BluetoothMap( 3125): Proxy object connected
D/MapProfile( 3125): Bluetooth service connected
D/BluetoothMap( 3125): getConnectedDevices()
,I/BT      ( 3048): Bluetooth DISABLED, stopping
I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stop Bluetooth
,D/BluetoothA2dp(  758): onBluetoothStateChange: up=true
,I/BT      ( 3048): Bluetooth enabled, re-starting
I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stop Bluetooth
I/        ( 3048): Starting All
I/        ( 3048): Stopping services
I/        ( 3048): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@3982bae9
I/        ( 3048): Stopping services
I/        ( 3048): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}
,D/BluetoothA2dp(  758): Proxy object connected
,I/        ( 3048): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5146","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3048): peerDiscoveryTimer timeout value:9039
,D/BluetoothManagerService(  758): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3932): onReceive
D/BluetoothMapService( 3932): STATE_ON
V/BluetoothMapService( 3932): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3932): Map Service startRfcommSocketListener
I/Telecom ( 1162): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothMapMasInstance( 3932): MAS initSocket()
D/BluetoothMapMasInstance( 3932):   masId = 00
D/BluetoothMapMasInstance( 3932):   msgTypes = 0e
D/BluetoothMapMasInstance( 3932):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3932):   SDP string = 000eSMS/MMS
V/BluetoothMapService( 3932): getConnectedDevices()
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothInputDevice( 3125): Proxy object connected
D/HidProfile( 3125): Bluetooth service connected
,I/        ( 3048): Stop Bluetooth
I/        ( 3048): StartBluetooth listener
I/        ( 3048): StartBluetooth listener
D/HeadsetStateMachine( 3932): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 3932): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3932): mNumber:  mType: 128
D/HeadsetStateMachine( 3932): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3932): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3932): getBluetoothService() called with no BluetoothManagerCallback
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3932): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3932): Accepting socket connection...
,I/        ( 3048): Discovery state changed to Started.
,I/BTListenerThread( 3048): starting to listen
I/BTListenerThread( 3048): waiting to accept incoming Connection
,D/BluetoothPan( 3125): BluetoothPAN Proxy object connected
D/PanProfile( 3125): Bluetooth service connected
,D/BluetoothA2dp( 3125): Proxy object connected
D/A2dpProfile( 3125): Bluetooth service connected
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3125): finishStartingService: stopping service
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3932): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbap( 3125): Proxy object connected
D/PbapServerProfile( 3125): Bluetooth service connected
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3932): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3932): Accept thread started.
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:38:94:96:B5:06:DC OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 38:94:96:B5:06:DC not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 38:94:96:B5:06:DC, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 38:94:96:B5:06:DC
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 38:94:96:B5:06:DC not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:38:94:96:B5:06:DC OldState: 11 NewState: 10
,E/BluetoothEventManager( 3125): Got bonding state changed for 38:94:96:B5:06:DC, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
,I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G800H_PT5954
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:12:59.485Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/wpa_supplicant( 3124): P2P-FIND-STOPPED 
,I/        ( 3048): Cleared local services
I/        ( 3048): Cleared service requests
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 3048): 2015-12-04T08:12:59.494Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:12:59.494Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,I/        ( 3048): Stopped peer discovery
,I/        ( 3048): Added local service
I/        ( 3048): Cleared service requests
,I/        ( 3048): Stopped peer discovery
,I/        ( 3048): Started peer discovery
,I/        ( 3048): Cleared local services
,I/wpa_supplicant( 3124): P2P-FIND-STOPPED 
,I/        ( 3048): Cleared service requests
,I/        ( 3048): Stopped peer discovery
,I/        ( 3048): Added local service
I/        ( 3048): Cleared service requests
,I/        ( 3048): Stopped peer discovery
,I/        ( 3048): Started peer discovery
,I/        ( 3048): Discovery state changed to Stopped.
,I/        ( 3048): Started peer discovery
,I/SS      ( 3048): We got empty peers list
,I/SS      ( 3048): We got empty peers list
,I/SS      ( 3048): We got empty peers list
,I/SS      ( 3048): We got empty peers list
,I/SS      ( 3048): We got empty peers list
I/SS      ( 3048): We got empty peers list
,I/SS      ( 3048): We got empty peers list
,I/        ( 3048): Discovery state changed to Started.
I/SS      ( 3048): We got empty peers list
,I/jxcore-log( 3048): 2015-12-04T08:13:00.525Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.534Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.540Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.549Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.557Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.609Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.642Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.654Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.691Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.706Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.741Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.754Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.793Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.803Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.840Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.908Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.939Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.948Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.959Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:00.989Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:13:04.503Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:04.510Z SendDataConnector.js: Connect (retry count 2) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:04.510Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:04.511Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 38:94:96:B5:06:DC, name: Galaxy S5-2
,I/        ( 3048): Connecting to Galaxy S5-2, at 38:94:96:B5:06:DC
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G800H_PT5954
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G800H_PT5954
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 46202
,I/BtConnectorHelper( 3048): Request socket is using : 46202
I/BtToRequestSocket( 3048): Now accepting connections
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :46202
,I/jxcore-log( 3048): 2015-12-04T08:13:05.324Z SendDataConnector.js: CLIENT connected to 46202, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:05.325Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 46202
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:13:05.353Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 2 peers.
I/SS      ( 3048): Peer(1): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(2): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 3048): 2015-12-04T08:13:06.595Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:06.751Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 3048): 2015-12-04T08:13:06.830Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:06.932Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 3048): 2015-12-04T08:13:07.113Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:13:08.254Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 84 bytes.
,I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT3449
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT3449
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:13:08.924Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:13:09.466Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:09.595Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:09.705Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:10.270Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:10.420Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:10.532Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:10.831Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:11.039Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): invalid rfc slot id: 3
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:13:11.093Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:11.731Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:13:12.127Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.640Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.648Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.750Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.843Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.857Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.893Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.921Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.928Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:12.961Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:13.102Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:13.395Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:14.030Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:14.089Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:14.370Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.360Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.472Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.771Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.802Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.813Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.849Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.879Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.913Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.920Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:15.952Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.049Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.263Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.303Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.314Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.349Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/jxcore-log( 3048): 2015-12-04T08:13:16.376Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.383Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.419Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.449Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.496Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.526Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.568Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.607Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.642Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.649Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.656Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:16.683Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 1
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 3 peers.
I/SS      ( 3048): Peer(1): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(3): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:13:20.270Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:20.270Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:20.270Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:20.270Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:20.270Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G800H_PT5954
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:13:23.086Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3048): 2015-12-04T08:13:23.621Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:23.649Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:23.738Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:23.754Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:24.031Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:25.271Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:25.272Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 3932): invalid rfc slot id: 6
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT3449
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:13:29.641Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:30.276Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:30.276Z SendDataConnector.js: Connect (retry count 3) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:30.282Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:13:30.285Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 38:94:96:B5:06:DC, name: Galaxy S5-2
,I/        ( 3048): Connecting to Galaxy S5-2, at 38:94:96:B5:06:DC
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x47
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d50ebc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3048): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G800H_PT5954
,I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G800H_PT5954
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 39794
I/BtConnectorHelper( 3048): Request socket is using : 39794
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :39794
I/jxcore-log( 3048): 2015-12-04T08:13:33.187Z SendDataConnector.js: CLIENT connected to 39794, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:33.188Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 39794
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:13:33.211Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): invalid rfc slot id: 8
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:13:33.710Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 6 peers.
I/SS      ( 3048): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
,W/bt-btif ( 3932): proc dm_pm_timer expires
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3048): 2015-12-04T08:13:43.282Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:43.282Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:43.284Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:43.284Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:43.285Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G800H_PT5954
I/BtToSocketBase( 3048): Stop ReceivingThread
,I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
,I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 3048): 2015-12-04T08:13:48.286Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:48.287Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Galaxy S5-2
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/jxcore-log( 3048): 2015-12-04T08:13:53.289Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:53.289Z SendDataConnector.js: Connect (retry count 4) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:53.289Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:13:53.289Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 38:94:96:B5:06:DC, name: Galaxy S5-2
,I/        ( 3048): Connecting to Galaxy S5-2, at 38:94:96:B5:06:DC
,I/BTConnectToThread( 3048): Starting to connect
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 7 peers.
I/SS      ( 3048): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/        ( 3048): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2828, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2828, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 7 peers.
I/SS      ( 3048): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2828, peerAddress: 08:EC:A9:50:76:27
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2828, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 9 peers.
I/SS      ( 3048): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3048): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3048): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 11
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:14:24.383Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 38:94:96:B5:06:DC failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:24.383Z SendDataConnector.js: CLIENT Can not Connect: Connection to 38:94:96:B5:06:DC failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:24.400Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:24.401Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:24.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- gotta redo : 38:94:96:B5:06:DC, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:24.412Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:24.412Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:24.413Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3048): Connecting to null, at 7C:F9:0E:37:96:AB
I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 38:94:96:B5:06:DC done with result: Connection to 38:94:96:B5:06:DC failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().,
,E/BluetoothEventManager( 3125): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-A500FU_PT1688
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-A500FU_PT1688
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-A500FU_PT1688
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 56820
I/BtConnectorHelper( 3048): Request socket is using : 56820
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :56820
I/jxcore-log( 3048): 2015-12-04T08:14:26.330Z SendDataConnector.js: CLIENT connected to 56820, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:26.331Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 56820
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:14:26.352Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 3048): 2015-12-04T08:14:27.179Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:27.249Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14088
,I/jxcore-log( 3048): 2015-12-04T08:14:27.428Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:27.575Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4188
,I/jxcore-log( 3048): 2015-12-04T08:14:27.731Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:27.790Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:27.816Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:28.022Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): dm_pm_timer expires
,W/bt-btif ( 3932): dm_pm_timer expires 0
,W/bt-btif ( 3932): proc dm_pm_timer expires
,I/jxcore-log( 3048): 2015-12-04T08:14:38.023Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:38.024Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:38.026Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:38.033Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:38.034Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-A500FU_PT1688
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3048): 2015-12-04T08:14:43.034Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:43.035Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A5-1
,I/jxcore-log( 3048): 2015-12-04T08:14:48.038Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:48.039Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:48.041Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:14:48.042Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3048): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-A500FU_PT1688
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-A500FU_PT1688
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-A500FU_PT1688
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 45405
I/BtConnectorHelper( 3048): Request socket is using : 45405
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :45405
I/jxcore-log( 3048): 2015-12-04T08:14:53.956Z SendDataConnector.js: CLIENT connected to 45405, error: null
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:14:53.957Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 45405
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:14:53.979Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/jxcore-log( 3048): 2015-12-04T08:15:04.044Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:04.045Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:04.046Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:04.047Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:04.055Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-A500FU_PT1688
I/BtToSocketBase( 3048): Stop ReceivingThread
,I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
,I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 3048): 2015-12-04T08:15:09.053Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:09.054Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A5-1
,I/jxcore-log( 3048): 2015-12-04T08:15:14.059Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:14.059Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:14.060Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:14.060Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3048): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3932): invalid rfc slot id: 14
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:15:19.243Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:19.243Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:19.244Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 9 peers.
I/SS      ( 3048): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3048): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3048): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:15:24.247Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:24.249Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:15:29.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:29.254Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:29.255Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:29.255Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3048): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 15
I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:15:34.428Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:34.428Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:34.428Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, motorola-XT1039_PT8025
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:15:35.508Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:15:36.450Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:36.826Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:36.841Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:36.903Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:36.913Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:36.929Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.004Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.042Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.055Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.120Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.160Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.176Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.191Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.202Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.239Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.248Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.279Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.295Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.312Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.325Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.362Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.379Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.411Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.441Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.448Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:37.479Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:39.428Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:39.429Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:15:44.432Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:44.432Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:44.433Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:15:44.433Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3048): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A5-1
,W/bt-btif ( 3932): invalid rfc slot id: 9
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:15:47.981Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
,W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3048): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-A500FU_PT1688
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-A500FU_PT1688
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-A500FU_PT1688
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 47308
I/BtConnectorHelper( 3048): Request socket is using : 47308
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :47308
,I/jxcore-log( 3048): 2015-12-04T08:15:50.066Z SendDataConnector.js: CLIENT connected to 47308, error: null
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:50.071Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 47308
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:15:50.107Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, motorola-XT1039_PT8025
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:15:58.638Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:15:59.075Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:59.087Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:15:59.094Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:00.155Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:00.156Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:00.160Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:00.176Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:00.176Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:00.180Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/BtConnectorHelper( 3048): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
I/jxcore-log( 3048): 2015-12-04T08:16:00.221Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:00.224Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:00.232Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:00.232Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:75:41
I/jxcore-log( 3048): 2015-12-04T08:16:00.243Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 19
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:16:00.678Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:00.679Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:00.679Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:16:05.680Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:05.681Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
,W/bt-btm  ( 3932): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=2
,W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A5-1,
,W/bt-btif ( 3932): invalid rfc slot id: 16
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:16:09.121Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x4b
,I/jxcore-log( 3048): 2015-12-04T08:16:10.684Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:10.685Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:10.686Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:10.686Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 20
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:16:13.272Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:13.272Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:13.273Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3048): 2015-12-04T08:16:18.274Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:18.275Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, motorola-XT1039_PT8025
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:16:20.634Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:16:21.046Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:21.056Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:21.065Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:21.077Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:23.280Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:23.281Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:23.281Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:23.282Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 22
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:16:27.485Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:27.486Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:27.487Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 5 peers.
I/SS      ( 3048): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,W/bt-btif ( 3932): invalid rfc slot id: 18
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:16:31.094Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
I/        ( 3048): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT2828","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT2828, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT2828, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x4e
,I/jxcore-log( 3048): 2015-12-04T08:16:32.491Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:32.492Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,I/jxcore-log( 3048): 2015-12-04T08:16:37.495Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:37.496Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:37.497Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:37.501Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x1f  CID 0x40
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 23
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:16:39.265Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:39.266Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:39.266Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 4 peers.
I/SS      ( 3048): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/jxcore-log( 3048): 2015-12-04T08:16:44.271Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:44.272Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, motorola-XT1039_PT8025
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:16:46.190Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:16:46.646Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:46.677Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:46.700Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:46.710Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:46.715Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:46.763Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:16:49.275Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:49.275Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:49.276Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:49.276Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 25
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3048): 2015-12-04T08:16:53.651Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:53.651Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:53.669Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:53.683Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:53.696Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:53.696Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:53.696Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3048): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): invalid rfc slot id: 21
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
,I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
,I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:16:57.012Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x43
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,W/bt-btm  ( 3932): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d515dc rs_disc_pending=2
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3048): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 45912
I/BtConnectorHelper( 3048): Request socket is using : 45912
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :45912
I/jxcore-log( 3048): 2015-12-04T08:16:58.951Z SendDataConnector.js: CLIENT connected to 45912, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:16:58.952Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 45912
I/BtToRequestSocket( 3048): Set local streams
,I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:16:58.984Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:402
,I/jxcore-log( 3048): 2015-12-04T08:16:59.905Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:16:59.988Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:00.061Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:00.152Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:00.233Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:00.309Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:00.391Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:00.472Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:00.479Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3048): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:17:10.480Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:10.480Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:10.482Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:10.482Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:10.483Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G900F_PT2753
,I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : motorola-XT1039_PT8025
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, motorola-XT1039_PT8025
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:17:12.306Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:17:13.929Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:13.938Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:14.025Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:14.049Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:14.056Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:14.184Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data,
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:17:15.484Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:15.485Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 9 peers.
I/SS      ( 3048): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:17:20.490Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:20.491Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:20.491Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:20.492Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 3048): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:34:8a:a0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT8025
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,W/bt-btif ( 3932): invalid rfc slot id: 24
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:17:22.936Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 44900
I/BtConnectorHelper( 3048): Request socket is using : 44900
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :44900
I/jxcore-log( 3048): 2015-12-04T08:17:27.294Z SendDataConnector.js: CLIENT connected to 44900, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:27.295Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 44900
I/BtToRequestSocket( 3048): Set local streams
,I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:17:27.319Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51414 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: XT1039
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/jxcore-log( 3048): 2015-12-04T08:17:37.410Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:37.411Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:37.412Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:37.413Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:37.414Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
,I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,I/jxcore-log( 3048): 2015-12-04T08:17:42.414Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:42.415Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:47.420Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:47.421Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:47.422Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:47.429Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 3048): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:34:8a:a0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 33859
I/BtConnectorHelper( 3048): Request socket is using : 33859
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :33859
I/jxcore-log( 3048): 2015-12-04T08:17:49.625Z SendDataConnector.js: CLIENT connected to 33859, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:49.626Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 33859
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:17:49.645Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
,W/bt-btif ( 3932): proc dm_pm_timer expires
,I/jxcore-log( 3048): 2015-12-04T08:17:59.714Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:59.715Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:17:59.716Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:59.717Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:17:59.725Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G900F_PT2753
,I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 3048): 2015-12-04T08:18:04.723Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:04.724Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,I/jxcore-log( 3048): 2015-12-04T08:18:09.727Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:09.729Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:09.730Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:09.731Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 3048): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 35696
I/BtConnectorHelper( 3048): Request socket is using : 35696
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :35696
I/jxcore-log( 3048): 2015-12-04T08:18:12.215Z SendDataConnector.js: CLIENT connected to 35696, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:12.216Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 35696
I/BtToRequestSocket( 3048): Set local streams
,I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:18:12.273Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/        ( 3048): Cleared service requests
,I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT5363
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/jxcore-log( 3048): 2015-12-04T08:18:19.123Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 11 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3048): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:18:19.860Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:19.940Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:18:20.265Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:20.293Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:18:20.483Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:20.828Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:18:20.899Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:20.989Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:20.994Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.033Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.043Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.189Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.479Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.520Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.736Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.769Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:21.871Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:22.198Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:18:22.318Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:22.318Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:22.320Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:22.320Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:22.321Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3048): Disconnect outgoing peer: samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Close bt socket
,I/BtToRequestSocket( 3048): Close server socket
,I/jxcore-log( 3048): 2015-12-04T08:18:22.363Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:22.484Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:22.605Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:18:22.646Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:22.652Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/jxcore-log( 3048): 2015-12-04T08:18:22.928Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:18:23.206Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:23.239Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:23.575Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:23.687Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3048): 2015-12-04T08:18:23.884Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3048): 2015-12-04T08:18:24.122Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:24.129Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:24.141Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:24.149Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:24.159Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:24.196Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/jxcore-log( 3048): 2015-12-04T08:18:24.345Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:24.435Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:24.480Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.068Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.100Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.158Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.465Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.623Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.658Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.671Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.856Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:25.865Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,I/        ( 3048): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT5544, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT5544, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3048): 2015-12-04T08:18:27.321Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:27.322Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3048): 2015-12-04T08:18:32.326Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:32.329Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:32.329Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:32.330Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 3048): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3048): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : samsung-SM-G900F_PT2753
I/HS      ( 3048): Hand Shake finished outgoing for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 40218
,I/BtConnectorHelper( 3048): Request socket is using : 40218
,I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :40218
I/jxcore-log( 3048): 2015-12-04T08:18:34.610Z SendDataConnector.js: CLIENT connected to 40218, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:34.611Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 40218
I/BtToRequestSocket( 3048): Set local streams
,I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:18:34.638Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): invalid rfc slot id: 27
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): Stop ReceivingThread
,I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:18:35.777Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x42
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8707, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8707, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
,W/bt-btif ( 3932): proc dm_pm_timer expires
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3048): 2015-12-04T08:18:44.704Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:44.705Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:44.706Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:44.723Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:44.723Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:44.724Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/BtConnectorHelper( 3048): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
I/jxcore-log( 3048): 2015-12-04T08:18:44.754Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- gotta redo : 7C:F9:0E:34:8A:A0, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:44.755Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:44.755Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:18:44.755Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3048): Connecting to null, at 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 2015-12-04T08:18:44.758Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT5363
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:18:48.082Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 5 peers.
I/SS      ( 3048): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:18:48.597Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:48.754Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:48.842Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:18:49.006Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:18:49.015Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-btif ( 3932): invalid rfc slot id: 31
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:18:58.706Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [34:fc:ef:11:b1:66]: 7, f, 610c
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT5363
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:19:09.523Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:19:09.949Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:09.956Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:09.963Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:09.970Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:10.002Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 8 peers.
I/SS      ( 3048): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3048): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3048): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT2368","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT2368, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT2368, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x22  CID 0x48
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 33
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3048): 2015-12-04T08:19:18.116Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:18.120Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:18.123Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8707, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8707, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3932): invalid rfc slot id: 34
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:19:20.269Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 3048): 2015-12-04T08:19:23.131Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:19:23.132Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3048): 2015-12-04T08:19:28.136Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:19:28.136Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:28.140Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:28.141Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3048): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): No ag scb for peer addr
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT5363
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:19:31.896Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:19:32.329Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:32.370Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:32.489Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:32.576Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:32.591Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:19:32.596Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 9 peers.
I/SS      ( 3048): Peer(1): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3048): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3048): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT5363
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,W/bt-btif ( 3932): invalid rfc slot id: 35
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:19:42.696Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3048): Found 9 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3048): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5196c rs_disc_pending=0
,W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6390, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6390, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3048): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: Galaxy S5-2, WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3048): Found 10 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): G3-1 02:9a:02:7b:60:ac
,I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3048): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3048): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT6390, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT6390, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/BtConnection( 3048): connectionTimeoutTimer
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3932): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:36, channel:-1
,I/CONNEC  ( 3048): Error: Cancelled
I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:20:28.170Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:28.170Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:28.171Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
W/jxcore-log( 3048): $$jxcore_callback_58 wasn't registered
W/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 10 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd,
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1688, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1688, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3048): 2015-12-04T08:20:33.172Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:33.172Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/jxcore-log( 3048): 2015-12-04T08:20:38.175Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:38.176Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:20:38.177Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:20:38.180Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3048): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:2, scn:-678686541
,W/bt-btif ( 3932): invalid rfc slot id: 38
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:20:38.223Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:38.224Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:38.224Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:20:43.224Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:43.225Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3048): Found 11 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1688, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1688, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3048): 2015-12-04T08:20:48.229Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:48.229Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:48.230Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:48.230Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3048): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:2, scn:-678686541
,W/bt-btif ( 3932): invalid rfc slot id: 39
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:20:48.282Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:48.282Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:48.283Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT8025"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT8025, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT8025, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3932): invalid rfc slot id: 36
E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,I/jxcore-log( 3048): 2015-12-04T08:20:53.304Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:53.305Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
,E/bt-l2cap( 3932): L2CAP got conn_comp in bad state: 5  status: 0x15
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 12 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3048): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(10): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(11): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(12): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/jxcore-log( 3048): 2015-12-04T08:20:58.306Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:58.306Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:58.306Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:58.306Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3048): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D802_PT5431
,I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D802_PT5431
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D802_PT5431
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 40288
I/BtConnectorHelper( 3048): Request socket is using : 40288
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :40288
I/jxcore-log( 3048): 2015-12-04T08:20:59.931Z SendDataConnector.js: CLIENT connected to 40288, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:20:59.932Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 40288
I/BtToRequestSocket( 3048): Set local streams
,I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:20:59.973Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT5544","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT5544, peerAddress: E0:DB:10:1F:C9:5E
I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT5544, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3048): 2015-12-04T08:21:00.503Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:00.676Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:00.786Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:01.103Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:01.280Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:01.308Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51b34 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:21:01.591Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:01.804Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:02.573Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
,W/bt-btif ( 3932): proc dm_pm_timer expires
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 13 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(8): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(10): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(11): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3048): Peer(12): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3048): Peer(13): S5mini-1 02:f4:6f:30:e0:6d,
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:21:12.574Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:12.575Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:12.576Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:12.592Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:12.593Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:12.593Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/BtConnectorHelper( 3048): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
I/jxcore-log( 3048): 2015-12-04T08:21:12.639Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:12.639Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:12.639Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:12.639Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:76:27
,I/jxcore-log( 3048): 2015-12-04T08:21:12.645Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51b34 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 41
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:21:15.094Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:15.094Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:15.095Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: Thali Test's G2
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3048): 2015-12-04T08:21:20.095Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:20.096Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/jxcore-log( 3048): 2015-12-04T08:21:25.102Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:25.102Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:25.103Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:25.103Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:76:27]: 6, f, 4106
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 42
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:21:26.513Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:26.513Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:26.514Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 14 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3048): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3048): Peer(10): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(11): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(12): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(13): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(14): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3048): 2015-12-04T08:21:31.517Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:31.518Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:36.521Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:36.522Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:36.522Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:36.523Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 43
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:21:38.042Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:38.043Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:38.044Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3048): 2015-12-04T08:21:43.045Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:43.046Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:48.051Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:48.052Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:48.052Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:48.053Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 44
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:21:48.258Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:48.258Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:48.259Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3048): 2015-12-04T08:21:53.259Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:53.259Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:21:58.261Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:58.261Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:58.262Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:21:58.262Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3048): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3048): Starting to connect
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 45
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:22:01.079Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:01.080Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:01.096Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:01.099Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:01.102Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:01.102Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:01.103Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3048): Connecting to null, at 58:3F:54:73:64:C0
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 46
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3048): 2015-12-04T08:22:06.269Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:06.291Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:06.292Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/jxcore-log( 3048): 2015-12-04T08:22:11.307Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:11.308Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:16.312Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:16.313Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:16.314Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:16.314Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3048): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 47
I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:22:21.489Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:21.489Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:21.489Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:26.489Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:26.490Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 10 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/jxcore-log( 3048): 2015-12-04T08:22:31.495Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:31.496Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:31.496Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:31.497Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3048): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3048): Starting to connect
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D855_PT6390
I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D855_PT6390
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D855_PT6390
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 45053
I/BtConnectorHelper( 3048): Request socket is using : 45053
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :45053
I/jxcore-log( 3048): 2015-12-04T08:22:33.371Z SendDataConnector.js: CLIENT connected to 45053, error: null
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:33.371Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 45053
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:22:33.396Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24978
,I/jxcore-log( 3048): 2015-12-04T08:22:33.982Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18048
,I/jxcore-log( 3048): 2015-12-04T08:22:34.043Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8148
,I/jxcore-log( 3048): 2015-12-04T08:22:34.085Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:34.118Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3048): 
,D/        ( 3932): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3198
,I/jxcore-log( 3048): 2015-12-04T08:22:34.210Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:34.260Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:34.289Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:34.378Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:34.402Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51ec4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/BTListenerThread( 3048): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7753","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:22:39.511Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:22:40.279Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.281Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.292Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.302Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.309Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.317Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.327Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.369Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.378Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.386Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.409Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.439Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.455Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.489Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.500Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.534Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.544Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.554Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.593Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.610Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.640Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.649Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.657Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.672Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.682Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.691Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:40.728Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 6 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/jxcore-log( 3048): 2015-12-04T08:22:44.402Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:44.402Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:44.402Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:44.402Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:44.402Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: LGE-LG-D855_PT6390
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51ec4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8707, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8707, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1688, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1688, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/UsageStatsService(  758): User[0] Flushing usage stats to disk
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3-1
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3048): 2015-12-04T08:22:49.402Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:49.403Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): invalid rfc slot id: 37
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:22:51.618Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x4d
,I/jxcore-log( 3048): 2015-12-04T08:22:54.406Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:54.407Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:54.412Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:54.415Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 58:3F:54:73:64:C0, name: G3-1
,I/        ( 3048): Connecting to G3-1, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3048): Starting to connect
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A5-1
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:3f:54:73:64:c0]: 7, f, 610c
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D855_PT6390
,I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D855_PT6390
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D855_PT6390
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 60043
,I/BtConnectorHelper( 3048): Request socket is using : 60043
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :60043
,I/jxcore-log( 3048): 2015-12-04T08:22:57.045Z SendDataConnector.js: CLIENT connected to 60043, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:22:57.046Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 60043
I/BtToRequestSocket( 3048): Set local streams
,I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:22:57.068Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/        ( 3048): Cleared service requests
,I/        ( 3048): Started peer discovery
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
,W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3048): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1688","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT1688
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-A500FU_PT1688
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:22:58.702Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:22:59.580Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.598Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.612Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.677Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.678Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.685Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.694Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.777Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.783Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.920Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:22:59.926Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.023Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.059Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.100Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.107Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.130Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.137Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.210Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.249Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.323Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:23:00.534Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.591Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.660Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.755Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:00.944Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 8 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/jxcore-log( 3048): 2015-12-04T08:23:01.177Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:01.359Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:01.596Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:01.603Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:01.614Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:23:01.713Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:01.750Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:01.828Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:01.830Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:02.010Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:02.040Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/jxcore-log( 3048): 2015-12-04T08:23:02.269Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Started service discovery
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7753","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:23:02.876Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:03.237Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:23:03.362Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:03.441Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:03.450Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:23:03.520Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:03.528Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:03.639Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:03.672Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:03.973Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:04.292Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:04.370Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:23:04.531Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 3048): 2015-12-04T08:23:04.771Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:05.127Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:05.141Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:23:07.124Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:07.125Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:07.126Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:07.126Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:07.135Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: LGE-LG-D855_PT6390
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/jxcore-log( 3048): 2015-12-04T08:23:12.133Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:12.133Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): invalid rfc slot id: 51
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:23:13.608Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5124c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): invalid rfc slot id: 49
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT1688
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:23:14.633Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x4f
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 11 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3048): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:23:17.139Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:17.140Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:17.141Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:17.141Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: 58:3F:54:73:64:C0, name: G3-1
,I/        ( 3048): Connecting to G3-1, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT6390","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D855_PT6390
I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D855_PT6390
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D855_PT6390
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 33122
I/BtConnectorHelper( 3048): Request socket is using : 33122
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :33122
I/jxcore-log( 3048): 2015-12-04T08:23:22.650Z SendDataConnector.js: CLIENT connected to 33122, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:22.651Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 33122
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:23:22.673Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7753","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7753
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7753
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:23:24.705Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d51ec4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:23:25.124Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:25.134Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:25.142Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): dm_pm_timer expires
,W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/jxcore-log( 3048): 2015-12-04T08:23:32.743Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:32.743Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:32.745Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:32.763Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:32.764Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:32.764Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/BtConnectorHelper( 3048): Disconnect outgoing peer: 58:3F:54:73:64:C0
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,I/jxcore-log( 3048): 2015-12-04T08:23:32.804Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:32.805Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:32.806Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:32.806Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3048): Connecting to null, at F8:95:C7:87:85:54
I/jxcore-log( 3048): 2015-12-04T08:23:32.809Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3932): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3932): invalid rfc slot id: 52
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: F8:95:C7:87:85:54
,I/BtToSocketBase( 3048): Close bt socket
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/jxcore-log( 3048): 2015-12-04T08:23:35.607Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D722_PT9142
I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D722_PT9142
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 50616
I/BtConnectorHelper( 3048): Request socket is using : 50616
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :50616
I/jxcore-log( 3048): 2015-12-04T08:23:36.918Z SendDataConnector.js: CLIENT connected to 50616, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:36.918Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 50616
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:23:36.942Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:37.545Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3048): 2015-12-04T08:23:37.607Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:37.722Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:37.844Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:37.972Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:38.164Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:38.216Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:38.271Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:38.704Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3-1
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:2a:f7:ed:96:be]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7753","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7753
I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:23:46.780Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:47.181Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:47.191Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:47.199Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:47.217Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:23:48.704Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:48.705Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:48.706Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:48.706Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:48.711Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3048): 2015-12-04T08:23:53.711Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:53.712Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): invalid rfc slot id: 54
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:23:57.622Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:23:58.712Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:58.713Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:58.713Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:23:58.713Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3048): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x4c
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f8:95:c7:87:85:54]: 6, 10f, 608
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D722_PT9142
I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D722_PT9142
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D722_PT9142
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 39445
I/BtConnectorHelper( 3048): Request socket is using : 39445
I/BtToRequestSocket( 3048): Now accepting connections
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :39445
I/jxcore-log( 3048): 2015-12-04T08:24:03.162Z SendDataConnector.js: CLIENT connected to 39445, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:03.162Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 39445
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:24:03.174Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
,W/bt-btif ( 3932): proc dm_pm_timer expires
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT7753","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
,I/HS      ( 3048): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT7753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:24:08.824Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:24:09.211Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:24:09.227Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:24:13.256Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:24:13.261Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:13.262Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:13.263Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:13.264Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 4 peers.
I/SS      ( 3048): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3048): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3048): 2015-12-04T08:24:18.263Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:18.264Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3932): invalid rfc slot id: 56
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT7753
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:24:19.720Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,I/art     (  758): Explicit concurrent mark sweep GC freed 66159(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.071ms total 137.197ms
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x49
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8707, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8707, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3048): 2015-12-04T08:24:23.269Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:23.270Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:23.270Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:23.271Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3048): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d5208c rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f8:95:c7:87:85:54]: 6, 10f, 608
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().,
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D722_PT9142
I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D722_PT9142
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 56338
I/BtConnectorHelper( 3048): Request socket is using : 56338
I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :56338
I/jxcore-log( 3048): 2015-12-04T08:24:28.190Z SendDataConnector.js: CLIENT connected to 56338, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:28.191Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 56338
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:24:28.217Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 7 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3048): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT4577"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT4577, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT4577, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3048): 2015-12-04T08:24:38.283Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:38.284Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:38.285Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:38.285Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:24:38.286Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
,I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8707, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8707, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:24:43.287Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:43.289Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:24:48.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:48.293Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:48.293Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:48.294Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3048): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,I/        ( 3048): Cleared service requests
,I/        ( 3048): Started peer discovery
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
,I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D722_PT9142
I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D722_PT9142
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 39217
,I/BtConnectorHelper( 3048): Request socket is using : 39217
,I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :39217
I/jxcore-log( 3048): 2015-12-04T08:24:52.109Z SendDataConnector.js: CLIENT connected to 39217, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:24:52.109Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 39217
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:24:52.142Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 8 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3048): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3048): 2015-12-04T08:25:02.201Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:02.202Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:02.203Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:02.204Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:02.205Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,I/BtToSocketBase( 3048): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3048): Disconnect outgoing peer: LGE-LG-D722_PT9142
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/jxcore-log( 3048): 2015-12-04T08:25:07.205Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:07.205Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3048): Found 9 peers.
,I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3048): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/jxcore-log( 3048): 2015-12-04T08:25:12.209Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:12.210Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:12.211Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:12.211Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3048): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3932): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3932): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3932): Entering PendingCommandState State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3932): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3932): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3932): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3932): StableState(): Entering Off State
,W/BluetoothEventManager( 3125): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3125): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3048): Starting to Handshake
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3048): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTConnectToThread( 3048): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3048): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3048): HandshakeOk : LGE-LG-D722_PT9142
I/HS      ( 3048): Hand Shake finished outgoing for : LGE-LG-D722_PT9142
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : false, LGE-LG-D722_PT9142
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3048): mHTTPPort  set to : 56904
I/BtConnectorHelper( 3048): Request socket is using : 56904
,I/BtToRequestSocket( 3048): Now accepting connections
,I/BtConnectorHelper( 3048): Calling ConnectionStatusUpdate with port :56904
,I/jxcore-log( 3048): 2015-12-04T08:25:14.311Z SendDataConnector.js: CLIENT connected to 56904, error: null
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:14.313Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): incoming data from: /127.0.0.1, port: 56904
I/BtToRequestSocket( 3048): Set local streams
I/BtToRequestSocket( 3048): rin ended ---------------------------;
,I/jxcore-log( 3048): 2015-12-04T08:25:14.338Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3932): dm_pm_timer expires
W/bt-btif ( 3932): dm_pm_timer expires 0
W/bt-btif ( 3932): proc dm_pm_timer expires
,I/jxcore-log( 3048): 2015-12-04T08:25:24.400Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:24.400Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:24.402Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:24.429Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:24.433Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:24.434Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3048): 
I/BtConnectorHelper( 3048): Disconnect outgoing peer: F8:95:C7:87:85:54
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
,I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
I/BtToRequestSocket( 3048): Close server socket
,I/jxcore-log( 3048): 2015-12-04T08:25:24.443Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- round done--------
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): do fake peer & start
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:24.443Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:24.444Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:24.444Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3048): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3048): 2015-12-04T08:25:24.455Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3048): 
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d52254 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3932): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G900F_PT2753
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
,I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:25:34.432Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:25:35.552Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:35.579Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:35.615Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:35.624Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:35.643Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:35.653Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:35.684Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:25:35.722Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:35.731Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.063Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.112Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.303Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.371Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.420Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.428Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.465Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.500Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.581Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.588Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.609Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.650Z SendDataTCPServer.js: TCP/IP server has received 45812 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.671Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.677Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.689Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.818Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.888Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:36.893Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.229Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.235Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.246Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.279Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.286Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.293Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.329Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.339Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.370Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.409Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.449Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.459Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.486Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.519Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.527Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.534Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.565Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.576Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.732Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.853Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:25:37.907Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d,
,W/bt-btif ( 3932): invalid rfc slot id: 58
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): Stop ReceivingThread
I/BtToSocketBase( 3048): Stop SendingThread
I/BtToSocketBase( 3048): Close local in
I/BtToSocketBase( 3048): Close LocalOutputStream
I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3048): 2015-12-04T08:25:48.136Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 62
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:25:57.024Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:57.024Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:25:57.025Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,W/bt-btif ( 3932): info:x10
,D/        ( 3932): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,W/bt-btif ( 3932): new conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3932): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3048): we got incoming connection
I/BTHandshakeSocketThread( 3048): Creating BTHandshakeSocketThread
I/BTListenerThread( 3048): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread started
,I/BTListenerThread( 3048): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3048): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3048): MESSAGE_WRITE 77 bytes.
I/HS      ( 3048): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2753
I/BTHandshakeSocketThread( 3048): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3048): Starting the connected thread incoming : true, samsung-SM-G900F_PT2753
,I/BtToSocketBase( 3048): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3048): Creating BTConnectedThread
I/BtConnectorHelper( 3048): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3048): --DoOneRunRound started
,I/jxcore-log( 3048): 2015-12-04T08:25:59.726Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3048): 
,I/BtToRequestSocket( 3048): LocalHost address: localhost/127.0.0.1, port: 38668
,I/BtToRequestSocket( 3048): --DoOneRunRound ended
,I/jxcore-log( 3048): 2015-12-04T08:26:00.257Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:26:00.263Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:26:00.346Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:26:00.355Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:26:00.412Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:26:02.026Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:02.026Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3048): 2015-12-04T08:26:07.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:07.031Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:07.031Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:07.032Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3048): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 3048): timeout now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): dun
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): done, now sending data to server
I/jxcore-log( 3048): 
I/jxcore-log( 3048): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): -- RESULT DATA {"name:":"LGE-Nexus 5_PT5146","time":1000066,"result":"TIMEOUT","sendList":[{"connections":1,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":1,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":1,"name":"38:94:96:B5:06:DC","time":0,"result":"Fail"},{"connections":1,"name
,I/jxcore-log( 3048): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Results list does not contain any items
I/jxcore-log( 3048): 
I/jxcore-log( 3048): sendList failed peers count : 10 [100 %]
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : B0:C5:59:3F:75:69, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 38:94:96:B5:06:DC, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 58:3F:54:73:64:C0, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : F8:95:C7:87:85:54, Tried : 1
I/jxcore-log( 3048): 
I/jxcore-log( 3048): sendList never tried peers count : 10 [50 %]
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 34:FC:EF:11:B1:66
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 3048): 
I/jxcore-log( 3048): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:07.789Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:07.790Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=1
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3932): invalid rfc slot id: 63
,I/BtToSocketBase( 3048): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): Stop ReceivingThread
,I/BtToSocketBase( 3048): Stop SendingThread
,I/BtToSocketBase( 3048): Close local in
,I/BtToSocketBase( 3048): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3048): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2753
I/BtToSocketBase( 3048): Close LocalOutputStream
,I/BtToSocketBase( 3048): Close localHostSocket
I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/BtToSocketBase( 3048): Close bt in
I/BtToSocketBase( 3048): Close bt out
I/BtToSocketBase( 3048): Close bt socket
,I/jxcore-log( 3048): 2015-12-04T08:26:10.254Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3048): 
,W/bt-rfcomm( 3932): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3932): RFCOMM_DisconnectInd LCID:0x48
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 9 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3932): tBTM_SEC_DEV:0xa3d517a4 rs_disc_pending=0
W/bt-btif ( 3932): bta_dm_check_av:0
,W/bt-btif ( 3932): btif_dm_cback : unhandled event (14)
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3932): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3932): onReceive
,I/BTConnectionReceiver( 1381): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1381): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3048): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT807","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT807, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT807, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8707, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8707, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3048): Found Service, :{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT5954"} -- peerIdentifier:38:94:96:B5:06:DC, peerName: samsung-SM-G800H_PT5954, peerAddress: 38:94:96:B5:06:DC
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 38:94:96:B5:06:DC, Name: samsung-SM-G800H_PT5954, WifiDirectName: , WifiDirect Address: 3a:94:96:b5:06:dd, peerId: 38:94:96:B5:06:DC
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 11 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3048): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2753","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2753, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2753, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5431"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5431, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5431, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3048): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"}, typeCordovap2p._tcp.local.:
,I/        ( 3048): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT3449"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT3449, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT3449, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
,E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 65
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:26:39.493Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:39.494Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:39.495Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:26:44.496Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:26:44.501Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 11 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b,
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/jxcore-log( 3048): 2015-12-04T08:26:49.505Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:49.505Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:49.505Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:26:49.505Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3048): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3048): Starting to connect
,W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9142","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT9142, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT9142, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3048): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT8707","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT8707, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT8707, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 12 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
,I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT5363"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT5363, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT5363, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3048): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"}, typeCordovap2p._tcp.local.:
I/        ( 3048): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT3559"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT3559, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3048): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT3559, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x22  CID 0x4b
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 66
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:27:21.649Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:27:21.649Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:27:21.650Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 12 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Galaxy S5-2 3a:94:96:b5:06:dd
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(7): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3048): Peer(10): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3048): Peer(11): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): 2015-12-04T08:27:26.650Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:27:26.651Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3048): 2015-12-04T08:27:31.655Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:27:31.656Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:27:31.656Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:27:31.660Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3048): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/EventLogService( 1600): Aggregate from 1449216232807 (log), 1449215641447 (data)
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x22  CID 0x4e
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 67
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3048): 2015-12-04T08:28:02.577Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:28:02.580Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:28:02.583Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:28:07.585Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:28:07.586Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:28:12.594Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:28:12.594Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:28:12.595Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
I/jxcore-log( 3048): 2015-12-04T08:28:12.595Z SendDataConnector.js: do connect now
I/jxcore-log( 3048): 
,I/        ( 3048): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3048): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3048): Starting to connect
W/BluetoothAdapter( 3048): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3932): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 8 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3048): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3048): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3932): SDP - Rcvd conn cnf with error: 0x22  CID 0x4d
E/bt-btif ( 3932): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3932): invalid rfc slot id: 68
,I/BTConnectToThread( 3048): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3048): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3048): 2015-12-04T08:28:44.146Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:28:44.146Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:28:44.155Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:28:44.161Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3048): 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 7 peers.
I/SS      ( 3048): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3048): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3048): Started service discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3048): Cleared service requests
I/        ( 3048): Started peer discovery
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3048): Found 7 peers.
I/SS      ( 3048): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3048): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3048): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3048): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3048): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3048): Peer(6): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3048): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3048): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3048): Added service request
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3048): DBG, CoordinatorConnector command called
I/jxcore-log( 3048): 
I/jxcore-log( 3048): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): stop tests now !
I/jxcore-log( 3048): 
I/jxcore-log( 3048): stop current!
I/jxcore-log( 3048): 
I/jxcore-log( 3048): testSendData stopped
I/jxcore-log( 3048): 
I/        ( 3048): Stoping All
I/        ( 3048): Stopping services
I/        ( 3048): Stopping services
I/wpa_supplicant( 3124): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 3048): Stop Bluetooth
I/        ( 3048): Stop Bluetooth
I/BTListenerThread( 3048): Stopped
,I/jxcore-log( 3048): StopBroadcasting went ok
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): 2015-12-04T08:30:27.871Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3048): 
I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3048): Cleared local services
I/        ( 3048): Cleared service requests
I/        ( 3048): Stopped peer discovery
,I/jxcore-log( 3048): DBG, CoordinatorConnector command called
I/jxcore-log( 3048): 
I/jxcore-log( 3048): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"38:94:96:B5:06:DC\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:37:96:AB\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:9D:93:0B\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:3F:54:73:64:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"F8:95:C7:87:3C:51\",\"tim
I/jxcore-log( 3048): ****TEST TOOK:  ms ****
I/jxcore-log( 3048): 
I/jxcore-log( 3048): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3048): 
I/jxcore-log( 3048): stop tests now !
I/jxcore-log( 3048): 
I/jxcore-log( 3048): end, event received
I/jxcore-log( 3048): 
I/jxcore-log( 3048): CoordinatorConnector close called
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3048): 
I/jxcore-log( 3048): The Coordinator has disconnected!
I/jxcore-log( 3048): 
I/jxcore-log( 3048): The Coordinator has closed!
I/jxcore-log( 3048): 
I/jxcore-log( 3048): stop tests now !
I/jxcore-log( 3048): 
I/jxcore-log( 3048): turning Radios off
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Toggling radios to false
I/jxcore-log( 3048): 
D/BluetoothManagerService(  758): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  758): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@166be08e mBinding = false
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3124): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/BluetoothManagerService(  758): Message: 2
D/BluetoothManagerService(  758): Sending off request.
D/BluetoothAdapterState( 3932): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3932): Setting state to 13
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3932): onBluetoothDisable()
I/BluetoothAdapterState( 3932): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/WifiService(  758): setWifiEnabled: false pid=3048, uid=10270
E/WifiService(  758): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothAdapterProperties( 3932): Scan Mode:20
,D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/btif_config_util( 3932): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 3932): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3932): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3932): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3932): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3932): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3932): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3932): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3932): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3932): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3932): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  758): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3932): onReceive
D/BluetoothMapService( 3932): STATE_TURNING_OFF
V/BluetoothMapService( 3932): Handler(): got msg=4
D/BluetoothMapService( 3932): MAP Service closeService in
D/BluetoothMapMasInstance( 3932): MAP Service shutdown
V/BluetoothMapService( 3932): MAP Service closeService out
,I/BtOppRfcommListener( 3932): stopping Accept Thread
,I/BtOppRfcommListener( 3932): BluetoothSocket listen thread finished
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  758): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3048): Radios toggled
I/jxcore-log( 3048): 
,I/chromium( 3048): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,E/native  (  758): do suspend true
,D/DockEventReceiver( 3125): finishStartingService: stopping service
,D/BluetoothPbap( 3125): Proxy object disconnected
D/PbapServerProfile( 3125): Bluetooth service disconnected
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,I/        ( 3048): Starting service discovery failed, error code 3
I/        ( 3048): Cleared service requests
D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/NativeCrypto( 1298): Read error: ssl=0x9b301200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1298): SSL shutdown failed: ssl=0x9b301200: I/O error during system call, Broken pipe
,D/ConnectivityService(  758): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  758): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  758): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  758): scanCount==0 - aborting
,D/WifiNetworkAgent(  758): NetworkAgent: NetworkAgent channel lost
,E/native  (  758): do suspend true
D/WifiScanningService(  758): SCAN_AVAILABLE : 1
D/RttService(  758): SCAN_AVAILABLE : 1
,D/WifiScanningService(  758): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  758): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
W/bt-btif ( 3932): ag scb idx 1 not allocated
E/bt-btif ( 3932): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3932): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3932): RX termination
W/bt_userial( 3932): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3932): Leaving userial_read_thread()
D/bt_userial( 3932): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3932): hw_epilog_process
,D/WifiScanningService(  758): DefaultState
,I/bt_userial_vendor( 3932): device fd = 64 close
,I/GKI_LINUX( 3932): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3932): GKI_exit_task 0 done
I/GKI_LINUX( 3932): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3932): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/HeadsetStateMachine( 3932): Exit Disconnected: -1
,D/BluetoothHeadset(  758): Proxy object disconnected
,D/BluetoothHeadset( 1191): Proxy object disconnected
,D/A2dpService( 3932): Received stop request...Stopping profile...
D/A2dpStateMachine( 3932): Exit Disconnected: -1
D/BluetoothAdapterState( 3932): Stopping profile services that were post enabled
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/BluetoothHeadset( 1162): Proxy object disconnected
D/BluetoothHeadset( 1162): Proxy object disconnected
,D/BluetoothA2dp(  758): Proxy object disconnected
,D/BluetoothHeadset( 3125): Proxy object disconnected
D/HeadsetProfile( 3125): Bluetooth service disconnected
,D/BluetoothA2dp( 3125): Proxy object disconnected
D/A2dpProfile( 3125): Bluetooth service disconnected
D/HidService( 3932): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/HealthService( 3932): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
D/BluetoothInputDevice( 3125): Proxy object disconnected
,D/HidProfile( 3125): Bluetooth service disconnected
,D/PanService( 3932): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/BtGatt.DebugUtils( 3932): handleDebugAction() action=null
,D/BtGatt.GattService( 3932): Received stop request...Stopping profile...
D/BtGatt.GattService( 3932): stop()
,D/BtGatt.AdvertiseManager( 3932): advertise clients cleared
,D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,D/HeadsetStateMachine( 3932): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3932): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3932): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothPan( 3125): BluetoothPAN Proxy object disconnected
D/PanProfile( 3125): Bluetooth service disconnected
,D/BluetoothMapService( 3932): Received stop request...Stopping profile...
D/BluetoothMapService( 3932): stop()
D/BluetoothMapEmailAppObserver( 3932): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3932): removeReceiver()
D/BluetoothAdapterService( 3932): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16ff0e03
,I/GKI_LINUX( 3932): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3932): GKI_exit_task 2 done
I/GKI_LINUX( 3932): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3932): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3932): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3932): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3932): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3932): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3932): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3932): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3932): Handler(): got msg=4
D/BluetoothMapService( 3932): MAP Service closeService in
V/BluetoothMapService( 3932): MAP Service closeService out
D/BluetoothAdapterState( 3932): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothAdapterProperties( 3932): Setting state to 10
I/BluetoothAdapterState( 3932): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  758): Message: 60
D/BluetoothManagerService(  758): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  758): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 3932): Entering OffState
D/BluetoothMapService( 3932): cleanup()
D/BluetoothMapService( 3932): MAP Service closeService in
V/BluetoothMapService( 3932): MAP Service closeService out
D/BluetoothPbap( 3125): onBluetoothStateChange: up=false
D/BluetoothHeadset( 3125): onBluetoothStateChange: up=false
D/BluetoothMap( 3125): onBluetoothStateChange: up=false
D/BluetoothHeadset(  758): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1162): onBluetoothStateChange: up=false
D/CommandListener(  178): Clearing all IP addresses on wlan0
D/BluetoothInputDevice( 3125): onBluetoothStateChange: up=false
D/ConnectivityService(  758): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
D/BluetoothHeadset( 1191): onBluetoothStateChange: up=false
D/BluetoothA2dp( 3125): onBluetoothStateChange: up=false
D/BluetoothA2dp(  758): onBluetoothStateChange: up=false
,D/Nat464Xlat(  758): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  758): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  758): Disconnected - quitting
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  758): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  758): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1191): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BluetoothManagerService(  758): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  758): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/ConnectivityManager.CallbackHandler( 1600): CM callback handler got msg 524292
,D/BluetoothManagerService(  758): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@166be08e mBinding = false
,D/BluetoothManagerService(  758): Sending unbind request.
,D/BluetoothManagerService(  758): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  899): 135864548: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1344): 782594929: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1344): 782594929: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3932): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3932): GKI_exit_task 1 done
I/GKI_LINUX( 3932): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3932): cleanupNative: return from cleanup
,D/AndroidRuntime( 4426): 
D/AndroidRuntime( 4426): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4426): CheckJNI is OFF
,W/ContextImpl( 3125): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/art     ( 3932): System.exit called, status: 0
I/AndroidRuntime( 3932): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 3125): finishStartingService: stopping service
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3124): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3124): p2p0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  758): Process com.android.bluetooth (pid 3932) has died
,I/wpa_supplicant( 3124): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/AndroidRuntime( 4426): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  758): Killing 3048:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  758): Skipping PackageSetting{23430a5a com.example.hello/10277} due to missing metadata
,I/WindowState(  758): WIN DEATH: Window{3be18c37 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  758): Client connection lost with reason: 4
,I/wpa_supplicant( 3124): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  758): InitialState.processMessage what=4
,I/ActivityManager(  758):   Force finishing activity ActivityRecord{3cbd962d u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  758): Spurious death for ProcessRecord{1ffccfc1 3048:com.test.thalitest/u0a270}, curProc for 3048: null
,D/Tethering(  758): sendTetherStateChangedBroadcast 0, 0, 0
,I/ActivityManager(  758): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,W/Settings( 1856): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1344): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1243): Explicit concurrent mark sweep GC freed 7242(471KB) AllocSpace objects, 2(207KB) LOS objects, 38% free, 26MB/42MB, paused 648us total 18.256ms
,W/GeofencerStateMachine( 1344): Ignoring removeGeofence because network location is disabled.
I/InputReader(  758): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1060): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1060): run()
,D/BluetoothAdapter( 3125): 455077554: getState() :  mService = null. Returning STATE_OFF
I/LibraryLoader( 1501): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/Decoder ( 1060): createOrResetDecoder
,I/art     ( 1381): Explicit concurrent mark sweep GC freed 79235(3MB) AllocSpace objects, 16(256KB) LOS objects, 24% free, 19MB/25MB, paused 682us total 96.677ms
,I/art     (  758): Explicit concurrent mark sweep GC freed 58067(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.673ms total 79.290ms
I/art     (  758): WaitForGcToComplete blocked for 65.094ms for cause Explicit
,I/ActivityManager(  758): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4483 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/LibraryLoader( 1501): Time to load native libraries: 62 ms (timestamps 1822-1884)
I/LibraryLoader( 1501): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/OpenGLRenderer(  947): Initialized EGL, version 1.4
,I/chromium( 1501): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1501): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1501): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer(  947): Enabling debug mode 0
,I/ConfigService( 1298): onCreate
,W/art     (  947): Attempt to remove local handle scope entry from IRT, ignoring
,W/InputMethodManagerService(  758): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@14a83de4 (uid=10034 pid=947)
,W/ResourcesManager( 4483): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1060): run()
,D/BackupManagerService(  758): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  758): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  758): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  758): Got RemoteException sending setActive(false) notification to pid 3048 uid 10270
,D/AdapterServiceConfig( 4483): Adding HeadsetService
D/AdapterServiceConfig( 4483): Adding A2dpService
D/AdapterServiceConfig( 4483): Adding HidService
,D/AdapterServiceConfig( 4483): Adding HealthService
D/AdapterServiceConfig( 4483): Adding PanService
D/AdapterServiceConfig( 4483): Adding GattService
D/AdapterServiceConfig( 4483): Adding BluetoothMapService
I/ActivityManager(  758): Killing 2871:com.google.android.gms:car/u0a8 (adj 15): empty #17
I/Keyboard.Facilitator( 1060): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1060): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1060): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1060): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1060): run()
I/StatsUtilsManager( 1060): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1060): shouldRecordStats() = Too Soon
,I/art     (  758): Explicit concurrent mark sweep GC freed 11666(605KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.077ms total 184.792ms
,D/AuthorizationBluetoothService( 1298): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  758): failed to open /acct/uid_10008/pid_2871/cgroup.procs: No such file or directory
,I/Launcher( 1243): Deferring update until onResume
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothAdapter( 3125): 455077554: getState() :  mService = null. Returning STATE_OFF
,D/VoicemailCleanupService( 1314): Cleaning up data for package: com.test.thalitest
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  758): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4520 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/Launcher( 1243): Deferring update until onResume
,D/AndroidRuntime( 4426): Shutting down VM
,W/Launcher( 1243): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@16ff0e03 new=com.google.android.velvet.VelvetApplication@16ff0e03
,I/UpdateIcingCorporaServi( 1381): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ActivityManager(  758): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4541 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  758): Killing 2811:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  758): failed to open /acct/uid_10005/pid_2811/cgroup.procs: No such file or directory
,W/ContextImpl( 4541): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1600): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1600): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1600): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1600): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1600): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1600): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1298): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1298): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  758): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4564 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1600): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1600): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1600): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1600): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1600): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1600): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1381): UpdateCorporaTask done [took 238 ms] updated apps [took 238 ms] 
,W/BaseAppContext( 1600): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1600): App measurement is starting up
,I/Icing   ( 1600): doRemovePackageData com.test.thalitest
,I/PeopleContactsSync( 1600): CP2 sync disabled
,E/SQLiteLog( 1600): (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
,E/GMPM-SVC( 1600): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
,E/SharedPreferencesImpl( 1600): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak

```
