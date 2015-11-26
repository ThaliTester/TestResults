#### Test 51790364a0f6051_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2917): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2917):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2917):   adb logcat -s GAv4
W/GAv4    ( 2917): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2917): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2917): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2917): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,--------- beginning of system
W/ResourcesManager( 2917): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2917): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2418): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  733): Killing 2139:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 2917): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2917): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2917): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2964): 
D/AndroidRuntime( 2964): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2964): CheckJNI is OFF
W/libprocessgroup(  733): failed to open /acct/uid_1000/pid_2139/cgroup.procs: No such file or directory
V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2964): Calling main entry com.android.commands.am.Am
I/ActivityManager(  733): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  733): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2995 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2964): Shutting down VM
V/ActivityManager(  733): Display changed displayId=0
I/Icing   ( 1562): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1562): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1562): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2995): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2995): Time to load native libraries: 2 ms (timestamps 6649-6651)
I/LibraryLoader( 2995): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2995): Binding Chromium to main looper Looper (main, tid 1) {1fe83f3d}
I/LibraryLoader( 2995): Expected native library version number "",actual native library version number ""
I/chromium( 2995): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2995): Initializing chromium process, singleProcess=true
,W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2995): ApplicationContext is null in ApplicationStatus
,W/chromium( 2995): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2995): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2995): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2995): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2995): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  733): Message: 20
,D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12616232:true
,D/BluetoothAdapter( 2995): 827876908: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2995): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2995): CordovaWebView is running on device made by: LGE
,W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2995): Render dirty regions requested: true
,D/Atlas   ( 2995): Validating map...
,W/chromium( 2995): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2995): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2995): Enabling debug mode 0
,I/ActivityManager(  733): Displayed com.test.thalitest/.MainActivity: +494ms (total +55s602ms)
,W/IInputConnectionWrapper( 2995): showStatusIcon on inactive InputConnection
,W/BindingManager( 2995): Cannot call determinedVisibility() - never saw a connection for the pid: 2995
,D/JsMessageQueue( 2995): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2995): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2995): jxcore cordova android initializing
I/ActivityManager(  733): Killing 2225:com.google.android.youtube/u0a80 (adj 15): empty #17
W/libprocessgroup(  733): failed to open /acct/uid_10080/pid_2225/cgroup.procs: No such file or directory
,W/jxcore-log( 2995): Initializing JXcore engine
W/jxcore-log( 2995): JXcore engine is ready
,W/jxcore-log( 2995): Starting JXcore engine
,W/.test.thalitest( 2995): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9451]" dev="sockfs" ino=9451 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2995): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2995): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8457]" dev="sockfs" ino=8457 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2995): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17631]" dev="sockfs" ino=17631 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2995): Platform android
W/jxcore-log( 2995): 
W/jxcore-log( 2995): Process ARCH arm
W/jxcore-log( 2995): 
,I/jxcore-log( 2995): JXcore Cordova bridge is ready!
I/jxcore-log( 2995): 
,W/jxcore-log( 2995): JXcore engine is started
,I/Choreographer( 2995): Skipped 110 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2995): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2995): Toggling radios to true
I/jxcore-log( 2995): 
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  733): Message: 1
D/BluetoothManagerService(  733): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  733): New client listening to asynchronous messages
,D/WifiService(  733): setWifiEnabled: true pid=2995, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  181): Softap fwReload - Ok
,I/jxcore-log( 2995): Radios toggled
I/jxcore-log( 2995): 
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring down wlan0
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,I/ActivityManager(  733): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3052 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiMonitor(  733): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  733): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3059 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3058): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3052): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3058): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3095d1e1:true
,D/BluetoothAdapter( 3059): 535314237: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothManagerService(  733): Message: 30
,D/LocalBluetoothProfileManager( 3059): Adding local MAP profile
D/BluetoothMap( 3059): Create BluetoothMap proxy object
,D/BluetoothManagerService(  733): Message: 30
,D/BluetoothManagerService(  733): Message: 30
,D/LocalBluetoothProfileManager( 3059): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3059): 535314237: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3059): 535314237: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  733): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3098 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  733): Killing 2334:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10038/pid_2334/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 3052): Adding HeadsetService
D/AdapterServiceConfig( 3052): Adding A2dpService
D/AdapterServiceConfig( 3052): Adding HidService
D/AdapterServiceConfig( 3052): Adding HealthService
D/AdapterServiceConfig( 3052): Adding PanService
D/AdapterServiceConfig( 3052): Adding GattService
D/AdapterServiceConfig( 3052): Adding BluetoothMapService
,D/BluetoothManagerService(  733): Message: 20
,D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34c26eb7:true
,D/BluetoothAdapterState( 3052): make
,I/bluedroid( 3052): init
,I/BluetoothAdapterState( 3052): Entering OffState
,I/bte_conf( 3052): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3052): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3052): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 3052): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3052): get_profile_interface socket
I/bluedroid( 3052): get_profile_interface map_client
,I/GKI_LINUX( 3052): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  733): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  733): Message: 40
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 3052): Address is:34:FC:EF:11:AE:67
I/bluedroid( 3052): config_hci_snoop_log
D/BluetoothManagerService(  733): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 3052): Name is: Nexus 5
D/BluetoothManagerService(  733): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  733): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  733): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 3052): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3052): Setting state to 11
,I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  733): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3052): make
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,D/BluetoothHeadset(  733): Proxy object connected
,D/BluetoothHeadset( 1213): Proxy object connected
,D/BluetoothHeadset( 1180): Proxy object connected
D/BluetoothHeadset( 1180): Proxy object connected
,D/HeadsetService( 3052): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3052): classInitNative: succeeds
,D/HeadsetStateMachine( 3052): make
,I/BluetoothAdapterState( 3052): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3052): max_hf_connections = 1
I/bluedroid( 3052): get_profile_interface handsfree
,D/HeadsetStateMachine( 3052): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,D/BluetoothA2dp(  733): Proxy object connected
,D/A2dpService( 3052): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3052): classInitNative: succeeds
I/bluedroid( 3052): get_profile_interface avrcp
,E/RemoteController( 3052): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3052): classInitNative: succeeds
D/A2dpStateMachine( 3052): make
,I/bluedroid( 3052): get_profile_interface a2dp
I/GKI_LINUX( 3052): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
I/BluetoothHidServiceJni( 3052): classInitNative: succeeds
D/A2dpStateMachine( 3052): Enter Disconnected: -2
,D/BluetoothInputDevice( 3059): Proxy object connected
D/HidService( 3052): Received start request. Starting profile...
I/bluedroid( 3052): get_profile_interface hidhost
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
D/HidProfile( 3059): Bluetooth service connected
I/BluetoothHealthServiceJni( 3052): classInitNative: succeeds
,D/HealthService( 3052): Received start request. Starting profile...
,I/bluedroid( 3052): get_profile_interface health
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
I/BluetoothPanServiceJni( 3052): classInitNative(L105): succeeds
,D/BluetoothPan( 3059): BluetoothPAN Proxy object connected
D/PanService( 3052): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3052): initializeNative(L110): pan
I/bluedroid( 3052): get_profile_interface pan
D/PanProfile( 3059): Bluetooth service connected
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,I/BtGatt.JNI( 3052): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3052): handleDebugAction() action=null
D/BtGatt.GattService( 3052): Received start request. Starting profile...
D/BtGatt.GattService( 3052): start()
,I/bluedroid( 3052): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3052): advertise manager created
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,V/BluetoothMapService( 3052): BluetoothMapBinder()
,D/BluetoothMap( 3059): Proxy object connected
D/BluetoothMapService( 3052): Received start request. Starting profile...
,D/BluetoothMapService( 3052): start()
D/MapProfile( 3059): Bluetooth service connected
D/BluetoothMap( 3059): getConnectedDevices()
,D/BluetoothMap( 3059): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3052): Found 0 applications
D/BluetoothMapEmailAppObserver( 3052): createReceiver()
,D/BluetoothMapEmailAppObserver( 3052): initObservers()
D/BluetoothMapEmailAppObserver( 3052): getEnabledAccountItems()
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
D/HeadsetStateMachine( 3052): Proxy object connected
V/BluetoothMapService( 3052): Handler(): got msg=1
D/HeadsetStateMachine( 3052): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3052): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 3052): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3052): enable
I/GKI_LINUX( 3052): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3052): btu_task pending for preload complete event
I/bt_hci_bdroid( 3052): init
,I/bt_vendor( 3052): init
I/bt_vnd_conf( 3052): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3052): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3052): userial_init
,I/art     ( 1393): Explicit concurrent mark sweep GC freed 9913(568KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 592us total 20.665ms
,I/bt_userial_vendor( 3052): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3052): device fd = 53 open
D/bt_userial( 3052): Entering userial_read_thread()
,I/art     (  733): Explicit concurrent mark sweep GC freed 14243(723KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.147ms total 50.221ms
,I/bt_hwcfg( 3052): bt vendor lib: set UART baud 4000000
,D/AuthorizationBluetoothService( 1393): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  733): Killing 2382:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,D/bt_hwcfg( 3052): Chipset BCM4335C0
D/bt_hwcfg( 3052): Target name = [BCM4335C0]
I/bt_hwcfg( 3052): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  733): failed to open /acct/uid_10069/pid_2382/cgroup.procs: No such file or directory
,D/Tethering(  733): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3058): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3058): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  733): Loading config and enabling all networks 
,I/bt_hwcfg( 3052): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3052): Settlement delay -- 100 ms
I/bt_hwcfg( 3052): Setting fw settlement delay to 100 
,D/WifiService(  733): New client listening to asynchronous messages
,E/WifiConfigStore(  733): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 1796): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  733): Setting external_sim to 1
,D/WifiStateMachine(  733): Setting OUI to DA-A1-19
I/WifiNative-HAL(  733): startHal
D/wifi    (  733): setting scan oui 0x9e69ae68
D/WifiHAL (  733): Sending mac address OUI
E/WifiHAL (  733): failed to set scanning mac OUI; result = -95
,E/native  (  733): do suspend true
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring up p2p0
,D/WifiMonitor(  733): startMonitoring(p2p0) with mConnected = true
,D/WifiScanningService(  733): SCAN_AVAILABLE : 3
D/RttService(  733): SCAN_AVAILABLE : 3
,D/WifiScanningService(  733): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  733): startHal
D/wifi    (  733): getting scan capabilities on interface[1] = 0x9e69ae68
D/WifiHAL (  733): Creating message to get scan capablities; iface = 21
D/WifiHAL (  733): In GetCapabilities::handleResponse
D/WifiHAL (  733): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  733): StartedState
,D/RttService(  733): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-HAL(  733): p2pGetDeviceAddress
D/WifiNative-HAL(  733): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3058): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3052): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 3052): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3052): vendor lib fwcfg completed
,I/bt-btu  ( 3052): btu_task received preload complete event
,I/        ( 3052): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3052): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3052): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3052): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3052): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3052): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3052): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3052): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3052): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3052): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3052): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3052): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 3052): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3052): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3052): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3052): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3dd99d5 
E/bt-btm  ( 3052): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3dd99d5 
,E/bt-btif ( 3052): Calling BTA_HhEnable
E/bt-btif ( 3052): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3052): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  733): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3052): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3052): Scan Mode:20
D/BluetoothAdapterProperties( 3052): Discoverable Timeout:120
D/bte_conf( 3052): Device ID record 1 : primary
D/bte_conf( 3052):   vendorId            = 000f
D/bte_conf( 3052):   vendorIdSource      = 0001
D/bte_conf( 3052):   product             = 1200
D/bte_conf( 3052):   version             = 1436
D/bte_conf( 3052):   clientExecutableURL = 
D/bte_conf( 3052):   serviceDescription  = 
D/bte_conf( 3052):   documentationURL    = 
D/bte_conf( 3052): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3052): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3052): ScanMode =  20
D/BluetoothAdapterProperties( 3052): State =  11
D/BluetoothAdapterProperties( 3052): Setting state to 12
I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  733): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothHeadset(  733): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3052): Entering On State
,D/BluetoothHeadset( 1213): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3052): Scan Mode:21
D/BluetoothAdapterProperties( 3052): Discoverable Timeout:120
,D/BluetoothA2dp(  733): onBluetoothStateChange: up=true
,D/BluetoothMap( 3059): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=true
D/BluetoothPan( 3059): onBluetoothStateChange(on) call bindService
,D/BluetoothPbap( 3059): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3059): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  733): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  733): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3052): onReceive
D/BluetoothMapService( 3052): STATE_ON
V/BluetoothMapService( 3052): Handler(): got msg=1
D/BluetoothMapMasInstance( 3052): Map Service startRfcommSocketListener
D/BluetoothManagerService(  733): Message: 40
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3052): MAS initSocket()
D/BluetoothMapMasInstance( 3052):   masId = 00
D/BluetoothMapMasInstance( 3052):   msgTypes = 0e
D/BluetoothMapMasInstance( 3052):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3052):   SDP string = 000eSMS/MMS
,E/bt_h4   ( 3052): vendor lib postload completed
W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = c4 e8 53 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = c3 e9 10 1f 17 c0 8f 65 83 b7 ce 33 24 87 aa c2 
W/bt-btm  ( 3052): Stopping oneshot timer
I/Telecom ( 1180): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3052): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3052): Succeed to create listening socket 
,D/BluetoothMapMasInstance( 3052): Accepting socket connection...
W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = 52 5d 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = 43 8a c0 54 33 76 4e 54 5d 05 4f f1 83 14 e5 00 
W/bt-btm  ( 3052): Stopping oneshot timer
W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = 29 e6 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = c5 ed 22 97 a0 d7 f1 96 70 81 05 0f 96 54 a8 e4 
W/bt-btm  ( 3052): Stopping oneshot timer
D/HeadsetStateMachine( 3052): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3052): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3052): mNumber:  mType: 128
D/HeadsetStateMachine( 3052): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3052): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/LocalBluetoothProfileManager( 3059): Adding local A2DP profile
W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = 40 3d 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = fc 7c b6 af bd 84 f8 55 e3 c9 34 ea cc c9 45 5d 
W/bt-btm  ( 3052): Stopping oneshot timer
D/BluetoothManagerService(  733): Message: 30
,D/LocalBluetoothProfileManager( 3059): Adding local HEADSET profile
,D/BluetoothManagerService(  733): Message: 30
,W/ContextImpl( 3059): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3059): Proxy object connected
,D/A2dpProfile( 3059): Bluetooth service connected
,W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = ea 49 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = c0 60 11 5c b8 e9 03 ab 38 dc c7 e6 f6 0b ce 74 
W/bt-btm  ( 3052): Stopping oneshot timer
,D/BluetoothHeadset( 3059): Proxy object connected
D/HeadsetProfile( 3059): Bluetooth service connected
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3052): getBluetoothService() called with no BluetoothManagerCallback
,D/DockEventReceiver( 3059): finishStartingService: stopping service
,W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
,W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = 37 27 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = 2e cf b1 ef a7 d2 72 ae b1 27 28 01 1c 1a 1a 43 
W/bt-btm  ( 3052): Stopping oneshot timer
,W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = ae 6c 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = 9b 49 4c df 3e fa 07 3a 21 f7 4a 36 e7 25 0a 77 
W/bt-btm  ( 3052): Stopping oneshot timer
,D/BluetoothPbap( 3059): Proxy object connected
,D/AuthorizationBluetoothService( 1393): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/PbapServerProfile( 3059): Bluetooth service connected
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3052): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3052): Accept thread started.
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2995): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): my name is : LGE-Nexus 5_PT1108
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): attempting to connect to test coordinator
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): check test folder
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): found test : ./testFindPeers.js
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): found test : ./testReConnect.js
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): found test : ./testSendData.js
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): Test app app.js loaded
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  733): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  733): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  733): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  733): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  733): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  733): will read network variables netId=1
,E/WifiStateMachine(  733): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  733): will read network variables netId=1
,I/wpa_supplicant( 3058): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  733): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3058): PNO: In assoc process
,I/wpa_supplicant( 3058): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3058): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3058): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  733): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
E/WifiStateMachine(  733): Start Dhcp Watchdog 1
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1360): OkHttp exception
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/EventLoggerService( 1360): Unable to send logs Error code: 262146
,W/Search.LoginHelper( 1360): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1360): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/native  (  733): do suspend false
,E/WifiStateMachine(  733): scanCount==0 - aborting
,I/dhcpcd  ( 3225): version 5.5.6 starting
,E/dhcpcd  ( 3225): get_duid: Read-only file system
,I/dhcpcd  ( 3225): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/dhcpcd  ( 3225): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3225): wlan0: leased 192.168.1.114 for 86400 seconds
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,E/native  (  733): do suspend true
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  733): Adding iface wlan0 to network 100
,E/ConnectivityService(  733): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  733): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  733): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  733): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  733): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  733): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  733): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733):    accepting network in place of null
,D/ConnectivityService(  733): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  733): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 26 Nov 2015 06:49:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448520557776], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448520557748]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Validated
,D/ConnectivityService(  733): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  733): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1213): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/jxcore-log( 2995): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2995): 
,D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  733): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  733): Setting time of day to sec=1448520560
,W/AlarmManagerService(  733): Unable to set rtc to 1448520560: Invalid argument
,I/NetworkMonitor( 2521): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2521): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  733): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3309 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/iu.SyncManager( 1562): SYNC; picasa accounts
,D/NetworkLogImpl( 1562): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1562): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1562): num queued entries: 0
,I/iu.UploadsManager( 1562): num updated entries: 0
,I/iu.SyncManager( 1562): NEXT; no task
,W/ResourcesManager( 3309): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3309): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1562): Checkin interval check for package: unspecified last checkin: 1448443186671 min interval config: 0 actual interval: 77374148
,I/SystemUpdateService( 1562): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,I/CheckinService( 1562): Checking schedule, now: 1448520560827 next: 1448485353642
I/CheckinService( 1562): active receiver: enabled
,D/SystemUpdateService( 1562): onCreate
,I/CheckinService( 1562): Preparing to send checkin request
I/EventLogService( 1562): Accumulating logs since 1448518805797
,D/SystemUpdateService( 1562): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 3309): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GpsLocationProvider(  733): No APN found to select.
,I/SystemUpdateService( 1562): active receiver: enabled
,I/SystemUpdateService( 1562): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,D/GpsLocationProvider(  733): NTP server returned: 1448520557692 (Thu Nov 26 07:49:17 GMT+01:00 2015) reference: 83847 certainty: 11 system time offset: -3177
E/LocSvc_eng(  733): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,V/SystemUpdateService( 1562): retry (wakeup: false) in 3599972 ms
,I/ActivityManager(  733): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3354 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 190us total 8.357ms
,W/System  ( 3309): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3309): Installed default security provider GmsCore_OpenSSL
,I/art     (  196): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 174us total 7.621ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 182us total 8.159ms
,D/SystemUpdateService( 1562): onDestroy
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1796): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1562): [CredentialSyncAdapter] Unknown sync event.
,I/GAv4    ( 3354): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3354):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3354):   adb logcat -s GAv4
,I/CheckinRequestBuilder( 1562): Checkin reason type: 12 attempt count: 1
,D/WifiService(  733): New client listening to asynchronous messages
,W/GAv4    ( 3354): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/GCM     ( 1393): GCM config loaded
E/YouTube MDX( 3309): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/ActivityThread( 1562): Failed to find provider info for com.google.android.wearable.settings
,W/GAv4    ( 3354): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3354): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/ConnectivityChangeReceiver( 1562): Ignoring connectivity change
,D/ConnectivityService(  733): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  733): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  733): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1562): CM callback handler got msg 524290
,I/dex2oat ( 3414): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1744346161.jar --oat-fd=38 --oat-location=/data/data/com.google.android.youtube/cache/ads1744346161.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     ( 1393): Explicit concurrent mark sweep GC freed 19601(1083KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 727us total 73.899ms
,I/art     (  733): Explicit concurrent mark sweep GC freed 47833(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 1.106ms total 61.823ms
,I/dex2oat ( 3414): dex2oat took 40.320ms (threads: 4)
,I/ActivityManager(  733): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3438 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/InstanceID/Rpc( 3309): Found 10008
,I/WebViewFactory( 3354): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/ResourcesManager( 3438): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3438): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3438): VM with version 2.1.0 has multidex support
I/MultiDex( 3438): install
I/MultiDex( 3438): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3438): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/LibraryLoader( 3354): Time to load native libraries: 5 ms (timestamps 7569-7574)
I/LibraryLoader( 3354): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3354): Binding Chromium to main looper Looper (main, tid 1) {3d0220a7}
,I/LibraryLoader( 3354): Expected native library version number "",actual native library version number ""
,I/chromium( 3354): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3354): Initializing chromium process, singleProcess=true
W/art     ( 3354): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3354): ApplicationContext is null in ApplicationStatus
,W/ActivityThread( 3438): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3438): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3238dbb7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3438): Installed default security provider GmsCore_OpenSSL
,W/chromium( 3354): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3354): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3354): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3354): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/art     ( 3438): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3438): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/NativeLibraryUtils( 3438): Install completed successfully. count=13 extracted=0
,I/NSApplication( 3354): Starting up...
W/AudioManagerAndroid( 3354): Requires BLUETOOTH permission
,I/ActivityManager(  733): Killing 1772:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/WVCdm   (  185): Instantiating CDM.
,I/WVCdm   (  185): CdmEngine::OpenSession
,I/WVCdm   (  185): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  185): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  185): Service_Initialize: starts!
D/QSEECOMAPI: (  185): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  185): App is not loaded in QSEE
,D/QSEECOMAPI: (  185): Loaded image: APP id = 3
,D/DrmWidevineDash(  185): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb49d9000
E/DrmWidevineDash(  185): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb49d9000
,W/libprocessgroup(  733): failed to open /acct/uid_10045/pid_1772/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
,D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  185): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: starts! SID=0xbea87500
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_GetRandom: starts! randomData=0xb4a21070, dataLength=8
,W/DriveInitializer( 1562): Awaiting to be initialized
W/DriveInitializer( 1562): Background init thread started
,D/DrmWidevineDash(  185): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60aa600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  185): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  185): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  185): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  185): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: starts! deviceID=0xb37bc440, idLength=0xb3eff710
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: starts!
,I/GoogleURLConnFactory( 3438): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
,D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  185): PrepareKeyRequest: nonce=3681104025
D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1b01600
D/DrmWidevineDash(  185): message_length=1597, signature=0xb3c9b280, signature_length=3018847988
,I/ActivityManager(  733): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3528 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  185): CdmEngine::CloseSession
D/DrmWidevineDash(  185): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  185): L3 Terminate.
D/DrmWidevineDash(  185): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  185): Service_Uninitialize: starts!
D/QSEECOMAPI: (  185): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  185): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  185): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_Terminate: ends! returns 0
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,D/TimeService( 3528): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448520561842
D/        ( 3528): TimeServiceNative: User Time to be set is 1448520561842
D/QC-time-services( 3528): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3528): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3528): Lib:time_genoff_operation: pargs->ts_val = 1448520561842
D/QC-time-services( 3528): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448520561842
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1448520561842, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/30/70 12:40:12
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 7648812000
D/QC-time-services(  199): Daemon:new time 1448520561842 
D/QC-time-services(  199): Daemon: delta 1440871749842 genoff 1440871749842 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871749842 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871749842 to memory
,D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
,E/QC-time-services( 3528): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1132555761842
I/ActivityManager(  733): Killing 2489:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  733): failed to open /acct/uid_10003/pid_2489/cgroup.procs: No such file or directory
,I/CheckinService( 1562): Checkin interval check for package: unspecified last checkin: 1448443186671 min interval config: 0 actual interval: 77375241
,W/DriveInitializer( 1562): Background init thread ended
,I/art     ( 1562): Explicit concurrent mark sweep GC freed 14033(968KB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 22MB/29MB, paused 730us total 60.054ms
,I/dex2oat ( 3564): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=35 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  733): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3570 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/dex2oat ( 3564): dex2oat took 38.228ms (threads: 4)
,I/Adreno-EGL( 3438): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/GAv4    ( 3570): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3570):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3570):   adb logcat -s GAv4
,W/GAv4    ( 3570): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  185): CdmEngine::OpenSession
I/WVCdm   (  185): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  185): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/GAv4    ( 3570): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  185): Service_Initialize: starts!
D/QSEECOMAPI: (  185): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  185): App is not loaded in QSEE
,I/GoogleURLConnFactory( 3438): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  185): Loaded image: APP id = 3
,D/DrmWidevineDash(  185): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb49d9000
E/DrmWidevineDash(  185): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb49d9000
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: starts!
,W/GAv4    ( 3570): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  185): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: starts! SID=0xbea87500
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_GetRandom: starts! randomData=0xb6072268, dataLength=8
,D/DrmWidevineDash(  185): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60aa000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  185): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  185): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  185): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  185): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: starts! deviceID=0xb37bc440, idLength=0xb3eff710
,I/ActivityManager(  733): Killing 2356:com.google.android.gm/u0a70 (adj 15): empty #17
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
,D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  185): PrepareKeyRequest: nonce=1882289707
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1b01600
D/DrmWidevineDash(  185): message_length=1597, signature=0xb3c9b280, signature_length=3018847988
,W/libprocessgroup(  733): failed to open /acct/uid_10070/pid_2356/cgroup.procs: No such file or directory
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  185): CdmEngine::CloseSession
D/DrmWidevineDash(  185): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  185): L3 Terminate.
D/DrmWidevineDash(  185): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  185): Service_Uninitialize: starts!
D/QSEECOMAPI: (  185): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  185): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  185): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_Terminate: ends! returns 0
,W/art     ( 2636): Attempt to remove local handle scope entry from IRT, ignoring
,D/WearableService( 1310): callingUid 10008, callindPid: 1310
,E/MDM     ( 1310): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1393): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1393): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/LocationInitializer( 1562): Restart initialization of location
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1562): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/art     ( 1393): Explicit concurrent mark sweep GC freed 19983(1174KB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 19MB/33MB, paused 776us total 27.877ms
,W/GCoreFlp( 1310): No location to return for getLastLocation()
W/FusedLocationProvider( 1393): location=null
,I/art     (  733): Explicit concurrent mark sweep GC freed 21640(950KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 879us total 52.014ms
,I/WVCdm   (  185): CdmEngine::OpenSession
I/WVCdm   (  185): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  185): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  185): Service_Initialize: starts!
D/QSEECOMAPI: (  185): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  185): App is not loaded in QSEE
,D/QSEECOMAPI: (  185): Loaded image: APP id = 3
,D/DrmWidevineDash(  185): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb49d9000
E/DrmWidevineDash(  185): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb49d9000
,D/DrmWidevineDash(  185): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  185): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  185): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: starts! SID=0xbea87500
,D/DrmWidevineDash(  185): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  185): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_GetRandom: starts! randomData=0xb2e060e0, dataLength=8
,D/DrmWidevineDash(  185): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60a9a00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  185): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  185): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  185): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  185): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  185): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: starts! deviceID=0xb37bc480, idLength=0xb4bff710
,D/DrmWidevineDash(  185): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  185): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  185): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  185): hlos api version =  9
D/DrmWidevineDash(  185): tz api version =  9
D/DrmWidevineDash(  185): OEMCrypto_APIVersion: ends! returns version 9
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  185): PrepareKeyRequest: nonce=967551206
D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4ad2600
D/DrmWidevineDash(  185): message_length=1632, signature=0xb4a9d500, signature_length=3032479476
,D/DrmWidevineDash(  185): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  185): CdmEngine::CloseSession,
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  185): OEMCrypto_CloseSession: ends! returns 0
,I/WVCdm   (  185): L3 Terminate.
D/DrmWidevineDash(  185): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  185): Service_Uninitialize: starts!
D/QSEECOMAPI: (  185): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  185): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  185): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  185): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 3438): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3438): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3438): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1562): Classify the device as Phone.
,I/CheckinTask( 1562): Sending checkin request (9475 bytes)
,I/ActivityManager(  733): Killing 1932:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10002/pid_1932/cgroup.procs: No such file or directory
,I/CheckinResponseProcessor( 1562): From server: 1 gservices updates and 0 deletes
,I/CertBlacklister(  733): Certificate blacklist changed, updating...
,I/CertBlacklister(  733): Certificate blacklist updated
,I/GservicesProvider( 1393): main difference update completed
,I/ContactAccountLoggerTas( 1360): canRun() : Opted Out
,I/Babel_SMS( 1796): ApnsOta: OTA version -1
,I/ActivityManager(  733): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3646 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1562): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1562): Failed to find provider info for com.google.android.wearable.settings
,I/Search.GservicesUpdateTask( 1360): Updating Gservices keys
,E/UpdateRequestReceiver( 3646): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3646): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3646): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3646): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/art     ( 1393): Explicit concurrent mark sweep GC freed 14457(755KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 19MB/33MB, paused 1.409ms total 32.987ms
,I/ActivityManager(  733): Killing 2799:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10008/pid_2799/cgroup.procs: No such file or directory
,I/ContactAccountLoggerTas( 1360): canRun() : Opted Out
I/ContactAccountLoggerTas( 1360): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1360): canRun() : Opted Out
,I/CheckinRequestBuilder( 1562): Classify the device as Phone.
,I/art     ( 1393): Explicit concurrent mark sweep GC freed 7019(354KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 740us total 29.268ms
,I/art     ( 1562): Explicit concurrent mark sweep GC freed 16474(1202KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 22MB/37MB, paused 992us total 38.475ms
,W/SQLiteConnectionPool( 1562): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/SystemEventReceiver( 1562): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1562): Updating ocr activity enabled=false
,I/CheckinTask( 1562): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1562): Checking schedule, now: 1448520565004 next: 1448562731986
I/CheckinService( 1562): active receiver: disabled
,D/CheckinService( 1562): Recording last checkin time for package unspecified as 1448520565033
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1393): Vacuum at: now=1448520565130 tag=VacuumService
,W/ActivityManager(  733): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,I/CheckinService( 1562): Checkin interval check for package: unspecified last checkin: 1448520565033 min interval config: 0 actual interval: 126
,I/CheckinService( 1562): Checking schedule, now: 1448520565172 next: 1448562731986
,I/CheckinService( 1562): active receiver: disabled
,I/SystemUpdateService( 1562): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1562): onCreate
,D/SystemUpdateService( 1562): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/OcrModelManager( 1562): Updating downloaded model state (gservices changed)
,I/SystemUpdateService( 1562): active receiver: enabled
,D/GCM     ( 1393): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1310): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1310): DispatchingService.onCreate()
,I/art     ( 1393): Explicit concurrent mark sweep GC freed 13756(777KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/33MB, paused 1.087ms total 50.589ms
,I/SystemUpdateService( 1562): showing system update notification
,I/ValidateNoPeople(  733): skipping global notification
,D/Finsky  ( 2418): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2418): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/SystemUpdateService( 1562): retry (wakeup: false) in 3599873 ms
,D/SystemUpdateService( 1562): onDestroy
,I/GCoreUlr( 1310): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ContactAccountLoggerTas( 1360): canRun() : Opted Out
,I/art     (  733): Explicit concurrent mark sweep GC freed 23523(1045KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 953us total 51.100ms
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1393): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     ( 1310): Explicit concurrent mark sweep GC freed 17007(1067KB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 19MB/32MB, paused 1.204ms total 52.443ms
,E/DataBuffer( 1310): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@314ab4e0)
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1562): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1393): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GCoreUlr( 1310): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1310): Unbound from all location providers
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1310): DispatchingService.onDestroy()
I/GCoreUlr( 1310): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1310): Unbound from all location providers
,I/ActivityManager(  733): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3727 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3727): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3727): Created com.android.providers.calendar.CalendarAlarmManager@2e3a9894(com.android.providers.calendar.CalendarProvider2@1fe83f3d)
,E/SQLiteLog( 3727): (284) automatic index on view_events(_id)
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/CalendarProvider2( 3727): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3727): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/GetConfigurationSnapshotOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1393): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1393): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  733): Killing 2888:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10015/pid_2888/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1393):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1393): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/ActivityManager(  733): Killing 2917:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10040/pid_2917/cgroup.procs: No such file or directory
,W/PackageSettings(  733): Skipping PackageSetting{33651085 com.example.hello/10277} due to missing metadata
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,W/Launcher( 1284): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f55b332 new=com.google.android.velvet.VelvetApplication@3f55b332
,I/UpdateIcingCorporaServi( 1360): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1562): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1562): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1562): updateResources: need to parse f{com.google.android.gms}
,D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  733): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  733): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  733): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  733): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@32827983
,V/GmsNetworkLocationProvi( 1310): DISABLE
,I/GCoreNlp( 1310): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1284): Deferring update until onResume
,W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1284): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1360): UpdateCorporaTask done [took 204 ms] updated apps [took 204 ms] 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/ClearcutLoggerApiImpl( 1310): disconnect managed GoogleApiClient
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): ,
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/EventLogService( 1562): Aggregate from 1448520561007 (log), 1448518805797 (data)
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect called
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Coordinator is now connected to the server!
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/art     (  733): Explicit concurrent mark sweep GC freed 29683(1573KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.650ms total 111.824ms
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  733): Killing 2759:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  733): failed to open /acct/uid_10005/pid_2759/cgroup.procs: No such file or directory
,I/jxcore-log( 2995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector command called
I/jxcore-log( 2995): 
I/jxcore-log( 2995): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"F8:CF:C5:D9:E5
,I/jxcore-log( 2995): Start now : testSendData.js
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): check server
I/jxcore-log( 2995): 
I/jxcore-log( 2995): serverPort is 52510
I/jxcore-log( 2995): 
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2995): Stoping All
I/        ( 2995): Stopping services
I/        ( 2995): Stop Bluetooth
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2995): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2995):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2995): All stuff available and enabled
I/        ( 2995): Stoping All
I/        ( 2995): Stopping services
I/        ( 2995): Stop Bluetooth
I/        ( 2995): Starting All
I/        ( 2995): Stopping services
I/        ( 2995): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@302d2b2a
I/        ( 2995): Stopping services
I/        ( 2995): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}
I/        ( 2995): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 2995): peerDiscoveryTimer timeout value:7988
,I/        ( 2995): Stop Bluetooth
I/        ( 2995): StartBluetooth listener
I/        ( 2995): StartBluetooth listener
,D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 2995): StartBroadcasting started ok
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:07.409Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:07.410Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:07.410Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2995): Connecting to null, at 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 2015-11-26T06:55:07.416Z SendDataTCPServer.js: TCP/IP server is bound to port: 52510
I/jxcore-log( 2995): 
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 2995): We already were running, thus doing nothing
I/        ( 2995): Added local service
I/        ( 2995): Cleared service requests
I/        ( 2995): Stopped peer discovery
I/        ( 2995): Started peer discovery
I/        ( 2995): Discovery state changed to Started.
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTListenerThread( 2995): starting to listen
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): No ag scb for peer addr
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/SS      ( 2995): Found 2 peers.
I/SS      ( 2995): Peer(1): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 2995): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,W/bt-rfcomm( 3052): PORT_StartCnf failed result:5
,W/bt-btif ( 3052): invalid rfc slot id: 5
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3052): No record of the device:null
I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 9 Address: 44:80:EB:7B:5A:05 newState: 0
,I/jxcore-log( 2995): 2015-11-26T06:55:09.451Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:09.451Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:09.451Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,E/BluetoothEventManager( 3059): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
E/BluetoothBondStateMachine( 3052): In stable state, received invalid newState: 10
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/bt-btif ( 3052): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/BTListenerThread( 2995): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
,I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT6155
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/jxcore-log( 2995): 2015-11-26T06:55:09.904Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/jxcore-log( 2995): 2015-11-26T06:55:10.997Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.002Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.018Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/BTListenerThread( 2995): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT2145
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/jxcore-log( 2995): 2015-11-26T06:55:11.049Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.058Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:55:11.099Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.108Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.114Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.239Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.253Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.280Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.511Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.527Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.621Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.639Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.770Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.790Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.801Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.806Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:11.807Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.831Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.861Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.891Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:11.952Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.124Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.174Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.188Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.195Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:12.197Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.205Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.239Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.275Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.310Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.367Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.374Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.389Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.444Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.571Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.653Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.656Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.683Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.696Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.717Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.727Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.732Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.739Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.745Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.769Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.804Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.901Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.907Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.917Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.930Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:12.942Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.010Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.061Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.098Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.173Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.188Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.232Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.241Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.265Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.271Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.278Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.291Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.300Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.314Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:13.316Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.321Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.399Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.579Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.690Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.798Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.825Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.837Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.857Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.866Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.876Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.883Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.894Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.909Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.911Z SendDataTCPServer.js: TCP/IP server has received 99816 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.915Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.925Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): invalid rfc slot id: 6
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-11-26T06:55:13.942Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.946Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 2995): 2015-11-26T06:55:13.963Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:13.999Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:14.010Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:14.017Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:14.044Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:14.083Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T06:55:14.452Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:14.461Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,D/BluetoothManagerService(  733): Message: 20
D/BluetoothManagerService(  733): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c2da03e:true
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2995): 2015-11-26T06:55:19.468Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:19.469Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:19.470Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:19.471Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2995): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-l2cap( 3052): L2CAP got conn_req while connected (state:2). Reject it
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): No ag scb for peer addr
,W/bt-btif ( 3052): invalid rfc slot id: 4
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x10  CID 0x47
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3052): invalid rfc slot id: 8
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x44
,I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-11-26T06:55:24.924Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T06:55:24.927Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:24.928Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:24.928Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 2995): 2015-11-26T06:55:29.930Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:29.931Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:34.939Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:34.940Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:34.940Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:34.941Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 2995): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): No ag scb for peer addr
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
I/BTListenerThread( 2995): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
I/BTConnectToThread( 2995): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : motorola-XT1072_PT2627
I/HS      ( 2995): Hand Shake finished outgoing for : motorola-XT1072_PT2627
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-XT1072_PT2627
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-XT1072_PT2627
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-XT1072_PT2627
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 57612
I/BtConnectorHelper( 2995): Request socket is using : 57612
I/BtToRequestSocket( 2995): Now accepting connections
,I/jxcore-log( 2995): 2015-11-26T06:55:39.940Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :57612
I/jxcore-log( 2995): 2015-11-26T06:55:40.239Z SendDataConnector.js: CLIENT connected to 57612, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:40.239Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 57612
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:55:40.250Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24266
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17330
,I/jxcore-log( 2995): 2015-11-26T06:55:40.853Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.888Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.901Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.921Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.930Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.947Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.956Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2995): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:6440
,I/jxcore-log( 2995): 2015-11-26T06:55:40.974Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.977Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.985Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.994Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:40.996Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.065Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.098Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T06:55:41.122Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.130Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.139Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.148Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.212Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.224Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.235Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.247Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.250Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.257Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.261Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.278Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.313Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.315Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.355Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.359Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.364Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.369Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.406Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.412Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.445Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.455Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.484Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:41.526Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 2995): 2015-11-26T06:55:51.262Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:51.263Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:51.269Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:51.270Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:51.271Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: motorola-XT1072_PT2627
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): invalid rfc slot id: 7
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT2627
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:55:51.637Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:56.271Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:55:56.272Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1072
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT6155
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:55:58.188Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:55:58.697Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:58.705Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:58.714Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:58.718Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:58.751Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:55:58.760Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T06:56:01.281Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:01.282Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:01.285Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:01.288Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2995): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): No ag scb for peer addr
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f5124c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 10
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:56:08.705Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4d
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 5 peers.
I/SS      ( 2995): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One_M8
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2995): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT6155
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:56:21.472Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:56:21.976Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:22.045Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:22.056Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:22.124Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): invalid rfc slot id: 11
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:56:32.193Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-rfcomm( 3052): PORT_StartCnf failed result:5
E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3052): invalid rfc slot id: 12
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothMapService( 3052): onReceive
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T06:56:32.445Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:32.446Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:32.446Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1,
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 2995): 2015-11-26T06:56:37.448Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:37.449Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:42.454Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:42.455Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:42.456Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:42.456Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2995): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): No ag scb for peer addr
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One_M8
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f5124c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT6155
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC One_M8_PT6155
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/jxcore-log( 2995): 2015-11-26T06:56:43.712Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:56:44.200Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:44.207Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:44.260Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:44.269Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:44.276Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2995): waiting to accept incoming Connection
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-XT1072_PT2627
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-XT1072_PT2627
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:56:47.682Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BTConnectToThread( 2995): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : motorola-XT1072_PT2627
I/HS      ( 2995): Hand Shake finished outgoing for : motorola-XT1072_PT2627
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-XT1072_PT2627
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 39727
I/BtConnectorHelper( 2995): Request socket is using : 39727
I/BtToRequestSocket( 2995): Now accepting connections
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :39727
I/jxcore-log( 2995): 2015-11-26T06:56:48.078Z SendDataConnector.js: CLIENT connected to 39727, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:48.078Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 39727
,I/jxcore-log( 2995): 2015-11-26T06:56:48.105Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:56:48.256Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:48.269Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:48.411Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:48.445Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 7C:F9:0E:37:96:AB
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,E/BluetoothEventManager( 3059): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2995): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT4327
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:56:49.673Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:56:50.863Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:50.874Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:50.880Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:50.931Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:50.944Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:50.951Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:50.965Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:50.995Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.026Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.035Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.102Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.118Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.198Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.211Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.219Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.267Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.307Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.366Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.405Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.445Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.452Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.462Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.496Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.730Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.742Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.751Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.826Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.866Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.896Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.908Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:51.987Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T06:56:52.198Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:52.210Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:52.269Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:52.279Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:52.315Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:52.359Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 13
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT6155
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:56:54.559Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x44
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T06:56:58.184Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:58.184Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:58.186Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:58.207Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:58.208Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:58.209Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/jxcore-log( 2995): 2015-11-26T06:56:58.248Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:58.261Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:58.261Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:58.262Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2995): Connecting to A5-1, at 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 2015-11-26T06:56:58.265Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51084 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 3052): invalid rfc slot id: 15
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT2627
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:56:58.552Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-A500FU_PT4327
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-A500FU_PT4327
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 52982
I/BtConnectorHelper( 2995): Request socket is using : 52982
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :52982
I/jxcore-log( 2995): 2015-11-26T06:56:58.999Z SendDataConnector.js: CLIENT connected to 52982, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:56:59.000Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 52982
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:56:59.036Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2995): 2015-11-26T06:56:59.610Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:59.689Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2995): 2015-11-26T06:56:59.801Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:56:59.949Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2995): 2015-11-26T06:57:00.121Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:00.207Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:00.285Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:00.387Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:00.472Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): invalid rfc slot id: 16
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:57:02.379Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T06:57:10.473Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:10.474Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:10.479Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:10.479Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:10.480Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
,I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
,I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT4327,
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:57:12.594Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:57:12.982Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:12.993Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:13.002Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:13.027Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:13.032Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T06:57:15.481Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:15.482Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f5124c rs_disc_pending=0
E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2995): Found 4 peers.
I/SS      ( 2995): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 2995): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2995): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2995): 2015-11-26T06:57:20.486Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:20.487Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:20.487Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:20.488Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2995): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-A500FU_PT4327
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-A500FU_PT4327
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-A500FU_PT4327
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 37268
I/BtConnectorHelper( 2995): Request socket is using : 37268
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :37268
I/jxcore-log( 2995): 2015-11-26T06:57:21.091Z SendDataConnector.js: CLIENT connected to 37268, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:21.092Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 37268
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:57:21.115Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3052): invalid rfc slot id: 17
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:57:22.984Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-11-26T06:57:31.180Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:31.181Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:31.182Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:31.186Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:31.192Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2995): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,I/BTListenerThread( 2995): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT4327
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/jxcore-log( 2995): 2015-11-26T06:57:33.285Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T06:57:33.700Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:33.708Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:33.718Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:33.729Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-D722_PT811
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-D722_PT811
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:57:34.971Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:57:36.190Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:36.191Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T06:57:36.247Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:36.276Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:36.440Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:36.635Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:36.942Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:36.955Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:36.965Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:36.998Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.006Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.015Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.023Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.197Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.523Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.529Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.574Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.606Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.672Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.842Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.850Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.870Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.958Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:37.963Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.201Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.213Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.227Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.265Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.277Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.281Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.315Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T06:57:38.599Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.635Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.657Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.695Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.714Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.732Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.765Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:38.774Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-11-26T06:57:41.197Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:41.197Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:41.198Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:41.198Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2995): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
I/BTConnectToThread( 2995): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-A500FU_PT4327
,I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-A500FU_PT4327
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-A500FU_PT4327
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 39486
,I/BtConnectorHelper( 2995): Request socket is using : 39486
I/BtToRequestSocket( 2995): Now accepting connections
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :39486
I/jxcore-log( 2995): 2015-11-26T06:57:42.028Z SendDataConnector.js: CLIENT connected to 39486, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:42.028Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 39486
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:57:42.032Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): invalid rfc slot id: 19
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:57:43.697Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,W/bt-btif ( 3052): invalid rfc slot id: 21
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT811
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:57:49.022Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 1
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T06:57:52.117Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:52.117Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:52.119Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:52.119Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:52.120Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 83 bytes.
,I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT4327
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A500FU_PT4327
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:57:55.703Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:57:56.070Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:56.081Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:56.089Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:56.094Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:56.101Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:57:57.120Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:57:57.121Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/jxcore-log( 2995): 2015-11-26T06:58:02.121Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:02.121Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:02.122Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:02.122Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2995): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-A500FU_PT4327
,I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-A500FU_PT4327
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 34136
,I/BtConnectorHelper( 2995): Request socket is using : 34136
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :34136
I/jxcore-log( 2995): 2015-11-26T06:58:03.061Z SendDataConnector.js: CLIENT connected to 34136, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:03.062Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 34136
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:58:03.093Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-D722_PT811
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-D722_PT811
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:58:04.322Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T06:58:05.519Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:05.527Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:05.610Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:05.681Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:05.687Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): invalid rfc slot id: 22
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:58:06.111Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 2995): 2015-11-26T06:58:13.167Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:13.168Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:13.169Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:13.170Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:13.171Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
,I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 24
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT811
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:58:14.936Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x44
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT4327
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:58:16.242Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:58:16.608Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:16.612Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:16.624Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:16.633Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:18.171Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:18.172Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/jxcore-log( 2995): 2015-11-26T06:58:23.180Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:23.181Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:23.182Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:23.182Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 2995): Connecting to A5-1, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3052): process_service_search_attr_rsp,
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
I/BTConnectToThread( 2995): got MESSAGE_READ 83 bytes.
,I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-A500FU_PT4327
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-A500FU_PT4327
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 49150
I/BtConnectorHelper( 2995): Request socket is using : 49150
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :49150
I/jxcore-log( 2995): 2015-11-26T06:58:23.970Z SendDataConnector.js: CLIENT connected to 49150, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:23.971Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 49150
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:58:23.996Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BTListenerThread( 2995): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-D722_PT811
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-D722_PT811
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/jxcore-log( 2995): 2015-11-26T06:58:26.314Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:58:26.727Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:26.742Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:26.760Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
,I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): invalid rfc slot id: 26
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT4327
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T06:58:28.070Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T06:58:34.080Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:34.081Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:34.082Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:34.102Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:34.103Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:34.104Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/BtConnectorHelper( 2995): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/jxcore-log( 2995): 2015-11-26T06:58:34.140Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:34.140Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:34.141Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:34.141Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2995): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 2015-11-26T06:58:34.144Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51414 rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,W/bt-btif ( 3052): invalid rfc slot id: 27
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT811
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-11-26T06:58:36.741Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x4e
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:cf:c5:d9:e5:61]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : motorola-Nexus 6_PT2145
I/HS      ( 2995): Hand Shake finished outgoing for : motorola-Nexus 6_PT2145
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 34428
I/BtConnectorHelper( 2995): Request socket is using : 34428
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :34428
I/jxcore-log( 2995): 2015-11-26T06:58:38.928Z SendDataConnector.js: CLIENT connected to 34428, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:38.929Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 34428
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:58:38.965Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2995): 2015-11-26T06:58:39.460Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15796
,I/jxcore-log( 2995): 2015-11-26T06:58:39.527Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:39.558Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 2995): 2015-11-26T06:58:39.562Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:39.602Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:39.673Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:39.726Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:39.731Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:39.766Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
,I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-13ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 1
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BTListenerThread( 2995): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-D722_PT811
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-D722_PT811
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:58:48.414Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:48.898Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:48.952Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:48.981Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:49.036Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:49.060Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:49.091Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:49.766Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:49.767Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:49.770Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:49.771Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:49.772Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: motorola-Nexus 6_PT2145
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8186","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8186","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT8186, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT8186, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T06:58:54.771Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:54.772Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 2995): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2159, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2159, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8186","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,W/bt-btif ( 3052): invalid rfc slot id: 29
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT811
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT811
I/BtToSocketBase( 2995): Close LocalOutputStream
,I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-11-26T06:58:58.869Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:58:59.779Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:59.780Z SendDataConnector.js: Connect (retry count 1) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:59.781Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:58:59.781Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2995): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x45
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : motorola-Nexus 6_PT2145
,I/HS      ( 2995): Hand Shake finished outgoing for : motorola-Nexus 6_PT2145
I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 43382
,I/BtConnectorHelper( 2995): Request socket is using : 43382
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :43382
I/jxcore-log( 2995): 2015-11-26T06:59:02.270Z SendDataConnector.js: CLIENT connected to 43382, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:02.271Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 43382
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:59:02.296Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/jxcore-log( 2995): 2015-11-26T06:59:12.360Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:12.360Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:12.360Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:12.360Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:12.361Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: F8:95:C7:87:85:54
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,E/BluetoothEventManager( 3059): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-D722_PT811
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-D722_PT811
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-11-26T06:59:13.125Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T06:59:13.498Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:59:13.511Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:59:13.518Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:59:13.549Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2995): 2015-11-26T06:59:17.360Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:17.361Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T06:59:22.366Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:22.367Z SendDataConnector.js: Connect (retry count 2) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:22.367Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:22.368Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2995): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): invalid rfc slot id: 31
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT811
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT811
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-11-26T06:59:23.525Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 2995): HandshakeOk : motorola-Nexus 6_PT2145
I/HS      ( 2995): Hand Shake finished outgoing for : motorola-Nexus 6_PT2145
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-Nexus 6_PT2145
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 53764
I/BtConnectorHelper( 2995): Request socket is using : 53764
I/BtToRequestSocket( 2995): Now accepting connections
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f515dc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x49
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :53764
I/jxcore-log( 2995): 2015-11-26T06:59:24.490Z SendDataConnector.js: CLIENT connected to 53764, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:24.490Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 53764
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:59:24.518Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T06:59:34.581Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:34.582Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:59:34.590Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:34.591Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:34.592Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2995): 2015-11-26T06:59:39.606Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:39.608Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T06:59:44.612Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:44.613Z SendDataConnector.js: Connect (retry count 3) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:44.614Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:44.614Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2995): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:cf:c5:d9:e5:61]: 6, f, 410d
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : motorola-Nexus 6_PT2145
I/HS      ( 2995): Hand Shake finished outgoing for : motorola-Nexus 6_PT2145
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 49245
I/BtConnectorHelper( 2995): Request socket is using : 49245
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :49245
I/jxcore-log( 2995): 2015-11-26T06:59:46.630Z SendDataConnector.js: CLIENT connected to 49245, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:46.631Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 49245
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T06:59:46.682Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/jxcore-log( 2995): 2015-11-26T06:59:56.727Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:56.728Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:56.729Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:56.730Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T06:59:56.731Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
,I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
,I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-11-26T07:00:01.731Z SendDataConnector.js: re-try now : F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:01.732Z SendDataConnector.js: ReStart called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 2995): 2015-11-26T07:00:06.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:06.737Z SendDataConnector.js: Connect (retry count 4) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:06.738Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:06.738Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:CF:C5:D9:E5:61, name: Nexus 6
,I/        ( 2995): Connecting to Nexus 6, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : motorola-Nexus 6_PT2145
I/HS      ( 2995): Hand Shake finished outgoing for : motorola-Nexus 6_PT2145
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-Nexus 6_PT2145
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 57692
I/BtConnectorHelper( 2995): Request socket is using : 57692
,I/BtToRequestSocket( 2995): Now accepting connections
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :57692
,I/jxcore-log( 2995): 2015-11-26T07:00:08.442Z SendDataConnector.js: CLIENT connected to 57692, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:08.445Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 57692
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T07:00:08.488Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2995): 2015-11-26T07:00:18.561Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:18.562Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:00:18.567Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:00:18.584Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:18.585Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:18.585Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/BtConnectorHelper( 2995): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/jxcore-log( 2995): 2015-11-26T07:00:18.619Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : F8:CF:C5:D9:E5:61, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:00:18.620Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:18.621Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:18.621Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 2015-11-26T07:00:18.624Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f50ebc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/SS      ( 2995): Found 3 peers.
I/SS      ( 2995): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 5 peers.
I/SS      ( 2995): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 5 peers.
I/SS      ( 2995): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x22  CID 0x4b
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 37
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:00:49.655Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:49.655Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:49.656Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2995): 2015-11-26T07:00:54.657Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:54.658Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:00:59.662Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:59.663Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:59.664Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:00:59.664Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): No ag scb for peer addr
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2995): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtConnection( 2995): connectionTimeoutTimer
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3052): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:38, channel:-1
,I/CONNEC  ( 2995): Error: Cancelled
I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:01:59.692Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:01:59.692Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:01:59.696Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,W/jxcore-log( 2995): $$jxcore_callback_38 wasn't registered
W/jxcore-log( 2995): 
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3052): invalid rfc slot id: 38
,I/jxcore-log( 2995): 2015-11-26T07:02:04.700Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:04.701Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:02:09.705Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:09.706Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:09.706Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:09.707Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 39
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:02:40.627Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:40.628Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:40.629Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:02:45.629Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:45.630Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:02:50.633Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:50.634Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:50.635Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:50.635Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x9  CID 0x41
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 40
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:02:52.850Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:52.850Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:52.850Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT811, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT811, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 2995): 2015-11-26T07:02:57.850Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:02:57.851Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:03:02.856Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:02.857Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:02.858Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:02.858Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 5 peers.
I/SS      ( 2995): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x22  CID 0x4d
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 41
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:03:34.067Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:34.068Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:03:34.084Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:34.087Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:03:34.093Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:03:34.100Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:03:34.101Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 42
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:03:35.951Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:35.952Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:03:35.953Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:03:40.966Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:40.968Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT2145, peerAddress: F8:CF:C5:D9:E5:61
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT2145, WifiDirectName: , WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:03:45.974Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:45.975Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:45.976Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:45.976Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 43
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:03:47.430Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:47.431Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:47.432Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:03:52.432Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:52.434Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(6): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2627, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2627, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 2995): 2015-11-26T07:03:57.437Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:57.438Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:57.439Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:57.439Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 44
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:03:57.668Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:57.669Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:03:57.669Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:04:02.671Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:02.671Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 11 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 2995): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:04:07.672Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:07.673Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:07.674Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:07.674Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 45
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:04:07.914Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:07.915Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:07.916Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:04:12.917Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:12.917Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:17.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:17.918Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:17.918Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:17.918Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 46
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:04:18.145Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:18.146Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:18.162Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:18.165Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:18.168Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:18.169Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:18.169Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 47
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:04:19.130Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:19.131Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:19.131Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/UdcCache:FPQuery( 1562): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1393): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T07:04:24.133Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:24.133Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:29.135Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:29.135Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:29.135Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:29.135Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 48
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:04:32.187Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:32.188Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:32.189Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:04:37.190Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:37.191Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:42.194Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:42.195Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:42.195Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:42.196Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 49
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:04:42.975Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:42.994Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:42.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:04:47.997Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:47.998Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:04:52.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:52.999Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:52.999Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:52.999Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 50
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:04:53.710Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:53.711Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:53.711Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:04:58.712Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:04:58.712Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/jxcore-log( 2995): 2015-11-26T07:05:03.715Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:03.716Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:03.717Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:03.717Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 51
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:05:04.649Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:04.650Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:04.667Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:04.669Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:04.672Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:04.678Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:04.679Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 2995): Connecting to null, at E0:DB:10:1F:C9:5E
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51cfc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N9005_PT4166
,I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N9005_PT4166
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 45044
I/BtConnectorHelper( 2995): Request socket is using : 45044
,I/BtToRequestSocket( 2995): Now accepting connections
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :45044
I/jxcore-log( 2995): 2015-11-26T07:05:07.439Z SendDataConnector.js: CLIENT connected to 45044, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:07.440Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 45044
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T07:05:07.461Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51cfc rs_disc_pending=0
,W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-11-26T07:05:08.402Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:08.609Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 2995): 2015-11-26T07:05:09.723Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:09.916Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:10.089Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:10.146Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T07:05:10.576Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:10.708Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:10.739Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-11-26T07:05:20.738Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:20.739Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:20.740Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:20.741Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:20.742Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2995): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 2995): 2015-11-26T07:05:25.742Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:05:25.743Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2995): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2627, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2627, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/jxcore-log( 2995): 2015-11-26T07:05:30.749Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:30.750Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:30.751Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:30.751Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 2995): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 2995): Starting to connect
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [e0:db:10:1f:c9:5e]: 6, f, 410d
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N9005_PT4166
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N9005_PT4166
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 58922
I/BtConnectorHelper( 2995): Request socket is using : 58922
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :58922
I/jxcore-log( 2995): 2015-11-26T07:05:32.971Z SendDataConnector.js: CLIENT connected to 58922, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:32.972Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 58922
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T07:05:32.995Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 2995): 2015-11-26T07:05:43.054Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:43.055Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:43.056Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:43.057Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:43.058Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT811, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT811, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-11-26T07:05:48.057Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:48.058Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
,I/SS      ( 2995): Peer(3): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 2995): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:05:53.064Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:53.065Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:53.065Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:53.066Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 2995): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N9005_PT4166
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N9005_PT4166
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 44089
I/BtConnectorHelper( 2995): Request socket is using : 44089
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :44089
I/jxcore-log( 2995): 2015-11-26T07:05:54.999Z SendDataConnector.js: CLIENT connected to 44089, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:05:55.000Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 44089
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T07:05:55.025Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 2995): 2015-11-26T07:06:05.094Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:05.095Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:05.096Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:05.096Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:05.098Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): Stop ReceivingThread
,I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
,I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-11-26T07:06:10.098Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:10.099Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,I/jxcore-log( 2995): 2015-11-26T07:06:15.102Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:15.107Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:15.108Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:15.111Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 2995): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N9005_PT4166
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N9005_PT4166
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 42050
I/BtConnectorHelper( 2995): Request socket is using : 42050
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :42050
I/jxcore-log( 2995): 2015-11-26T07:06:17.110Z SendDataConnector.js: CLIENT connected to 42050, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:17.111Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 42050
I/BtToRequestSocket( 2995): Set local streams
,I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T07:06:17.136Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
,W/bt-btif ( 3052): proc dm_pm_timer expires
,I/jxcore-log( 2995): 2015-11-26T07:06:27.209Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:27.210Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:27.211Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:27.211Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:27.212Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N9005_PT4166
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
,I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/jxcore-log( 2995): 2015-11-26T07:06:32.213Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:32.214Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,I/jxcore-log( 2995): 2015-11-26T07:06:37.216Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:37.217Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:37.218Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:37.218Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:1F:C9:5E, name: Note3-1
,I/        ( 2995): Connecting to Note3-1, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N9005_PT4166
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N9005_PT4166
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N9005_PT4166
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 38254
I/BtConnectorHelper( 2995): Request socket is using : 38254
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :38254
,I/jxcore-log( 2995): 2015-11-26T07:06:38.662Z SendDataConnector.js: CLIENT connected to 38254, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:38.671Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 38254
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T07:06:38.691Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51cfc rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/jxcore-log( 2995): 2015-11-26T07:06:48.751Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:48.752Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:48.756Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:48.772Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:48.772Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:48.777Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2995): Close LocalOutputStream
,I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out,
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/jxcore-log( 2995): 2015-11-26T07:06:48.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:48.829Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:48.829Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:48.829Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 2015-11-26T07:06:48.833Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f51cfc rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 57
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:06:59.032Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:06:59.040Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:06:59.041Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:07:04.042Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:04.043Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:09.046Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:09.047Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:09.048Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:09.048Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2995): Starting to connect
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 58
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:07:14.224Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:14.224Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:14.224Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:07:19.225Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:19.226Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:07:24.229Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:24.230Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:24.230Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:24.231Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 3 peers.
I/SS      ( 2995): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 59
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:07:29.404Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:29.404Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:29.404Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-11-26T07:07:34.404Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:34.405Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:39.407Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:39.408Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:39.409Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:39.409Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 60
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:07:44.583Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:44.584Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:44.584Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:49.585Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:49.586Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
,W/bt-btm  ( 3052): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=2
E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [34:fc:ef:9d:93:0b]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test's G2
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,E/BluetoothEventManager( 3059): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-D802_PT944
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-D802_PT944
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T07:07:51.712Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.716Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.725Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.734Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.743Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.778Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.791Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.830Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.844Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.878Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.889Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.926Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.944Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.950Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:52.987Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:53.001Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:53.036Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:07:54.589Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:54.589Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:54.590Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:07:54.590Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 62
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:08:04.635Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:04.636Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:08:04.653Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:04.655Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 7C:F9:0E:51:18:22, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:04.658Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:04.659Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:04.659Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:34:8A:A0
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: Connection to 7C:F9:0E:51:18:22 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 63
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:08:09.817Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:09.817Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:09.818Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/UsageStatsService(  733): User[0] Flushing usage stats to disk
,I/jxcore-log( 2995): 2015-11-26T07:08:14.820Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:14.820Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:08:19.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:19.827Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:19.827Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:19.828Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 64
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:08:25.006Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:25.007Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:25.007Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2995): Found 4 peers.
I/SS      ( 2995): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-11-26T07:08:30.007Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:30.008Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/        ( 2995): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 2995): 2015-11-26T07:08:35.010Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:35.011Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:35.012Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:35.012Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 65
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:08:40.192Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:40.193Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:40.193Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/SS      ( 2995): Found 5 peers.
I/SS      ( 2995): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/        ( 2995): Started service discovery
,I/jxcore-log( 2995): 2015-11-26T07:08:45.194Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:45.194Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 2995): 2015-11-26T07:08:50.198Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:50.199Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:50.200Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:50.200Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 66
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:08:55.373Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:55.373Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:08:55.373Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 2995): 2015-11-26T07:09:00.374Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:00.375Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:09:05.378Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:05.379Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:05.379Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:05.380Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 2995): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(3): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 2995): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 67
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:09:10.554Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:10.554Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:10.556Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:10.557Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 7C:F9:0E:34:8A:A0, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:10.558Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:10.558Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:10.559Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: Connection to 7C:F9:0E:34:8A:A0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 68
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:09:15.707Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:15.707Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:15.708Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=1
,W/bt-btif ( 3052): invalid rfc slot id: 33
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/BluetoothMapService( 3052): onReceive
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT944
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T07:09:17.168Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test's G2
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 2995): 2015-11-26T07:09:20.708Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:20.709Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test's G2
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3052): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 2995): got MESSAGE_READ 76 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-D802_PT944
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-D802_PT944
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
,I/jxcore-log( 2995): 2015-11-26T07:09:25.478Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T07:09:25.710Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:25.711Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:25.711Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:25.711Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3052): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3052): Entering PendingCommandState State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3052): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
D/BluetoothAdapterProperties( 3052): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3052): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3052): StableState(): Entering Off State
,W/BluetoothEventManager( 3059): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3059): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-XT1039_PT186
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-XT1039_PT186
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 52510
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-11-26T07:09:27.001Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:09:27.895Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:27.902Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:27.914Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.002Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.070Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.110Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.122Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.186Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.199Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.237Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.257Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.349Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.386Z SendDataTCPServer.js: TCP/IP server has received 24576 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.398Z SendDataTCPServer.js: TCP/IP server has received 26556 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.407Z SendDataTCPServer.js: TCP/IP server has received 28536 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.488Z SendDataTCPServer.js: TCP/IP server has received 30516 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.499Z SendDataTCPServer.js: TCP/IP server has received 32496 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.608Z SendDataTCPServer.js: TCP/IP server has received 34476 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.621Z SendDataTCPServer.js: TCP/IP server has received 36456 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.703Z SendDataTCPServer.js: TCP/IP server has received 38436 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.710Z SendDataTCPServer.js: TCP/IP server has received 40416 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.721Z SendDataTCPServer.js: TCP/IP server has received 42396 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.780Z SendDataTCPServer.js: TCP/IP server has received 44376 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.788Z SendDataTCPServer.js: TCP/IP server has received 46356 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.796Z SendDataTCPServer.js: TCP/IP server has received 48336 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.804Z SendDataTCPServer.js: TCP/IP server has received 50316 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.841Z SendDataTCPServer.js: TCP/IP server has received 52296 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.873Z SendDataTCPServer.js: TCP/IP server has received 54276 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.904Z SendDataTCPServer.js: TCP/IP server has received 56256 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.938Z SendDataTCPServer.js: TCP/IP server has received 58236 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.945Z SendDataTCPServer.js: TCP/IP server has received 60216 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:28.985Z SendDataTCPServer.js: TCP/IP server has received 62196 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.072Z SendDataTCPServer.js: TCP/IP server has received 64176 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.111Z SendDataTCPServer.js: TCP/IP server has received 66156 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.133Z SendDataTCPServer.js: TCP/IP server has received 68136 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.221Z SendDataTCPServer.js: TCP/IP server has received 70116 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.269Z SendDataTCPServer.js: TCP/IP server has received 72096 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.310Z SendDataTCPServer.js: TCP/IP server has received 74076 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.319Z SendDataTCPServer.js: TCP/IP server has received 76056 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.402Z SendDataTCPServer.js: TCP/IP server has received 78036 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.439Z SendDataTCPServer.js: TCP/IP server has received 80016 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.459Z SendDataTCPServer.js: TCP/IP server has received 81996 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.483Z SendDataTCPServer.js: TCP/IP server has received 83976 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.544Z SendDataTCPServer.js: TCP/IP server has received 85956 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.554Z SendDataTCPServer.js: TCP/IP server has received 87936 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.594Z SendDataTCPServer.js: TCP/IP server has received 89916 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.602Z SendDataTCPServer.js: TCP/IP server has received 91896 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.632Z SendDataTCPServer.js: TCP/IP server has received 93876 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.776Z SendDataTCPServer.js: TCP/IP server has received 95856 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:29.786Z SendDataTCPServer.js: TCP/IP server has received 97836 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-11-26T07:09:29.905Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): dm_pm_timer expires
W/bt-btif ( 3052): dm_pm_timer expires 0
W/bt-btif ( 3052): proc dm_pm_timer expires
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 70
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:09:35.386Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:35.387Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:35.388Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,W/bt-btif ( 3052): invalid rfc slot id: 69
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT186
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T07:09:40.080Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:09:40.389Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:40.390Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,W/bt-rfcomm( 3052): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3052): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-11-26T07:09:45.392Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:45.393Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:45.394Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:45.394Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 72
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:09:50.568Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:50.569Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:50.570Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:09:55.571Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:09:55.571Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:10:00.575Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:00.576Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:00.576Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:00.577Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): SDP - Rcvd L2CAP disc cfm, unknown CID: 0x46
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 73
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:10:05.755Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:05.755Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:05.756Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:10:10.757Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:10.757Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:10:15.760Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:15.761Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:15.762Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:15.762Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 74
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:10:20.948Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:20.948Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:10:20.950Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:20.951Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:20.952Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:20.952Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:20.952Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2995): Connecting to null, at B4:CE:F6:AB:A4:6A
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 75
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:10:26.099Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:26.099Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:26.100Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:10:31.101Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:31.102Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-11-26T07:10:36.112Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:10:36.112Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:36.118Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:36.118Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2995): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3052): invalid rfc slot id: 76
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:10:41.292Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:41.292Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:41.292Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:10:46.293Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:46.294Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:10:51.298Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:51.298Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:51.299Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:51.299Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2995): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3052): invalid rfc slot id: 77
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:10:56.473Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:56.474Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:10:56.474Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f517a4 rs_disc_pending=1
,W/bt-btif ( 3052): invalid rfc slot id: 61
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT944
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-11-26T07:10:59.177Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test's G2
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:11:01.475Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:01.475Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:11:06.480Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:06.480Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:06.481Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:06.481Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2995): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 78
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:11:08.791Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:08.792Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:08.815Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:11:13.817Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:13.825Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:11:18.826Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:18.826Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:18.826Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:18.826Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 2995): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3052): invalid rfc slot id: 79
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:11:19.530Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:19.531Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:19.554Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:19.557Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:19.561Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:19.562Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:19.562Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 2995): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f5241c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,W/bt-btif ( 3052): new conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3052): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f5241c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2995): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : motorola-XT1039_PT186
I/HS      ( 2995): Hand Shake finished outgoing for : motorola-XT1039_PT186
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, motorola-XT1039_PT186
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 52169
I/BtConnectorHelper( 2995): Request socket is using : 52169
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :52169
I/jxcore-log( 2995): 2015-11-26T07:11:22.126Z SendDataConnector.js: CLIENT connected to 52169, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:22.127Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 52169
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-11-26T07:11:22.153Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24266
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:22280
,I/jxcore-log( 2995): 2015-11-26T07:11:22.945Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:22.982Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12380
,I/jxcore-log( 2995): 2015-11-26T07:11:23.231Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:23.441Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3052): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2480
,I/jxcore-log( 2995): 2015-11-26T07:11:23.868Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:23.957Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:24.027Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:11:24.445Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:24.521Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:24.549Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:24.550Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:24.566Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:24.567Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/BtConnectorHelper( 2995): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/jxcore-log( 2995): 2015-11-26T07:11:24.591Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:24.600Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:24.601Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:24.601Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:75:41
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3052): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f5241c rs_disc_pending=1
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 81
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:11:27.188Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:27.189Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:27.190Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): tBTM_SEC_DEV:0xa3f5241c rs_disc_pending=0
W/bt-btif ( 3052): bta_dm_check_av:0
,W/bt-btif ( 3052): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3052): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:11:32.191Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:32.192Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 2995): 2015-11-26T07:11:37.195Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:37.195Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:37.196Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:37.196Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 82
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:11:38.654Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:38.655Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:38.655Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2627, peerAddress: 44:80:EB:7B:5A:05
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2627, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:11:43.657Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:43.658Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): dun
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): weAreDoneNow , resultArray.length: 1
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): done, now sending data to server
I/jxcore-log( 2995): 
I/jxcore-log( 2995): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): -- RESULT DATA {"name:":"LGE-Nexus 5_PT1108","time":1000065,"result":"TIMEOUT","sendList":[{"name":"F4:F1:E1:5C:3B:E2","time":4988,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"50:2E:6C:AC:21:50","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections":0,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":1,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":1,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":1,"nam
,I/jxcore-log( 2995): sendList : 100% : 4988 ms, 99% : 4988 ms, 95 : 4988 ms, 90% : 4988 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Result count 1, range 4988 ms to  4988 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): sendList failed peers count : 12 [92.3076923076923 %]
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : F8:CF:C5:D9:E5:61, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 7C:F9:0E:51:18:22, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): sendList never tried peers count : 7 [35 %]
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 50:2E:6C:AC:21:50
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:47.514Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:11:47.515Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-11-26T07:11:48.662Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:48.663Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:48.663Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:48.664Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 83
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-11-26T07:11:51.465Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:51.466Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:51.466Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-11-26T07:11:56.467Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:11:56.468Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:12:01.469Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:01.470Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:01.470Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:01.470Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  733): Explicit concurrent mark sweep GC freed 79612(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/43MB, paused 4.561ms total 90.910ms
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 84
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:12:02.984Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:02.985Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:02.985Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:12:07.986Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:07.987Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-11-26T07:12:12.990Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:12.991Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:12.992Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:12.992Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:75:41, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3052): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3052): info:x10
,D/        ( 3052): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3052): process_service_search_attr_rsp
,E/bt-btif ( 3052): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3052): invalid rfc slot id: 85
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-11-26T07:12:13.186Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-11-26T07:12:13.186Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:12:13.187Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:12:13.188Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3052): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3052): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2627, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2627, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(6): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/        ( 2995): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2627, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2627, WifiDirectName: XT1072_23d5, WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,W/bt-smp  ( 3052): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3052): Plain text(LSB ~ MSB) = 04 f8 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3052): Encrypted text(LSB ~ MSB) = 37 e0 be f4 c5 c7 81 e9 c6 dd a3 e3 ca a5 aa 77 
W/bt-btm  ( 3052): Stopping oneshot timer
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 2995): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2995): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 4 peers.
I/SS      ( 2995): Peer(1): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3058): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3058): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 2995): DBG, CoordinatorConnector command called
I/jxcore-log( 2995): 
I/jxcore-log( 2995): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): stop tests now !
I/jxcore-log( 2995): 
I/jxcore-log( 2995): stop current!
I/jxcore-log( 2995): 
I/jxcore-log( 2995): testSendData stopped
I/jxcore-log( 2995): 
I/        ( 2995): Stoping All
I/        ( 2995): Stopping services
I/        ( 2995): Stopping services
,I/wpa_supplicant( 3058): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3058): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 2995): Stop Bluetooth
I/        ( 2995): Stop Bluetooth
I/BTListenerThread( 2995): Stopped
,I/jxcore-log( 2995): StopBroadcasting went ok
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-11-26T07:16:07.398Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2995): 
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2995): Cleared local services
I/        ( 2995): Cleared service requests
I/        ( 2995): Stopped peer discovery
,I/jxcore-log( 2995): DBG, CoordinatorConnector command called
I/jxcore-log( 2995): 
I/jxcore-log( 2995): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":4988,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:37:96:AB\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:9D:93:0B\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:51:18:22\",\"time\":0,\"result\":\"Fail
I/jxcore-log( 2995): ****TEST TOOK:  ms ****
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2995): 
I/jxcore-log( 2995): stop tests now !
I/jxcore-log( 2995): 
I/jxcore-log( 2995): end, event received
I/jxcore-log( 2995): 
I/jxcore-log( 2995): CoordinatorConnector close called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2995): 
I/jxcore-log( 2995): The Coordinator has disconnected!
I/jxcore-log( 2995): 
I/jxcore-log( 2995): The Coordinator has closed!
I/jxcore-log( 2995): 
I/jxcore-log( 2995): stop tests now !
I/jxcore-log( 2995): 
I/jxcore-log( 2995): turning Radios off
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Toggling radios to false
I/jxcore-log( 2995): 
D/BluetoothManagerService(  733): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  733): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@251b7916 mBinding = false
,D/BluetoothManagerService(  733): Message: 2
D/BluetoothManagerService(  733): Sending off request.
,D/BluetoothAdapterState( 3052): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3052): Setting state to 13
I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3052): onBluetoothDisable()
I/BluetoothAdapterState( 3052): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3052): Scan Mode:20
,D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3052): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3052): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3052): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3052): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3052): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3052): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3052): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  733): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3052): onReceive
D/BluetoothMapService( 3052): STATE_TURNING_OFF
V/BluetoothMapService( 3052): Handler(): got msg=4
D/BluetoothMapService( 3052): MAP Service closeService in
D/BluetoothMapMasInstance( 3052): MAP Service shutdown
V/BluetoothMapService( 3052): MAP Service closeService out
,I/BtOppRfcommListener( 3052): stopping Accept Thread
,I/BtOppRfcommListener( 3052): BluetoothSocket listen thread finished
,W/ContextImpl( 3059): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/WifiService(  733): setWifiEnabled: false pid=2995, uid=10270
E/WifiService(  733): Invoking mWifiStateMachine.setWifiEnabled
,D/DockEventReceiver( 3059): finishStartingService: stopping service
,E/WifiStateMachine(  733): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 2995): Radios toggled
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
E/native  (  733): do suspend true
D/AuthorizationBluetoothService( 1393): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 3059): Proxy object disconnected
,D/PbapServerProfile( 3059): Bluetooth service disconnected
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1393): Read error: ssl=0xaf98c400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1393): SSL shutdown failed: ssl=0xaf98c400: I/O error during system call, Broken pipe
,D/ConnectivityService(  733): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/bt_userial( 3052): RX termination
W/bt_userial( 3052): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3052): Leaving userial_read_thread()
,W/bt-btif ( 3052): ag scb idx 1 not allocated
E/bt-btif ( 3052): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3052): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 3052): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 3052): hw_epilog_process
,I/bt_userial_vendor( 3052): device fd = 53 close
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/GKI_LINUX( 3052): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3052): GKI_exit_task 0 done
I/GKI_LINUX( 3052): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3052): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/HeadsetStateMachine( 3052): Exit Disconnected: -1
,D/BluetoothHeadset( 1213): Proxy object disconnected
,D/BluetoothHeadset( 1180): Proxy object disconnected
D/BluetoothHeadset(  733): Proxy object disconnected
,D/A2dpService( 3052): Received stop request...Stopping profile...
,D/A2dpStateMachine( 3052): Exit Disconnected: -1
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,D/BluetoothHeadset( 1180): Proxy object disconnected
,D/HidService( 3052): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,D/HeadsetStateMachine( 3052): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3052): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3052): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothA2dp(  733): Proxy object disconnected
,D/BluetoothAdapterState( 3052): Stopping profile services that were post enabled
,D/HealthService( 3052): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,I/GKI_LINUX( 3052): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3052): GKI_exit_task 2 done
I/GKI_LINUX( 3052): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3052): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3052): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3052): Cleaning up Bluetooth GID callback object
,D/PanService( 3052): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,D/BtGatt.DebugUtils( 3052): handleDebugAction() action=null
,D/BtGatt.GattService( 3052): Received stop request...Stopping profile...
D/BtGatt.GattService( 3052): stop()
D/BtGatt.AdvertiseManager( 3052): advertise clients cleared
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
,D/BluetoothMapService( 3052): Received stop request...Stopping profile...
D/BluetoothMapService( 3052): stop()
,D/BluetoothHeadset( 3059): Proxy object disconnected
D/HeadsetProfile( 3059): Bluetooth service disconnected
,D/BluetoothMapEmailAppObserver( 3052): deinitObservers()
D/BluetoothMapEmailAppObserver( 3052): removeReceiver()
,D/BluetoothAdapterService( 3052): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f55b332
D/BluetoothA2dp( 3059): Proxy object disconnected
,D/A2dpProfile( 3059): Bluetooth service disconnected
,W/BluetoothHealthServiceJni( 3052): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3052): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3052): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3052): Cleaning up Bluetooth PAN callback object
,E/WifiConfigStore(  733): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  733): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/BluetoothInputDevice( 3059): Proxy object disconnected
D/HidProfile( 3059): Bluetooth service disconnected
,V/BluetoothMapService( 3052): Handler(): got msg=4
D/BluetoothMapService( 3052): MAP Service closeService in
V/BluetoothMapService( 3052): MAP Service closeService out
D/BluetoothAdapterState( 3052): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3052): Setting state to 10
D/BluetoothMapService( 3052): cleanup()
I/BluetoothAdapterState( 3052): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3052): MAP Service closeService in
V/BluetoothMapService( 3052): MAP Service closeService out
,D/BluetoothPan( 3059): BluetoothPAN Proxy object disconnected
D/PanProfile( 3059): Bluetooth service disconnected
D/BluetoothManagerService(  733): Message: 60
D/BluetoothManagerService(  733): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  733): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset(  733): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3052): Entering OffState
,D/BluetoothMap( 3059): Proxy object disconnected
D/MapProfile( 3059): Bluetooth service disconnected
,E/WifiStateMachine(  733): scanCount==0 - aborting
D/BluetoothHeadset( 1213): onBluetoothStateChange: up=false
D/BluetoothA2dp(  733): onBluetoothStateChange: up=false
D/WifiNetworkAgent(  733): NetworkAgent: NetworkAgent channel lost
,D/BluetoothA2dp( 3059): onBluetoothStateChange: up=false
,E/native  (  733): do suspend true
,D/WifiScanningService(  733): SCAN_AVAILABLE : 1
D/RttService(  733): SCAN_AVAILABLE : 1
,D/WifiScanningService(  733): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  733): DefaultState
,D/RttService(  733): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/BluetoothMap( 3059): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1180): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3059): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3059): onBluetoothStateChange: up=false
D/AndroidRuntime( 4244): 
D/AndroidRuntime( 4244): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothInputDevice( 3059): onBluetoothStateChange: up=false
,D/AndroidRuntime( 4244): CheckJNI is OFF
,D/BluetoothManagerService(  733): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  733): Broadcasting onBluetoothServiceDown() to 11 receivers.
D/BluetoothManagerService(  733): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@251b7916 mBinding = false
,D/BluetoothManagerService(  733): Sending unbind request.
D/BluetoothManagerService(  733): Bluetooth State Change Intent: 13 -> 10
I/GKI_LINUX( 3052): gki_task task_id=1 [BTIF] terminating
D/BluetoothAdapter(  896): 33115895: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  896): 33115895: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  896): 33115895: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 3052): GKI_exit_task 1 done
I/GKI_LINUX( 3052): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3052): cleanupNative: return from cleanup
I/art     ( 3052): System.exit called, status: 0
I/AndroidRuntime( 3052): VM exiting with result code 0, cleanup skipped.
W/ContextImpl( 3059): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  733): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/Nat464Xlat(  733): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  733): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  733): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1213): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  733): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler( 1562): CM callback handler got msg 524292
D/BluetoothAdapter( 1310): 825369408: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1310): 825369408: getState() :  mService = null. Returning STATE_OFF
,D/AndroidRuntime( 4244): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  733): Process com.android.bluetooth (pid 3052) has died
,I/wpa_supplicant( 3058): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3058): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  733): Skipping PackageSetting{33651085 com.example.hello/10277} due to missing metadata
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  733): Killing 2995:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  733): WIN DEATH: Window{1052bbe2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  733): Client connection lost with reason: 4
,I/wpa_supplicant( 3058): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  733): InitialState.processMessage what=4
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{3691c9ef u0 com.test.thalitest/.MainActivity t214}
,D/DockEventReceiver( 3059): finishStartingService: stopping service
,I/ActivityManager(  733): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  733):   Force finishing activity ActivityRecord{3691c9ef u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  733): Duplicate finish request for ActivityRecord{3691c9ef u0 com.test.thalitest/.MainActivity t214 f}
,I/art     ( 1360): Explicit concurrent mark sweep GC freed 55123(2MB) AllocSpace objects, 14(236KB) LOS objects, 24% free, 19MB/25MB, paused 318us total 27.558ms
,I/art     ( 1284): Explicit concurrent mark sweep GC freed 7196(469KB) AllocSpace objects, 2(207KB) LOS objects, 23% free, 26MB/34MB, paused 234us total 25.636ms
,D/Tethering(  733): sendTetherStateChangedBroadcast 0, 0, 0
,W/ActivityManager(  733): Spurious death for ProcessRecord{20e65cf0 2995:com.test.thalitest/u0a270}, curProc for 2995: null
,I/InputReader(  733): Reconfiguring input devices.  changes=0x00000010
,W/Settings( 1796): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator( 1076): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1310): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1076): run()
,W/Settings( 1310): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Decoder ( 1076): createOrResetDecoder
,I/Adreno-EGL(  946): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  946): Initialized EGL, version 1.4
D/BluetoothAdapter( 3059): 535314237: getState() :  mService = null. Returning STATE_OFF
,D/OpenGLRenderer(  946): Enabling debug mode 0
,I/ConfigService( 1393): onCreate
,I/art     (  733): Explicit concurrent mark sweep GC freed 52213(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.465ms total 97.203ms
,I/art     (  733): WaitForGcToComplete blocked for 45.531ms for cause Explicit
,I/ActivityManager(  733): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4315 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/InputMethodManagerService(  733): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@2ff72d26 (uid=10034 pid=946)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1076): run()
W/ResourcesManager( 4315): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
D/BackupManagerService(  733): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  733): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  733): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1076): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1076): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1076): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1076): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1076): run()
I/StatsUtilsManager( 1076): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1076): shouldRecordStats() = Too Soon
,D/AdapterServiceConfig( 4315): Adding HeadsetService
,D/AdapterServiceConfig( 4315): Adding A2dpService
D/AdapterServiceConfig( 4315): Adding HidService
,D/AdapterServiceConfig( 4315): Adding HealthService
D/AdapterServiceConfig( 4315): Adding PanService
D/AdapterServiceConfig( 4315): Adding GattService
D/AdapterServiceConfig( 4315): Adding BluetoothMapService
,I/ActivityManager(  733): Killing 2521:com.google.android.music:main/u0a60 (adj 15): empty #17
,I/Launcher( 1284): Deferring update until onResume
,I/art     (  733): Explicit concurrent mark sweep GC freed 11733(559KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 2.202ms total 145.212ms
,W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1284): Deferring update until onResume
,D/AuthorizationBluetoothService( 1393): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  733): failed to open /acct/uid_10060/pid_2521/cgroup.procs: No such file or directory
,D/BluetoothAdapter( 3059): 535314237: getState() :  mService = null. Returning STATE_OFF
,D/AndroidRuntime( 4244): Shutting down VM
,D/VoicemailCleanupService( 1341): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  733): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4339 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1360): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1284): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f55b332 new=com.google.android.velvet.VelvetApplication@3f55b332
,I/ActivityManager(  733): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4364 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  733): Killing 3354:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,--------- beginning of crash
E/AndroidRuntime( 1360): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1360): Process: com.google.android.googlequicksearchbox:search, PID: 1360
E/AndroidRuntime( 1360): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 1360): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
E/AndroidRuntime( 1360): 	at csx.d(PG:192)
E/AndroidRuntime( 1360): 	at cun.g(PG:594)
E/AndroidRuntime( 1360): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 1360): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 1360): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1360): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 1360): 	at cuy.ub(PG:301)
E/AndroidRuntime( 1360): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 1360): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 1360): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1360): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1360): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
