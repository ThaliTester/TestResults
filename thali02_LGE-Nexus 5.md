#### Test 51986340afa1391_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2885): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2885):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2885):   adb logcat -s GAv4
W/GAv4    ( 2885): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2885): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2885): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2885): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,--------- beginning of system
W/ResourcesManager( 2885): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2885): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2406): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  761): Killing 2216:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 2885): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2885): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2885): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2933): 
D/AndroidRuntime( 2933): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2933): CheckJNI is OFF
D/AndroidRuntime( 2933): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2216/cgroup.procs: No such file or directory
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1555): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2954 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2933): Shutting down VM
D/Icing   ( 1555): Loaded CLD2 Version V2.0 - 20141016
V/ActivityManager(  761): Display changed displayId=0
I/Icing   ( 1555): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2954): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2954): Time to load native libraries: 1 ms (timestamps 5779-5780)
I/LibraryLoader( 2954): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2954): Binding Chromium to main looper Looper (main, tid 1) {1583027f}
I/LibraryLoader( 2954): Expected native library version number "",actual native library version number ""
I/chromium( 2954): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2954): Initializing chromium process, singleProcess=true
W/art     ( 2954): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2954): ApplicationContext is null in ApplicationStatus
W/chromium( 2954): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2954): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2954): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2954): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14e670b5:true
D/BluetoothAdapter( 2954): 109687569: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2954): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2954): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2954): CordovaWebView is running on device made by: LGE
W/art     ( 2954): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2954): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2954): Render dirty regions requested: true
D/Atlas   ( 2954): Validating map...
W/chromium( 2954): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2954): Initialized EGL, version 1.4
D/OpenGLRenderer( 2954): Enabling debug mode 0
I/Keyboard.Facilitator( 1074): onFinishInput()
W/IInputConnectionWrapper( 2954): showStatusIcon on inactive InputConnection
I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +476ms (total +54s252ms)
W/BindingManager( 2954): Cannot call determinedVisibility() - never saw a connection for the pid: 2954
D/JsMessageQueue( 2954): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2954): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2954): jxcore cordova android initializing
I/ActivityManager(  761): Killing 2318:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2318/cgroup.procs: No such file or directory
,W/jxcore-log( 2954): Initializing JXcore engine
W/jxcore-log( 2954): JXcore engine is ready
W/jxcore-log( 2954): Starting JXcore engine
,W/.test.thalitest( 2954): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9408]" dev="sockfs" ino=9408 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2954): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2954): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9517]" dev="sockfs" ino=9517 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2954): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17988]" dev="sockfs" ino=17988 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2954): Platform android
W/jxcore-log( 2954): 
W/jxcore-log( 2954): Process ARCH arm
W/jxcore-log( 2954): 
,I/jxcore-log( 2954): JXcore Cordova bridge is ready!
I/jxcore-log( 2954): 
,W/jxcore-log( 2954): JXcore engine is started
I/Choreographer( 2954): Skipped 108 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2954): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2954): Toggling radios to true
I/jxcore-log( 2954): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  761): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  761): Message: 1
D/BluetoothManagerService(  761): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  761): setWifiEnabled: true pid=2954, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  761): New client listening to asynchronous messages
,I/ActivityManager(  761): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3010 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/WifiMonitor(  761): startMonitoring(wlan0) with mConnected = false
I/jxcore-log( 2954): Radios toggled
I/jxcore-log( 2954): 
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3022 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3017): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3010): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3017): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d43fb20:true
,D/BluetoothAdapter( 3022): 360907391: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3022): Adding local MAP profile
D/BluetoothMap( 3022): Create BluetoothMap proxy object
D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3022): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapter( 3022): 360907391: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3022): 360907391: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3056 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  761): Killing 2366:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10069/pid_2366/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 3010): Adding HeadsetService
D/AdapterServiceConfig( 3010): Adding A2dpService
D/AdapterServiceConfig( 3010): Adding HidService
D/AdapterServiceConfig( 3010): Adding HealthService
D/AdapterServiceConfig( 3010): Adding PanService
D/AdapterServiceConfig( 3010): Adding GattService
D/AdapterServiceConfig( 3010): Adding BluetoothMapService
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@388ca34e:true
,D/BluetoothAdapterState( 3010): make
,I/bluedroid( 3010): init
,I/BluetoothAdapterState( 3010): Entering OffState
,I/bte_conf( 3010): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3010): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3010): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3010): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3010): get_profile_interface socket
I/bluedroid( 3010): get_profile_interface map_client
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3010): config_hci_snoop_log
,D/BluetoothManagerService(  761): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceUp() to 10 receivers.
,I/GKI_LINUX( 3010): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3010): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 3010): Name is: Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterState( 3010): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3010): Setting state to 11
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3010): make
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,D/BluetoothHeadset(  761): Proxy object connected
,D/BluetoothHeadset( 1202): Proxy object connected
,D/HeadsetService( 3010): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3010): classInitNative: succeeds
,I/BluetoothAdapterState( 3010): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothHeadset( 1173): Proxy object connected
,D/BluetoothHeadset( 1173): Proxy object connected
,D/HeadsetStateMachine( 3010): make
,D/HeadsetStateMachine( 3010): max_hf_connections = 1
I/bluedroid( 3010): get_profile_interface handsfree
,D/HeadsetStateMachine( 3010): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4f24c
,D/BluetoothA2dp(  761): Proxy object connected
D/A2dpService( 3010): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3010): classInitNative: succeeds
I/bluedroid( 3010): get_profile_interface avrcp
,E/RemoteController( 3010): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3010): classInitNative: succeeds
D/A2dpStateMachine( 3010): make
,I/bluedroid( 3010): get_profile_interface a2dp
I/GKI_LINUX( 3010): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4f24c
I/BluetoothHidServiceJni( 3010): classInitNative: succeeds
,D/A2dpStateMachine( 3010): Enter Disconnected: -2
,D/BluetoothInputDevice( 3022): Proxy object connected
D/HidService( 3010): Received start request. Starting profile...
I/bluedroid( 3010): get_profile_interface hidhost
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4f24c
D/HidProfile( 3022): Bluetooth service connected
I/BluetoothHealthServiceJni( 3010): classInitNative: succeeds
,D/HealthService( 3010): Received start request. Starting profile...
,I/bluedroid( 3010): get_profile_interface health
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4f24c
I/BluetoothPanServiceJni( 3010): classInitNative(L105): succeeds
,D/BluetoothPan( 3022): BluetoothPAN Proxy object connected
D/PanProfile( 3022): Bluetooth service connected
D/PanService( 3010): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3010): initializeNative(L110): pan
I/bluedroid( 3010): get_profile_interface pan
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4f24c
,I/BtGatt.JNI( 3010): classInitNative(L863): classInitNative: Success!
,I/art     ( 1432): Explicit concurrent mark sweep GC freed 9428(549KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 803us total 21.468ms
,D/BtGatt.DebugUtils( 3010): handleDebugAction() action=null
,D/BtGatt.GattService( 3010): Received start request. Starting profile...
D/BtGatt.GattService( 3010): start()
I/bluedroid( 3010): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3010): advertise manager created
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4f24c
,V/BluetoothMapService( 3010): BluetoothMapBinder()
,D/BluetoothMap( 3022): Proxy object connected
D/BluetoothMapService( 3010): Received start request. Starting profile...
D/BluetoothMapService( 3010): start()
D/MapProfile( 3022): Bluetooth service connected
,D/BluetoothMap( 3022): getConnectedDevices()
D/BluetoothMap( 3022): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3010): Found 0 applications
D/BluetoothMapEmailAppObserver( 3010): createReceiver()
,D/BluetoothMapEmailAppObserver( 3010): initObservers()
D/BluetoothMapEmailAppObserver( 3010): getEnabledAccountItems()
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4f24c
D/HeadsetStateMachine( 3010): Proxy object connected
D/HeadsetStateMachine( 3010): Disconnected process message: 10, size: 0
V/BluetoothMapService( 3010): Handler(): got msg=1
D/HeadsetPhoneState( 3010): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3010): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3010): enable
,I/GKI_LINUX( 3010): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3010): btu_task pending for preload complete event
I/bt_hci_bdroid( 3010): init
,I/bt_vendor( 3010): init
I/bt_vnd_conf( 3010): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3010): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3010): userial_init
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_userial_vendor( 3010): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3010): device fd = 53 open
,D/bt_userial( 3010): Entering userial_read_thread()
,I/art     (  761): Explicit concurrent mark sweep GC freed 12120(629KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 872us total 48.233ms
,D/AuthorizationBluetoothService( 1432): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  761): Killing 1776:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 4000000
,I/wpa_supplicant( 3017): rfkill: Cannot open RFKILL control device
,D/bt_hwcfg( 3010): Chipset BCM4335C0
D/bt_hwcfg( 3010): Target name = [BCM4335C0]
I/bt_hwcfg( 3010): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1776/cgroup.procs: No such file or directory
,I/wpa_supplicant( 3017): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  761): Loading config and enabling all networks 
,D/WifiService(  761): New client listening to asynchronous messages
,E/WifiConfigStore(  761): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 1794): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  761): Setting external_sim to 1
,D/WifiStateMachine(  761): Setting OUI to DA-A1-19
I/WifiNative-HAL(  761): startHal
D/wifi    (  761): setting scan oui 0x91045040
D/WifiHAL (  761): Sending mac address OUI
E/WifiHAL (  761): failed to set scanning mac OUI; result = -95
,E/native  (  761): do suspend true
,D/WifiScanningService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): SCAN_AVAILABLE : 3
,D/WifiScanningService(  761): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  761): startHal
D/RttService(  761): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/wifi    (  761): getting scan capabilities on interface[1] = 0x91045040
D/WifiHAL (  761): Creating message to get scan capablities; iface = 21
D/WifiHAL (  761): In GetCapabilities::handleResponse
D/WifiHAL (  761): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  761): StartedState
,D/WifiMonitor(  761): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  761): p2pGetDeviceAddress
,D/WifiNative-HAL(  761): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3017): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3010): Settlement delay -- 100 ms
I/bt_hwcfg( 3010): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 3010): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3010): vendor lib fwcfg completed
,I/bt-btu  ( 3010): btu_task received preload complete event
,I/        ( 3010): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3010): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3010): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3010): BTE_InitTraceLevels -- TRC_AVDT
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
E/bt-btm  ( 3010): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3010): Calling BTA_HhEnable
E/bt-btif ( 3010): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3010): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3010): Name is: Nexus 5
D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3010): Scan Mode:20
D/BluetoothAdapterProperties( 3010): Discoverable Timeout:120
,D/bte_conf( 3010): Device ID record 1 : primary
D/bte_conf( 3010):   vendorId            = 000f
D/bte_conf( 3010):   vendorIdSource      = 0001
D/bte_conf( 3010):   product             = 1200
,D/bte_conf( 3010):   version             = 1436
D/bte_conf( 3010):   clientExecutableURL = 
D/bte_conf( 3010):   serviceDescription  = 
D/bte_conf( 3010):   documentationURL    = 
D/bte_conf( 3010): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3010): ScanMode =  20
D/BluetoothPanServiceJni( 3010): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3010): State =  11
D/BluetoothAdapterProperties( 3010): Setting state to 12
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3010): Entering On State
,D/BluetoothMap( 3022): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 3010): Scan Mode:21
D/BluetoothAdapterProperties( 3010): Discoverable Timeout:120
,D/BluetoothHeadset(  761): onBluetoothStateChange: up=true
,D/BluetoothPbap( 3022): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3022): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1173): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1202): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1173): onBluetoothStateChange: up=true
D/BluetoothPan( 3022): onBluetoothStateChange(on) call bindService
,D/BluetoothManagerService(  761): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,E/bt_h4   ( 3010): vendor lib postload completed
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 2d 0e 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = d7 f5 89 c8 f8 00 2e 4b 63 d3 98 40 36 95 b1 4b 
W/bt-btm  ( 3010): Stopping oneshot timer
,D/BluetoothMapService( 3010): onReceive
D/BluetoothMapService( 3010): STATE_ON
V/BluetoothMapService( 3010): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3010): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = ee 40 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 5a ba d8 2a 2a df b1 d0 bb d9 1e 29 af 75 46 d9 
W/bt-btm  ( 3010): Stopping oneshot timer
,D/LocalBluetoothProfileManager( 3022): Adding local A2DP profile
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 0b 0d 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = fe 85 24 f5 24 5e 65 20 12 60 84 04 4d c1 f8 04 
W/bt-btm  ( 3010): Stopping oneshot timer
D/BluetoothManagerService(  761): Message: 30
,I/Telecom ( 1173): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = f1 28 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 04 5e 32 fa da 2a 22 c1 d0 9d b8 0d b6 ad c3 ac 
W/bt-btm  ( 3010): Stopping oneshot timer
,D/BluetoothMapMasInstance( 3010): MAS initSocket()
,D/BluetoothMapMasInstance( 3010):   masId = 00
D/BluetoothMapMasInstance( 3010):   msgTypes = 0e
D/BluetoothMapMasInstance( 3010):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3010):   SDP string = 000eSMS/MMS
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = ee e4 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = db c9 b4 f0 cf af bb 86 77 c8 24 45 57 d8 d1 06 
W/bt-btm  ( 3010): Stopping oneshot timer
D/HeadsetStateMachine( 3010): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3010): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3010): mNumber:  mType: 128
D/HeadsetStateMachine( 3010): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3010): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3022): Adding local HEADSET profile
V/BluetoothMapMasInstance( 3010): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3010): Accepting socket connection...
D/BluetoothManagerService(  761): Message: 30
W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 4a f0 7b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = cb 76 8a a1 3c f6 d2 c1 9a 1f fd f9 de d3 ba 8e 
W/bt-btm  ( 3010): Stopping oneshot timer
W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 01 2f 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = ca d1 00 53 1e 51 8d 0d 6b 16 15 e8 03 0d 0c 60 
W/bt-btm  ( 3010): Stopping oneshot timer
,W/ContextImpl( 3022): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothA2dp( 3022): Proxy object connected
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,D/A2dpProfile( 3022): Bluetooth service connected
,D/BluetoothHeadset( 3022): Proxy object connected
,D/HeadsetProfile( 3022): Bluetooth service connected
D/DockEventReceiver( 3022): finishStartingService: stopping service
,D/BluetoothPbap( 3022): Proxy object connected
D/PbapServerProfile( 3022): Bluetooth service connected
,D/AuthorizationBluetoothService( 1432): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2954): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): my name is : LGE-Nexus 5_PT5801
I/jxcore-log( 2954): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3010): Accept thread started.
,I/jxcore-log( 2954): attempting to connect to test coordinator
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): check test folder
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): found test : ./testFindPeers.js
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): found test : ./testReConnect.js
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): found test : ./testSendData.js
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): Test app app.js loaded
I/jxcore-log( 2954): 
,I/Choreographer( 2954): Skipped 133 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/chromium( 2954): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3017): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  761): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): will read network variables netId=1
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  761): will read network variables netId=1
,I/wpa_supplicant( 3017): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  761): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3017): PNO: In assoc process
,I/wpa_supplicant( 3017): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3017): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3017): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 1
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3188): version 5.5.6 starting
,E/dhcpcd  ( 3188): get_duid: Read-only file system
,I/dhcpcd  ( 3188): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/dhcpcd  ( 3188): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3188): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 100
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  761): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761):    accepting network in place of null
D/ConnectivityService(  761): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 07 Dec 2015 10:08:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449482901223], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449482901208]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
,D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524290
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/TelephonyNetworkFactory( 1202): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524295
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2484): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2484): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.SyncManager( 1555): SYNC; picasa accounts
,E/GpsLocationProvider(  761): No APN found to select.
,E/Auth.Api.Credentials( 1555): [CredentialSyncAdapter] Unknown sync event.
,D/NetworkLogImpl( 1555): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1555): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1555): num queued entries: 0
,I/iu.UploadsManager( 1555): num updated entries: 0
,I/iu.SyncManager( 1555): NEXT; no task
,D/ChimeraCfgMgr( 1555): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1555): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/jxcore-log( 2954): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2954): 
,I/SystemUpdateService( 1555): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1555): onCreate
,D/SystemUpdateService( 1555): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1555): active receiver: enabled
,I/SystemUpdateService( 1555): showing system update notification
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1555): retry (wakeup: false) in 3599978 ms
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3282 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1555): onDestroy
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1794): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1432): GCM config loaded
,D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  761): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1555): CM callback handler got msg 524290
,I/GAv4    ( 3282): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3282):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3282):   adb logcat -s GAv4
,W/GAv4    ( 3282): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3282): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3282): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1432): Ack for not saved message 26
,I/art     ( 1432): Explicit concurrent mark sweep GC freed 9563(535KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 892us total 35.099ms
,W/DriveInitializer( 1555): Awaiting to be initialized
,W/DriveInitializer( 1555): Background init thread started
,I/art     (  761): Explicit concurrent mark sweep GC freed 47026(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 1.064ms total 57.553ms
,I/WebViewFactory( 3282): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3282): Time to load native libraries: 2 ms (timestamps 5767-5769)
I/LibraryLoader( 3282): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3282): Binding Chromium to main looper Looper (main, tid 1) {11de4f99}
,I/LibraryLoader( 3282): Expected native library version number "",actual native library version number ""
I/chromium( 3282): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3282): Initializing chromium process, singleProcess=true
,W/art     ( 3282): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3282): ApplicationContext is null in ApplicationStatus
,W/chromium( 3282): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3282): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/RemindersSync( 1555): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=223:priority=5:group=main]
,W/DriveInitializer( 1555): Background init thread ended
,W/art     ( 2592): Attempt to remove local handle scope entry from IRT, ignoring
,I/NSApplication( 3282): Starting up...
,W/AudioManagerAndroid( 3282): Requires BLUETOOTH permission
,I/ActivityManager(  761): Killing 2454:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2454/cgroup.procs: No such file or directory
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,D/AlarmManagerService(  761): Setting time of day to sec=1449482909
,W/AlarmManagerService(  761): Unable to set rtc to 1449482909: Invalid argument
,I/ActivityManager(  761): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3402 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/GpsLocationProvider(  761): NTP server returned: 1449482909597 (Mon Dec 07 11:08:29 GMT+01:00 2015) reference: 90207 certainty: 21 system time offset: -10
E/LocSvc_eng(  761): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/art     (  194): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 174us total 12.808ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.295ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 7.488ms
,D/TimeService( 3402): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449482909739
D/        ( 3402): TimeServiceNative: User Time to be set is 1449482909739
D/QC-time-services( 3402): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3402): Lib:time_genoff_operation: pargs->operation = 0
,D/QC-time-services( 3402): Lib:time_genoff_operation: pargs->ts_val = 1449482909739
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3402): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449482909739
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1449482909739, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/10/70 15:59:15
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8611155000
D/QC-time-services(  197): Daemon:new time 1449482909739 
D/QC-time-services(  197): Daemon: delta 1440871754739 genoff 1440871754739 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871754739 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871754739 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133518109739
,E/QC-time-services( 3402): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1555): Checkin interval check for package: unspecified last checkin: 1449470914839 min interval config: 0 actual interval: 11994927
,D/Finsky  ( 2406): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2406): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  761): Killing 2340:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2340/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3442 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3442): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3442):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3442):   adb logcat -s GAv4
,W/GAv4    ( 3442): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3442): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3442): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 1930:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_1930/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3471 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2746:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_2746/cgroup.procs: No such file or directory
,W/ResourcesManager( 3471): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3471): Created com.android.providers.calendar.CalendarAlarmManager@1c39379e(com.android.providers.calendar.CalendarProvider2@1583027f)
,I/CalendarProvider2( 3471): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3471): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,E/SQLiteLog( 3471): (284) automatic index on view_events(_id)
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1432): Vacuum at: now=1449482934853 tag=VacuumService
,D/GetConfigurationSnapshotOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1432): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1432): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/UdcCache:FPQuery( 1555): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1432):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1432): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1074): run()
I/Keyboard.Facilitator( 1074): flushDynamicLanguageModels()
,I/ConfigService( 1432): onCreate
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/ConfigService( 1432): onDestroy
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/ClearcutLoggerApiImpl( 1315): disconnect managed GoogleApiClient
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,E/DataBuffer( 1432): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2322bd99)
,E/DataBuffer( 1432): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8e5885e)
E/DataBuffer( 1432): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ffbe43f)
E/DataBuffer( 1432): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1585910c)
,E/DataBuffer( 1432): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17589a55)
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector connect called
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Coordinator is now connected to the server!
I/jxcore-log( 2954): 
,I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1432): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 32046(1334KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 996us total 56.352ms
,I/ActivityManager(  761): Killing 1330:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10004/pid_1330/cgroup.procs: No such file or directory
,I/jxcore-log( 2954): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector command called
I/jxcore-log( 2954): 
I/jxcore-log( 2954): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":22,"addressList":[{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:51:18
,I/jxcore-log( 2954): Start now : testSendData.js
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 22
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): check server
I/jxcore-log( 2954): 
I/jxcore-log( 2954): serverPort is 36370
I/jxcore-log( 2954): 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT5801
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2954): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): setState: INITIALIZED
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5801","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 2954): start: OK
I/jxcore-log( 2954): StartBroadcasting started ok
I/jxcore-log( 2954): 
I/jxcore-log( 2954): do fake peer & start
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:09.972Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:09.972Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:09.972Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log( 2954): 2015-12-07T10:14:09.978Z SendDataTCPServer.js: TCP/IP server is bound to port: 36370
I/jxcore-log( 2954): 
I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
I/io.jxcore.node.ConnectionHelper( 2954): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 2954): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 58:3F:54:73:64:C0
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 5
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 6
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 58:3F:54:73:64:C0
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,E/BluetoothEventManager( 3022): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Socket connection succeeded after 3 attempt(s)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Outgoing connection initialized (thread ID: 274)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesWritten: 77 bytes successfully written (thread ID: 274)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Entering thread (ID: 274)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesRead: Read 77 bytes successfully (thread ID: 274)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT5410 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5410 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Exiting thread (ID: 274)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT5410 58:3F:54:73:64:C0]
,I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT5410, Bluetooth address: 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2954): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing socket thread, for peer with ID 58:3F:54:73:64:C0, created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2954): Entering thread (ID: 275)
,I/io.jxcore.node.OutgoingSocketThread( 2954): Server socket local port: 52983
,I/io.jxcore.node.OutgoingSocketThread( 2954): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2954): onListeningForIncomingConnections: Outgoing connection is using port 52983 (peer ID: 58:3F:54:73:64:C0)
,I/jxcore-log( 2954): 2015-12-07T10:14:24.677Z SendDataConnector.js: CLIENT connected to 52983, error: null
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:24.678Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2954): 
,I/io.jxcore.node.OutgoingSocketThread( 2954): Incoming data from: /127.0.0.1, port: 52983
,I/io.jxcore.node.OutgoingSocketThread( 2954): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2954): startStreamCopyingThreads: OK
I/io.jxcore.node.OutgoingSocketThread( 2954): Exiting thread (ID: 275)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 276, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 277, name: Receiver)
,I/jxcore-log( 2954): 2015-12-07T10:14:24.699Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 276, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 276, thread name: Sender)
,I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 276, thread name: Sender)
,I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 848 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 848 bytes (thread ID: 276, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 848 bytes
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:28.775Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19756
,I/jxcore-log( 2954): 2015-12-07T10:14:28.819Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:28.908Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2954): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:28.970Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2954): 2015-12-07T10:14:29.118Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:29.167Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:29.281Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:29.360Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:29.410Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 277, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:29.464Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:29.469Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:29.491Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:29.492Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2954): 
,I/io.jxcore.node.ConnectionHelper( 2954): disconnectOutgoingConnection: Found an outgoing connection to peer with ID 58:3F:54:73:64:C0
I/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 2954): close
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 277
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 276
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 276, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 277, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 58:3F:54:73:64:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2954): disconnectOutgoingConnection: Successfully disconnected (peer ID: 58:3F:54:73:64:C0)
,W/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Failed to find a thread with ID 275
I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 276, name: Sender)
W/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Failed to find a thread with ID 275
I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 277, name: Receiver)
,I/jxcore-log( 2954): 2015-12-07T10:14:29.512Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2954): 
I/jxcore-log( 2954): ---- round done--------
I/jxcore-log( 2954): 
I/jxcore-log( 2954): do fake peer & start
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:29.513Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:29.513Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:29.514Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 7C:F9:0E:51:18:22
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 8
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@203d7c29:true
,I/BTConnectionReceiver( 1364): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1364): Bluetooth Device Name: G3-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Incoming connection initialized (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Entering thread (ID: 279)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): onBytesRead: Read 82 bytes successfully (thread ID: 279)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3707 00:F4:6F:30:E0:6C]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): onBytesWritten: 77 bytes successfully written (thread ID: 279)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): removeThreadFromList: Removing thread with ID 279
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Handshake thread disposed (thread ID: 279)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3707 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3707 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Incoming connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3707, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2954): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
,I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Incoming socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Exiting thread (ID: 279)
,I/io.jxcore.node.IncomingSocketThread( 2954): Entering thread (ID: 280)
,I/io.jxcore.node.IncomingSocketThread( 2954): Local host address: localhost/127.0.0.1, port: 36370
I/io.jxcore.node.IncomingSocketThread( 2954): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2954): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 2954): Exiting thread (ID: 280)
,I/jxcore-log( 2954): 2015-12-07T10:14:43.220Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 282, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 281, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:43.876Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:43.888Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:43.899Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 1980 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 1980 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 1980 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:43.939Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:43.950Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 272 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 272 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 272 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
,I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:43.988Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:44.011Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.033Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.043Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.077Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.083Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.116Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2954): 
I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.128Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 272 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 272 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 272 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.160Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.169Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.178Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.207Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.213Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.247Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.281Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.288Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.302Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.345Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.389Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.424Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:44.430Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.482Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 1980 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 1980 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 1980 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.526Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.566Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.603Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:44.608Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.630Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.663Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.694Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.743Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.763Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 990 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 990 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.797Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 946 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 946 bytes (thread ID: 282, thread name: Receiver)
I/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread succeeded to read/write 946 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:44.840Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 281, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 281, thread name: Sender)
I/io.jxcore.node.IncomingSocketThread( 2954): The sending thread succeeded to read/write 3 bytes
,W/bt-btif ( 3010): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 282, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 2954): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 280
I/io.jxcore.node.IncomingSocketThread( 2954): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 282
I/io.jxcore.node.IncomingSocketThread( 2954): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 281
I/io.jxcore.node.IncomingSocketThread( 2954): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 281, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2954): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2954): closeBluetoothSocketAndStreams
,I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 281, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 282, name: Receiver)
,I/jxcore-log( 2954): 2015-12-07T10:14:44.957Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2954): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x47
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1364): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1364): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Socket connection succeeded after 2 attempt(s)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Outgoing connection initialized (thread ID: 283)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesWritten: 77 bytes successfully written (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Entering thread (ID: 283)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesRead: Read 83 bytes successfully (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3468 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3468 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT3468 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT3468, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 2954): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
,I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Exiting thread (ID: 283)
,I/io.jxcore.node.OutgoingSocketThread( 2954): Entering thread (ID: 284)
,I/io.jxcore.node.OutgoingSocketThread( 2954): Server socket local port: 41230
I/io.jxcore.node.OutgoingSocketThread( 2954): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 2954): onListeningForIncomingConnections: Outgoing connection is using port 41230 (peer ID: 7C:F9:0E:51:18:22)
,I/jxcore-log( 2954): 2015-12-07T10:14:53.035Z SendDataConnector.js: CLIENT connected to 41230, error: null
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:53.035Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:53.038Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.OutgoingSocketThread( 2954): Incoming data from: /127.0.0.1, port: 41230
I/io.jxcore.node.OutgoingSocketThread( 2954): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2954): startStreamCopyingThreads: OK
I/io.jxcore.node.OutgoingSocketThread( 2954): Exiting thread (ID: 284)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 286, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 285, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 848 bytes (thread ID: 285, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 848 bytes (thread ID: 285, thread name: Sender)
,I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 848 bytes
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/ProcessCpuTracker(  761): Skipping unknown process pid 3618
,W/ProcessCpuTracker(  761): Skipping unknown process pid 3619
W/ProcessCpuTracker(  761): Skipping unknown process pid 3621
W/ProcessCpuTracker(  761): Skipping unknown process pid 3622
W/ProcessCpuTracker(  761): Skipping unknown process pid 3623
W/ProcessCpuTracker(  761): Skipping unknown process pid 3624
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:54.457Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:54.728Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2954): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:55.107Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:55.360Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2954): 2015-12-07T10:14:55.818Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:56.072Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:56.447Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:56.572Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:56.779Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 286, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:14:56.996Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:56.997Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:57.013Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:14:57.013Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): disconnectOutgoingConnection: Found an outgoing connection to peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 2954): close
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 286
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 285
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 285, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 286, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2954): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:51:18:22)
,W/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Failed to find a thread with ID 284
,W/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Failed to find a thread with ID 284
I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 286, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 285, name: Sender)
,I/jxcore-log( 2954): 2015-12-07T10:14:57.059Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2954): 
I/jxcore-log( 2954): ---- round done--------
I/jxcore-log( 2954): 
I/jxcore-log( 2954): do fake peer & start
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:57.062Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:57.074Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:14:57.075Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 80:01:84:8A:B3:68)
I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 80:01:84:8A:B3:68
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1364): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1364): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 80:01:84:8A:B3:68
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,E/BluetoothEventManager( 3022): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Socket connection succeeded after 1 attempt(s)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Outgoing connection initialized (thread ID: 288)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesWritten: 77 bytes successfully written (thread ID: 288)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Entering thread (ID: 288)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesRead: Read 84 bytes successfully (thread ID: 288)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT9127 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT9127 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Exiting thread (ID: 288)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT9127 80:01:84:8A:B3:68]
I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT9127, Bluetooth address: 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2954): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing socket thread, for peer with ID 80:01:84:8A:B3:68, created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2954): Entering thread (ID: 289)
I/io.jxcore.node.OutgoingSocketThread( 2954): Server socket local port: 46613
I/io.jxcore.node.OutgoingSocketThread( 2954): Now accepting connections...
I/io.jxcore.node.ConnectionHelper( 2954): onListeningForIncomingConnections: Outgoing connection is using port 46613 (peer ID: 80:01:84:8A:B3:68)
,I/jxcore-log( 2954): 2015-12-07T10:15:26.644Z SendDataConnector.js: CLIENT connected to 46613, error: null
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:15:26.644Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:15:26.657Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.OutgoingSocketThread( 2954): Incoming data from: /127.0.0.1, port: 46613
I/io.jxcore.node.OutgoingSocketThread( 2954): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 2954): startStreamCopyingThreads: OK,
I/io.jxcore.node.OutgoingSocketThread( 2954): Exiting thread (ID: 289)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 290, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 291, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 290, thread name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 848 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 848 bytes (thread ID: 290, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 848 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:27.195Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:27.229Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:27.280Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2954): 
,W/bt-btif ( 3010): dm_pm_timer expires
W/bt-btif ( 3010): dm_pm_timer expires 0
W/bt-btif ( 3010): proc dm_pm_timer expires
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:33.369Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:33.827Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:33.967Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:34.123Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:34.260Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:36.195Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 291, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:38.942Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:15:38.943Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:15:38.958Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:15:38.959Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2954): 
,I/io.jxcore.node.ConnectionHelper( 2954): disconnectOutgoingConnection: Found an outgoing connection to peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 80:01:84:8A:B3:68
I/io.jxcore.node.OutgoingSocketThread( 2954): close
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 291
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 290
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 290, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 291, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2954): disconnectOutgoingConnection: Successfully disconnected (peer ID: 80:01:84:8A:B3:68)
,W/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Failed to find a thread with ID 289
I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 290, name: Sender)
,W/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Failed to find a thread with ID 289
I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 291, name: Receiver)
,I/jxcore-log( 2954): 2015-12-07T10:15:38.996Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): ---- round done--------
I/jxcore-log( 2954): 
I/jxcore-log( 2954): do fake peer & start
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:15:38.998Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:15:38.998Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:15:38.998Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 08:EC:A9:50:75:41
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1,
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1364): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1364): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 12
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State,
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3022): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3022): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Socket connection succeeded after 2 attempt(s)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Outgoing connection initialized (thread ID: 293)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesWritten: 77 bytes successfully written (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Entering thread (ID: 293)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): onBytesRead: Read 83 bytes successfully (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2954): Exiting thread (ID: 293)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT4160, Bluetooth address: 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 2954): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
,I/io.jxcore.node.OutgoingSocketThread( 2954): Entering thread (ID: 294)
I/io.jxcore.node.OutgoingSocketThread( 2954): Server socket local port: 45155
I/io.jxcore.node.OutgoingSocketThread( 2954): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2954): onListeningForIncomingConnections: Outgoing connection is using port 45155 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 2954): 2015-12-07T10:15:48.464Z SendDataConnector.js: CLIENT connected to 45155, error: null
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:15:48.465Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:15:48.472Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2954): 
,I/io.jxcore.node.OutgoingSocketThread( 2954): Incoming data from: /127.0.0.1, port: 45155
,I/io.jxcore.node.OutgoingSocketThread( 2954): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2954): startStreamCopyingThreads: OK
I/io.jxcore.node.OutgoingSocketThread( 2954): Exiting thread (ID: 294)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 296, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Entering thread (ID: 295, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2954): Read 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 8192 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 848 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 848 bytes (thread ID: 295, thread name: Sender)
I/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread succeeded to read/write 848 bytes
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716,
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 296, thread name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 296, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:50.984Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2954): 
,I/io.jxcore.node.StreamCopyingThread( 2954): Read 3 bytes (thread ID: 296, thread name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Wrote 3 bytes (thread ID: 296, thread name: Receiver)
I/io.jxcore.node.OutgoingSocketThread( 2954): The receiving thread succeeded to read/write 3 bytes
,I/jxcore-log( 2954): 2015-12-07T10:15:52.730Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2954): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): dm_pm_timer expires
W/bt-btif ( 3010): dm_pm_timer expires 0
,W/bt-btif ( 3010): proc dm_pm_timer expires
,I/jxcore-log( 2954): 2015-12-07T10:16:02.732Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:16:02.733Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:16:02.735Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:16:02.736Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:16:02.737Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2954): 
,E/io.jxcore.node.StreamCopyingThread( 2954): Input stream got -1 on read (thread ID: 295, thread name: Sender)
,E/io.jxcore.node.OutgoingSocketThread( 2954): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
,I/io.jxcore.node.OutgoingSocketThread( 2954): close
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 296
I/io.jxcore.node.OutgoingSocketThread( 2954): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2954): doStop: Thread ID: 295
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2954): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2954): Either failed to read from the output stream or write to the input stream (thread ID: 296, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2954): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2954): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 2954): closeAndRemoveOutgoingConnectionThread: Failed to find a thread with ID 294
I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 296, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2954): Exiting thread (ID: 295, name: Sender)
,I/jxcore-log( 2954): 2015-12-07T10:16:07.738Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:16:07.744Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:16:12.753Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:16:12.754Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:16:12.755Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:16:12.755Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 08:EC:A9:50:75:41
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x41
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 14
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
,I/jxcore-log( 2954): 2015-12-07T10:17:12.780Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:17:12.781Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:17:12.781Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
,I/jxcore-log( 2954): 2015-12-07T10:17:17.783Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:17:17.784Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:17:22.788Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:17:22.789Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:17:22.794Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:17:22.794Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
,I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 08:EC:A9:50:75:41
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x42
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 15
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
,I/jxcore-log( 2954): 2015-12-07T10:18:22.831Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:18:22.832Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:18:22.833Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
,I/jxcore-log( 2954): 2015-12-07T10:18:27.834Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:18:27.835Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:18:32.840Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:18:32.841Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:18:32.841Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:18:32.842Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 08:EC:A9:50:75:41
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x43
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 16
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
I/jxcore-log( 2954): 2015-12-07T10:19:32.856Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:19:32.856Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:19:32.857Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
,I/jxcore-log( 2954): 2015-12-07T10:19:37.858Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:19:37.859Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:19:42.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:19:42.867Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:19:42.868Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:19:42.869Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
,I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address 08:EC:A9:50:75:41
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x44
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 17
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
I/jxcore-log( 2954): 2015-12-07T10:20:42.887Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:42.888Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:20:42.905Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:42.906Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:42.909Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): ---- round done--------
I/jxcore-log( 2954): 
I/jxcore-log( 2954): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 2954): 
I/jxcore-log( 2954): do fake peer & start
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:42.916Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:42.917Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:42.917Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to peer with ID 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F4:F1:E1:5C:3B:E2
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT4160 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:18, channel:-1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 2954): 2015-12-07T10:20:43.866Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:43.867Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:43.867Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 18
,I/jxcore-log( 2954): 2015-12-07T10:20:48.869Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:48.869Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:20:53.873Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2,
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:53.874Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:53.874Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:20:53.875Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F4:F1:E1:5C:3B:E2
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:19, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 2954): 2015-12-07T10:21:53.913Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:21:53.913Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:21:53.914Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x48
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 19
,I/jxcore-log( 2954): 2015-12-07T10:21:58.915Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:21:58.916Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2954): 2015-12-07T10:22:03.919Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:22:03.922Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:22:03.922Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:22:03.923Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F4:F1:E1:5C:3B:E2
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:20, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 2954): 2015-12-07T10:23:03.954Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:23:03.954Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:23:03.955Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x49
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 20,
,I/jxcore-log( 2954): 2015-12-07T10:23:08.957Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:23:08.958Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2954): 2015-12-07T10:23:13.963Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:23:13.964Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:23:13.966Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:23:13.967Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F4:F1:E1:5C:3B:E2
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x1f  CID 0x47
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 21
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1,
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:22, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 2954): 2015-12-07T10:24:14.004Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:24:14.004Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:24:14.005Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:24:19.007Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:24:19.008Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:24:24.013Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:24:24.013Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:24:24.014Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:24:24.015Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F4:F1:E1:5C:3B:E2
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 23
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x45
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 22
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4a
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 24
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 25
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:26, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
I/jxcore-log( 2954): 2015-12-07T10:25:24.047Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:25:24.048Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:25:24.064Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:25:24.067Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2954): 
I/jxcore-log( 2954): ---- round done--------
I/jxcore-log( 2954): 
I/jxcore-log( 2954): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 2954): 
I/jxcore-log( 2954): do fake peer & start
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:25:24.074Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:25:24.075Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:25:24.076Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F8:CF:C5:D9:E5:61
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:2, scn:-410251100
W/bt-btif ( 3010): invalid rfc slot id: 27
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 28
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 29
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 30
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 31
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 32
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 6 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:2, scn:-410251100,
,W/bt-btif ( 3010): invalid rfc slot id: 33
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 7 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 34
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 8 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 35
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 9 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 36
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 10 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 37
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 11 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 38
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 12 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 39
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 13 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 40
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 14 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 41
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 15 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 42
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 16 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 43
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 17 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 44
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 18 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 45
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 19 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 46
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 20 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 47
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 21 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 48
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 22 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 49
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 23 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 50
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 24 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 51
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 25 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 52
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 26 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 53
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 27 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 54
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 28 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 55
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 29 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 56
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 30 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 57
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 31 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 58
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 32 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 59
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 33 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 60
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 34 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 61
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 35 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4c
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 26
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 0, 0, 0
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 36 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 36 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:62, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 36 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2954): 2015-12-07T10:26:24.106Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:26:24.107Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:26:24.109Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:26:29.114Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:26:29.115Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:26:34.119Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:26:34.120Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:26:34.120Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:26:34.121Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F8:CF:C5:D9:E5:61
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 63
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 64
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 65
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 66
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 67
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 68
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 6 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 69
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 7 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 70
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 8 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 71
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 9 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 72
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 10 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 73
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 11 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 74
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 12 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 75
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 13 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 76
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 14 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 77
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 15 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 78
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 16 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 79
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 17 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 80
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 18 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 81
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 19 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 82
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 20 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 83
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 21 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 84
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 22 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 85
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 23 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 86
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 24 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 87
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 25 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 88
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 26 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 89
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 27 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 90
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 28 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 91
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 29 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4d
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 62
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 30 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 30 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:92, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 30 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2954): 2015-12-07T10:27:34.153Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:27:34.154Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:27:34.154Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:27:39.155Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:27:39.156Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:27:44.159Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:27:44.164Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:27:44.164Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:27:44.167Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
,I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F8:CF:C5:D9:E5:61
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 93
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 94
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 95
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 96
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 97
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 98
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 6 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 99
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 7 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 100
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 8 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 101
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 9 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 102
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 10 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 103
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 11 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 104
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 12 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 105
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 13 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 106
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 14 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:107, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 107
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 15 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:108, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 108
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 16 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:109, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 109
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 17 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:110, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 110
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 18 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:111, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 111
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 19 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:112, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 112
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 20 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4e
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 92
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 21 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 21 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:113, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 21 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2954): 2015-12-07T10:28:44.203Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:28:44.204Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:28:44.205Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:28:49.206Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:28:49.208Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:28:54.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:28:54.216Z SendDataConnector.js: Connect (retry count 3) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:28:54.217Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:28:54.217Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F8:CF:C5:D9:E5:61
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:114, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 114
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:115, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 115
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:116, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 116
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:117, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 117
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:118, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 118
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:119, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 119
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 6 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:120, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 120
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 7 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:121, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 121
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 8 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:122, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 122
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 9 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:123, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 123
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 10 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:124, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 124
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 11 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4f
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:113, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 113
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     ( 1555): Explicit concurrent mark sweep GC freed 24938(1661KB) AllocSpace objects, 21(336KB) LOS objects, 25% free, 22MB/29MB, paused 569us total 54.053ms
,I/EventLogService( 1555): Aggregate from 1449481950574 (log), 1449481950574 (data)
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 82 17 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = a7 8b 09 50 73 18 2e 2b fa b6 fa ad c9 85 67 b5 
W/bt-btm  ( 3010): Stopping oneshot timer
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 12 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 12 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:125, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 12 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2954): 2015-12-07T10:29:54.248Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:29:54.249Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:29:54.249Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:29:59.254Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:29:59.255Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:30:04.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:30:04.258Z SendDataConnector.js: Connect (retry count 4) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:30:04.259Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:30:04.259Z SendDataConnector.js: do connect now
I/jxcore-log( 2954): 
,I/io.jxcore.node.ConnectionHelper( 2954): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
W/io.jxcore.node.ConnectionHelper( 2954): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Trying to start connecting to null in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnecting: null F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): connect: Started connecting to null in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2954): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect to peer with address F8:CF:C5:D9:E5:61
W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:126, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3010): invalid rfc slot id: 126
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Trying to connect again in 1000 ms
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x41
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:125, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 125
,W/BluetoothAdapter( 2954): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2954): timeout now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): dun
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): weAreDoneNow , resultArray.length: 3
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): done, now sending data to server
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): -- RESULT DATA {"name:":"LGE-Nexus 5_PT5801","time":1000052,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":19503,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":27485,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"80:01:84:8A:B3:68","time":41869,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0
I/jxcore-log( 2954): sendList : 100% : 41869 ms, 99% : 41869 ms, 95 : 41869 ms, 90% : 41869 ms.
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Result count 3, range 19503 ms to  41869 ms.
I/jxcore-log( 2954): 
I/jxcore-log( 2954): sendList failed peers count : 3 [50 %]
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 2954): 
I/jxcore-log( 2954): sendList never tried peers count : 16 [72.72727272727273 %]
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 34:FC:EF:11:B1:66
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 38:94:96:B5:06:DC
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 90:E7:C4:F6:69:77
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 2954): 
I/jxcore-log( 2954): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:30:50.043Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:30:50.043Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:127, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2954): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Cancelled: Connection timeout [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 [F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61 F8:CF:C5:D9:E5:61]
I/jxcore-log( 2954): 2015-12-07T10:31:04.296Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:31:04.296Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2954): 
I/jxcore-log( 2954): 2015-12-07T10:31:04.297Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:31:04.304Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2954): 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x42
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:127, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 127
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2954): DBG, CoordinatorConnector command called
I/jxcore-log( 2954): 
I/jxcore-log( 2954): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2954): 
I/jxcore-log( 2954): stop tests now !
I/jxcore-log( 2954): 
I/jxcore-log( 2954): stop current!
I/jxcore-log( 2954): 
I/jxcore-log( 2954): testSendData stopped
I/jxcore-log( 2954): 
I/io.jxcore.node.ConnectionHelper( 2954): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2954): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2954): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): setState: NOT_INITIALIZED
I/jxcore-log( 2954): StopBroadcasting went ok
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): 2015-12-07T10:35:10.391Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2954): 
I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2954): onConnectionFailed: Socket is null
,I/io.jxcore.node.ConnectionHelper( 2954): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 2954): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 2954): DBG, CoordinatorConnector command called
I/jxcore-log( 2954): 
I/jxcore-log( 2954): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"58:3F:54:73:64:C0\",\"time\":19503,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"7C:F9:0E:51:18:22\",\"time\":27485,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"80:01:84:8A:B3:68\",\"time\":41869,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\
I/jxcore-log( 2954): ****TEST TOOK:  ms ****
I/jxcore-log( 2954): 
I/jxcore-log( 2954): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2954): 
I/jxcore-log( 2954): stop tests now !
I/jxcore-log( 2954): 
I/jxcore-log( 2954): end, event received
I/jxcore-log( 2954): 
I/jxcore-log( 2954): CoordinatorConnector close called
I/jxcore-log( 2954): 
,I/jxcore-log( 2954): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2954): 
I/jxcore-log( 2954): The Coordinator has disconnected!
I/jxcore-log( 2954): 
I/jxcore-log( 2954): The Coordinator has closed!
I/jxcore-log( 2954): 
I/jxcore-log( 2954): stop tests now !
I/jxcore-log( 2954): 
I/jxcore-log( 2954): turning Radios off
I/jxcore-log( 2954): 
I/jxcore-log( 2954): Toggling radios to false
I/jxcore-log( 2954): 
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@5b4ba mBinding = false
,D/BluetoothManagerService(  761): Message: 2
D/BluetoothManagerService(  761): Sending off request.
,D/BluetoothAdapterState( 3010): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3010): Setting state to 13
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3010): onBluetoothDisable()
I/BluetoothAdapterState( 3010): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3010): Scan Mode:20
,D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3010): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3010): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3010): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3010): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3010): onReceive
D/BluetoothMapService( 3010): STATE_TURNING_OFF
V/BluetoothMapService( 3010): Handler(): got msg=4
D/BluetoothMapService( 3010): MAP Service closeService in
D/BluetoothMapMasInstance( 3010): MAP Service shutdown
V/BluetoothMapService( 3010): MAP Service closeService out
,I/BtOppRfcommListener( 3010): stopping Accept Thread
,I/BtOppRfcommListener( 3010): BluetoothSocket listen thread finished
,W/ContextImpl( 3022): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiService(  761): setWifiEnabled: false pid=2954, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,D/DockEventReceiver( 3022): finishStartingService: stopping service
,E/WifiStateMachine(  761): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  761): do suspend true
,I/jxcore-log( 2954): Radios toggled
I/jxcore-log( 2954): 
,I/chromium( 2954): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/AuthorizationBluetoothService( 1432): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 3022): Proxy object disconnected
D/PbapServerProfile( 3022): Bluetooth service disconnected
V/NativeCrypto( 1432): Read error: ssl=0x9ca3c400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1432): SSL shutdown failed: ssl=0x9ca3c400: I/O error during system call, Broken pipe
,D/ConnectivityService(  761): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiStateMachine(  761): scanCount==0 - aborting
D/WifiNetworkAgent(  761): NetworkAgent: NetworkAgent channel lost
D/WifiScanningService(  761): SCAN_AVAILABLE : 1
D/RttService(  761): SCAN_AVAILABLE : 1
D/WifiScanningService(  761): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  761): DefaultState
D/RttService(  761): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/native  (  761): do suspend true
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  761): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  761): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  761): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityManager.CallbackHandler( 1555): CM callback handler got msg 524292
,D/TelephonyNetworkFactory( 1202): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/AndroidRuntime( 3704): 
D/AndroidRuntime( 3704): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3704): CheckJNI is OFF
,D/AndroidRuntime( 3704): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  761): Killing 2954:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/wpa_supplicant( 3017): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3017): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  761): Skipping PackageSetting{265e1587 com.example.hello/10277} due to missing metadata
,I/WindowState(  761): WIN DEATH: Window{35d5f125 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  761): Client connection lost with reason: 4
,I/wpa_supplicant( 3017): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  761): InitialState.processMessage what=4
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{3eb34b66 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  761): Spurious death for ProcessRecord{13ca6286 2954:com.test.thalitest/u0a270}, curProc for 2954: null
I/ActivityManager(  761): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  761):   Force finishing activity ActivityRecord{3eb34b66 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  761): Duplicate finish request for ActivityRecord{3eb34b66 u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1364): Explicit concurrent mark sweep GC freed 34335(1901KB) AllocSpace objects, 5(103KB) LOS objects, 25% free, 19MB/25MB, paused 324us total 38.089ms
D/Tethering(  761): sendTetherStateChangedBroadcast 0, 0, 0
,I/InputReader(  761): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1258): Explicit concurrent mark sweep GC freed 3972(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 757us total 42.645ms
,W/GeofencerStateMachine( 1315): Ignoring removeGeofence because network location is disabled.
,W/Settings( 1315): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1794): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator( 1074): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1074): run()
,I/Decoder ( 1074): createOrResetDecoder
,I/ActivityManager(  761): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3757 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/art     (  761): Explicit concurrent mark sweep GC freed 25150(1551KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.276ms total 84.297ms
,I/art     (  761): WaitForGcToComplete blocked for 22.297ms for cause Explicit
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
I/ConfigService( 1432): onCreate
,D/OpenGLRenderer(  946): Enabling debug mode 0
,D/BackupManagerService(  761): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1074): run()
D/JobSchedulerService(  761): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  761): removeObsoleteFile: deleting file=214_task.xml
W/InputMethodManagerService(  761): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@21d0cf88 (uid=10034 pid=946)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1074): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1074): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1074): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1074): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1074): run()
I/StatsUtilsManager( 1074): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1074): shouldRecordStats() = Too Soon
,W/InputMethodManagerService(  761): Got RemoteException sending setActive(false) notification to pid 2954 uid 10270
,I/Keyboard.Facilitator( 1074): onFinishInput()
I/art     (  761): Explicit concurrent mark sweep GC freed 7636(417KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.143ms total 138.289ms
,D/VoicemailCleanupService( 3757): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1364): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1258): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@c4f24c new=com.google.android.velvet.VelvetApplication@c4f24c
,I/ActivityManager(  761): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3794 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ContactLocale( 3757): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  761): Killing 1463:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,I/Launcher( 1258): Deferring update until onResume
,D/AndroidRuntime( 3704): Shutting down VM
,W/ResourcesManager( 1258): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1258): Deferring update until onResume
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1463/cgroup.procs: No such file or directory
,W/ContextImpl( 3794): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1364): UpdateCorporaTask done [took 166 ms] updated apps [took 166 ms] 
,D/PackageBroadcastService( 1555): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1555): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1555): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1555): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1555): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1555): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1555): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1432): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1432): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1555): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1555): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1555): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1555): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1555): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1555): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1555): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1555): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1555): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1555): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1555): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1555): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1555): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  761): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3826 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1555): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1555): App measurement is starting up
,W/BaseAppContext( 1555): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1555): CP2 sync disabled
I/Icing   ( 1555): doRemovePackageData com.test.thalitest
,I/ActivityManager(  761): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3849 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2722:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10005/pid_2722/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 2484:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10060/pid_2484/cgroup.procs: No such file or directory
,D/ExternalStorage( 3849): After updating volumes, found 1 active roots

```
