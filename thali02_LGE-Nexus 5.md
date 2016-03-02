#### Test 613623660556c10_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/NetworkUtils( 1370): OkHttp exception
W/EventLoggerService( 1370): Unable to send logs Error code: 262146
D/Finsky  ( 2433): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 2433): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/art     (  760): Explicit concurrent mark sweep GC freed 21091(967KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 918us total 76.767ms
E/Auth    ( 1277): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1370): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Auth    ( 1277): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1370): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
D/AndroidRuntime( 2930): 
D/AndroidRuntime( 2930): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2930): CheckJNI is OFF
D/AndroidRuntime( 2930): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2947 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2930): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 2947): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2947): Time to load native libraries: 1 ms (timestamps 2140-2141)
I/LibraryLoader( 2947): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2947): Binding Chromium to main looper Looper (main, tid 1) {520ff9b}
I/LibraryLoader( 2947): Expected native library version number "",actual native library version number ""
I/chromium( 2947): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2947): Initializing chromium process, singleProcess=true
W/art     ( 2947): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2947): ApplicationContext is null in ApplicationStatus
,W/chromium( 2947): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2947): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2947): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2947): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2947): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@358f1cec:true
,D/BluetoothAdapter( 2947): 256418306: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2947): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2947): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2947): CordovaWebView is running on device made by: LGE
,W/art     ( 2947): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2947): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2947): Render dirty regions requested: true
,D/Atlas   ( 2947): Validating map...
,W/chromium( 2947): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2947): Initialized EGL, version 1.4
D/OpenGLRenderer( 2947): Enabling debug mode 0
,I/Keyboard.Facilitator( 1065): onFinishInput()
,W/IInputConnectionWrapper( 2947): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +451ms (total +1m9s407ms)
,W/BindingManager( 2947): Cannot call determinedVisibility() - never saw a connection for the pid: 2947
,D/JsMessageQueue( 2947): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2947): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257331840
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2947): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2947):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2947):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2947):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2947):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 2947): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21220057 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Bluetooth MAC address: 34:FC:EF:11:AE:67
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36c94962 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 2947): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  760): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2947): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2947): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 2947): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2947): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2947): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 2947): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 2947): Initializing JXcore engine
W/jxcore-log( 2947): JXcore engine is ready
,W/Thread-280( 3002): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6754]" dev="sockfs" ino=6754 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-280( 3002): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/Thread-280( 3002): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7753]" dev="sockfs" ino=7753 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-280( 3002): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17408]" dev="sockfs" ino=17408 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2947): Starting JXcore engine
,W/jxcore-log( 2947): Platform android
W/jxcore-log( 2947): 
W/jxcore-log( 2947): Process ARCH arm
W/jxcore-log( 2947): 
,I/jxcore-log( 2947): JXcore Cordova bridge is ready!
I/jxcore-log( 2947): 
,W/jxcore-log( 2947): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 2947): execute: REQUEST_ACCESS_COARSE_LOCATION
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2947): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 2947): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 2947): BLE multiple advertisement supported
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): INFO testUtils Toggling radios to: true
I/jxcore-log( 2947): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  760): Message: 1
D/BluetoothManagerService(  760): MESSAGE_ENABLE: mBluetooth = null
,I/jxcore-log( 2947): Unit Test app is loaded
I/jxcore-log( 2947): 
,D/WifiService(  760): setWifiEnabled: true pid=2947, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/chromium( 2947): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/ActivityManager(  760): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3006 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/WifiMonitor(  760): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3012 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3005): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3006): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3005): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3945af52:true
,D/BluetoothAdapter( 3012): 505595818: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  760): Message: 30
,D/AdapterServiceConfig( 3006): Adding HeadsetService
,D/AdapterServiceConfig( 3006): Adding A2dpService
D/AdapterServiceConfig( 3006): Adding HidService
D/AdapterServiceConfig( 3006): Adding HealthService
,D/AdapterServiceConfig( 3006): Adding PanService
D/AdapterServiceConfig( 3006): Adding GattService
D/AdapterServiceConfig( 3006): Adding BluetoothMapService
D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3012): Adding local MAP profile
D/BluetoothMap( 3012): Create BluetoothMap proxy object
D/BluetoothManagerService(  760): Message: 30
D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3012): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3012): 505595818: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3012): 505595818: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37aac450:true
,D/BluetoothAdapterState( 3006): make
,I/bluedroid( 3006): init
I/BluetoothAdapterState( 3006): Entering OffState
,I/bte_conf( 3006): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3006): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3006): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3006): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3006): get_profile_interface socket
I/bluedroid( 3006): get_profile_interface map_client
,I/GKI_LINUX( 3006): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3006): Address is:34:FC:EF:11:AE:67
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3057 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1761:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1761/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 3006): Name is: Nexus 5
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3006): config_hci_snoop_log
,D/BluetoothManagerService(  760): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3006): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3006): Setting state to 11
I/BluetoothAdapterState( 3006): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  760): Message: 60
,D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3006): make
,I/BluetoothBondStateMachine( 3006): StableState(): Entering Off State
,D/BluetoothHeadset(  760): Proxy object connected
,D/HeadsetService( 3006): Received start request. Starting profile...
D/BluetoothHeadset( 1166): Proxy object connected
,I/BluetoothHeadsetServiceJni( 3006): classInitNative: succeeds
D/BluetoothHeadset( 1166): Proxy object connected
D/BluetoothHeadset( 1194): Proxy object connected
D/HeadsetStateMachine( 3006): make
,I/BluetoothAdapterState( 3006): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3006): max_hf_connections = 1
I/bluedroid( 3006): get_profile_interface handsfree
,D/HeadsetStateMachine( 3006): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@520ff9b
,D/BluetoothA2dp(  760): Proxy object connected
,D/A2dpService( 3006): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3006): classInitNative: succeeds
I/bluedroid( 3006): get_profile_interface avrcp
,E/RemoteController( 3006): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 3006): classInitNative: succeeds
D/A2dpStateMachine( 3006): make
,I/bluedroid( 3006): get_profile_interface a2dp
I/GKI_LINUX( 3006): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@520ff9b
D/A2dpStateMachine( 3006): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3006): classInitNative: succeeds
,D/BluetoothInputDevice( 3012): Proxy object connected
,D/HidService( 3006): Received start request. Starting profile...
,D/HidProfile( 3012): Bluetooth service connected
I/bluedroid( 3006): get_profile_interface hidhost
D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@520ff9b
I/BluetoothHealthServiceJni( 3006): classInitNative: succeeds
,D/HealthService( 3006): Received start request. Starting profile...
,I/bluedroid( 3006): get_profile_interface health
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@520ff9b
I/BluetoothPanServiceJni( 3006): classInitNative(L105): succeeds
,D/BluetoothPan( 3012): BluetoothPAN Proxy object connected
,D/PanService( 3006): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3006): initializeNative(L110): pan
I/bluedroid( 3006): get_profile_interface pan
D/PanProfile( 3012): Bluetooth service connected
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@520ff9b
I/BtGatt.JNI( 3006): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3006): handleDebugAction() action=null
,D/BtGatt.GattService( 3006): Received start request. Starting profile...
,D/BtGatt.GattService( 3006): start()
I/bluedroid( 3006): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3006): advertise manager created
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@520ff9b
,V/BluetoothMapService( 3006): BluetoothMapBinder()
,D/BluetoothMap( 3012): Proxy object connected
,D/BluetoothMapService( 3006): Received start request. Starting profile...
D/BluetoothMapService( 3006): start()
D/MapProfile( 3012): Bluetooth service connected
D/BluetoothMap( 3012): getConnectedDevices()
,D/BluetoothMap( 3012): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3006): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3006): createReceiver()
,D/BluetoothMapEmailAppObserver( 3006): initObservers()
D/BluetoothMapEmailAppObserver( 3006): getEnabledAccountItems()
,D/BluetoothAdapterService( 3006): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@520ff9b
D/HeadsetStateMachine( 3006): Proxy object connected
D/HeadsetStateMachine( 3006): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3006): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3006): Disconnected process message: 11, size: 0
V/BluetoothMapService( 3006): Handler(): got msg=1
D/BluetoothAdapterState( 3006): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3006): enable
,I/GKI_LINUX( 3006): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3006): btu_task pending for preload complete event
I/bt_hci_bdroid( 3006): init
,I/bt_vendor( 3006): init
I/bt_vnd_conf( 3006): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3006): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,D/bt_userial( 3006): userial_init
,I/bt_userial_vendor( 3006): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3006): device fd = 53 open
,D/bt_userial( 3006): Entering userial_read_thread()
,I/bt_hwcfg( 3006): bt vendor lib: set UART baud 4000000
,D/AuthorizationBluetoothService( 1277): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  760): Killing 2509:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/bt_hwcfg( 3006): Chipset BCM4335C0
D/bt_hwcfg( 3006): Target name = [BCM4335C0]
,I/bt_hwcfg( 3006): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2509/cgroup.procs: No such file or directory
,D/Tethering(  760): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 3006): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3006): Settlement delay -- 100 ms
I/bt_hwcfg( 3006): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3005): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  760): Loading config and enabling all networks 
,D/WifiService(  760): New client listening to asynchronous messages
,E/WifiConfigStore(  760): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/wpa_supplicant( 3005): wlan0: CTRL-EVENT-SCAN-STARTED 
,W/Settings( 2279): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  760): Setting external_sim to 1
,D/WifiStateMachine(  760): Setting OUI to DA-A1-19
I/WifiNative-HAL(  760): startHal
,D/wifi    (  760): setting scan oui 0x93cde328
D/WifiHAL (  760): Sending mac address OUI
E/WifiHAL (  760): failed to set scanning mac OUI; result = -95
,E/native  (  760): do suspend true
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  760): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  760): SCAN_AVAILABLE : 3
D/RttService(  760): SCAN_AVAILABLE : 3
,D/WifiScanningService(  760): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  760): startHal
D/RttService(  760): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,I/bt_hwcfg( 3006): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3006): Setting local bd addr to 34:FC:EF:11:AE:67
,D/wifi    (  760): getting scan capabilities on interface[1] = 0x93cde328
D/WifiHAL (  760): Creating message to get scan capablities; iface = 21
D/WifiHAL (  760): In GetCapabilities::handleResponse
D/WifiHAL (  760): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  760): StartedState
,D/WifiNative-HAL(  760): p2pGetDeviceAddress
,D/WifiNative-HAL(  760): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3005): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3006): vendor lib fwcfg completed
,I/bt-btu  ( 3006): btu_task received preload complete event
,I/        ( 3006): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3006): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3006): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3006): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3006): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3006): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3006): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3006): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3006): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3006): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3006): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3006): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3006): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3006): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3006): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3006): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ed99d5 
E/bt-btm  ( 3006): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ed99d5 
,E/bt-btif ( 3006): Calling BTA_HhEnable
E/bt-btif ( 3006): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3006): Address is:34:FC:EF:11:AE:67
,W/bt-smp  ( 3006): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3006): Plain text(LSB ~ MSB) = b1 60 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3006): Encrypted text(LSB ~ MSB) = 2d 05 cc d6 d4 df 55 1e fe 26 c8 74 c7 9d 70 e2 
,W/bt-btm  ( 3006): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3006): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3006): Scan Mode:20
,D/BluetoothAdapterProperties( 3006): Discoverable Timeout:120
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
,D/bte_conf( 3006): Device ID record 1 : primary
D/bte_conf( 3006):   vendorId            = 000f
D/bte_conf( 3006):   vendorIdSource      = 0001
D/bte_conf( 3006):   product             = 1200
D/bte_conf( 3006):   version             = 1436
D/bte_conf( 3006):   clientExecutableURL = 
D/bte_conf( 3006):   serviceDescription  = 
D/bte_conf( 3006):   documentationURL    = 
D/bte_conf( 3006): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3006): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3006): ScanMode =  20
D/BluetoothAdapterProperties( 3006): State =  11
D/BluetoothAdapterProperties( 3006): Setting state to 12
I/BluetoothAdapterState( 3006): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 9 receivers.
,I/BluetoothAdapterState( 3006): Entering On State
,D/BluetoothPan( 3012): onBluetoothStateChange(on) call bindService
,D/BluetoothPanServiceJni( 3006): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,E/bt_h4   ( 3006): vendor lib postload completed
,D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3006): Scan Mode:21
D/BluetoothAdapterProperties( 3006): Discoverable Timeout:120
,D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3012): onBluetoothStateChange: up=true
,D/BluetoothPbap( 3012): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1166): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
D/BluetoothMap( 3012): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1194): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1166): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3006): onReceive
D/BluetoothMapService( 3006): STATE_ON
V/BluetoothMapService( 3006): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3006): Map Service startRfcommSocketListener
,I/Telecom ( 1166): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapMasInstance( 3006): MAS initSocket()
D/BluetoothMapMasInstance( 3006):   masId = 00
D/BluetoothMapMasInstance( 3006):   msgTypes = 0e
D/BluetoothMapMasInstance( 3006):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3006):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/HeadsetStateMachine( 3006): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3006): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3006): mNumber:  mType: 128
D/HeadsetStateMachine( 3006): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3006): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/BluetoothAdapter( 3006): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3006): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3006): Accepting socket connection...
,D/LocalBluetoothProfileManager( 3012): Adding local A2DP profile
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3012): Adding local HEADSET profile
,D/BluetoothManagerService(  760): Message: 30
,W/ContextImpl( 3012): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3012): Proxy object connected
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3006): getBluetoothService() called with no BluetoothManagerCallback
,D/A2dpProfile( 3012): Bluetooth service connected
,D/BluetoothHeadset( 3012): Proxy object connected
,D/HeadsetProfile( 3012): Bluetooth service connected
,D/DockEventReceiver( 3012): finishStartingService: stopping service
,D/BluetoothPbap( 3012): Proxy object connected
,D/AuthorizationBluetoothService( 1277): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/PbapServerProfile( 3012): Bluetooth service connected
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3006): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3006): Accept thread started.
,I/wpa_supplicant( 3005): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  760): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,E/WifiConfigStore(  760): will read network variables netId=0
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  760): will read network variables netId=0
,I/wpa_supplicant( 3005): wlan0: Trying to associate with f4:f2:6d:22:99:3e (SSID='NG700' freq=2437 MHz)
,E/WifiConfigStore(  760): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3005): PNO: In assoc process
,I/wpa_supplicant( 3005): wlan0: Associated with f4:f2:6d:22:99:3e
,I/wpa_supplicant( 3005): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3005): wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 1
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3185): version 5.5.6 starting
,E/dhcpcd  ( 3185): get_duid: Read-only file system
,I/dhcpcd  ( 3185): wlan0: rebinding lease of 192.168.1.120
,I/dhcpcd  ( 3185): wlan0: acknowledged 192.168.1.120 from 192.168.1.1
,I/dhcpcd  ( 3185): wlan0: leased 192.168.1.120 for 172800 seconds
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  760): Adding iface wlan0 to network 100
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  760): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  760): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG700"
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.120/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  906): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Mar 2016 08:54:41 GMT], X-Android-Received-Millis=[1456908880592], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1456908880577]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1194): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  906): CM callback handler got msg 524290
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  906): CM callback handler got msg 524295
,I/jxcore-log( 2947): My device name is: LGE-Nexus 5
I/jxcore-log( 2947): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  760): Setting time of day to sec=1456908884
,W/AlarmManagerService(  760): Unable to set rtc to 1456908884: Invalid argument
,I/NetworkMonitor( 2546): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2546): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3266 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 224us total 10.582ms
I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 212us total 9.482ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 212us total 9.201ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 39002(2007KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 1.165ms total 63.342ms
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1456842615330 min interval config: 0 actual interval: 66269302
,E/GpsLocationProvider(  760): No APN found to select.
,D/GpsLocationProvider(  760): NTP server returned: 1456908881564 (Wed Mar 02 09:54:41 GMT+01:00 2016) reference: 102201 certainty: 20 system time offset: -3079
E/LocSvc_eng(  760): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/SystemUpdateService( 1558): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/CheckinService( 1558): Checking schedule, now: 1456908884659 next: 1456884782239
I/CheckinService( 1558): active receiver: enabled
,I/CheckinService( 1558): Preparing to send checkin request
I/EventLogService( 1558): Accumulating logs since 1456908101775
,I/GoogleURLConnFactory( 1277): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 3266): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3266): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SystemUpdateService( 1558): onCreate
,D/SystemUpdateService( 1558): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1558): active receiver: enabled
,I/SystemUpdateService( 1558): showing system update notification
,E/ActivityThread( 1558): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  760): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 26775, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  760): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 136416, reason: UserStart
,V/JNIHelp ( 3266): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ValidateNoPeople(  760): skipping global notification
V/SystemUpdateService( 1558): retry (wakeup: false) in 3599975 ms
,I/iu.SyncManager( 1558): SYNC; picasa accounts
,D/NetworkLogImpl( 1558): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1558): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/SystemUpdateService( 1558): onDestroy
,W/System  ( 3266): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3266): Installed default security provider GmsCore_OpenSSL
,I/iu.UploadsManager( 1558): num queued entries: 0
I/iu.UploadsManager( 1558): num updated entries: 0
I/iu.SyncManager( 1558): NEXT; no task
,E/Auth.Api.Credentials( 1558): [CredentialSyncAdapter] Unknown sync event.
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3318 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel   ( 2279): connection state changed from UNKNOWN to CONNECTED
,I/PhenotypeConfigurator( 1277): Scheduling Phenotype for one-off execution 8779 seconds from now (1456908884926)
,E/YouTube MDX( 3266): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/ConnectivityChangeReceiver( 1558): Ignoring connectivity change
,I/GAv4    ( 3318): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3318):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3318):   adb logcat -s GAv4
,I/CheckinRequestBuilder( 1558): Checkin reason type: 12 attempt count: 1
,D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  760): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
I/dex2oat ( 3368): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-848106907.jar --oat-fd=30 --oat-location=/data/data/com.google.android.youtube/cache/ads-848106907.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/ConnectivityService(  760): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1558): CM callback handler got msg 524290
,I/GCM     ( 1277): GCM config loaded
,W/GAv4    ( 3318): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/WifiService(  760): New client listening to asynchronous messages
E/ActivityThread( 1558): Failed to find provider info for com.google.android.wearable.settings
,W/GAv4    ( 3318): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 1868(70KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 615us total 42.524ms
,W/GAv4    ( 3318): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 3368): dex2oat took 89.808ms (threads: 4)
,W/InstanceID/Rpc( 3266): Found 10008
,I/WebViewFactory( 3318): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3318): Time to load native libraries: 2 ms (timestamps 6076-6078)
I/LibraryLoader( 3318): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3318): Binding Chromium to main looper Looper (main, tid 1) {7c9a30c}
I/LibraryLoader( 3318): Expected native library version number "",actual native library version number ""
I/chromium( 3318): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3318): Initializing chromium process, singleProcess=true
W/art     ( 3318): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3318): ApplicationContext is null in ApplicationStatus
,V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 3318): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3318): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3318): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3318): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3318): Requires BLUETOOTH permission
,I/art     (  760): Explicit concurrent mark sweep GC freed 23882(1002KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.047ms total 55.632ms
,I/NSApplication( 3318): Starting up...
,W/DriveInitializer( 1558): Awaiting to be initialized
W/DriveInitializer( 1558): Background init thread started
,I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3477 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 1459:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,D/TimeService( 3477): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1456908885797
D/        ( 3477): TimeServiceNative: User Time to be set is 1456908885798
D/QC-time-services( 3477): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3477): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3477): Lib:time_genoff_operation: pargs->ts_val = 1456908885798
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 3477): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1456908885798
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1456908885798, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/5/70 14:45:2
,D/QC-time-services(  197): Daemon:Value read from RTC seconds = 16037102000
D/QC-time-services(  197): Daemon:new time 1456908885798 
D/QC-time-services(  197): Daemon: delta 1440871783798 genoff 1440871783798 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871783798 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871783798 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1140944085798
,E/QC-time-services( 3477): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_1459/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2638:com.android.musicfx/u0a15 (adj 15): empty #17
,W/DriveInitializer( 1558): Background init thread ended
,W/libprocessgroup(  760): failed to open /acct/uid_10015/pid_2638/cgroup.procs: No such file or directory
,I/PhenotypeFlagCommitter( 1277): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1456842615330 min interval config: 0 actual interval: 66270631
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 12994(993KB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 22MB/37MB, paused 1.163ms total 51.441ms
,W/art     ( 2707): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3517 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3517): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3517):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3517):   adb logcat -s GAv4
,I/ActivityManager(  760): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3535 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/GAv4    ( 3517): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3517): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ResourcesManager( 3535): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3535): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 3517): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2671:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/MultiDex( 3535): VM with version 2.1.0 has multidex support
I/MultiDex( 3535): install
I/MultiDex( 3535): VM has multidex support, MultiDex support library is disabled.
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 2947): 
,W/libprocessgroup(  760): failed to open /acct/uid_10040/pid_2671/cgroup.procs: No such file or directory
,I/GCM     ( 1558): Message from null null
E/GCM     ( 1558): Dropping message from null
,V/JNIHelp ( 3535): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3535): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3535): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a0fcadc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3535): Installed default security provider GmsCore_OpenSSL
,D/WearableService( 1277): callingUid 10008, callindPid: 1277
,D/AuthorizationBluetoothService( 1277): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1277): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1558): Restart initialization of location
,I/art     ( 3535): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3535): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/PhenotypeFlagCommitter( 1277): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1277): No location to return for getLastLocation()
,W/FusedLocationProvider( 1277): location=null
,D/NativeLibraryUtils( 3535): Install completed successfully. count=14 extracted=0
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 2753(112KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 383us total 11.257ms
,D/WVCdm   (  183): Instantiating CDM.
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,I/GoogleURLConnFactory( 3535): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xb46ff940
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb1a1e070, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb45c7000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb1aba440, idLength=0xbe8842d0
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
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  183): PrepareKeyRequest: nonce=3048683454
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb6092600
D/DrmWidevineDash(  183): message_length=1597, signature=0xb605e5c0, signature_length=3196601012
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 2947): 
,I/ActivityManager(  760): Killing 2349:com.google.android.gm/u0a70 (adj 15): empty #17
,I/jxcore-log( 2947): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 2947): 
,I/io.jxcore.node.ConnectivityInfo( 2947): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 2947):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 2947):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 2947):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 2947):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 2947):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 2947):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 2947):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 2947):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 2947): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 2947): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 2947): 
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2349/cgroup.procs: No such file or directory
,I/art     ( 1277): Explicit concurrent mark sweep GC freed 61045(3MB) AllocSpace objects, 51(839KB) LOS objects, 40% free, 22MB/36MB, paused 1.226ms total 52.536ms
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb586d000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!,
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xb3303940
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb1a1e118, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1acb600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
,I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb1aba480, idLength=0xbe8842d0
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  183): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
,D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  183): PrepareKeyRequest: nonce=998853311
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb6092600
D/DrmWidevineDash(  183): message_length=1632, signature=0xb605e5c0, signature_length=3196601012
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/dex2oat ( 3612): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3612): dex2oat took 116.411ms (threads: 4)
,I/Adreno-EGL( 3535): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Adreno-EGL( 3535): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3535): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1558): Classify the device as Phone.
,I/CheckinTask( 1558): Sending checkin request (9781 bytes)
,I/CheckinResponseProcessor( 1558): From server: 3 gservices updates and 0 deletes,
,I/CertBlacklister(  760): Certificate blacklist changed, updating...
,I/CertBlacklister(  760): Certificate blacklist updated
,I/GservicesProvider( 1479): main difference update completed
,I/ActivityManager(  760): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=3643 uid=10013 gids={50013, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1558): Checkin reason type: 12 attempt count: 1
,I/Babel_SMS( 2279): ApnsOta: OTA version -1
,E/ActivityThread( 1558): Failed to find provider info for com.google.android.wearable.settings
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,I/ActivityManager(  760): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3676 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/art     (  760): Explicit concurrent mark sweep GC freed 22652(1001KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.006ms total 62.415ms
,I/Search.GservicesUpdateTask( 1370): Updating Gservices keys
,E/UpdateRequestReceiver( 3676): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/UpdateFetcherService( 3676): Update started
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 10310(506KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 495us total 18.794ms
,E/UpdateRequestReceiver( 3676): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3676): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3676): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1456842615330 min interval config: 0 actual interval: 66275055
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,I/SystemUpdateService( 1558): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1558): onCreate
,I/ActivityManager(  760): Killing 2005:com.android.defcontainer/u0a5 (adj 15): empty #17
,D/DownloadManager(  899): [81] Starting
,W/libprocessgroup(  760): failed to open /acct/uid_10005/pid_2005/cgroup.procs: No such file or directory
,D/SystemUpdateService( 1558): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1558): active receiver: enabled
,I/SystemUpdateService( 1558): showing system update notification
,I/CheckinRequestBuilder( 1558): Classify the device as Phone.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1558): retry (wakeup: false) in 3599934 ms
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 3355(136KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 1.155ms total 20.751ms
,D/DownloadManager(  899): [81] Finished with status SUCCESS
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 19171(1254KB) AllocSpace objects, 10(159KB) LOS objects, 40% free, 22MB/38MB, paused 783us total 36.165ms
,W/SQLiteConnectionPool( 1558): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  760): Killing 2615:android.process.acore/u0a4 (adj 15): empty #17
,D/SystemUpdateService( 1558): onDestroy
,W/libprocessgroup(  760): failed to open /acct/uid_10004/pid_2615/cgroup.procs: No such file or directory
,E/DynamiteModule( 1558): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1558): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1558): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1558): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1558): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1558): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1558): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1558): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1558): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1558): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1558): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1558): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/DynamiteModule( 1558): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/DynamiteModule( 1558): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/DynamiteModule( 1558): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1558): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1558): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/DynamiteModule( 1558): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1558): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/DynamiteModule( 1558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/DynamiteModule( 1558): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1558): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1558): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1558): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1558): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1558): 		... 17 more
E/DynamiteModule( 1558): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 1558): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 1558): Selected local version of com.google.android.gms.flags
I/CheckinTask( 1558): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/art     ( 1479): Explicit concurrent mark sweep GC freed 2550(99KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 1.001ms total 21.732ms
,I/CheckinService( 1558): Checking schedule, now: 1456908890957 next: 1456951057926
I/CheckinService( 1558): active receiver: disabled
,I/CheckinService( 1558): Checking schedule, now: 1456908891020 next: 1456951057926
I/CheckinService( 1558): active receiver: disabled
,D/SystemEventReceiver( 1558): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1558): Updating ocr activity enabled=false
,D/CheckinService( 1558): Recording last checkin time for package unspecified as 1456908891102
,I/VacuumService( 1277): Vacuum at: now=1456908891260 tag=VacuumService
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1558): Updating downloaded model state (gservices changed)
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 2784(109KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/26MB, paused 551us total 10.435ms
,I/art     ( 1277): Explicit concurrent mark sweep GC freed 31670(1676KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 21MB/36MB, paused 773us total 81.030ms
,I/ContactAccountLoggerTas( 1370): canRun() : Opted Out
,D/GCM     ( 1277): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1277): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1277): DispatchingService.onCreate()
,W/GeofencerStateMachine( 1277): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1277): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,E/ctxmgr  ( 1277): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/art     (  760): Explicit concurrent mark sweep GC freed 19431(943KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.035ms total 55.105ms
,D/DownloadManager(  899): [82] Starting
,I/GCoreUlr( 1277): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1277): Unbound from all location providers
I/GCoreUlr( 1277): Place inference reporting - stopped
,D/GCM     ( 1277): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1277): DispatchingService.onDestroy()
I/GCoreUlr( 1277): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1277): Unbound from all location providers
I/GCoreUlr( 1277): Place inference reporting - stopped
,W/ctxmgr  ( 1277): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1277): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,D/DownloadManager(  899): [82] Finished with status SUCCESS
,I/UpdateFetcherService( 3676): Update downloaded, starting installation
,I/UpdateFetcherService( 3676): doneInstall
,I/ConfigUpdateInstallReceiver(  760): Found new update, installing...
,I/ConfigUpdateInstallReceiver(  760): Installation successful
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 2947): 
I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 2947): 
,I/ActivityManager(  760): Killing 2863:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_2863/cgroup.procs: No such file or directory
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 2947): 
,W/PackageSettings(  760): Skipping PackageSetting{38edab9e com.example.hello/10278} due to missing metadata
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  760): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3794 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,W/ResourcesManager( 2279): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2279): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  760): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  760): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@db6cccf
,I/UpdateIcingCorporaServi( 1370): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/GCoreNlp( 1277): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Launcher( 1243): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@520ff9b new=com.google.android.velvet.VelvetApplication@520ff9b
,D/PackageBroadcastService( 1558): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1558): Null package name or gms related package.  Ignoreing.
,I/Launcher( 1243): Deferring update until onResume
,I/ContactLocale( 3794): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 1558): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1243): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1370): UpdateCorporaTask done [took 235 ms] updated apps [took 235 ms] 
,I/Icing   ( 1558): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,D/Icing   ( 1558): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1558): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  760): Killing 3012:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_3012/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1065): run()
I/Keyboard.Facilitator( 1065): flushDynamicLanguageModels()
,I/ConfigService( 1277): onCreate
,I/ConfigService( 1277): onDestroy
,I/ClearcutLoggerApiImpl( 1277): disconnect managed GoogleApiClient
,E/ActivityThread( 1558): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  760): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 136416, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  760): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 227610, reason: UserStart
,I/art     ( 1277): Explicit concurrent mark sweep GC freed 34396(1963KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 22MB/37MB, paused 855us total 34.110ms
,E/DataBuffer( 1277): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@77618df)
,E/DataBuffer( 1277): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@456b92c)
E/DataBuffer( 1277): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29606ff5)
,E/DataBuffer( 1277): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@caa818a)
,E/DataBuffer( 1277): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@12cd63fb)
,I/PhenotypeFlagCommitter( 1277): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1277): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1277): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2947): Reconnected to the test server
I/jxcore-log( 2947): 
,I/jxcore-log( 2947): --= Surplus to requirements =--
I/jxcore-log( 2947): 
I/jxcore-log( 2947): ****TEST TOOK:  ms ****
I/jxcore-log( 2947): 
I/jxcore-log( 2947): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2947): 
,D/AndroidRuntime( 3923): 
D/AndroidRuntime( 3923): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3923): CheckJNI is OFF
,D/AndroidRuntime( 3923): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 2947:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  760): WIN DEATH: Window{1a09991c u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  760): Client connection lost with reason: 4
,W/PackageSettings(  760): Skipping PackageSetting{38edab9e com.example.hello/10278} due to missing metadata
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{240b7fc1 u0 com.test.thalitest/.MainActivity t218}
,W/ActivityManager(  760): Spurious death for ProcessRecord{3817df1c 2947:com.test.thalitest/u0a270}, curProc for 2947: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  760):   Force finishing activity ActivityRecord{240b7fc1 u0 com.test.thalitest/.MainActivity t218 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{240b7fc1 u0 com.test.thalitest/.MainActivity t218 f}
,I/art     ( 1370): Explicit concurrent mark sweep GC freed 12209(818KB) AllocSpace objects, 6(108KB) LOS objects, 24% free, 18MB/25MB, paused 333us total 23.498ms
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1065): resetDictionaries() : en_US
,I/art     ( 1243): Explicit concurrent mark sweep GC freed 8853(618KB) AllocSpace objects, 2(207KB) LOS objects, 38% free, 26MB/42MB, paused 508us total 48.296ms
,I/Keyboard.Facilitator.DecoderInitializer( 1065): run()
,W/GeofencerStateMachine( 1277): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1065): createOrResetDecoder
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 22398(1384KB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 22MB/30MB, paused 28.481ms total 93.165ms
D/VoicemailCleanupService( 3794): Cleaning up data for package: com.test.thalitest
,I/art     (  760): Explicit concurrent mark sweep GC freed 38438(2MB) AllocSpace objects, 8(119KB) LOS objects, 33% free, 27MB/41MB, paused 2.619ms total 71.649ms
I/art     (  760): WaitForGcToComplete blocked for 33.443ms for cause Explicit
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3957 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ConfigService( 1277): onCreate
,I/Adreno-EGL(  941): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  941): Initialized EGL, version 1.4
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/OpenGLRenderer(  941): Enabling debug mode 0
,D/TaskPersister(  760): removeObsoleteFile: deleting file=218_task.xml
,I/UpdateIcingCorporaServi( 1370): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3d007dc (uid=10034 pid=941)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1065): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1065): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1065): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1065): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1065): run()
I/StatsUtilsManager( 1065): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1065): shouldRecordStats() = Too Soon
,W/Launcher( 1243): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@520ff9b new=com.google.android.velvet.VelvetApplication@520ff9b
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3990 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  760): Explicit concurrent mark sweep GC freed 10160(541KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.737ms total 161.619ms
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2947 uid 10270
,I/Keyboard.Facilitator( 1065): onFinishInput()
,I/Launcher( 1243): Deferring update until onResume
,I/ActivityManager(  760): Killing 2546:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1243): Deferring update until onResume
,D/AndroidRuntime( 3923): Shutting down VM
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2546/cgroup.procs: No such file or directory
,W/ContextImpl( 3990): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1558): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1558): Module APK com.google.android.play.games already loaded
,I/UpdateIcingCorporaServi( 1370): UpdateCorporaTask done [took 181 ms] updated apps [took 181 ms] 
,D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1558): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1558): Clearing selected account for com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1277): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1277): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4014 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/LocationSettingsChecker( 1558): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  760): Killing 3318:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1558): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1558): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1558): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1558): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1558): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1558): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1558): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1558): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1558): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1558): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1558): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1558): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1558): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/libprocessgroup(  760): failed to open /acct/uid_10061/pid_3318/cgroup.procs: No such file or directory
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,W/BaseAppContext( 1558): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1558): App measurement is starting up, version: 8489
I/GMPM-SVC( 1558): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1558): doRemovePackageData com.test.thalitest

```
