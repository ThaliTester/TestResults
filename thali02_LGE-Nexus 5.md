#### Test 5133502830f515a_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2864): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2864): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
V/JNIHelp ( 2864): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/Finsky  ( 2378): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  736): Killing 2189:com.google.android.youtube/u0a80 (adj 15): empty #17
W/System  ( 2864): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2864): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  736): failed to open /acct/uid_10080/pid_2189/cgroup.procs: No such file or directory
V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1557): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1557): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1557): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 2927): 
D/AndroidRuntime( 2927): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2927): CheckJNI is OFF
D/AndroidRuntime( 2927): Calling main entry com.android.commands.am.Am
I/ActivityManager(  736): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  736): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2948 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2927): Shutting down VM
V/ActivityManager(  736): Display changed displayId=0
I/WebViewFactory( 2948): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2948): Time to load native libraries: 3 ms (timestamps 8731-8734)
I/LibraryLoader( 2948): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2948): Binding Chromium to main looper Looper (main, tid 1) {1328ffd5}
I/LibraryLoader( 2948): Expected native library version number "",actual native library version number ""
I/chromium( 2948): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2948): Initializing chromium process, singleProcess=true
W/art     ( 2948): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2948): ApplicationContext is null in ApplicationStatus
W/chromium( 2948): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/chromium( 2948): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
E/libEGL  ( 2948): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2948): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2948): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2038d583:true
,I/ActivityManager(  736): Killing 2291:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/BluetoothAdapter( 2948): 307786934: getState() :  mService = null. Returning STATE_OFF
,W/libprocessgroup(  736): failed to open /acct/uid_10038/pid_2291/cgroup.procs: No such file or directory
,W/art     ( 2948): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2948): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2948): CordovaWebView is running on device made by: LGE
,W/art     ( 2948): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2948): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2948): Render dirty regions requested: true
,D/Atlas   ( 2948): Validating map...
,W/chromium( 2948): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2948): Initialized EGL, version 1.4
D/OpenGLRenderer( 2948): Enabling debug mode 0
,W/IInputConnectionWrapper( 2948): showStatusIcon on inactive InputConnection
,I/ActivityManager(  736): Displayed com.test.thalitest/.MainActivity: +452ms (total +58s225ms)
,W/BindingManager( 2948): Cannot call determinedVisibility() - never saw a connection for the pid: 2948
,D/JsMessageQueue( 2948): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2948): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1549043584
D/JX-Cordova( 2948): jxcore cordova android initializing
,W/jxcore-log( 2948): Initializing JXcore engine
W/jxcore-log( 2948): JXcore engine is ready
W/jxcore-log( 2948): Starting JXcore engine
,W/.test.thalitest( 2948): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8384]" dev="sockfs" ino=8384 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2948): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2948): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8459]" dev="sockfs" ino=8459 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2948): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18381]" dev="sockfs" ino=18381 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2948): Platform android
W/jxcore-log( 2948): 
W/jxcore-log( 2948): Process ARCH arm
W/jxcore-log( 2948): 
,I/jxcore-log( 2948): JXcore Cordova bridge is ready!
I/jxcore-log( 2948): 
W/jxcore-log( 2948): JXcore engine is started
,I/Choreographer( 2948): Skipped 106 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2948): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2948): Toggling radios to true
I/jxcore-log( 2948): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  736): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  736): Message: 1
D/BluetoothManagerService(  736): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  736): New client listening to asynchronous messages
,D/WifiService(  736): setWifiEnabled: true pid=2948, uid=10270
E/WifiService(  736): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2948): Radios toggled
I/jxcore-log( 2948): 
I/ActivityManager(  736): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3010 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  181): Softap fwReload - Ok
D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring down wlan0
D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/WifiMonitor(  736): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  736): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3017 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3016): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3010): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3016): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23dcbbe1:true
,D/BluetoothAdapter( 3017): 321454037: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  736): Message: 30
,D/BluetoothManagerService(  736): Message: 30
,D/LocalBluetoothProfileManager( 3017): Adding local MAP profile
D/BluetoothMap( 3017): Create BluetoothMap proxy object
D/BluetoothManagerService(  736): Message: 30
,D/BluetoothManagerService(  736): Message: 30
,D/LocalBluetoothProfileManager( 3017): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3017): 321454037: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3017): 321454037: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  736): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3059 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  736): Killing 2342:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10069/pid_2342/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 3010): Adding HeadsetService
D/AdapterServiceConfig( 3010): Adding A2dpService
,D/AdapterServiceConfig( 3010): Adding HidService
D/AdapterServiceConfig( 3010): Adding HealthService
D/AdapterServiceConfig( 3010): Adding PanService
D/AdapterServiceConfig( 3010): Adding GattService
D/AdapterServiceConfig( 3010): Adding BluetoothMapService
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3acb0824:true
D/BluetoothAdapterState( 3010): make
,I/BluetoothAdapterState( 3010): Entering OffState
,I/bluedroid( 3010): init
V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/bte_conf( 3010): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 3010): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3010): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3010): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3010): get_profile_interface socket
,I/bluedroid( 3010): get_profile_interface map_client
I/GKI_LINUX( 3010): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3010): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothAdapterProperties( 3010): Name is: Nexus 5
D/BluetoothManagerService(  736): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  736): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  736): Message: 40
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3010): config_hci_snoop_log
D/BluetoothManagerService(  736): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  736): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 3010): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3010): Setting state to 11
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  736): Message: 60
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  736): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3010): make
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,D/BluetoothHeadset( 1232): Proxy object connected
D/HeadsetService( 3010): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3010): classInitNative: succeeds
D/BluetoothHeadset(  736): Proxy object connected
D/BluetoothHeadset( 1196): Proxy object connected
D/BluetoothHeadset( 1196): Proxy object connected
D/HeadsetStateMachine( 3010): make
I/BluetoothAdapterState( 3010): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 3010): max_hf_connections = 1
I/bluedroid( 3010): get_profile_interface handsfree
,D/HeadsetStateMachine( 3010): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
,D/A2dpService( 3010): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3010): classInitNative: succeeds
I/bluedroid( 3010): get_profile_interface avrcp
,D/BluetoothA2dp(  736): Proxy object connected
,W/NetworkUtils( 1367): OkHttp exception
W/EventLoggerService( 1367): Unable to send logs Error code: 262146
,I/art     (  736): Explicit concurrent mark sweep GC freed 13484(640KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.151ms total 51.063ms
,E/RemoteController( 3010): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3010): classInitNative: succeeds
D/A2dpStateMachine( 3010): make
,I/bluedroid( 3010): get_profile_interface a2dp
I/GKI_LINUX( 3010): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
I/BluetoothHidServiceJni( 3010): classInitNative: succeeds
,D/A2dpStateMachine( 3010): Enter Disconnected: -2
,D/HidService( 3010): Received start request. Starting profile...
W/Search.LoginHelper( 1367): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/bluedroid( 3010): get_profile_interface hidhost
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
I/BluetoothHealthServiceJni( 3010): classInitNative: succeeds
D/HealthService( 3010): Received start request. Starting profile...
I/bluedroid( 3010): get_profile_interface health
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
,D/BluetoothInputDevice( 3017): Proxy object connected
,I/BluetoothPanServiceJni( 3010): classInitNative(L105): succeeds
,D/HidProfile( 3017): Bluetooth service connected
,D/PanService( 3010): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3010): initializeNative(L110): pan
I/bluedroid( 3010): get_profile_interface pan
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothPan( 3017): BluetoothPAN Proxy object connected
D/PanProfile( 3017): Bluetooth service connected
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
I/BtGatt.JNI( 3010): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3010): handleDebugAction() action=null
,D/BtGatt.GattService( 3010): Received start request. Starting profile...
D/BtGatt.GattService( 3010): start()
I/bluedroid( 3010): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3010): advertise manager created
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
,W/Search.LoginHelper( 1367): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/BluetoothMapService( 3010): BluetoothMapBinder()
,D/BluetoothMapService( 3010): Received start request. Starting profile...
D/BluetoothMapService( 3010): start()
,D/BluetoothMap( 3017): Proxy object connected
D/MapProfile( 3017): Bluetooth service connected
D/BluetoothMap( 3017): getConnectedDevices()
,D/BluetoothMapEmailSettingsLoader( 3010): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3010): createReceiver()
,D/BluetoothMapEmailAppObserver( 3010): initObservers()
D/BluetoothMapEmailAppObserver( 3010): getEnabledAccountItems()
D/BluetoothMap( 3017): Bluetooth is Not enabled
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
,D/HeadsetStateMachine( 3010): Proxy object connected
D/HeadsetStateMachine( 3010): Disconnected process message: 10, size: 0
,V/BluetoothMapService( 3010): Handler(): got msg=1
,D/HeadsetPhoneState( 3010): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3010): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3010): enable
,I/GKI_LINUX( 3010): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3010): btu_task pending for preload complete event
I/bt_hci_bdroid( 3010): init
,I/bt_vendor( 3010): init
I/bt_vnd_conf( 3010): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3010): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3010): userial_init
,I/bt_userial_vendor( 3010): userial vendor open: opening /dev/ttyHS99
I/art     ( 1414): Explicit concurrent mark sweep GC freed 13593(795KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 1.345ms total 43.054ms
,I/bt_userial_vendor( 3010): device fd = 53 open
,D/bt_userial( 3010): Entering userial_read_thread()
,D/AuthorizationBluetoothService( 1414): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  736): Killing 1772:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3010): Chipset BCM4335C0
D/bt_hwcfg( 3010): Target name = [BCM4335C0]
I/bt_hwcfg( 3010): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  736): failed to open /acct/uid_10045/pid_1772/cgroup.procs: No such file or directory
,D/Tethering(  736): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3016): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3010): Settlement delay -- 100 ms
I/bt_hwcfg( 3010): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  736): Loading config and enabling all networks 
,D/WifiService(  736): New client listening to asynchronous messages
,E/WifiConfigStore(  736): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  736): Setting external_sim to 1
,W/Settings( 1791): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  736): Setting OUI to DA-A1-19
I/WifiNative-HAL(  736): startHal
,D/wifi    (  736): setting scan oui 0x9b8946e8
D/WifiHAL (  736): Sending mac address OUI
E/WifiHAL (  736): failed to set scanning mac OUI; result = -95
,E/native  (  736): do suspend true
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring up p2p0
,D/WifiMonitor(  736): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  736): p2pGetDeviceAddress
,D/WifiNative-HAL(  736): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,D/WifiScanningService(  736): SCAN_AVAILABLE : 3
D/RttService(  736): SCAN_AVAILABLE : 3
D/RttService(  736): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  736): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  736): startHal
,D/wifi    (  736): getting scan capabilities on interface[1] = 0x9b8946e8
,D/WifiHAL (  736): Creating message to get scan capablities; iface = 21
D/WifiHAL (  736): In GetCapabilities::handleResponse
D/WifiHAL (  736): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  736): StartedState
,I/bt_hwcfg( 3010): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3010): Setting local bd addr to 34:FC:EF:11:AE:67
,I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3010): vendor lib fwcfg completed
I/bt-btu  ( 3010): btu_task received preload complete event
,I/        ( 3010): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3010): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3010): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3010): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3010): BTE_InitTraceLevels -- TRC_AVRC
,I/        ( 3010): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3010): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3010): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3010): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3010): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3010): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3010): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3010): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3010): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3010): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3010): BTM_SecRegister:p_cb_info->p_le_callback == 0xa409d9d5 
E/bt-btm  ( 3010): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa409d9d5 
,E/bt-btif ( 3010): Calling BTA_HhEnable
E/bt-btif ( 3010): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3010): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  736): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterProperties( 3010): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3010): Scan Mode:20
D/BluetoothAdapterProperties( 3010): Discoverable Timeout:120
,D/bte_conf( 3010): Device ID record 1 : primary
D/bte_conf( 3010):   vendorId            = 000f
D/bte_conf( 3010):   vendorIdSource      = 0001
D/bte_conf( 3010):   product             = 1200
D/bte_conf( 3010):   version             = 1436
D/bte_conf( 3010):   clientExecutableURL = 
D/bte_conf( 3010):   serviceDescription  = 
D/bte_conf( 3010):   documentationURL    = 
D/bte_conf( 3010): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3010): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3010): ScanMode =  20
D/BluetoothAdapterProperties( 3010): State =  11
D/BluetoothAdapterProperties( 3010): Setting state to 12
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3010): Entering On State
D/BluetoothManagerService(  736): Message: 60
,D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  736): Broadcasting onBluetoothStateChange(true) to 9 receivers.
,D/BluetoothHeadset( 1232): onBluetoothStateChange: up=true
,D/BluetoothAdapterProperties( 3010): Scan Mode:21
D/BluetoothAdapterProperties( 3010): Discoverable Timeout:120
D/BluetoothPbap( 3017): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3017): onBluetoothStateChange: up=true
D/BluetoothHeadset(  736): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1196): onBluetoothStateChange: up=true
D/BluetoothPan( 3017): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1196): onBluetoothStateChange: up=true
D/BluetoothA2dp(  736): onBluetoothStateChange: up=true
D/BluetoothMap( 3017): onBluetoothStateChange: up=true
D/BluetoothManagerService(  736): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  736): Bluetooth State Change Intent: 11 -> 12
,E/bt_h4   ( 3010): vendor lib postload completed
W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 43 48 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 19 b2 46 db e8 5c b3 b0 9f c1 b2 e8 5d 3d be 75 
W/bt-btm  ( 3010): Stopping oneshot timer
D/BluetoothMapService( 3010): onReceive
D/BluetoothMapService( 3010): STATE_ON
V/BluetoothMapService( 3010): Handler(): got msg=1
D/BluetoothMapMasInstance( 3010): Map Service startRfcommSocketListener
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = a2 cf 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 5e 1a d4 63 4f 82 76 a3 70 be 83 3a 12 5c b2 51 
W/bt-btm  ( 3010): Stopping oneshot timer
W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 67 70 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = ab 4f d5 5c 18 3a 58 a8 0f 92 ce a3 6a 3a 97 84 
W/bt-btm  ( 3010): Stopping oneshot timer
W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = a2 73 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 3e f4 a7 3a 3e 93 10 62 01 3c cb e3 b8 bf ec d4 
W/bt-btm  ( 3010): Stopping oneshot timer
D/BluetoothManagerService(  736): Message: 40
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 24 d0 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = df f3 91 53 af f9 55 9b 71 03 67 f4 89 ba bc 4b 
W/bt-btm  ( 3010): Stopping oneshot timer
D/BluetoothMapMasInstance( 3010): MAS initSocket()
D/BluetoothMapMasInstance( 3010):   masId = 00
D/BluetoothMapMasInstance( 3010):   msgTypes = 0e
D/BluetoothMapMasInstance( 3010):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3010):   SDP string = 000eSMS/MMS
I/Telecom ( 1196): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/HeadsetStateMachine( 3010): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3010): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3010): mNumber:  mType: 128
D/HeadsetStateMachine( 3010): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3010): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = b1 24 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 0b 9d ba d9 2d c4 ed 70 4a e1 07 8a 18 34 5f 26 
W/bt-btm  ( 3010): Stopping oneshot timer
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3010): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3010): Accepting socket connection...
,D/LocalBluetoothProfileManager( 3017): Adding local A2DP profile
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = b3 cc 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = 0f 79 6c 6f 82 87 d1 01 6f 22 d4 c9 1e 2a a2 05 
W/bt-btm  ( 3010): Stopping oneshot timer
,D/BluetoothManagerService(  736): Message: 30
,D/LocalBluetoothProfileManager( 3017): Adding local HEADSET profile
,D/BluetoothManagerService(  736): Message: 30
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3017): Proxy object connected
D/A2dpProfile( 3017): Bluetooth service connected
D/BluetoothHeadset( 3017): Proxy object connected
D/HeadsetProfile( 3017): Bluetooth service connected
D/DockEventReceiver( 3017): finishStartingService: stopping service
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbap( 3017): Proxy object connected
,D/PbapServerProfile( 3017): Bluetooth service connected
,D/AuthorizationBluetoothService( 1414): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3010): getBluetoothService() called with no BluetoothManagerCallback
I/BtOppRfcommListener( 3010): Accept thread started.
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2948): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): my name is : LGE-Nexus 5_PT3699
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): attempting to connect to test coordinator
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): check test folder
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): found test : ./testFindPeers.js
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): found test : ./testReConnect.js
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): found test : ./testSendData.js
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): Test app app.js loaded
I/jxcore-log( 2948): 
,I/Choreographer( 2948): Skipped 128 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
I/chromium( 2948): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  736): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  736): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  736): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  736): will read network variables netId=1
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  736): will read network variables netId=1
,I/wpa_supplicant( 3016): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  736): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3016): PNO: In assoc process
,I/wpa_supplicant( 3016): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3016): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  736): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  736): Start Dhcp Watchdog 1
,E/native  (  736): do suspend false
,E/WifiStateMachine(  736): scanCount==0 - aborting
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/dhcpcd  ( 3172): version 5.5.6 starting
,E/dhcpcd  ( 3172): get_duid: Read-only file system
,I/dhcpcd  ( 3172): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3172): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3172): wlan0: leased 192.168.1.114 for 86400 seconds
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,E/native  (  736): do suspend true
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  736): Adding iface wlan0 to network 100
,E/ConnectivityService(  736): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  736): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  736): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  736): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  736): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736):    accepting network in place of null
,D/ConnectivityService(  736): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  736): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  736): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 25 Nov 2015 10:09:43 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448446183826], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448446183812]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Validated
,D/ConnectivityService(  736): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1232): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 2948): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2948): 
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  736): Setting time of day to sec=1448446186
,W/AlarmManagerService(  736): Unable to set rtc to 1448446186: Invalid argument
,I/NetworkMonitor( 2470): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2470): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.SyncManager( 1557): SYNC; picasa accounts
,D/NetworkLogImpl( 1557): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1557): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1557): num queued entries: 0
,I/iu.UploadsManager( 1557): num updated entries: 0
,I/iu.SyncManager( 1557): NEXT; no task
,D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1557): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1557): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1557): onCreate
,D/SystemUpdateService( 1557): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1557): active receiver: enabled
,I/SystemUpdateService( 1557): showing system update notification
,E/GpsLocationProvider(  736): No APN found to select.
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  736): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3272 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1557): retry (wakeup: false) in 3599955 ms
,D/SystemUpdateService( 1557): onDestroy
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GpsLocationProvider(  736): NTP server returned: 1448446183433 (Wed Nov 25 11:09:43 GMT+01:00 2015) reference: 86181 certainty: 8 system time offset: -3048
E/LocSvc_eng(  736): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1791): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1557): [CredentialSyncAdapter] Unknown sync event.
,I/GCM     ( 1414): GCM config loaded
,D/ConnectivityService(  736): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  736): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1557): CM callback handler got msg 524290
,I/GAv4    ( 3272): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3272):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3272):   adb logcat -s GAv4
,W/GAv4    ( 3272): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3272): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3272): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/DriveInitializer( 1557): Awaiting to be initialized
,W/DriveInitializer( 1557): Background init thread started
,W/ResourcesManager( 2864): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2864): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 1414): Explicit concurrent mark sweep GC freed 7952(430KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 1.009ms total 31.145ms
,D/WifiService(  736): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@14c7bc34}
,W/DriveInitializer( 1557): Background init thread ended
,I/WebViewFactory( 3272): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3272): Time to load native libraries: 1 ms (timestamps 9607-9608)
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
,W/Flag    ( 2864): Duration spec must be at least 2 characters long
,V/WebViewChromiumFactoryProvider( 3272): Binding Chromium to main looper Looper (main, tid 1) {2dee717f}
I/LibraryLoader( 3272): Expected native library version number "",actual native library version number ""
I/chromium( 3272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3272): Initializing chromium process, singleProcess=true
,W/art     ( 3272): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3272): ApplicationContext is null in ApplicationStatus
,W/chromium( 3272): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3272): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/art     (  736): Explicit concurrent mark sweep GC freed 47807(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 27MB/41MB, paused 1.454ms total 59.536ms
,W/AudioManagerAndroid( 3272): Requires BLUETOOTH permission
,I/NSApplication( 3272): Starting up...
,I/ActivityManager(  736): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3370 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 188us total 7.802ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 171us total 7.378ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.310ms
,D/TimeService( 3370): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448446187065
D/        ( 3370): TimeServiceNative: User Time to be set is 1448446187066
D/QC-time-services( 3370): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3370): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3370): Lib:time_genoff_operation: pargs->ts_val = 1448446187066
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3370): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448446187066
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1448446187066, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/29/70 16:0:37
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 7574437000
D/QC-time-services(  199): Daemon:new time 1448446187066 
D/QC-time-services(  199): Daemon: delta 1440871750066 genoff 1440871750066 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871750066 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871750066 to memory
,D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
,D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1132481387066
E/QC-time-services( 3370): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,I/CheckinService( 1557): Checkin interval check for package: unspecified last checkin: 1448443186671 min interval config: 0 actual interval: 3000419
,W/art     ( 2584): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  736): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3401 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAv4    ( 3401): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3401):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3401):   adb logcat -s GAv4
,W/GAv4    ( 3401): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3401): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3401): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  736): Killing 2440:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10003/pid_2440/cgroup.procs: No such file or directory
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,E/DefaultHttpIssuer( 2864): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 2864): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 2864): java.io.IOException
E/DefaultHttpIssuer( 2864): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 2864): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 2864): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 2864): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 2864): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 2864): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 2864): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 2864): IOException
E/BaseSyncManager( 2864): java.io.IOException: stream was reset: PROTOCOL_ERROR
E/BaseSyncManager( 2864): 	at hzd.b(PG:145)
E/BaseSyncManager( 2864): 	at hya.b(PG:104)
E/BaseSyncManager( 2864): 	at hxn.d(PG:917)
E/BaseSyncManager( 2864): 	at hxn.a(PG:95)
E/BaseSyncManager( 2864): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 2864): 	at hvz.a(PG:50089)
E/BaseSyncManager( 2864): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 2864): 	at hvz.a(PG:3201)
E/BaseSyncManager( 2864): 	at clz.a(PG:127)
E/BaseSyncManager( 2864): 	at cjr.a(PG:47)
E/BaseSyncManager( 2864): 	at cjq.a(PG:22)
E/BaseSyncManager( 2864): 	at cjs.a(PG:68)
E/BaseSyncManager( 2864): 	at cjw.b(PG:92)
E/BaseSyncManager( 2864): 	at cjw.a(PG:80)
E/BaseSyncManager( 2864): 	at cju.b(PG:5140)
E/BaseSyncManager( 2864): 	at cju.a(PG:1096)
E/BaseSyncManager( 2864): 	at dlh.b(PG:14062)
E/BaseSyncManager( 2864): 	at dlh.a(PG:140)
E/BaseSyncManager( 2864): 	at dqo.a(PG:224)
E/BaseSyncManager( 2864): 	at dlt.run(PG:9618)
E/BaseSyncManager( 2864): 	at dlr.run(PG:3031)
,D/WifiService(  736): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@14c7bc34}
,I/ActivityManager(  736): Killing 2319:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10070/pid_2319/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Killing 1925:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10002/pid_1925/cgroup.procs: No such file or directory
,D/Finsky  ( 2378): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2378): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  736): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3453 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3453): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3453): Created com.android.providers.calendar.CalendarAlarmManager@156a1c8c(com.android.providers.calendar.CalendarProvider2@1328ffd5)
,E/SQLiteLog( 3453): (284) automatic index on view_events(_id)
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/CalendarProvider2( 3453): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3453): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/ActivityManager(  736): Killing 2751:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10008/pid_2751/cgroup.procs: No such file or directory
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1414): Vacuum at: now=1448446197965 tag=VacuumService
V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UdcCache:FPQuery( 1557): Bootstrapping UDC settings cache for all accounts
,I/dex2oat ( 3514): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-1672757186.jar --oat-fd=102 --oat-location=/data/data/com.google.android.gms/cache/ads-1672757186.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3514): dex2oat took 34.542ms (threads: 4)
,I/art     ( 1557): Explicit concurrent mark sweep GC freed 32079(2MB) AllocSpace objects, 19(304KB) LOS objects, 25% free, 22MB/29MB, paused 491us total 69.845ms
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/ClearcutLoggerApiImpl( 1302): disconnect managed GoogleApiClient
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector connect called
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Coordinator is now connected to the server!
I/jxcore-log( 2948): 
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  736): Killing 1377:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10004/pid_1377/cgroup.procs: No such file or directory
,I/jxcore-log( 2948): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector command called
I/jxcore-log( 2948): 
I/jxcore-log( 2948): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"5000\",\"conReTryCount\":\"5\"}","devices":19,"addressList":[{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"
I/jxcore-log( 2948): Start now : testSendData.js
I/jxcore-log( 2948): 
I/jxcore-log( 2948): stop tests now !
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"5000","conReTryCount":"5"}, bt-address lenght : 19
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): check server
I/jxcore-log( 2948): 
I/jxcore-log( 2948): serverPort is 42450
I/jxcore-log( 2948): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2948): Stoping All
I/        ( 2948): Stopping services
I/        ( 2948): Stop Bluetooth
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2948): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2948):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3699","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2948): All stuff available and enabled
I/        ( 2948): Stoping All
I/        ( 2948): Stopping services
I/        ( 2948): Stop Bluetooth
I/        ( 2948): Starting All
I/        ( 2948): Stopping services
I/        ( 2948): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3699","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@ab59ee2
I/        ( 2948): Stopping services
I/        ( 2948): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3699","ra":"34:FC:EF:11:AE:67"}
I/        ( 2948): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT3699","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 2948): peerDiscoveryTimer timeout value:9506
,I/        ( 2948): Stop Bluetooth
I/        ( 2948): StartBluetooth listener
I/        ( 2948): StartBluetooth listener
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 2948): StartBroadcasting started ok
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:32.222Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:15:32.223Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:15:32.223Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2948): Connecting to null, at B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 2015-11-25T10:15:32.227Z SendDataTCPServer.js: TCP/IP server  is bound to : undefined
I/jxcore-log( 2948): 
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2948): We already were running, thus doing nothing
I/        ( 2948): Added local service
I/        ( 2948): Cleared service requests
I/        ( 2948): Stopped peer discovery
I/        ( 2948): Started peer discovery
I/        ( 2948): Discovery state changed to Started.
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 2948): starting to listen
I/BTListenerThread( 2948): waiting to accept incoming Connection
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 5
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:15:33.594Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:15:33.595Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:15:33.598Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTListenerThread( 2948): got MESSAGE_READ 76 bytes.
,I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : LGE-LG-H815_PT153
I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, LGE-LG-H815_PT153
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/SS      ( 2948): Found 1 peers.
I/SS      ( 2948): Peer(1): Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:15:38.200Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.600Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.604Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.818Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.824Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.838Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.851Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.867Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:38.901Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.139Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.156Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.200Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2948): 2015-11-25T10:15:39.227Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2948): 
I/        ( 2948): Started service discovery
,I/jxcore-log( 2948): 2015-11-25T10:15:39.297Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.306Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.357Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.395Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.399Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.403Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.406Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.410Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.414Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.451Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.554Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.605Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.616Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.627Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.645Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.665Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.715Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.754Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.780Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.808Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.842Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:39.874Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 4
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT153
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
,I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT153
I/BtToSocketBase( 2948): Close LocalOutputStream
,I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/jxcore-log( 2948): 2015-11-25T10:15:40.000Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=0
,W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x42
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:15:43.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:15:43.615Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:15:43.616Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:15:43.616Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2948): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2948): Starting to connect
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3845ef6d:true
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: G4-1
,W/bt-btif ( 3010): No ag scb for peer addr
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421524c rs_disc_pending=0
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
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
,I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421524c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2948): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : LGE-LG-D802_PT5232
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, LGE-LG-D802_PT5232
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:16:05.937Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421524c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2948): 2015-11-25T10:16:06.733Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:06.742Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:06.884Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:06.912Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:06.917Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:06.924Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:06.956Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.045Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.121Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.127Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.183Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.332Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.375Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.470Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.498Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.613Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.626Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.664Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.714Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.770Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.799Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:07.856Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.079Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.111Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.211Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.239Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.326Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.416Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.465Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.512Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.558Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.592Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.804Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:08.875Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.003Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.042Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.084Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.114Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:16:09.172Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.239Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.279Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.319Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.333Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.360Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.525Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.535Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.542Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.564Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.713Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:09.788Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 6
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5232
,I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT5232
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/jxcore-log( 2948): 2015-11-25T10:16:09.944Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421524c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421524c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421524c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215414 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT7850","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT7850
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, samsung-SM-N910C_PT7850
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:16:14.566Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.076Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.083Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.115Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.129Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.138Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.199Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2948): 
,W/bt-rfcomm( 3010): PORT_StartCnf failed result:5
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3010): invalid rfc slot id: 7
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:16:15.226Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:15.227Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:15.228Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.236Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,D/BluetoothMapService( 3010): onReceive
,I/jxcore-log( 2948): 2015-11-25T10:16:15.278Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2948): 2015-11-25T10:16:15.291Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.299Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.307Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.341Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.344Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.381Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.389Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.421Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.445Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.448Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.452Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.491Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.516Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.521Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.552Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.594Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.605Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.665Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:15.704Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 8
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT7850
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:16:15.794Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215414 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x4c
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,I/art     (  736): Explicit concurrent mark sweep GC freed 29815(1323KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.180ms total 57.829ms
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215414 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2948): 2015-11-25T10:16:20.230Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:20.231Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2948): 2015-11-25T10:16:25.235Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:25.236Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:25.236Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:25.237Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2948): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): No ag scb for peer addr
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4214ebc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT6304
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT6304
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:16:30.358Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/BTConnectToThread( 2948): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT6304"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2948): HandshakeOk : HTC-HTC Desire 820_PT6304
I/HS      ( 2948): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT6304
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT6304
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 45179
I/BtConnectorHelper( 2948): Request socket is using : 45179
,I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :45179
I/jxcore-log( 2948): 2015-11-25T10:16:30.688Z SendDataConnector.js: CLIENT connected to 45179, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:30.688Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:30.691Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 45179
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:16:30.800Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:30.832Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:30.838Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:30.883Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:30.912Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:30.924Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:30.990Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.027Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.038Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.103Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.124Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.146Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.184Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.267Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.319Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.387Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/jxcore-log( 2948): 2015-11-25T10:16:31.497Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.504Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.539Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.626Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.636Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.648Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.689Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.692Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.819Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.932Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.976Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.982Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.991Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:31.998Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.089Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.123Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.138Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.146Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.170Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.179Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:32.180Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.200Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.200Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
I/BtConnectorHelper( 2948): Disconnect outgoing peer: B4:CE:F6:AB:A4:6A
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 08:EC:A9:50:76:27
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket,
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
,I/jxcore-log( 2948): 2015-11-25T10:16:32.249Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:32.250Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:32.251Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:32.251Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/        ( 2948): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2948): Connecting to null, at 44:80:EB:7B:5A:05
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 59963 ms, rnd: 3, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2948): 2015-11-25T10:16:32.256Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2948): 
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/BluetoothEventManager( 3017): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/jxcore-log( 2948): 2015-11-25T10:16:32.271Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.468Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:32.612Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:33.917Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:33.952Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:33.995Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:34.000Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:16:35.196Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.310Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.468Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.504Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.626Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.631Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.640Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.775Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
,I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/jxcore-log( 2948): 2015-11-25T10:16:35.840Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2948): 
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/jxcore-log( 2948): 2015-11-25T10:16:35.893Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.903Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.945Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:35.954Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:36.108Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:36.116Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,I/BTListenerThread( 2948): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT3108","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT3108
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, samsung-SM-A300FU_PT3108
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/jxcore-log( 2948): 2015-11-25T10:16:36.508Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4214ebc rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): invalid rfc slot id: 9
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT6304
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:16:36.587Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.067Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.077Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.271Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.278Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.310Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.364Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.417Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.690Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.698Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.707Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.827Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.873Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.912Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.928Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:37.983Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.037Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.049Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2948): 
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.292Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.303Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.311Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.316Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.529Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.618Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.899Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.908Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:38.915Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): info:x10
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:16:39.070Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.102Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.161Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.168Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/jxcore-log( 2948): 2015-11-25T10:16:39.293Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.510Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.544Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=1
,W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/jxcore-log( 2948): 2015-11-25T10:16:39.746Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.754Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.766Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.768Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.846Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:39.882Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2948): 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2948): 2015-11-25T10:16:40.224Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2948): 
,I/SS      ( 2948): Found 3 peers.
I/SS      ( 2948): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2948): Peer(3): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 2948): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:16:40.450Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:40.483Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/jxcore-log( 2948): 2015-11-25T10:16:40.819Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:40.827Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:40.844Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2948): 
,I/BTConnectToThread( 2948): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : motorola-XT1072_PT5868
I/HS      ( 2948): Hand Shake finished outgoing for : motorola-XT1072_PT5868
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, motorola-XT1072_PT5868
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 60393
I/BtConnectorHelper( 2948): Request socket is using : 60393
I/BtToRequestSocket( 2948): Now accepting connections
,I/jxcore-log( 2948): 2015-11-25T10:16:41.070Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :60393
,I/jxcore-log( 2948): 2015-11-25T10:16:41.240Z SendDataConnector.js: CLIENT connected to 60393, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:41.243Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 60393
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:16:41.264Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:16:41.366Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,W/bt-btif ( 3010): invalid rfc slot id: 11
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT3108
I/BtToSocketBase( 2948): Stop ReceivingThread
,I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT3108
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,I/jxcore-log( 2948): 2015-11-25T10:16:41.573Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2948): 2015-11-25T10:16:41.996Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:42.260Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT1879
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, samsung-SM-N9005_PT1879
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/jxcore-log( 2948): 2015-11-25T10:16:42.667Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/        ( 2948): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 2948): 2015-11-25T10:16:43.979Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:43.988Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.075Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.176Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 2948): 2015-11-25T10:16:44.311Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.339Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.439Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.531Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.601Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.775Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.888Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:44.905Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.008Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:16:45.076Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.166Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.178Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 2948): 2015-11-25T10:16:45.413Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.424Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.515Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.605Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.685Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:45.936Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:46.002Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:46.092Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:46.280Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:46.293Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:46.373Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:46.454Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:46.827Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/jxcore-log( 2948): 2015-11-25T10:16:46.992Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2948): 2015-11-25T10:16:47.014Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.037Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 2948): 2015-11-25T10:16:47.307Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.342Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.374Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.453Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.609Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.620Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.830Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.913Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:47.926Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.033Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.039Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.108Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.142Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.181Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.192Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.311Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.342Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): invalid rfc slot id: 13
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT1879
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:16:48.836Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:48.930Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x49
,I/jxcore-log( 2948): 2015-11-25T10:16:50.928Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:52.607Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:52.608Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:52.610Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:16:52.615Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
,I/BtConnectorHelper( 2948): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
,I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
I/jxcore-log( 2948): 2015-11-25T10:16:52.645Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:52.647Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:52.648Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:16:52.649Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/        ( 2948): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 2948): Connecting to G4-1, at F8:95:C7:87:3C:51
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 20358 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 3 peers.
I/SS      ( 2948): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2948): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(3): Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2948): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 50:2E:6C:AC:21:50
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,E/BluetoothEventManager( 3017): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215b34 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215b34 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2948): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT4589
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, HTC-HTC One_M8_PT4589
,I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:17:06.416Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:17:06.854Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:06.863Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:06.903Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:06.943Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:06.952Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:06.962Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2948): 2015-11-25T10:17:07.154Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.162Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.208Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.237Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.282Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.312Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.392Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.402Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.432Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.452Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.460Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.509Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.553Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.597Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.608Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.679Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.684Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.705Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.744Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.745Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.754Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.807Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.839Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.874Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.884Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.894Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.901Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:07.978Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.014Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.021Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.029Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.068Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.093Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.114Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.121Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.127Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.158Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.192Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.220Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:17:08.225Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 14
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT4589
I/BtToSocketBase( 2948): Stop ReceivingThread,
I/BtToSocketBase( 2948): Stop SendingThread
,I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:17:08.331Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x46
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 4 peers.
I/SS      ( 2948): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2948): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(4): Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/        ( 2948): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
,I/        ( 2948): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2948): Peer(4): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 2948): Peer(5): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): wlan0: WPA: Group rekeying completed with c0:ff:d4:d3:aa:4a [GTK=CCMP]
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/BtConnection( 2948): connectionTimeoutTimer
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3010): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:15, channel:-1
,I/CONNEC  ( 2948): Error: Cancelled
I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:17:52.683Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:17:52.684Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:17:52.684Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
W/jxcore-log( 2948): $$jxcore_callback_14 wasn't registered
W/jxcore-log( 2948): 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0xeeee  CID 0x4b
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 15
,I/jxcore-log( 2948): 2015-11-25T10:17:57.685Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:17:57.686Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
,W/bt-l2cap( 3010): L2CAP - no CCB for conn rsp, LCID: 75 RCID: 69
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
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
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT9163","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT9163
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, samsung-SM-A500FU_PT9163
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/jxcore-log( 2948): 2015-11-25T10:17:59.663Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:18:00.125Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.226Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.238Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.344Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.566Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.579Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.614Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.622Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.650Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.660Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.697Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.723Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.737Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.746Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.769Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.804Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.809Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.818Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.949Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:00.962Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.048Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.057Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.126Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.164Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2948): 2015-11-25T10:18:01.262Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.340Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.461Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.532Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.564Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.624Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.632Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.642Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: G4-1
,I/jxcore-log( 2948): 2015-11-25T10:18:01.729Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.761Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.826Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.861Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.922Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:01.963Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 16
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT9163
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT9163
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/jxcore-log( 2948): 2015-11-25T10:18:02.073Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:02.693Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:02.694Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:02.694Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:02.695Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2948): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x4d
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
,I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTConnectToThread( 2948): got MESSAGE_READ 76 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : LGE-LG-H815_PT153
,I/HS      ( 2948): Hand Shake finished outgoing for : LGE-LG-H815_PT153
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, LGE-LG-H815_PT153
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 46024
I/BtConnectorHelper( 2948): Request socket is using : 46024
I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :46024
I/jxcore-log( 2948): 2015-11-25T10:18:13.694Z SendDataConnector.js: CLIENT connected to 46024, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:13.695Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 46024
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:18:13.729Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:14.241Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:14.476Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:14.872Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:15.037Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:15.406Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:15.934Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:16.360Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:17.235Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/jxcore-log( 2948): 2015-11-25T10:18:17.451Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:17.567Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:17.568Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:17.589Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:17.590Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
,I/BtConnectorHelper( 2948): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
,I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
,I/jxcore-log( 2948): 2015-11-25T10:18:17.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:17.630Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:17.630Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:17.630Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,I/        ( 2948): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 2948): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 84921 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215084 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
,I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421596c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2948): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : samsung-SM-N9005_PT1879
I/HS      ( 2948): Hand Shake finished outgoing for : samsung-SM-N9005_PT1879
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, samsung-SM-N9005_PT1879
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 55222
I/BtConnectorHelper( 2948): Request socket is using : 55222
I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :55222
,I/jxcore-log( 2948): 2015-11-25T10:18:20.884Z SendDataConnector.js: CLIENT connected to 55222, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:20.886Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 55222
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:18:20.911Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.187Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.310Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.355Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.526Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.578Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.666Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.728Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.792Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:21.907Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:18:22.002Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:22.003Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:22.020Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:22.021Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
I/BtConnectorHelper( 2948): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
,I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
I/jxcore-log( 2948): 2015-11-25T10:18:22.046Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:22.049Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:22.049Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:22.050Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 2948): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 4374 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: G4-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215ec4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
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
,I/BTConnectToThread( 2948): Starting to Handshake
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTConnectToThread( 2948): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : motorola-XT1039_PT6119
I/HS      ( 2948): Hand Shake finished outgoing for : motorola-XT1039_PT6119
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, motorola-XT1039_PT6119
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 50531
I/BtConnectorHelper( 2948): Request socket is using : 50531
,I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :50531
I/jxcore-log( 2948): 2015-11-25T10:18:25.218Z SendDataConnector.js: CLIENT connected to 50531, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:25.218Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.220Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 50531
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2948): 2015-11-25T10:18:25.371Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16787
,I/jxcore-log( 2948): 2015-11-25T10:18:25.418Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 2948): 2015-11-25T10:18:25.429Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.508Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 2948): 2015-11-25T10:18:25.545Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.586Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.720Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.767Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.770Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.819Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:25.819Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:25.822Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:25.822Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
I/BtConnectorHelper( 2948): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
,I/jxcore-log( 2948): 2015-11-25T10:18:25.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:25.827Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:25.827Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:25.828Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 3770 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: XT1039
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 21
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:18:30.962Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:30.962Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:30.962Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 4 peers.
I/SS      ( 2948): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 2948): 2015-11-25T10:18:35.963Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:35.963Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:40.967Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:40.968Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:40.969Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:40.969Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 5 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216254 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2491","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT2491
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, motorola-Nexus 6_PT2491
,I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
,I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/jxcore-log( 2948): 2015-11-25T10:18:48.695Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:18:49.072Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.080Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.245Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.405Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.432Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.453Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.532Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.562Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.579Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.593Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.622Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.716Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.756Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.807Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.840Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.847Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:49.928Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.034Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.041Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 2948): 2015-11-25T10:18:50.073Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.127Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.294Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.301Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.306Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.314Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.362Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.407Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.490Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:18:50.534Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.544Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216254 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2948): 2015-11-25T10:18:50.764Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.804Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.875Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:50.995Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.032Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.105Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.113Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.138Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.202Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.210Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.233Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:18:51.322Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 17
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT2491
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:18:51.436Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421608c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216254 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x45
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 22
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:18:51.930Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:51.931Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:51.931Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:18:56.933Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:18:56.933Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:01.936Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:01.937Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:01.939Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:01.940Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, f, 230f,
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 24
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:19:04.509Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:04.510Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:04.514Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:19:09.517Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:09.518Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:14.524Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:14.525Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:14.525Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:14.526Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 25
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:19:16.171Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:16.172Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:16.172Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:19:21.174Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:21.175Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:26.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:26.180Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:26.180Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:26.184Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 26
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:19:27.692Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:27.693Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:27.708Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:27.714Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:27.718Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:27.718Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:27.719Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 61866 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4d
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 27
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:19:29.227Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:29.234Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:29.234Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:19:34.235Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:34.236Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:39.241Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:39.241Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:39.242Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:39.243Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:28, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 28
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:19:41.133Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:41.134Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:41.135Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:19:46.136Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:46.137Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2948): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/jxcore-log( 2948): 2015-11-25T10:19:51.138Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:51.138Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:51.138Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:51.138Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 29
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:19:56.353Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:19:56.353Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:19:56.354Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42165e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2948): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 2948): 2015-11-25T10:20:01.371Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:01.372Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
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
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT4115
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, samsung-SM-G900F_PT4115
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/jxcore-log( 2948): 2015-11-25T10:20:02.288Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:20:02.749Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:02.761Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:02.804Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 2948): 2015-11-25T10:20:02.849Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:02.868Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.016Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.115Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.309Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.335Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.341Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.353Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.394Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.405Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.512Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.577Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2948): 
,I/        ( 2948): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT7376"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT7376, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT7376, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 2948): 2015-11-25T10:20:03.625Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.699Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.705Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.734Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.789Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.822Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.869Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.937Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:03.976Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.036Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.104Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.225Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.235Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.241Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.282Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.301Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.352Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.452Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.482Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.512Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.518Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.533Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.553Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.627Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.692Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.755Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.811Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.907Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.968Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:04.982Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:05.038Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:05.044Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 23
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT4115
,I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT4115
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/jxcore-log( 2948): 2015-11-25T10:20:05.276Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x44
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:20:06.375Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:06.376Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:06.376Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:06.377Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42165e4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421641c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 31
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:20:09.124Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:09.125Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:09.125Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: S5-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/jxcore-log( 2948): 2015-11-25T10:20:14.128Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:14.130Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2948): 2015-11-25T10:20:19.140Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:19.143Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:19.144Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:19.147Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 32
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:20:20.325Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:20.326Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:20.350Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:20.356Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:20.359Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:20.359Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:20.360Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 52609 ms, rnd: 5, ex: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421641c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 33
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:20:21.217Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:21.217Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:21.217Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/jxcore-log( 2948): 2015-11-25T10:20:26.219Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:26.220Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9507
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9507
,I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
,I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:20:29.539Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:20:29.907Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:29.910Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:29.921Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:29.930Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:29.937Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:29.977Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.012Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.034Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.047Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.084Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.088Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.124Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.164Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.173Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.213Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.220Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.231Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.264Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.270Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.276Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.286Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.324Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.335Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.394Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.418Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.424Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:30.461Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 30
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:20:30.512Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x48
,I/jxcore-log( 2948): 2015-11-25T10:20:31.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:31.225Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:31.226Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:31.226Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42167ac rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 35
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:20:34.100Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:34.100Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:34.100Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:20:39.103Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:39.108Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,W/bt-btm  ( 3010): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42167ac rs_disc_pending=2
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2948): 2015-11-25T10:20:44.110Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:44.112Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:44.113Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:44.114Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 36
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:20:45.518Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:45.518Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:45.519Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/jxcore-log( 2948): 2015-11-25T10:20:50.519Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:50.520Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/jxcore-log( 2948): 2015-11-25T10:20:55.528Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:55.528Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:55.529Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:55.530Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 37
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:20:55.748Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:20:55.748Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:20:55.748Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/jxcore-log( 2948): 2015-11-25T10:21:00.749Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:00.749Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:05.749Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:05.750Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:05.750Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:05.750Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 38
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:21:09.164Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:09.168Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:09.197Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:09.200Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:09.208Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:09.208Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:09.208Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 48810 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215cfc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 39
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:21:10.233Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:10.234Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:10.235Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215cfc rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:21:15.236Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:15.237Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2948): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2948): 2015-11-25T10:21:20.240Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:20.242Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:20.243Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:20.243Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 40
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:21:20.862Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:20.862Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:20.863Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 2948): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2948): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2948): 2015-11-25T10:21:25.865Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:25.865Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2491","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
,I/        ( 2948): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2491","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT2491, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT2491, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:21:30.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:30.875Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:30.875Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:30.876Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 41
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:21:31.522Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:31.523Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:31.523Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/        ( 2948): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:21:36.524Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:36.525Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:21:41.528Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:41.528Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:41.529Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:41.529Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 42
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:21:43.067Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:43.068Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:43.069Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:21:48.069Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:48.073Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:53.078Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:53.079Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:53.079Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:53.080Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 43
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:21:54.427Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:54.428Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:54.444Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:54.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:54.449Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:54.450Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:21:54.456Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 45220 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216974 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 44
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:21:59.775Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:59.776Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:21:59.777Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:22:04.779Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:04.779Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:22:09.784Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:09.785Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:09.786Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:09.786Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 45
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:22:14.991Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:14.991Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:14.991Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:22:19.993Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:19.994Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:22:24.997Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:24.998Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:24.999Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:24.999Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 46
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:22:30.188Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:30.189Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:30.189Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:22:35.190Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:35.193Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:22:40.196Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:40.197Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:40.197Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:40.198Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(7): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 47
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:22:45.372Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:45.372Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:45.373Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2948): 2015-11-25T10:22:50.374Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:50.374Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:22:55.377Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:55.378Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:55.379Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:22:55.379Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 48
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:23:00.560Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:00.560Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:00.562Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:00.563Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:00.564Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:00.564Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:00.564Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/        ( 2948): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 66110 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:9d:93:0b]: 6, f, 6109
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test's G2
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3010): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3010): Entering PendingCommandState State
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3017): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3010): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3010): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3010): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,W/BluetoothEventManager( 3017): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3010): StableState(): Entering Off State
,E/BluetoothEventManager( 3017): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTConnectToThread( 2948): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : LGE-LG-D802_PT5232
I/HS      ( 2948): Hand Shake finished outgoing for : LGE-LG-D802_PT5232
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, LGE-LG-D802_PT5232
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 57070
I/BtConnectorHelper( 2948): Request socket is using : 57070
I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :57070
,I/jxcore-log( 2948): 2015-11-25T10:23:04.875Z SendDataConnector.js: CLIENT connected to 57070, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:04.876Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 57070
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:23:04.896Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:05.135Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:05.314Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:05.366Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:05.402Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:05.506Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:05.632Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:05.855Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:06.081Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:06.350Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:06.448Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:06.449Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:06.475Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:06.476Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
I/BtConnectorHelper( 2948): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
,I/jxcore-log( 2948): 2015-11-25T10:23:06.500Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:06.508Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:06.508Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:06.509Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 5891 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421524c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 6109
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 50
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:23:07.865Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:07.866Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:07.866Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: XT1039
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215ec4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215ec4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2948): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : motorola-XT1039_PT6119
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, motorola-XT1039_PT6119
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:23:10.842Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:23:11.252Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.260Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.271Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.277Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.288Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.329Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.340Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.350Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.387Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.396Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.434Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.458Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.465Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.502Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.531Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.565Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.573Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.594Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.634Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.664Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.695Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.705Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.753Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:11.762Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 3010): invalid rfc slot id: 34
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6119
,I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT6119
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/jxcore-log( 2948): 2015-11-25T10:23:12.206Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x4d
,I/jxcore-log( 2948): 2015-11-25T10:23:12.867Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:12.867Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215ec4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: XT1039
,I/jxcore-log( 2948): 2015-11-25T10:23:17.870Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:17.871Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:17.871Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:17.872Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 4106
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 52
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:23:18.756Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:18.756Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:18.756Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2948): 2015-11-25T10:23:23.757Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:23.758Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:28.759Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:28.759Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:28.759Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:28.759Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 53
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:23:29.176Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:29.177Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:29.177Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2948): 2015-11-25T10:23:34.178Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:34.179Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:39.180Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:39.180Z SendDataConnector.js: Connect (retry count 3) to peer F8:CF:C5:D9:E5:61 with availability status: true
,I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:39.180Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:39.180Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2948): Starting to connect
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 54
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:23:39.676Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:39.676Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:39.676Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/jxcore-log( 2948): 2015-11-25T10:23:44.678Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:44.678Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2948): 2015-11-25T10:23:49.683Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:49.684Z SendDataConnector.js: Connect (retry count 4) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:49.685Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:49.685Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 55
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:23:50.800Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:50.801Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:23:50.814Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:50.817Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : F8:CF:C5:D9:E5:61, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:50.818Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:50.818Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:50.818Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 2948): Connecting to null, at 58:2A:F7:ED:96:BE
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 44294 ms, rnd: 5, ex: Connection to F8:CF:C5:D9:E5:61 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3010): invalid rfc slot id: 56
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:23:55.965Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:55.966Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:23:55.967Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:00.967Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:00.968Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:05.973Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:05.974Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:05.975Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:05.975Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 2948): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
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
,I/BTConnectToThread( 2948): Starting to Handshake
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTConnectToThread( 2948): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT8047","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : HUAWEI-ALE-L21_PT8047
,I/HS      ( 2948): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT8047
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT8047
,I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 52967
I/BtConnectorHelper( 2948): Request socket is using : 52967
I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :52967
I/jxcore-log( 2948): 2015-11-25T10:24:21.686Z SendDataConnector.js: CLIENT connected to 52967, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:21.687Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 52967
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:24:21.706Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2948): 2015-11-25T10:24:22.038Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:22.220Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 2948): 2015-11-25T10:24:22.408Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:22.620Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 2948): 2015-11-25T10:24:22.775Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:22.909Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:23.086Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:24:23.329Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:23.585Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:23.820Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:23.823Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:23.843Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:23.844Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
I/BtConnectorHelper( 2948): Disconnect outgoing peer: 58:2A:F7:ED:96:BE
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
,I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
I/jxcore-log( 2948): 2015-11-25T10:24:23.870Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:23.880Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:23.886Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:23.886Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2948): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 33005 ms, rnd: 2, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216d04 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: ALE-L21
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 58
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:24:29.442Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:29.442Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:29.443Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:34.445Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:34.446Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:39.449Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:39.450Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:24:39.455Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:39.458Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2948): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 59
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:24:44.634Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:44.634Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:44.634Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 5 peers.
,I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/        ( 2948): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/EventLogService( 1557): Aggregate from 1448444908860 (log), 1448444908860 (data)
,D/GetConfigurationSnapshotOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1414): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1414): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1414):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2948): 2015-11-25T10:24:49.643Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:49.644Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1414): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2948): 2015-11-25T10:24:54.654Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:54.654Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:54.655Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:54.655Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2948): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 60
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:24:59.828Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:59.829Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:24:59.829Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/        ( 2948): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2948): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2948): 2015-11-25T10:25:04.830Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:04.830Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:09.836Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:09.837Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:09.837Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:09.838Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/        ( 2948): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [80:01:84:8a:b3:68]: 6, 10f, 608
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,I/        ( 2948): Cleared service requests
,I/        ( 2948): Started peer discovery
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTConnectToThread( 2948): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : HTC-HTC Desire 820_PT9507
I/HS      ( 2948): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9507
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9507
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 33141
I/BtConnectorHelper( 2948): Request socket is using : 33141
I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :33141
I/jxcore-log( 2948): 2015-11-25T10:25:11.598Z SendDataConnector.js: CLIENT connected to 33141, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:11.598Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 33141
I/BtToRequestSocket( 2948): Set local streams
,I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:25:11.644Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:11.799Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:11.846Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.014Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.196Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.255Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.267Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.312Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.359Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.398Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:12.398Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:12.417Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:12.418Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
I/BtConnectorHelper( 2948): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
,I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
I/jxcore-log( 2948): 2015-11-25T10:25:12.446Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:12.448Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:12.448Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:12.449Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,I/        ( 2948): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2948): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 48513 ms, rnd: 4, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42167ac rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:76:27]: 7, f, 230f
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3010): invalid rfc slot id: 62
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:25:12.941Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:12.941Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:12.942Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC Desire 820
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:25:17.943Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:17.943Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: XT1072
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : motorola-XT1072_PT5868
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, motorola-XT1072_PT5868
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
,I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:25:18.829Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:25:19.238Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.245Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.270Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.304Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.424Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.451Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.499Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.534Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.547Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.585Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.597Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.634Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.657Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.805Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.845Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.880Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.918Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.925Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.939Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:19.987Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.016Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.064Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.093Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.121Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.154Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.164Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.204Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.219Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.232Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:20.262Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 51
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5868
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:25:20.353Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:25:22.946Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:22.947Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:22.947Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:22.948Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2948): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42157a4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3),
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 64
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:25:25.814Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:25.814Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:25.814Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: XT1072
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2948): 2015-11-25T10:25:30.814Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:30.814Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:35.817Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:35.818Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:35.819Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:35.819Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2948): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 65
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:25:37.150Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:37.151Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:37.152Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2948): 2015-11-25T10:25:42.153Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:42.153Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:47.156Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:47.157Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:47.157Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:47.158Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2948): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 66
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:25:47.384Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:47.385Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:47.385Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2948): 2015-11-25T10:25:52.385Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:52.385Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 2948): 2015-11-25T10:25:57.385Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:57.385Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:57.385Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:57.385Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 2948): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 67
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:25:58.959Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:58.960Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:25:58.970Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:58.970Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:58.970Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:58.971Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:58.971Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2948): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 46512 ms, rnd: 5, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 68
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:25:59.663Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:59.663Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:25:59.663Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2948): 2015-11-25T10:26:04.665Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:04.666Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:26:09.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:09.671Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:09.672Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:09.672Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2948): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 69
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:26:10.681Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:10.682Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:10.682Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 5 peers.
I/SS      ( 2948): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/        ( 2948): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 2948): 2015-11-25T10:26:15.683Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:15.683Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
,I/        ( 2948): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 2948): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2948): 2015-11-25T10:26:20.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:20.688Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:20.688Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:20.689Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2948): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 70
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:26:21.078Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:21.078Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:21.078Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:26:26.080Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:26:26.080Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Cleared service requests
,I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2948): 2015-11-25T10:26:31.086Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:31.087Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:31.088Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:31.088Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2948): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 71
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:26:31.345Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:31.346Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:31.346Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/art     (  736): Explicit concurrent mark sweep GC freed 52813(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 2.407ms total 99.212ms
,I/        ( 2948): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2948): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/        ( 2948): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,I/jxcore-log( 2948): 2015-11-25T10:26:36.346Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:36.346Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
,I/        ( 2948): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:26:41.347Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:41.347Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:41.347Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:41.347Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2948): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2948): Starting to connect
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 72
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:26:42.185Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:42.186Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:26:42.196Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:42.196Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:42.197Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:42.197Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:42.197Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2948): Connecting to null, at F8:95:C7:87:85:54
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 43215 ms, rnd: 5, ex: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 73
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:26:42.594Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:42.595Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:42.595Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/        ( 2948): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:26:47.596Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:47.597Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:26:52.599Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:52.599Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:52.599Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:52.599Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2948): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 7, f, 2205
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 74
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:26:53.559Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:53.560Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:26:53.560Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Cleared service requests
,I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 7 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2948): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/        ( 2948): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2948): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2948): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT4115, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT4115, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2948): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 2948): 2015-11-25T10:26:58.566Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:26:58.567Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
,I/        ( 2948): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2948): 2015-11-25T10:27:03.570Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:03.572Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:03.573Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:03.573Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2948): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 75
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:27:04.372Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:04.372Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:04.373Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Cleared service requests
,I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/jxcore-log( 2948): 2015-11-25T10:27:09.375Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:09.375Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2948): 2015-11-25T10:27:14.379Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:14.380Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:14.380Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:14.384Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2948): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 76
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:27:15.320Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:15.323Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:15.323Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:27:20.324Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:20.325Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:25.328Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:25.329Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:25.329Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:25.330Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 2948): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 77
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:27:26.720Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:26.723Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:26.740Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:26.743Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:26.745Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:26.746Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:26.746Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/        ( 2948): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 44529 ms, rnd: 5, ex: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:34:8a:a0]: 6, f, 410d
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42165e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
,I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42165e4 rs_disc_pending=1
,W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2948): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT4115","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : samsung-SM-G900F_PT4115
I/HS      ( 2948): Hand Shake finished outgoing for : samsung-SM-G900F_PT4115
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, samsung-SM-G900F_PT4115
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 46561
I/BtConnectorHelper( 2948): Request socket is using : 46561
,I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :46561
,I/jxcore-log( 2948): 2015-11-25T10:27:29.530Z SendDataConnector.js: CLIENT connected to 46561, error: null
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.533Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 46561
I/BtToRequestSocket( 2948): Set local streams
,I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:27:29.560Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.721Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.755Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.805Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.811Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.855Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.870Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.919Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.936Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:29.987Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:30.023Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:30.023Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:30.040Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:30.041Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
I/BtConnectorHelper( 2948): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
I/jxcore-log( 2948): 2015-11-25T10:27:30.068Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:30.076Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:30.077Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:30.077Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 2948): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 3278 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42165e4 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [50:2e:6c:ac:21:50]: 6, f, 410d
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa42165e4 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4215b34 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2948): Starting to Handshake
,I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2948): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTConnectToThread( 2948): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2948): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2948): HandshakeOk : HTC-HTC One_M8_PT4589
I/HS      ( 2948): Hand Shake finished outgoing for : HTC-HTC One_M8_PT4589
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4589
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2948): mHTTPPort  set to : 46434
I/BtConnectorHelper( 2948): Request socket is using : 46434
,I/BtToRequestSocket( 2948): Now accepting connections
,I/BtConnectorHelper( 2948): Calling ConnectionStatusUpdate with port :46434
I/jxcore-log( 2948): 2015-11-25T10:27:32.169Z SendDataConnector.js: CLIENT connected to 46434, error: null
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:32.170Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): incoming data from: /127.0.0.1, port: 46434
I/BtToRequestSocket( 2948): Set local streams
I/BtToRequestSocket( 2948): rin ended ---------------------------;
,I/jxcore-log( 2948): 2015-11-25T10:27:32.194Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 2948): 2015-11-25T10:27:32.478Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 2948): 2015-11-25T10:27:32.526Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:32.716Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2948): 
,D/        ( 3010): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7877
,I/jxcore-log( 2948): 2015-11-25T10:27:32.881Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:32.922Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:32.960Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:33.047Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:33.098Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:33.237Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:33.306Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:33.307Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:33.328Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:33.329Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2948): 
,I/BtConnectorHelper( 2948): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 2948): Stop ReceivingThread
,I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
I/BtToRequestSocket( 2948): Close server socket
,I/jxcore-log( 2948): 2015-11-25T10:27:33.357Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:33.359Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:33.359Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:33.360Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 3230 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: S5-1
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, f, 610c
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 80
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:27:35.561Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:35.562Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:35.562Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: HTC One_M8
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:27:40.564Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:40.565Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:45.569Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:45.570Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:45.570Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:45.574Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 81
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:27:46.747Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:46.748Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:46.748Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:27:51.749Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:51.750Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/jxcore-log( 2948): 2015-11-25T10:27:56.751Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:56.751Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:56.751Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:27:56.751Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 82
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:27:58.280Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:58.280Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:27:58.284Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:28:03.287Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:03.288Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:08.291Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:08.292Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:08.292Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:08.293Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 83
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:28:11.070Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:11.073Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:11.076Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2948): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:28:16.077Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:16.078Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:21.083Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:21.084Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:21.084Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:21.085Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2948): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 84
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:28:22.601Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:22.601Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:22.618Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:22.624Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:22.626Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:22.627Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:22.627Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 49243 ms, rnd: 5, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421641c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 85
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:28:24.437Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:24.437Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:24.438Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:28:29.439Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:29.439Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:34.445Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:34.445Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:34.446Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:34.446Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  736): User[0] Flushing usage stats to disk
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 86
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:28:37.230Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:37.235Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:37.238Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:28:42.242Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:42.243Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:47.247Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:47.247Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:47.248Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:47.248Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 87
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:28:48.804Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:48.804Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:48.805Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:28:53.807Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:53.807Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:28:58.812Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:58.813Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:58.813Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:28:58.814Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 88
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:29:00.276Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:00.277Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:00.277Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:29:05.279Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:05.279Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:29:10.283Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:10.283Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:10.284Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:10.284Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2948): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 89
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:29:11.876Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:11.876Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:29:11.892Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:11.895Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:11.897Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:11.898Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:11.898Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 49250 ms, rnd: 5, ex: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa421641c rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 90
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:29:12.396Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:12.396Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:12.396Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/jxcore-log( 2948): 2015-11-25T10:29:17.396Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:29:17.397Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:29:22.400Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:22.402Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:22.403Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:22.403Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 91
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:29:22.604Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:22.604Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:22.604Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/jxcore-log( 2948): 2015-11-25T10:29:27.604Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:27.604Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:29:32.605Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:32.605Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:32.605Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:32.605Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 92
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:29:32.864Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:32.865Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:32.865Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/GoogleURLConnFactory( 1557): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AbstractGoogleClient( 2010): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 2010): PlayLogger.onLoggerConnected
,I/CalendarSyncAdapter( 2010): Found no pending settings
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  736): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3861 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1302): Using Auth Proxy for data requests.
,D/ActivityThread( 3861): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 3861): getAccountsCursor
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  736): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=3897 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  736): Explicit concurrent mark sweep GC freed 40553(2034KB) AllocSpace objects, 24(384KB) LOS objects, 33% free, 27MB/41MB, paused 799us total 52.875ms
,W/GAV2    ( 3861): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  736): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 3861): Observing account changes for notifications,
,I/Exchange( 3897): EasService.onCreate
,I/Exchange( 3897): RestartPingTask
,W/Gmail   ( 3861): Sync started for account: account:61035162
,I/Gmail   ( 3861): getAccountsCursor
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3861): (283) recovered 41 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Exchange( 3897): RestartPingsTask did not start any pings.
I/Exchange( 3897): PSS stopIfIdle
I/Exchange( 3897): PSS has no active accounts; stopping service.
,I/Exchange( 3897): onDestroy
,I/Gmail   ( 3861): notifyAccountChanged
,I/Gmail   ( 3861): getAccountsCursor
,I/Gmail   ( 3861): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3861): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3861): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3861): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3861): notifyAccountChanged
,I/Gmail   ( 3861): getAccountsCursor
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3861): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11152, normalSync: true
,I/art     ( 1414): Explicit concurrent mark sweep GC freed 57545(3MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 20MB/34MB, paused 852us total 116.381ms
,I/GCoreUlr( 1302): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
I/GCoreUlr( 1302): DispatchingService.onCreate()
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,I/ActivityManager(  736): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=3944 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/art     ( 1302): Explicit concurrent mark sweep GC freed 31154(1796KB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 19MB/32MB, paused 810us total 51.140ms
,E/DataBuffer( 1302): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7c088b3)
,I/GCoreUlr( 1302): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1302): Unbound from all location providers
,W/ResourcesManager( 3861): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3861): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GCoreUlr( 1302): DispatchingService.onDestroy()
I/GCoreUlr( 1302): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1302): Unbound from all location providers
,I/ContactLocale( 3944): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,V/JNIHelp ( 3861): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 3861): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3861): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  736): mEvictionCount: 0
,E/SQLiteLog( 3944): (284) automatic index on sqlite_sq_A3928C40(STAT_DATA_ID)
,E/SQLiteLog( 3944): (284) automatic index on sqlite_sq_A39281F0(STAT_DATA_ID)
,E/SQLiteLog( 3944): (284) automatic index on sqlite_sq_A3B2ECE0(STAT_DATA_ID)
,E/SQLiteLog( 3944): (284) automatic index on sqlite_sq_A3B2E290(STAT_DATA_ID)
,I/ActivityManager(  736): Killing 1482:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10013/pid_1482/cgroup.procs: No such file or directory
,I/art     (  736): Explicit concurrent mark sweep GC freed 13931(597KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 962us total 49.609ms
,I/jxcore-log( 2948): 2015-11-25T10:29:37.866Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:37.866Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/GHttpClientFactory( 2470): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2470): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2470): Sync started
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicSyncAdapter( 2470): Skipping periodic sync. Last sync was 86399 seconds ago. Frequency: 86400
,W/MusicApiClient( 2470): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 2470): Sync ended
,I/MusicLeanback( 2470): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2470): Stop autocaching.
,I/SyncAdapterService( 3272): Ignoring sync request for non-current account
,I/art     ( 3861): Explicit concurrent mark sweep GC freed 149088(5MB) AllocSpace objects, 15(263KB) LOS objects, 24% free, 18MB/25MB, paused 411us total 78.152ms
,D/WearableService( 1302): callingUid 10008, callindPid: 1302
,E/GmsUtils( 2470): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Gmail   ( 3861): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11231, normalSync: true
,I/Gmail   ( 3861): lowestBackward conversation id 0
,E/GmsUtils( 2470): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DelayedSyncController(  946): Delaying sync.
,I/Gmail   ( 3861): notifyAccountChanged
,I/Gmail   ( 3861): getAccountsCursor
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3861): notifyAccountChanged
,W/Gmail   ( 3861): Sync complete for account: account:61035162
,I/Gmail   ( 3861): getAccountsCursor
,V/GLSActivity( 1414): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  736): Killing 2837:com.android.musicfx/u0a15 (adj 15): empty #17
,I/art     ( 1414): Explicit concurrent mark sweep GC freed 38291(1906KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 20MB/33MB, paused 1.236ms total 44.901ms
,W/libprocessgroup(  736): failed to open /acct/uid_10015/pid_2837/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4037 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/BaseAppContext( 1557): Using Auth Proxy for data requests.
,W/BaseAppContext( 1557): Using Auth Proxy for data requests.
,W/BaseAppContext( 1557): Using Auth Proxy for data requests.
,W/BaseAppContext( 1557): Using Auth Proxy for data requests.
,W/BaseAppContext( 1557): Using Auth Proxy for data requests.
,W/BaseAppContext( 1557): Using Auth Proxy for data requests.
,W/ResourcesManager( 4037): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/BaseAppContext( 1557): Using Auth Proxy for data requests.
,I/ActivityManager(  736): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4056 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  736): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=4092 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,D/PlayMovies( 4037): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 4037): TransferService.onCreate:52 creating transfer service
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4056): Sync request not initiated by GCP app. Dropping
,W/VideoCapabilities( 4037): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  736): Killing 2718:com.android.defcontainer/u0a5 (adj 15): empty #17
,I/VideoCapabilities( 4037): Unsupported profile 4 for video/mp4v-es
,W/libprocessgroup(  736): failed to open /acct/uid_10005/pid_2718/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Killing 3370:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10076/pid_3370/cgroup.procs: No such file or directory
,W/ResourcesManager( 1557): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/art     ( 1557): Explicit concurrent mark sweep GC freed 18202(1305KB) AllocSpace objects, 24(407KB) LOS objects, 40% free, 22MB/37MB, paused 941us total 46.110ms
,E/Auth.Api.Credentials( 1557): [CredentialSyncAdapter] Unknown sync event.
,I/Icing   ( 1557): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/art     (  736): Explicit concurrent mark sweep GC freed 25499(1069KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.183ms total 75.270ms
,I/PlayMovies( 4037): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/Gmail   ( 3861): Backfilling search sequence table
I/CalendarSyncAdapter( 2010): Found no pending settings
,I/Icing   ( 1557): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,I/PlayMovies( 4037): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 4037): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  736): Killing 1791:com.google.android.talk/u0a54 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10054/pid_1791/cgroup.procs: No such file or directory
,I/GAV2    ( 3861): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  736): Killing 2864:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10040/pid_2864/cgroup.procs: No such file or directory
,I/jxcore-log( 2948): 2015-11-25T10:29:42.867Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:42.867Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:42.867Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:42.867Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 93
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:29:43.106Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:43.106Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:29:43.107Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/jxcore-log( 2948): 2015-11-25T10:29:48.108Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:48.108Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
,I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
,W/Launcher( 1320): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1a2603ea new=com.google.android.velvet.VelvetApplication@1a2603ea
,I/UpdateIcingCorporaServi( 1367): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/PackageBroadcastService( 1557): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/PeopleContactsSync( 1557): CP2 sync disabled
,I/UpdateIcingCorporaServi( 1367): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
,I/Launcher( 1320): Deferring update until onResume
,W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1320): Deferring update until onResume
,I/jxcore-log( 2948): 2015-11-25T10:29:53.109Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.109Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.109Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.109Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2948): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2948): Starting to connect
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 94
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:29:53.339Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.339Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:29:53.347Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.348Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.348Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.348Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.348Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 41442 ms, rnd: 5, ex: Connection to 7C:F9:0E:37:96:AB failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 95
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:29:53.966Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.966Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:53.967Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: A5-1
,I/jxcore-log( 2948): 2015-11-25T10:29:58.968Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:29:58.969Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:30:03.973Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:03.974Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:03.974Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:03.975Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 96
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:30:04.393Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:04.394Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:04.394Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:30:09.395Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:09.396Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:14.400Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:14.400Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:14.404Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:14.404Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 97
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:30:15.512Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:15.512Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:15.513Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:30:20.514Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:20.515Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 4 peers.
I/SS      ( 2948): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/jxcore-log( 2948): 2015-11-25T10:30:25.518Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:25.525Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:25.525Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:25.525Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 98
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:30:27.027Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:27.028Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:27.028Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:30:32.030Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:32.035Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:37.038Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:37.039Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:37.039Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:37.040Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2948): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:2a:f7:ed:96:be]: 6, f, 6109
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: ALE-L21
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216974 rs_disc_pending=0
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 99
I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:30:38.412Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:38.412Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:38.414Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:38.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:38.416Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:38.416Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:38.416Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 45065 ms, rnd: 5, ex: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216974 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
,I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT8047","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT8047
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT8047
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:30:41.431Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3010): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2948): 2015-11-25T10:30:42.346Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:42.483Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:42.618Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:42.685Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:42.820Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:43.025Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:43.156Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:43.293Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:43.494Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:43.630Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 100
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:30:43.746Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:43.747Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:43.747Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:43.769Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:48.748Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:48.749Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): dm_pm_timer expires
W/bt-btif ( 3010): dm_pm_timer expires 0
,W/bt-btif ( 3010): proc dm_pm_timer expires
,I/jxcore-log( 2948): 2015-11-25T10:30:50.763Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:52.828Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:53.753Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:53.754Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:53.754Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:53.755Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2948): 2015-11-25T10:30:53.868Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:53.938Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:54.240Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:55.233Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 2948): 2015-11-25T10:30:57.723Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:58.220Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2948): 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 102
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:30:58.931Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:58.931Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:30:58.932Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:30:58.955Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:03.933Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:03.933Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): dm_pm_timer expires
W/bt-btif ( 3010): dm_pm_timer expires 0
W/bt-btif ( 3010): proc dm_pm_timer expires
,I/jxcore-log( 2948): 2015-11-25T10:31:08.941Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:08.942Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:08.943Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:08.943Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2948): 2015-11-25T10:31:09.118Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:09.196Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:09.200Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:10.694Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:12.186Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2948): 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 103
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:31:14.129Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:14.130Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:14.130Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): dm_pm_timer expires
W/bt-btif ( 3010): dm_pm_timer expires 0
W/bt-btif ( 3010): proc dm_pm_timer expires
E/bt-btif ( 3010): bta_dm_pm_sniff BTM_SetPowerMode() returns ERROR status=3
,I/jxcore-log( 2948): 2015-11-25T10:31:19.138Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:19.138Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:24.144Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:24.144Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:24.145Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:24.145Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:31:27.156Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 104
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:31:29.330Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:29.333Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:29.336Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): invalid rfc slot id: 63
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT8047
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT8047
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/jxcore-log( 2948): 2015-11-25T10:31:29.400Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x41
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 3 peers.
I/SS      ( 2948): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTListenerThread( 2948): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT8047","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT8047
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT8047
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/jxcore-log( 2948): 2015-11-25T10:31:31.170Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:31:33.127Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.188Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.246Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.274Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.485Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.623Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.649Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.682Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.785Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:33.816Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:34.341Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:34.341Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:39.026Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:31:39.095Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2948): 2015-11-25T10:31:39.345Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:39.345Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:39.346Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:39.346Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2948): Connecting to null, at 00:F4:6F:30:E0:6C
,I/        ( 2948): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2948): 2015-11-25T10:31:39.423Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:39.427Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:31:39.929Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3010): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 106
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:31:44.559Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:44.560Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:44.578Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:44.588Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- round done--------
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 2
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): do fake peer & start
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:44.598Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:44.602Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:31:44.602Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback round[0] time: 66144 ms, rnd: 5, ex: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 6109
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:107, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 107
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:31:44.853Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:44.854Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:44.854Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT8047
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-btif ( 3010): invalid rfc slot id: 101
,D/BluetoothMapService( 3010): onReceive
,I/jxcore-log( 2948): 2015-11-25T10:31:44.929Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2948): 2015-11-25T10:31:49.855Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:49.856Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 2948): 2015-11-25T10:31:54.873Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:54.874Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:54.875Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:54.875Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:108, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 108
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2948): 2015-11-25T10:31:55.611Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:55.612Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:31:55.612Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2948): 2015-11-25T10:32:00.614Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:00.614Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [58:2a:f7:ed:96:be]: 7, f, 230f
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3010): new conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3010): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2948): we got incoming connection
I/BTHandshakeSocketThread( 2948): Creating BTHandshakeSocketThread
I/BTListenerThread( 2948): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread started
,I/BTListenerThread( 2948): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2948): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT8047","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2948): MESSAGE_WRITE 77 bytes.
I/HS      ( 2948): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT8047
I/BTHandshakeSocketThread( 2948): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2948): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT8047
I/BtToSocketBase( 2948): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2948): Creating BTConnectedThread
I/BtConnectorHelper( 2948): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2948): --DoOneRunRound started
,I/BtToRequestSocket( 2948): LocalHost address: localhost/127.0.0.1, port: 42450
,I/jxcore-log( 2948): 2015-11-25T10:32:02.677Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2948): 
,I/BtToRequestSocket( 2948): --DoOneRunRound ended
,I/jxcore-log( 2948): 2015-11-25T10:32:03.054Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.080Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.159Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.185Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.211Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.264Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.318Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.371Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.397Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.528Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.586Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.633Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.686Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.712Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.743Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2948): 
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.845Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:03.974Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.027Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.079Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.133Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.158Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.184Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2948): 
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2948): 2015-11-25T10:32:04.223Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.264Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2948): 2015-11-25T10:32:04.302Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2948): 
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/jxcore-log( 2948): 2015-11-25T10:32:04.346Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.394Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.447Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.552Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.578Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:32:04.602Z SendDataTCPServer.js: TCP/IP server has received 60002 bytes of data
I/jxcore-log( 2948): 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 3010): invalid rfc slot id: 105
,I/BtToSocketBase( 2948): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2948): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT8047
I/BtToSocketBase( 2948): Stop ReceivingThread
I/BtToSocketBase( 2948): Stop SendingThread
I/BtToSocketBase( 2948): Close local in
I/BtToSocketBase( 2948): Close LocalOutputStream
I/BtToSocketBase( 2948): Close localHostSocket
I/BtToSocketBase( 2948): Close bt in
I/BtToSocketBase( 2948): Close bt out
I/BtToSocketBase( 2948): Close bt socket
,I/BtToSocketBase( 2948): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2948): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2948): 2015-11-25T10:32:04.727Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 2948): 
,W/bt-rfcomm( 3010): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3010): RFCOMM_DisconnectInd LCID:0x40
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): 2015-11-25T10:32:05.617Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:05.618Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:05.618Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:05.619Z SendDataConnector.js: do connect now
I/jxcore-log( 2948): 
,I/        ( 2948): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2948): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2948): Starting to connect
W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3010): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3010): tBTM_SEC_DEV:0xa4216d04 rs_disc_pending=1
W/bt-btif ( 3010): bta_dm_check_av:0
,W/bt-btif ( 3010): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3010): info:x10
,D/        ( 3010): remote version info [f8:cf:c5:d9:e5:61]: 6, 10f, 608
,W/bt-sdp  ( 3010): process_service_search_attr_rsp
,E/bt-btif ( 3010): DISCOVERY_COMP_EVT slot id:110, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3010): invalid rfc slot id: 110
,I/BTConnectToThread( 2948): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2948): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2948): 2015-11-25T10:32:07.412Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:07.413Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:CF:C5:D9:E5:61 failed
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:07.413Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2948): 
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: ALE-L21
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3010): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3010): onReceive
,I/BTConnectionReceiver( 1367): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1367): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2948): timeout now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): dun
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): weAreDoneNow , resultArray.length: 10
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): done, now sending data to server
I/jxcore-log( 2948): 
I/jxcore-log( 2948): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): -- RESULT DATA {"name:":"LGE-Nexus 5_PT3699","time":1000150,"result":"TIMEOUT","sendList":[{"name":"B4:CE:F6:AB:A4:6A","time":59963,"result":"OK","connections":3,"tryCount":1},{"name":"44:80:EB:7B:5A:05","time":20358,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":84921,"result":"OK","connections":2,"tryCount":1},{"name":"E0:DB:10:1F:C9:5E","time":4374,"result":"OK","connections":1,"tryCount":1},{"name":"F4:F1:E1:5C:3B:E2","time":3770,"result":"OK","connections":1,"tryCount":1},{"name":"34:FC:EF:9D:93:0B","time":5891,"result":"OK","connections":1,"tryCount":1},{"name":"58:2A:F7:ED:96:BE","time":33005,"result":"OK","connections":2,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":48513,"result":"OK","connections":4,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":3278,"result":"OK","connections":1,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":3230,"result":"OK","connections":1,"tryCount":1},{"connections":2,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":1,
I/jxcore-log( 2948): sendList : 100% : 84921 ms, 99% : 84921 ms, 95 : 84921 ms, 90% : 59963 ms.
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Result count 10, range 3230 ms to  84921 ms.
I/jxcore-log( 2948): 
I/jxcore-log( 2948): sendList failed peers count : 9 [47.36842105263158 %]
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : F8:CF:C5:D9:E5:61, Tried : 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : F8:95:C7:87:85:54, Tried : 1
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : 08:EC:A9:50:75:41, Tried : 2
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): - Peer ID : 58:3F:54:73:64:C0, Tried : 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : 34:FC:EF:11:B1:66, Tried : 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 2
I/jxcore-log( 2948): 
I/jxcore-log( 2948): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:12.292Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:12.292Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 2948): 
I/jxcore-log( 2948): 2015-11-25T10:32:12.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2948): 
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 6 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(4): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2948): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1879","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1879, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1879, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2948): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5868","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5868, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5868, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2948): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT4589","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT4589, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT4589, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 2948): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2948): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 9 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9507"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9507, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9507, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2948): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 9 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT5232"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT5232, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT5232, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 9 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 7 peers.
I/SS      ( 2948): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2948): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2948): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2948): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT153","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT153, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT153, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2948): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"}, typeCordovap2p._tcp.local.:
I/        ( 2948): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT6119"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT6119, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2948): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT6119, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 9 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2948): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2948): Started service discovery
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-smp  ( 3010): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3010): Plain text(LSB ~ MSB) = 94 ce 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3010): Encrypted text(LSB ~ MSB) = c0 6c cd 5f 73 06 53 92 97 a8 67 2b 28 0d a0 4c 
,W/bt-btm  ( 3010): Stopping oneshot timer
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/        ( 2948): Cleared service requests
I/        ( 2948): Started peer discovery
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2948): Found 8 peers.
I/SS      ( 2948): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2948): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2948): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2948): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2948): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2948): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2948): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2948): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2948): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2948): Added service request
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2948): DBG, CoordinatorConnector command called
I/jxcore-log( 2948): 
I/jxcore-log( 2948): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): stop tests now !
I/jxcore-log( 2948): 
I/jxcore-log( 2948): stop current!
I/jxcore-log( 2948): 
I/jxcore-log( 2948): testSendData stopped
I/jxcore-log( 2948): 
I/        ( 2948): Stoping All
I/        ( 2948): Stopping services
I/        ( 2948): Stopping services
,I/wpa_supplicant( 3016): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/        ( 2948): Stop Bluetooth
I/        ( 2948): Stop Bluetooth
I/BTListenerThread( 2948): Stopped
,I/jxcore-log( 2948): StopBroadcasting went ok
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): 2015-11-25T10:36:32.204Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2948): 
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 2948): Cleared local services
I/        ( 2948): Cleared service requests
I/        ( 2948): Stopped peer discovery
,I/jxcore-log( 2948): DBG, CoordinatorConnector command called
I/jxcore-log( 2948): 
I/jxcore-log( 2948): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"50:2E:6C:AC:21:50\",\"time\":3230,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":3278,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":3770,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":4374,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":5891,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":20358,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"58:2A:F7:ED:96:BE\",\"time\":33005,\"result\":\"OK\",\"connections\":2,\"tryCount\":1},{\"name\":\"80:01:84:8A:B3:68\",\"time\":48513,\"result\":\"OK\",\"connections\":4,\"tryCount\":1},{\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":59963,\"result\":\"OK\",\"connections\":3,\"tryCount\":1},{\"name\":\"F8:95:C7:87:3C:51\",\"time\":
I/jxcore-log( 2948): ****TEST TOOK:  ms ****
I/jxcore-log( 2948): 
I/jxcore-log( 2948): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2948): 
I/jxcore-log( 2948): stop tests now !
I/jxcore-log( 2948): 
I/jxcore-log( 2948): end, event received
I/jxcore-log( 2948): 
I/jxcore-log( 2948): CoordinatorConnector close called
I/jxcore-log( 2948): 
,I/jxcore-log( 2948): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2948): 
I/jxcore-log( 2948): The Coordinator has disconnected!
I/jxcore-log( 2948): 
I/jxcore-log( 2948): The Coordinator has closed!
I/jxcore-log( 2948): 
I/jxcore-log( 2948): stop tests now !
I/jxcore-log( 2948): 
I/jxcore-log( 2948): turning Radios off
I/jxcore-log( 2948): 
I/jxcore-log( 2948): Toggling radios to false
I/jxcore-log( 2948): 
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  736): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@382ed841 mBinding = false
,D/BluetoothManagerService(  736): Message: 2
D/BluetoothManagerService(  736): Sending off request.
D/BluetoothAdapterState( 3010): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3010): Setting state to 13
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3010): onBluetoothDisable()
I/BluetoothAdapterState( 3010): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3010): Scan Mode:20
,D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/btif_config_util( 3010): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothMapMasInstance( 3010): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3010): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3010): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3010): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3010): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3010): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  736): Message: 60
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  736): Bluetooth State Change Intent: 12 -> 13
,I/wpa_supplicant( 3016): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3016): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/BluetoothMapService( 3010): onReceive
D/BluetoothMapService( 3010): STATE_TURNING_OFF
V/BluetoothMapService( 3010): Handler(): got msg=4
D/BluetoothMapService( 3010): MAP Service closeService in
D/BluetoothMapMasInstance( 3010): MAP Service shutdown
V/BluetoothMapService( 3010): MAP Service closeService out
,I/BtOppRfcommListener( 3010): stopping Accept Thread
,I/BtOppRfcommListener( 3010): BluetoothSocket listen thread finished
,D/WifiService(  736): setWifiEnabled: false pid=2948, uid=10270
E/WifiService(  736): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  736): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 2948): Radios toggled
I/jxcore-log( 2948): 
I/chromium( 2948): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2948): Starting service discovery failed, error code 3
,E/native  (  736): do suspend true
,I/        ( 2948): Cleared service requests
,D/DockEventReceiver( 3017): finishStartingService: stopping service
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/bt_userial( 3010): RX termination
W/bt_userial( 3010): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3010): Leaving userial_read_thread()
D/bt_userial( 3010): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3010): hw_epilog_process
I/bt_userial_vendor( 3010): device fd = 53 close
,W/bt-btif ( 3010): ag scb idx 1 not allocated
E/bt-btif ( 3010): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3010): L2CAP - PSM: 0x0017 not found for deregistration
,V/NativeCrypto( 1414): Read error: ssl=0xaf7dd200: I/O error during system call, Connection timed out
I/GKI_LINUX( 3010): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3010): GKI_exit_task 0 done
I/GKI_LINUX( 3010): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterState( 3010): Stopping profile services that were post enabled
,D/HeadsetService( 3010): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/HeadsetStateMachine( 3010): Exit Disconnected: -1
D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/BluetoothHeadset(  736): Proxy object disconnected
,D/BluetoothHeadset( 1196): Proxy object disconnected
D/BluetoothHeadset( 1196): Proxy object disconnected
D/BluetoothHeadset( 1232): Proxy object disconnected
D/A2dpService( 3010): Received stop request...Stopping profile...
D/A2dpStateMachine( 3010): Exit Disconnected: -1
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/HidService( 3010): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
,E/WifiStateMachine(  736): scanCount==0 - aborting
,D/HealthService( 3010): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
D/WifiNetworkAgent(  736): NetworkAgent: NetworkAgent channel lost
,E/native  (  736): do suspend true
D/PanService( 3010): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
D/BtGatt.DebugUtils( 3010): handleDebugAction() action=null
,D/BtGatt.GattService( 3010): Received stop request...Stopping profile...
D/BtGatt.GattService( 3010): stop()
D/BtGatt.AdvertiseManager( 3010): advertise clients cleared
,D/BluetoothA2dp(  736): Proxy object disconnected
,V/NativeCrypto( 1414): SSL shutdown failed: ssl=0xaf7dd200: I/O error during system call, Broken pipe
D/WifiScanningService(  736): SCAN_AVAILABLE : 1
,D/WifiScanningService(  736): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  736): DefaultState
D/RttService(  736): SCAN_AVAILABLE : 1
D/RttService(  736): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
D/ConnectivityService(  736): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/BluetoothMapService( 3010): Received stop request...Stopping profile...
D/BluetoothMapService( 3010): stop()
,D/BluetoothMapEmailAppObserver( 3010): deinitObservers()
D/BluetoothMapEmailAppObserver( 3010): removeReceiver()
D/BluetoothAdapterService( 3010): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1a2603ea
,D/HeadsetStateMachine( 3010): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3010): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3010): Cleaning up Bluetooth Handsfree callback object
I/GKI_LINUX( 3010): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3010): GKI_exit_task 2 done
I/GKI_LINUX( 3010): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3010): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3010): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 3010): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3010): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3010): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 3010): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3010): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3010): Handler(): got msg=4
D/BluetoothMapService( 3010): MAP Service closeService in
V/BluetoothMapService( 3010): MAP Service closeService out
,D/BluetoothAdapterState( 3010): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3010): Setting state to 10
I/BluetoothAdapterState( 3010): Bluetooth adapter state changed: 13-> 10
,D/BluetoothMapService( 3010): cleanup()
D/BluetoothMapService( 3010): MAP Service closeService in
D/BluetoothManagerService(  736): Message: 60
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  736): Broadcasting onBluetoothStateChange(false) to 11 receivers.
V/BluetoothMapService( 3010): MAP Service closeService out
I/BluetoothAdapterState( 3010): Entering OffState
,D/BluetoothHeadset( 3017): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3017): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1232): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3017): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3017): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  736): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1196): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1196): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  736): onBluetoothStateChange: up=false
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/BluetoothMap( 3017): onBluetoothStateChange: up=false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  736): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  736): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  736): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Disconnected - quitting
,D/BluetoothManagerService(  736): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  736): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  736): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  736): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/TelephonyNetworkFactory( 1232): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1557): CM callback handler got msg 524292
,D/BluetoothManagerService(  736): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@382ed841 mBinding = false
,D/BluetoothManagerService(  736): Sending unbind request.
,D/BluetoothManagerService(  736): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  900): 382271951: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  900): 382271951: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  900): 382271951: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1302): 162093345: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1302): 162093345: getState() :  mService = null. Returning STATE_OFF
,E/BluetoothAdapterService(438698986)( 3010): Repeated wake lock release; aborting release: bluedroid_timer
,E/GKI_LINUX( 3010): alarm_service_reschedule unable to release wake lock with no timers: 1
,I/GKI_LINUX( 3010): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3010): GKI_exit_task 1 done
I/GKI_LINUX( 3010): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3010): cleanupNative: return from cleanup
,I/art     ( 3010): System.exit called, status: 0
I/AndroidRuntime( 3010): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 4250): 
D/AndroidRuntime( 4250): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4250): CheckJNI is OFF
,I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3016): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/ActivityManager(  736): Process com.android.bluetooth (pid 3010) has died
,I/wpa_supplicant( 3016): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/AndroidRuntime( 4250): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  736): Killing 2948:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  736): WIN DEATH: Window{c4a2573 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  736): Client connection lost with reason: 4
,W/PackageSettings(  736): Skipping PackageSetting{3165361d com.example.hello/10277} due to missing metadata
,D/Tethering(  736): InitialState.processMessage what=4
I/wpa_supplicant( 3016): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  736):   Force finishing activity ActivityRecord{296983ef u0 com.test.thalitest/.MainActivity t214}
,I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  736):   Force finishing activity ActivityRecord{296983ef u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  736): Duplicate finish request for ActivityRecord{296983ef u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1367): Explicit concurrent mark sweep GC freed 18075(918KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 18MB/25MB, paused 599us total 40.918ms
,I/art     ( 1320): Explicit concurrent mark sweep GC freed 7196(468KB) AllocSpace objects, 2(207KB) LOS objects, 23% free, 26MB/34MB, paused 513us total 48.891ms
,D/Tethering(  736): sendTetherStateChangedBroadcast 0, 0, 0
,W/ActivityManager(  736): Spurious death for ProcessRecord{9876672 2948:com.test.thalitest/u0a270}, curProc for 2948: null
,I/Keyboard.Facilitator( 1093): resetDictionaries() : en_US
,I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1302): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1093): run()
,D/AuthorizationBluetoothService( 1414): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/Settings( 1302): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Decoder ( 1093): createOrResetDecoder
,W/art     (  736): Suspending all threads took: 6.682ms
,I/ActivityManager(  736): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4314 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  736): Explicit concurrent mark sweep GC freed 50305(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 9.023ms total 112.738ms
,I/art     (  736): WaitForGcToComplete blocked for 69.909ms for cause Explicit
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  946): Initialized EGL, version 1.4
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/ConfigService( 1414): onCreate
,D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  736): Receieved: android.intent.action.PACKAGE_REMOVED
,W/ResourcesManager( 4314): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  736): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@25ad2e85 (uid=10034 pid=946)
,D/TaskPersister(  736): removeObsoleteFile: deleting file=214_task.xml
,I/CheckinRequestBuilder( 1414): Classify the device as Phone.
,I/art     (  736): Explicit concurrent mark sweep GC freed 12638(682KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.725ms total 131.465ms
,W/FetchTask( 1414): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/NativeCrypto( 1414): SSL shutdown failed: ssl=0x9d7a2600: I/O error during system call, Connection timed out
,I/CheckinRequestBuilder( 1414): Classify the device as Phone.
I/Launcher( 1320): Deferring update until onResume
,W/FetchTask( 1414): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/NativeCrypto( 1414): SSL shutdown failed: ssl=0xaf460e00: I/O error during system call, Connection timed out
,W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 1414): Classify the device as Phone.
,W/FetchTask( 1414): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 1320): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 1414): Classify the device as Phone.
,I/Babel_SMS( 4314): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4314): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4314): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4314): MmsConfig.loadFromDatabase
,I/Launcher( 1320): Deferring update until onResume
,D/AndroidRuntime( 4250): Shutting down VM
,E/Babel_SMS( 4314): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4314): MmsConfig.loadFromResources
,E/Babel_SMS( 4314): canonicalizeMccMnc: invalid mccmnc nullnull
W/FetchTask( 1414): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Babel_SMS( 4314): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4314): ApnsOta: OTA version -1
,I/CheckinRequestBuilder( 1414): Classify the device as Phone.
,W/FetchTask( 1414): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): run()
,W/Settings( 4314): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4314): startup - clean
I/Keyboard.Facilitator.MainLanguageModelLoader( 1093): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1093): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1093): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1093): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1093): run()
I/StatsUtilsManager( 1093): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1093): shouldRecordStats() = Too Soon
,I/Babel   ( 4314): deleted: false for 0
,W/ContextImpl( 3017): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  736): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4362 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 3017): finishStartingService: stopping service
,W/VideoCapabilities( 4314): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 4362): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/VideoCapabilities( 4314): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4314): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4314): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4314): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4314): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4314): onServiceConnected
I/ActivityManager(  736): Killing 3897:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/Babel   ( 4314): Attempted to change video mute state without an active call.
,W/libprocessgroup(  736): failed to open /acct/uid_10069/pid_3897/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 4362): Adding HeadsetService
D/AdapterServiceConfig( 4362): Adding A2dpService
D/AdapterServiceConfig( 4362): Adding HidService
D/AdapterServiceConfig( 4362): Adding HealthService
,D/AdapterServiceConfig( 4362): Adding PanService
,D/AdapterServiceConfig( 4362): Adding GattService
D/AdapterServiceConfig( 4362): Adding BluetoothMapService
,D/BluetoothAdapter( 3017): 321454037: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  736): Killing 2470:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10060/pid_2470/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 1414): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/SQLiteLog( 3944): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/VoicemailCleanupService( 3944): Cleaning up data for package: com.test.thalitest

```
