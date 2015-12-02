#### Test 52445159d291820_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1553): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1553): Module APK com.google.android.play.games already loaded
I/GAv4    ( 2902): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2902):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2902):   adb logcat -s GAv4
W/GAv4    ( 2902): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2902): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2902): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2902): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 2902): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2902): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2383): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  760): Killing 2207:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 2902): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2902): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2902): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2207/cgroup.procs: No such file or directory
V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1553): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1553): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1553): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 2974): 
D/AndroidRuntime( 2974): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2974): CheckJNI is OFF
D/AndroidRuntime( 2974): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2995 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2974): Shutting down VM
V/ActivityManager(  760): Display changed displayId=0
I/WebViewFactory( 2995): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2995): Time to load native libraries: 2 ms (timestamps 7653-7655)
I/LibraryLoader( 2995): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2995): Binding Chromium to main looper Looper (main, tid 1) {17d8b311}
I/LibraryLoader( 2995): Expected native library version number "",actual native library version number ""
I/chromium( 2995): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2995): Initializing chromium process, singleProcess=true
W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2995): ApplicationContext is null in ApplicationStatus
W/chromium( 2995): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2995): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2995): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2995): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2995): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/ActivityManager(  760): Killing 2303:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d8c4584:true
,D/BluetoothAdapter( 2995): 369639140: getState() :  mService = null. Returning STATE_OFF
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2303/cgroup.procs: No such file or directory
,W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2995): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2995): CordovaWebView is running on device made by: LGE
,W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2995): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2995): Render dirty regions requested: true
,D/Atlas   ( 2995): Validating map...
,W/chromium( 2995): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2995): Initialized EGL, version 1.4
D/OpenGLRenderer( 2995): Enabling debug mode 0
,I/Keyboard.Facilitator( 1069): onFinishInput()
,W/IInputConnectionWrapper( 2995): showStatusIcon on inactive InputConnection
,I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +475ms (total +56s186ms)
,W/BindingManager( 2995): Cannot call determinedVisibility() - never saw a connection for the pid: 2995
,D/JsMessageQueue( 2995): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2995): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 2995): jxcore cordova android initializing
,W/jxcore-log( 2995): Initializing JXcore engine
W/jxcore-log( 2995): JXcore engine is ready
,W/jxcore-log( 2995): Starting JXcore engine
,W/.test.thalitest( 2995): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8401]" dev="sockfs" ino=8401 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2995): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2995): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10309]" dev="sockfs" ino=10309 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2995): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18116]" dev="sockfs" ino=18116 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2995): Platform android
W/jxcore-log( 2995): 
,W/jxcore-log( 2995): Process ARCH arm
W/jxcore-log( 2995): 
,I/jxcore-log( 2995): JXcore Cordova bridge is ready!
I/jxcore-log( 2995): 
W/jxcore-log( 2995): JXcore engine is started
,I/Choreographer( 2995): Skipped 106 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2995): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2995): Toggling radios to true
I/jxcore-log( 2995): 
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  760): Message: 1
D/BluetoothManagerService(  760): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  760): setWifiEnabled: true pid=2995, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  760): New client listening to asynchronous messages
,I/ActivityManager(  760): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3054 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  179): Softap fwReload - Ok
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
,I/jxcore-log( 2995): Radios toggled
I/jxcore-log( 2995): 
,D/WifiMonitor(  760): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3065 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3064): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3054): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3064): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2700d5e4:true
,D/BluetoothAdapter( 3065): 400077585: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3065): Adding local MAP profile
D/BluetoothMap( 3065): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3065): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3065): 400077585: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3065): 400077585: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3104 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  760): Killing 2352:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2352/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 3054): Adding HeadsetService
D/AdapterServiceConfig( 3054): Adding A2dpService
D/AdapterServiceConfig( 3054): Adding HidService
D/AdapterServiceConfig( 3054): Adding HealthService
D/AdapterServiceConfig( 3054): Adding PanService
D/AdapterServiceConfig( 3054): Adding GattService
D/AdapterServiceConfig( 3054): Adding BluetoothMapService
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@253a6b2:true
,D/BluetoothAdapterState( 3054): make
,I/BluetoothAdapterState( 3054): Entering OffState
I/bluedroid( 3054): init
,I/bte_conf( 3054): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3054): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3054): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3054): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3054): get_profile_interface socket
I/bluedroid( 3054): get_profile_interface map_client
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3054): config_hci_snoop_log
,D/BluetoothManagerService(  760): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceUp() to 10 receivers.
,I/GKI_LINUX( 3054): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3054): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3054): Name is: Nexus 5
D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
D/BluetoothAdapterState( 3054): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3054): Setting state to 11
I/BluetoothAdapterState( 3054): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3054): make
I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,D/BluetoothHeadset( 1179): Proxy object connected
,D/HeadsetService( 3054): Received start request. Starting profile...
,D/BluetoothHeadset( 1179): Proxy object connected
I/BluetoothHeadsetServiceJni( 3054): classInitNative: succeeds
D/BluetoothHeadset(  760): Proxy object connected
D/BluetoothHeadset( 1208): Proxy object connected
,D/HeadsetStateMachine( 3054): make
,I/BluetoothAdapterState( 3054): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3054): max_hf_connections = 1
I/bluedroid( 3054): get_profile_interface handsfree
,D/HeadsetStateMachine( 3054): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,D/BluetoothA2dp(  760): Proxy object connected
D/A2dpService( 3054): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3054): classInitNative: succeeds
I/bluedroid( 3054): get_profile_interface avrcp
,E/RemoteController( 3054): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3054): classInitNative: succeeds
D/A2dpStateMachine( 3054): make
I/bluedroid( 3054): get_profile_interface a2dp
,I/GKI_LINUX( 3054): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,I/BluetoothHidServiceJni( 3054): classInitNative: succeeds
,D/A2dpStateMachine( 3054): Enter Disconnected: -2
,D/BluetoothInputDevice( 3065): Proxy object connected
D/HidService( 3054): Received start request. Starting profile...
I/bluedroid( 3054): get_profile_interface hidhost
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
D/HidProfile( 3065): Bluetooth service connected
,I/BluetoothHealthServiceJni( 3054): classInitNative: succeeds
,D/HealthService( 3054): Received start request. Starting profile...
,I/bluedroid( 3054): get_profile_interface health
,D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,I/BluetoothPanServiceJni( 3054): classInitNative(L105): succeeds
,D/BluetoothPan( 3065): BluetoothPAN Proxy object connected
D/PanProfile( 3065): Bluetooth service connected
,D/PanService( 3054): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3054): initializeNative(L110): pan
,I/bluedroid( 3054): get_profile_interface pan
,D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,I/BtGatt.JNI( 3054): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3054): handleDebugAction() action=null
,D/BtGatt.GattService( 3054): Received start request. Starting profile...
D/BtGatt.GattService( 3054): start()
,I/bluedroid( 3054): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3054): advertise manager created
,D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,V/BluetoothMapService( 3054): BluetoothMapBinder()
,D/BluetoothMapService( 3054): Received start request. Starting profile...
,D/BluetoothMapService( 3054): start()
D/BluetoothMap( 3065): Proxy object connected
,D/MapProfile( 3065): Bluetooth service connected
D/BluetoothMap( 3065): getConnectedDevices()
,D/BluetoothMap( 3065): Bluetooth is Not enabled
,I/art     ( 1446): Explicit concurrent mark sweep GC freed 8913(509KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 663us total 21.091ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 13012(651KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 856us total 49.731ms
,D/BluetoothMapEmailSettingsLoader( 3054): Found 0 applications
D/BluetoothMapEmailAppObserver( 3054): createReceiver()
,D/BluetoothMapEmailAppObserver( 3054): initObservers()
D/BluetoothMapEmailAppObserver( 3054): getEnabledAccountItems()
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
D/HeadsetStateMachine( 3054): Proxy object connected
V/BluetoothMapService( 3054): Handler(): got msg=1
,D/HeadsetStateMachine( 3054): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3054): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3054): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3054): enable
,I/bt_hci_bdroid( 3054): init
,I/GKI_LINUX( 3054): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3054): btu_task pending for preload complete event
,I/bt_vendor( 3054): init
I/bt_vnd_conf( 3054): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3054): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3054): userial_init
,I/bt_userial_vendor( 3054): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3054): device fd = 53 open
D/bt_userial( 3054): Entering userial_read_thread()
,I/bt_hwcfg( 3054): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3054): Chipset BCM4335C0
D/bt_hwcfg( 3054): Target name = [BCM4335C0]
I/bt_hwcfg( 3054): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1446): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  760): Killing 1766:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1766/cgroup.procs: No such file or directory
I/wpa_supplicant( 3064): rfkill: Cannot open RFKILL control device
,D/Tethering(  760): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3064): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  760): Loading config and enabling all networks 
,D/WifiService(  760): New client listening to asynchronous messages
,E/WifiConfigStore(  760): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 1784): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  760): Setting external_sim to 1
,D/WifiStateMachine(  760): Setting OUI to DA-A1-19
I/WifiNative-HAL(  760): startHal
D/wifi    (  760): setting scan oui 0xa014fdf0
D/WifiHAL (  760): Sending mac address OUI
,E/WifiHAL (  760): failed to set scanning mac OUI; result = -95
,E/native  (  760): do suspend true
,D/WifiScanningService(  760): SCAN_AVAILABLE : 3
,D/RttService(  760): SCAN_AVAILABLE : 3
D/WifiScanningService(  760): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  760): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  760): startHal
,D/CommandListener(  179): Setting iface cfg
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  760): startMonitoring(p2p0) with mConnected = true
,D/wifi    (  760): getting scan capabilities on interface[1] = 0xa014fdf0
D/WifiHAL (  760): Creating message to get scan capablities; iface = 21
,D/WifiHAL (  760): In GetCapabilities::handleResponse
,D/WifiHAL (  760): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  760): StartedState
,D/WifiNative-HAL(  760): p2pGetDeviceAddress
,D/WifiNative-HAL(  760): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3054): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3054): Settlement delay -- 100 ms
I/bt_hwcfg( 3054): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3064): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3054): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3054): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3054): vendor lib fwcfg completed
,I/bt-btu  ( 3054): btu_task received preload complete event
,I/        ( 3054): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3054): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 3054): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3054): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3054): BTE_InitTraceLevels -- TRC_AVRC
,I/        ( 3054): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3054): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3054): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3054): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3054): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3054): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3054): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3054): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3054): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3054): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3054): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 3054): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3054): Calling BTA_HhEnable
E/bt-btif ( 3054): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3054): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothAdapterProperties( 3054): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3054): Scan Mode:20
D/BluetoothAdapterProperties( 3054): Discoverable Timeout:120
,D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5,
,D/bte_conf( 3054): Device ID record 1 : primary
D/bte_conf( 3054):   vendorId            = 000f
D/bte_conf( 3054):   vendorIdSource      = 0001
D/bte_conf( 3054):   product             = 1200
D/bte_conf( 3054):   version             = 1436
D/bte_conf( 3054):   clientExecutableURL = 
D/bte_conf( 3054):   serviceDescription  = 
D/bte_conf( 3054):   documentationURL    = 
D/bte_conf( 3054): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3054): ScanMode =  20
,D/BluetoothAdapterProperties( 3054): State =  11
D/BluetoothAdapterProperties( 3054): Setting state to 12
I/BluetoothAdapterState( 3054): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothPanServiceJni( 3054): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 9 receivers.
I/BluetoothAdapterState( 3054): Entering On State
,D/BluetoothAdapterProperties( 3054): Scan Mode:21
D/BluetoothAdapterProperties( 3054): Discoverable Timeout:120
,D/BluetoothPbap( 3065): onBluetoothStateChange: up=true
,D/BluetoothMap( 3065): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1179): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1179): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1208): onBluetoothStateChange: up=true
,D/BluetoothPan( 3065): onBluetoothStateChange(on) call bindService
,D/BluetoothInputDevice( 3065): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
,I/Telecom ( 1179): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,E/bt_h4   ( 3054): vendor lib postload completed
,W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = 31 41 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = a3 e0 b9 d8 1d 97 91 6f 93 ed 40 2c dc 3a ab d1 
W/bt-btm  ( 3054): Stopping oneshot timer
,D/BluetoothMapService( 3054): onReceive
,D/BluetoothMapService( 3054): STATE_ON
V/BluetoothMapService( 3054): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3054): Map Service startRfcommSocketListener
D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/HeadsetStateMachine( 3054): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3054): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3054): mNumber:  mType: 128
D/HeadsetStateMachine( 3054): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3054): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothMapMasInstance( 3054): MAS initSocket()
D/BluetoothMapMasInstance( 3054):   masId = 00
D/BluetoothMapMasInstance( 3054):   msgTypes = 0e
D/BluetoothMapMasInstance( 3054):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3054):   SDP string = 000eSMS/MMS
,W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = 18 e1 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = 1a 69 90 9f de 15 22 fd 9a 31 53 cf 44 27 78 19 
W/bt-btm  ( 3054): Stopping oneshot timer
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3054): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3054): Succeed to create listening socket 
W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = dc 15 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/BluetoothMapMasInstance( 3054): Accepting socket connection...
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = 87 35 31 5b 0e 2a aa c7 fb 62 65 2f 3c a5 af 93 
W/bt-btm  ( 3054): Stopping oneshot timer
,W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = f2 f5 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = f3 ad 3a 04 4c 67 ae ad 54 c3 4c 86 ef 20 b3 c6 
W/bt-btm  ( 3054): Stopping oneshot timer
,D/LocalBluetoothProfileManager( 3065): Adding local A2DP profile
D/BluetoothManagerService(  760): Message: 30
D/LocalBluetoothProfileManager( 3065): Adding local HEADSET profile
,D/BluetoothManagerService(  760): Message: 30
,W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = 8f 41 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = 13 38 78 3d 58 64 cc 33 6b d1 bc 9b 0d 72 36 64 
W/bt-btm  ( 3054): Stopping oneshot timer
,W/ContextImpl( 3065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3065): Proxy object connected
,W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = 8b 0e 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = b5 50 ab 29 8c 04 db 90 7f a6 aa fb f0 74 ea 72 
W/bt-btm  ( 3054): Stopping oneshot timer
,W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = c5 88 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = 46 97 b3 f4 26 b0 36 c2 7e e6 88 94 b9 3c d5 0d 
W/bt-btm  ( 3054): Stopping oneshot timer
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3054): getBluetoothService() called with no BluetoothManagerCallback
,D/A2dpProfile( 3065): Bluetooth service connected
,D/BluetoothHeadset( 3065): Proxy object connected
D/HeadsetProfile( 3065): Bluetooth service connected
,D/DockEventReceiver( 3065): finishStartingService: stopping service
,D/BluetoothPbap( 3065): Proxy object connected
,D/PbapServerProfile( 3065): Bluetooth service connected
,D/AuthorizationBluetoothService( 1446): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3054): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3054): Accept thread started.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2995): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): my name is : LGE-Nexus 5_PT5777
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
,I/Choreographer( 2995): Skipped 127 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/NetworkUtils( 1354): OkHttp exception
,W/EventLoggerService( 1354): Unable to send logs Error code: 262146
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  760): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  760): will read network variables netId=1
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  760): will read network variables netId=1
,I/wpa_supplicant( 3064): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  760): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3064): PNO: In assoc process
,I/wpa_supplicant( 3064): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3064): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3064): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiStateMachine(  760): Start Dhcp Watchdog 1
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/dhcpcd  ( 3217): version 5.5.6 starting
,E/dhcpcd  ( 3217): get_duid: Read-only file system
,I/dhcpcd  ( 3217): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3217): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3217): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  760): do suspend true
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 100
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  760): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760):    accepting network in place of null
,D/ConnectivityService(  760): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Dec 2015 20:06:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449086801328], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449086801305]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1208): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524295
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2487): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2487): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  760): Setting time of day to sec=1449086805
W/AlarmManagerService(  760): Unable to set rtc to 1449086805: Invalid argument
,E/GpsLocationProvider(  760): No APN found to select.
,I/iu.SyncManager( 1553): SYNC; picasa accounts
,D/NetworkLogImpl( 1553): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1553): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/GpsLocationProvider(  760): NTP server returned: 1449086805237 (Wed Dec 02 21:06:45 GMT+01:00 2015) reference: 86850 certainty: 13 system time offset: -23
E/LocSvc_eng(  760): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/iu.UploadsManager( 1553): num queued entries: 0
I/iu.UploadsManager( 1553): num updated entries: 0
,I/iu.SyncManager( 1553): NEXT; no task
,D/ChimeraCfgMgr( 1553): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1553): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1553): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1553): onCreate
,D/SystemUpdateService( 1553): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1553): active receiver: enabled
,I/SystemUpdateService( 1553): showing system update notification
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1553): retry (wakeup: false) in 3599982 ms
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3307 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1553): onDestroy
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1553): [CredentialSyncAdapter] Unknown sync event.
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1784): connection state changed from UNKNOWN to CONNECTED
,D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  760): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1553): CM callback handler got msg 524290
,I/GAv4    ( 3307): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3307):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3307):   adb logcat -s GAv4
,W/GAv4    ( 3307): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/jxcore-log( 2995): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2995): 
,W/DriveInitializer( 1553): Awaiting to be initialized
,W/DriveInitializer( 1553): Background init thread started
,W/GAv4    ( 3307): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3307): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1446): GCM config loaded
,I/art     ( 1446): Explicit concurrent mark sweep GC freed 14718(788KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 19MB/32MB, paused 1.618ms total 32.673ms
,W/DriveInitializer( 1553): Background init thread ended
,I/art     (  760): Explicit concurrent mark sweep GC freed 46405(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 1.001ms total 60.460ms
,I/WebViewFactory( 3307): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3307): Time to load native libraries: 2 ms (timestamps 7349-7351)
I/LibraryLoader( 3307): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3307): Binding Chromium to main looper Looper (main, tid 1) {28da875b}
,I/LibraryLoader( 3307): Expected native library version number "",actual native library version number ""
,I/chromium( 3307): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3307): Initializing chromium process, singleProcess=true
W/art     ( 3307): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3307): ApplicationContext is null in ApplicationStatus
,W/chromium( 3307): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3307): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3307): Requires BLUETOOTH permission
,I/NSApplication( 3307): Starting up...
,W/art     ( 2595): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3396 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 176us total 9.552ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.556ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.567ms
,D/TimeService( 3396): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449086805941
D/        ( 3396): TimeServiceNative: User Time to be set is 1449086805941
D/QC-time-services( 3396): Lib:time_genoff_operation: pargs->base = 2
,D/QC-time-services( 3396): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3396): Lib:time_genoff_operation: pargs->ts_val = 1449086805941
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3396): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449086805941
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1449086805941, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/6/70 1:57:33
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8215053000
D/QC-time-services(  197): Daemon:new time 1449086805941 
D/QC-time-services(  197): Daemon: delta 1440871752941 genoff 1440871752941 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871752941 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871752941 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133122005941
E/QC-time-services( 3396): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  760): Killing 2450:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2450/cgroup.procs: No such file or directory
,I/CheckinService( 1553): Checkin interval check for package: unspecified last checkin: 1449052176483 min interval config: 0 actual interval: 34629508
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3423 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3423): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3423):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3423):   adb logcat -s GAv4
,W/GAv4    ( 3423): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3423): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3423): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2326:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2326/cgroup.procs: No such file or directory
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/ActivityManager(  760): Killing 2770:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_2770/cgroup.procs: No such file or directory
,D/Finsky  ( 2383): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2383): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
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
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1446): Vacuum at: now=1449086835449 tag=VacuumService
,D/GetConfigurationSnapshotOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1446): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1446): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/UdcCache:FPQuery( 1553): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1446):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1446): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1069): run()
I/Keyboard.Facilitator( 1069): flushDynamicLanguageModels()
,I/ConfigService( 1446): onCreate
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/ConfigService( 1446): onDestroy
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/ClearcutLoggerApiImpl( 1287): disconnect managed GoogleApiClient
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2995): 
,E/DataBuffer( 1446): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a99bf0d)
,E/DataBuffer( 1446): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3cba7ec2)
E/DataBuffer( 1446): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a1344d3)
E/DataBuffer( 1446): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@275ec810)
E/DataBuffer( 1446): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@30b03f09)
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
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1446): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 1336:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10004/pid_1336/cgroup.procs: No such file or directory
,I/jxcore-log( 2995): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): DBG, CoordinatorConnector command called
I/jxcore-log( 2995): 
I/jxcore-log( 2995): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":18,"addressList":[{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F4:F1:E1:5C:3B
,I/jxcore-log( 2995): Start now : testSendData.js
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 18
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): check server
I/jxcore-log( 2995): 
I/jxcore-log( 2995): serverPort is 58041
I/jxcore-log( 2995): 
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2995): Stoping All
I/        ( 2995): Stopping services
I/        ( 2995): Stop Bluetooth
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2995): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 2995):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5777","ra":"34:FC:EF:11:AE:67"}
,I/        ( 2995): All stuff available and enabled
I/        ( 2995): Stoping All
I/        ( 2995): Stopping services
I/        ( 2995): Stop Bluetooth
I/        ( 2995): Starting All
I/        ( 2995): Stopping services
I/        ( 2995): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5777","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@32fa477d
I/        ( 2995): Stopping services
I/        ( 2995): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5777","ra":"34:FC:EF:11:AE:67"}
I/        ( 2995): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5777","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 2995): peerDiscoveryTimer timeout value:5774
,I/        ( 2995): Stop Bluetooth
I/        ( 2995): StartBluetooth listener
I/        ( 2995): StartBluetooth listener
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 2995): StartBroadcasting started ok
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:25.889Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:12:25.890Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:25.890Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2995): Connecting to null, at 80:01:84:8A:B3:68
I/jxcore-log( 2995): 2015-12-02T20:12:25.895Z SendDataTCPServer.js: TCP/IP server is bound to port: 58041
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
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/BTListenerThread( 2995): starting to listen
I/BTListenerThread( 2995): waiting to accept incoming Connection
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 5
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:12:26.239Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:26.240Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:26.242Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2995): Found 1 peers.
I/SS      ( 2995): Peer(1): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2995): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:12:31.244Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:31.246Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:12:36.255Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:36.256Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:12:36.260Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:36.261Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2995): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,W/bt-rfcomm( 3054): PORT_StartCnf failed result:5
,W/bt-btif ( 3054): invalid rfc slot id: 6
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3054): No record of the device:null
I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 9 Address: 80:01:84:8A:B3:68 newState: 0
,E/BluetoothBondStateMachine( 3054): In stable state, received invalid newState: 10
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:12:38.162Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:12:38.163Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:38.163Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3054): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:12:43.164Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:43.165Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:12:48.170Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:48.171Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:48.172Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:48.172Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2995): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,W/bt-rfcomm( 3054): PORT_StartCnf failed result:5
,W/bt-btif ( 3054): invalid rfc slot id: 7
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3054): No record of the device:null
I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 9 Address: 80:01:84:8A:B3:68 newState: 0
,E/BluetoothBondStateMachine( 3054): In stable state, received invalid newState: 10
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:12:50.965Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:12:50.966Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:12:50.969Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3054): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:12:55.974Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:12:55.975Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:00.980Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:00.981Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:00.981Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:00.982Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2995): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,W/bt-rfcomm( 3054): PORT_StartCnf failed result:5
,W/bt-btif ( 3054): invalid rfc slot id: 8
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c,
I/BluetoothBondStateMachine( 3054): No record of the device:null
I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 9 Address: 80:01:84:8A:B3:68 newState: 0
,E/BluetoothBondStateMachine( 3054): In stable state, received invalid newState: 10
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:13:02.437Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:02.438Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:02.439Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3054): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:13:07.439Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:07.440Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:12.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:12.448Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:12.449Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:12.449Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 2995): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().,
,E/BluetoothEventManager( 3065): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : HTC-HTC Desire 820_PT9856
,I/HS      ( 2995): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9856
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9856
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 46870
I/BtConnectorHelper( 2995): Request socket is using : 46870
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :46870
I/jxcore-log( 2995): 2015-12-02T20:13:17.390Z SendDataConnector.js: CLIENT connected to 46870, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:17.390Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 46870
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:13:17.414Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.052Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.106Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.181Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.216Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.261Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.331Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.364Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.411Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:18.419Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 5 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-12-02T20:13:28.421Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:28.423Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:28.432Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:28.452Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:28.453Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:28.453Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: 80:01:84:8A:B3:68
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
I/jxcore-log( 2995): 2015-12-02T20:13:28.504Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:28.505Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:28.505Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:28.505Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 2995): Connecting to null, at F8:95:C7:87:3C:51
I/jxcore-log( 2995): 2015-12-02T20:13:28.508Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, typeCordovap2p._tcp.local.:
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/        ( 2995): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT680, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT680, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-H815_PT2788
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-H815_PT2788
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-H815_PT2788
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 60790
I/BtConnectorHelper( 2995): Request socket is using : 60790
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :60790
I/jxcore-log( 2995): 2015-12-02T20:13:31.920Z SendDataConnector.js: CLIENT connected to 60790, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:31.920Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 60790
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:13:31.945Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:32.563Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3536b4f3:true
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 2995): 2015-12-02T20:13:32.628Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:32.810Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:32.863Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:32.914Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:32.921Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:32.925Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:32.959Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:33.028Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): dm_pm_timer expires
,W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/SS      ( 2995): Found 1 peers.
I/SS      ( 2995): Peer(1): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/        ( 2995): Started service discovery
,I/jxcore-log( 2995): 2015-12-02T20:13:43.033Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:43.034Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:43.035Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:43.036Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:43.042Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: LGE-LG-H815_PT2788
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
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:13:48.042Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:48.043Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT680, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT680, WifiDirectName: , WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2995): 2015-12-02T20:13:53.046Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:53.046Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:53.049Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:13:53.052Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2995): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-H815_PT2788
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-H815_PT2788
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-H815_PT2788
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 43142
I/BtConnectorHelper( 2995): Request socket is using : 43142
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :43142
I/jxcore-log( 2995): 2015-12-02T20:13:54.731Z SendDataConnector.js: CLIENT connected to 43142, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:13:54.732Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 43142
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:13:54.754Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 4 peers.
I/SS      ( 2995): Peer(1): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-12-02T20:14:04.822Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:04.823Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:04.824Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:04.825Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:04.826Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: LGE-LG-H815_PT2788
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
,I/BtToSocketBase( 2995): Close bt socket
,I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-12-02T20:14:09.826Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:09.828Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/jxcore-log( 2995): 2015-12-02T20:14:14.831Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:14.832Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:14.833Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:14.833Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2995): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-H815_PT2788
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-H815_PT2788
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-H815_PT2788
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 40533
,I/BtConnectorHelper( 2995): Request socket is using : 40533
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :40533
,I/jxcore-log( 2995): 2015-12-02T20:14:18.651Z SendDataConnector.js: CLIENT connected to 40533, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:18.652Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 40533
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:14:18.674Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/jxcore-log( 2995): 2015-12-02T20:14:28.734Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:28.735Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:28.736Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:28.741Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:28.747Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: LGE-LG-H815_PT2788
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-12-02T20:14:33.745Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:33.745Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/jxcore-log( 2995): 2015-12-02T20:14:38.750Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:38.750Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:38.751Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:38.752Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2995): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/art     (  760): Explicit concurrent mark sweep GC freed 36953(1595KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.031ms total 96.382ms
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-H815_PT2788
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-H815_PT2788
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-H815_PT2788
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 51820
I/BtConnectorHelper( 2995): Request socket is using : 51820
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :51820
,I/jxcore-log( 2995): 2015-12-02T20:14:44.246Z SendDataConnector.js: CLIENT connected to 51820, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:44.250Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:44.259Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 51820
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
,W/bt-btif ( 3054): proc dm_pm_timer expires
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT880
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:14:51.093Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:14:51.768Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.820Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.827Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.839Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.852Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.869Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.900Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.907Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.930Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.937Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.987Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:51.994Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.002Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.013Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.054Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.064Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.073Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.109Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.138Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.181Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.194Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.232Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.248Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.281Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.318Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.330Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:52.359Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:54.330Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:54.331Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:54.332Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:54.335Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:14:54.336Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: LGE-LG-H815_PT2788
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
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/jxcore-log( 2995): 2015-12-02T20:14:59.337Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:14:59.338Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3054): invalid rfc slot id: 4
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): Close LocalOutputStream
,I/BtToSocketBase( 2995): Close localHostSocket
,I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-12-02T20:15:02.733Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 2995): 2015-12-02T20:15:04.342Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:04.342Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:04.343Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:04.343Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/        ( 2995): Connecting to G4-1, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT880
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A300FU_PT880
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/jxcore-log( 2995): 2015-12-02T20:15:13.891Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:15:14.391Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:14.437Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:14.504Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:14.513Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:14.521Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3054): invalid rfc slot id: 14
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): Close LocalOutputStream
,I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-12-02T20:15:24.708Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT880
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A300FU_PT880
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:15:36.048Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:15:36.479Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:36.505Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:36.522Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
,W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-H815_PT2788
,I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-H815_PT2788
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-H815_PT2788
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 60785
I/BtConnectorHelper( 2995): Request socket is using : 60785
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :60785
I/jxcore-log( 2995): 2015-12-02T20:15:44.020Z SendDataConnector.js: CLIENT connected to 60785, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:44.021Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 60785
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:15:44.048Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): invalid rfc slot id: 16
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT880
,I/BtToSocketBase( 2995): Stop ReceivingThread
,I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-12-02T20:15:46.704Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x4c
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
,I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT7267
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT7267
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/jxcore-log( 2995): 2015-12-02T20:15:53.393Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:15:54.039Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:54.093Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:54.112Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:54.112Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:54.112Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:54.115Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:54.115Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:54.115Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/BtConnectorHelper( 2995): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 2995): Stop ReceivingThread
,I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToRequestSocket( 2995): Close server socket
,I/jxcore-log( 2995): 2015-12-02T20:15:54.150Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:54.153Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:54.154Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:15:54.154Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 2995): Connecting to null, at E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 2015-12-02T20:15:54.174Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:54.176Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-12-02T20:15:56.124Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.158Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.235Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.244Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.255Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.273Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.367Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.383Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:15:56.442Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.454Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.525Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.535Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:15:56.667Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.674Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.919Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.958Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.989Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:56.996Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.004Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.051Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:15:57.119Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.127Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.178Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.191Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:15:57.310Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.349Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.355Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.361Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.369Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2995): 
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/jxcore-log( 2995): 2015-12-02T20:15:57.466Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.520Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.529Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.534Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.591Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.601Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.642Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.650Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.655Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.762Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.798Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.822Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:15:57.826Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
D/BluetoothAdapterProperties( 3054): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:75:41]: 7, f, 6109
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(4): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 2995): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N910C_PT785
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 36986
I/BtConnectorHelper( 2995): Request socket is using : 36986
I/BtToRequestSocket( 2995): Now accepting connections
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :36986
,I/jxcore-log( 2995): 2015-12-02T20:16:00.920Z SendDataConnector.js: CLIENT connected to 36986, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:00.921Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 36986
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:16:00.951Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:16:02.012Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:02.153Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:02.226Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT880
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:16:02.569Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:16:02.702Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:02.945Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:02.957Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:02.965Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:02.985Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:03.115Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:03.385Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:03.495Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:03.689Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:16:04.205Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:04.245Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8756, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8756, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-btif ( 3054): invalid rfc slot id: 17
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT7267
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
,I/jxcore-log( 2995): 2015-12-02T20:16:08.211Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x40
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 1
,W/bt-btif ( 3054): proc dm_pm_timer expires
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/SS      ( 2995): Found 3 peers.
I/SS      ( 2995): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/        ( 2995): Started service discovery
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:16:14.246Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:14.248Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:14.254Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:14.254Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:14.255Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N910C_PT785
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): invalid rfc slot id: 18
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x45
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-12-02T20:16:14.545Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1792, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1792, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [b4:ce:f6:ab:a4:6a]: 7, f, 2205
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT7267
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT7267
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:16:18.542Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:16:18.959Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:18.964Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:18.990Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:19.001Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:19.027Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:19.049Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:19.255Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:19.256Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9856, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9856, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2995): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-XT1072_PT5715
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:16:22.025Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
I/        ( 2995): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3384","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3384","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3384, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3384, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:16:22.930Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.061Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.174Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.216Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.224Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.254Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.289Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.303Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.387Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.461Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.623Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.738Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.751Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.774Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.787Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:23.819Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.041Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.077Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.089Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.119Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.127Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.200Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.262Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:24.262Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:24.263Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:24.263Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2995): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 2995): 2015-12-02T20:16:24.306Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:16:24.538Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.544Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.552Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.579Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.586Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.597Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.644Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:24.655Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/jxcore-log( 2995): 2015-12-02T20:16:25.480Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.483Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 2995): 
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/jxcore-log( 2995): 2015-12-02T20:16:25.507Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.725Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.734Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.748Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.781Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:25.785Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.791Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.798Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.850Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2995): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT880
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 2995): 2015-12-02T20:16:25.925Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:25.936Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 2995): 
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
I/jxcore-log( 2995): 2015-12-02T20:16:25.945Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:16:25.973Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [e0:db:10:14:e2:c0]: 0, 0, 0
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:16:26.383Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:26.461Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/jxcore-log( 2995): 2015-12-02T20:16:26.687Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:26.767Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:26.775Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2995): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N910C_PT785
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 36652
I/BtConnectorHelper( 2995): Request socket is using : 36652
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :36652
,I/jxcore-log( 2995): 2015-12-02T20:16:27.736Z SendDataConnector.js: CLIENT connected to 36652, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:27.741Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 36652
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:16:27.772Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,W/bt-btif ( 3054): invalid rfc slot id: 20
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT7267
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
,I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT7267
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-12-02T20:16:29.211Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x49
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 2
,W/bt-btif ( 3054): proc dm_pm_timer expires
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2995): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): invalid rfc slot id: 21
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
,I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
,I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Close bt socket
,I/jxcore-log( 2995): 2015-12-02T20:16:36.208Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT880
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,W/bt-btif ( 3054): invalid rfc slot id: 22
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-12-02T20:16:36.612Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 2995): 2015-12-02T20:16:37.826Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:37.829Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:37.832Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:37.834Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:37.835Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N910C_PT785
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
,I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: A3-1
,I/jxcore-log( 2995): 2015-12-02T20:16:42.835Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:42.836Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-XT1072_PT5715
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:16:47.485Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:16:47.844Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:47.844Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:47.845Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:47.845Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2995): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 2995): 2015-12-02T20:16:47.905Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:47.912Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:16:48.811Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:48.934Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:48.941Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:16:48.949Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectToThread( 2995): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N910C_PT785
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 34495
I/BtConnectorHelper( 2995): Request socket is using : 34495
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :34495
I/jxcore-log( 2995): 2015-12-02T20:16:53.875Z SendDataConnector.js: CLIENT connected to 34495, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:16:53.876Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 34495
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:16:53.897Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): invalid rfc slot id: 24
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
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
,I/jxcore-log( 2995): 2015-12-02T20:16:57.945Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,I/jxcore-log( 2995): 2015-12-02T20:17:03.988Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:03.989Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:03.990Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:03.991Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:03.992Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N910C_PT785
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
,I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-XT1072_PT5715
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:17:08.561Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:08.964Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:08.975Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:08.982Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:08.991Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:08.992Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-12-02T20:17:13.995Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:13.996Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:14.000Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:14.000Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2995): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2995): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N910C_PT785
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 51429
I/BtConnectorHelper( 2995): Request socket is using : 51429
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :51429
,I/jxcore-log( 2995): 2015-12-02T20:17:17.456Z SendDataConnector.js: CLIENT connected to 51429, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:17.460Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 51429
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:17:17.481Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): invalid rfc slot id: 25
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
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
,I/jxcore-log( 2995): 2015-12-02T20:17:19.001Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 1
W/bt-btif ( 3054): proc dm_pm_timer expires
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,I/jxcore-log( 2995): 2015-12-02T20:17:27.543Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:27.544Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:27.545Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:27.546Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:27.553Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: samsung-SM-N910C_PT785
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-12-02T20:17:32.553Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:32.554Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 2995): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:17:37.558Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:37.559Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:37.560Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:37.560Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: E0:DB:10:14:E2:C0, name: Note4-1
,I/        ( 2995): Connecting to Note4-1, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [e0:db:10:14:e2:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : samsung-SM-N910C_PT785
I/HS      ( 2995): Hand Shake finished outgoing for : samsung-SM-N910C_PT785
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, samsung-SM-N910C_PT785
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 51331
I/BtConnectorHelper( 2995): Request socket is using : 51331
I/BtToRequestSocket( 2995): Now accepting connections
,I/        ( 2995): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT1414, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT1414, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :51331
I/jxcore-log( 2995): 2015-12-02T20:17:42.990Z SendDataConnector.js: CLIENT connected to 51331, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:42.990Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 51331
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:17:43.026Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1792, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1792, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:17:53.101Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:53.102Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:53.104Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:17:53.121Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:53.122Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:53.123Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/BtConnectorHelper( 2995): Disconnect outgoing peer: E0:DB:10:14:E2:C0
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
I/jxcore-log( 2995): 2015-12-02T20:17:53.149Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:53.152Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:53.154Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:17:53.155Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 2995): Connecting to null, at 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 2015-12-02T20:17:53.175Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 7 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3054): PORT_StartCnf failed result:5
,W/bt-btif ( 3054): invalid rfc slot id: 30
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3054): No record of the device:null
I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 9 Address: 58:2A:F7:ED:96:BE newState: 0
,E/BluetoothBondStateMachine( 3054): In stable state, received invalid newState: 10
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3054): Do not find the bg connection mask for the remote device
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:18:02.136Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:02.143Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:02.146Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:18:07.154Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:07.155Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 7 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:18:12.160Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:12.161Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:12.161Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:12.162Z SendDataConnector.js: do connect now,
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 2995): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [44:80:eb:7b:5a:05]: 6, 10f, 608
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5715","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : motorola-XT1072_PT5715
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, motorola-XT1072_PT5715
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/jxcore-log( 2995): 2015-12-02T20:18:13.843Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/jxcore-log( 2995): 2015-12-02T20:18:14.272Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:14.279Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:14.282Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:14.286Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:14.292Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 2995): got MESSAGE_READ 79 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT410","ra":"58:2A:F7:ED:96:BE"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : HUAWEI-ALE-L21_PT410
I/HS      ( 2995): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT410
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT410
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 55564
I/BtConnectorHelper( 2995): Request socket is using : 55564
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :55564
,I/jxcore-log( 2995): 2015-12-02T20:18:15.066Z SendDataConnector.js: CLIENT connected to 55564, error: null
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:15.071Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 55564
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:18:15.123Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,D/        ( 3054): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2995): 2015-12-02T20:18:15.755Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:16.097Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,D/        ( 3054): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2995): 2015-12-02T20:18:16.273Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:16.799Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,D/        ( 3054): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2995): 2015-12-02T20:18:16.903Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:17.070Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1792","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT1792, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT1792, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 2995): 2015-12-02T20:18:17.535Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT680"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT680, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT680, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/jxcore-log( 2995): 2015-12-02T20:18:18.101Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:18.521Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 1
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,W/bt-btif ( 3054): invalid rfc slot id: 27
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5715
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
,I/jxcore-log( 2995): 2015-12-02T20:18:24.677Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x4c
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e5196c rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2995): 2015-12-02T20:18:28.520Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:28.521Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:28.522Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:28.523Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:28.524Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: HUAWEI-ALE-L21_PT410
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1028","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1028","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT1028, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT1028, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 2995): 2015-12-02T20:18:33.524Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:33.525Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:18:38.530Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:38.531Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:38.532Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:38.532Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2995): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 11 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(7): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 2995): got MESSAGE_READ 79 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT410","ra":"58:2A:F7:ED:96:BE"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : HUAWEI-ALE-L21_PT410
I/HS      ( 2995): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT410
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT410
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 36455
I/BtConnectorHelper( 2995): Request socket is using : 36455
I/BtToRequestSocket( 2995): Now accepting connections
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :36455
,I/jxcore-log( 2995): 2015-12-02T20:18:40.602Z SendDataConnector.js: CLIENT connected to 36455, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:40.603Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 36455
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:18:40.660Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,I/EventLogService( 1553): Aggregate from 1449085203616 (log), 1449085203616 (data)
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/jxcore-log( 2995): 2015-12-02T20:18:50.710Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:50.710Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:50.711Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:50.712Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:18:50.713Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: HUAWEI-ALE-L21_PT410
I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
,I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
I/BtToRequestSocket( 2995): Close server socket
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/jxcore-log( 2995): 2015-12-02T20:18:55.715Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:18:55.721Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 2995): 2015-12-02T20:19:00.729Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:00.730Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:00.731Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:00.731Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2995): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x10  CID 0x41
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 34
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:19:08.459Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:08.460Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:08.461Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:13.462Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:13.463Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): ,
,I/jxcore-log( 2995): 2015-12-02T20:19:18.466Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:18.469Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:18.469Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:18.470Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 2995): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 6, 10f, 608
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
,I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9856
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9856
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/jxcore-log( 2995): 2015-12-02T20:19:28.288Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:19:28.938Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:28.946Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.012Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.023Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.033Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.075Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.107Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.140Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.154Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.161Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.167Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.194Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.205Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.211Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.232Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.268Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.299Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.326Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.340Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.370Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.385Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.395Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.464Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.499Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.512Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.550Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.560Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.569Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.600Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.639Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.646Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.657Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.691Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.695Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:29.704Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 35
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:19:38.614Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:38.615Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:38.631Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:38.632Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:38.635Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:38.645Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:38.646Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:19:38.646Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: null,
,I/        ( 2995): Connecting to null, at 34:FC:EF:9D:93:0B
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): invalid rfc slot id: 32
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9856
,I/BtToSocketBase( 2995): Stop ReceivingThread
I/BtToSocketBase( 2995): Stop SendingThread
I/BtToSocketBase( 2995): Close local in
,I/BtToSocketBase( 2995): Close LocalOutputStream
I/BtToSocketBase( 2995): Close localHostSocket
I/BtToSocketBase( 2995): Close bt in
I/BtToSocketBase( 2995): Close bt out
I/BtToSocketBase( 2995): Close bt socket
,I/BtToSocketBase( 2995): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 2995): 2015-12-02T20:19:40.724Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x45
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3054): onReceive
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 3054): L2CAP got sec_comp for unknown BD_ADDR
,W/bt-btif ( 3054): invalid rfc slot id: 37
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/BluetoothMapService( 3054): onReceive
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:19:58.029Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:58.029Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:19:58.030Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3054): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3054): Entering PendingCommandState State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3054): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3054): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3054): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3054): StableState(): Entering Off State
,W/BluetoothEventManager( 3065): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3065): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 2995): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : LGE-LG-H815_PT2788
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, LGE-LG-H815_PT2788
,I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
,I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:20:02.141Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:20:03.021Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.032Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.039Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:03.040Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:03.042Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.066Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.097Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.104Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.107Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.147Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.151Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.155Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.188Z SendDataTCPServer.js: TCP/IP server has received 44920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.195Z SendDataTCPServer.js: TCP/IP server has received 46900 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.200Z SendDataTCPServer.js: TCP/IP server has received 48880 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.204Z SendDataTCPServer.js: TCP/IP server has received 50860 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.214Z SendDataTCPServer.js: TCP/IP server has received 52840 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.247Z SendDataTCPServer.js: TCP/IP server has received 60760 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.250Z SendDataTCPServer.js: TCP/IP server has received 62740 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.289Z SendDataTCPServer.js: TCP/IP server has received 70660 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.295Z SendDataTCPServer.js: TCP/IP server has received 74620 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.328Z SendDataTCPServer.js: TCP/IP server has received 84520 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.332Z SendDataTCPServer.js: TCP/IP server has received 86500 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:03.369Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): invalid rfc slot id: 36
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT2788
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
,I/jxcore-log( 2995): 2015-12-02T20:20:03.709Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: G4-1
,I/jxcore-log( 2995): 2015-12-02T20:20:08.043Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:08.044Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:08.044Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:08.045Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/        ( 2995): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:9d:93:0b]: 7, f, 6109
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-D802_PT7328
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-D802_PT7328
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-D802_PT7328
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 36068
,I/BtConnectorHelper( 2995): Request socket is using : 36068
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :36068
I/jxcore-log( 2995): 2015-12-02T20:20:10.273Z SendDataConnector.js: CLIENT connected to 36068, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:10.274Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 36068
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:20:10.296Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:10.967Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:11.074Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:11.473Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:11.559Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:11.606Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:11.820Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:12.121Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-12-02T20:20:12.590Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:13.084Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/jxcore-log( 2995): 2015-12-02T20:20:23.083Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:23.084Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:23.085Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:23.085Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:23.086Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: LGE-LG-D802_PT7328
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
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/jxcore-log( 2995): 2015-12-02T20:20:28.088Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:28.089Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 2995): 2015-12-02T20:20:33.093Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:33.093Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:33.094Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:33.094Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/        ( 2995): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-D802_PT7328
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-D802_PT7328
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-D802_PT7328
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 50110
I/BtConnectorHelper( 2995): Request socket is using : 50110
I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :50110
,I/jxcore-log( 2995): 2015-12-02T20:20:36.081Z SendDataConnector.js: CLIENT connected to 50110, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:36.082Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 50110
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:20:36.102Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
W/bt-btif ( 3054): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 2995): 2015-12-02T20:20:46.164Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:46.164Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:46.166Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:46.166Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:46.175Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 2995): Disconnect outgoing peer: LGE-LG-D802_PT7328
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
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:20:51.174Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:51.175Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/SS      ( 2995): Found 7 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:20:56.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:56.180Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:56.180Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:20:56.181Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/        ( 2995): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/        ( 2995): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT7267, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT7267, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-D802_PT7328
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-D802_PT7328
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-D802_PT7328
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 44162
,I/BtConnectorHelper( 2995): Request socket is using : 44162
,I/BtToRequestSocket( 2995): Now accepting connections
,I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :44162
,I/jxcore-log( 2995): 2015-12-02T20:20:58.306Z SendDataConnector.js: CLIENT connected to 44162, error: null
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:20:58.309Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 44162
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:20:58.337Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 0
,W/bt-btif ( 3054): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2995): 2015-12-02T20:21:08.411Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:08.412Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:08.413Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:08.413Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:08.414Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/BtToSocketBase( 2995): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 2995): Disconnect outgoing peer: LGE-LG-D802_PT7328
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
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,I/        ( 2995): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT7267, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT7267, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 2995): 2015-12-02T20:21:13.414Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:13.415Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/jxcore-log( 2995): 2015-12-02T20:21:18.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B,
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:18.416Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:18.416Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:18.426Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/        ( 2995): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 6, f, 4106
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
,I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9856
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9856
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/jxcore-log( 2995): 2015-12-02T20:21:20.516Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 2995): Starting to Handshake
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 2995): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTConnectToThread( 2995): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 2995): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 2995): HandshakeOk : LGE-LG-D802_PT7328
I/HS      ( 2995): Hand Shake finished outgoing for : LGE-LG-D802_PT7328
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 2995): Starting the connected thread incoming : false, LGE-LG-D802_PT7328
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 2995): mHTTPPort  set to : 38192
I/BtConnectorHelper( 2995): Request socket is using : 38192
I/BtToRequestSocket( 2995): Now accepting connections
,I/jxcore-log( 2995): 2015-12-02T20:21:20.969Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
I/BtConnectorHelper( 2995): Calling ConnectionStatusUpdate with port :38192
,I/jxcore-log( 2995): 2015-12-02T20:21:20.978Z SendDataConnector.js: CLIENT connected to 38192, error: null
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:20.979Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): incoming data from: /127.0.0.1, port: 38192
I/BtToRequestSocket( 2995): Set local streams
I/BtToRequestSocket( 2995): rin ended ---------------------------;
,I/jxcore-log( 2995): 2015-12-02T20:21:20.998Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:21.058Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:21.068Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:21.070Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1028","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT1028","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT1028, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT1028, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): dm_pm_timer expires
W/bt-btif ( 3054): dm_pm_timer expires 1
,W/bt-btif ( 3054): proc dm_pm_timer expires
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:21:31.056Z SendDataConnector.js: Receiving data timeout now,
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:31.056Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:31.062Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:31.078Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:31.079Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:31.079Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2995): 
I/BtConnectorHelper( 2995): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
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
I/jxcore-log( 2995): 2015-12-02T20:21:31.123Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:31.124Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:31.124Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:31.124Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2995): Connecting to XT1072, at 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 2015-12-02T20:21:31.128Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): invalid rfc slot id: 38
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9856
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
,I/jxcore-log( 2995): 2015-12-02T20:21:31.172Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x40
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: Thali Test's G2
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 44
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3054): onReceive
,I/jxcore-log( 2995): 2015-12-02T20:21:36.260Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:36.264Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:36.264Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT785, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT785, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/jxcore-log( 2995): 2015-12-02T20:21:41.265Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:41.266Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [80:01:84:8a:b3:68]: 6, f, 4106
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,I/        ( 2995): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT880","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT880, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT880, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-btif ( 3054): new conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3054): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 2995): we got incoming connection
I/BTHandshakeSocketThread( 2995): Creating BTHandshakeSocketThread
I/BTListenerThread( 2995): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread started
,I/BTListenerThread( 2995): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 2995): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 2995): MESSAGE_WRITE 77 bytes.
I/HS      ( 2995): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9856
I/BTHandshakeSocketThread( 2995): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 2995): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9856
I/BtToSocketBase( 2995): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 2995): Creating BTConnectedThread
I/BtConnectorHelper( 2995): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 2995): --DoOneRunRound started
,I/BtToRequestSocket( 2995): LocalHost address: localhost/127.0.0.1, port: 58041
,I/jxcore-log( 2995): 2015-12-02T20:21:41.931Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2995): 
,I/BtToRequestSocket( 2995): --DoOneRunRound ended
,I/jxcore-log( 2995): 2015-12-02T20:21:42.302Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:42.309Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:42.325Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:42.354Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:21:42.366Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-12-02T20:21:46.273Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:46.273Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:46.274Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:46.274Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2995): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,W/bt-btif ( 3054): invalid rfc slot id: 43
,I/BtToSocketBase( 2995): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 2995): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9856
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
,I/jxcore-log( 2995): 2015-12-02T20:21:53.171Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,W/bt-rfcomm( 3054): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3054): RFCOMM_DisconnectInd LCID:0x48
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT7503, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT7503, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,W/bt-rfcomm( 3054): PORT_StartCnf failed result:5
E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3054): invalid rfc slot id: 46
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:21:57.314Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:57.315Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:21:57.316Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3054): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3054): bta_dm_check_av:0
,W/bt-btif ( 3054): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3054): onReceive
,I/BTConnectionReceiver( 1354): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1354): Bluetooth Device Name: HTC Desire 820
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:22:02.318Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:02.319Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 2995): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(8): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(9): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:22:07.323Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:07.324Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:07.324Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:07.325Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2995): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 47
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:22:12.500Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:12.500Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:12.500Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:22:17.502Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:17.503Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:22:22.506Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:22.509Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:22.509Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:22.510Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2995): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x49
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 48
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:22:54.728Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:54.729Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:54.729Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:22:59.731Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:22:59.731Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:23:04.735Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:23:04.736Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:23:04.736Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:23:04.742Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 2995): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2995): Found 7 peers.
I/SS      ( 2995): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9856, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9856, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x1f  CID 0x4c
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 49
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:23:25.931Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:23:25.932Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:23:25.948Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:23:25.951Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:23:25.953Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:23:25.954Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:23:25.955Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2995): Connecting to null, at 58:3F:54:73:64:C0
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(8): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8756, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8756, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x4e
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 50
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:23:57.947Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:23:57.948Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:23:57.948Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:24:02.950Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:02.950Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 9 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:24:07.953Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:07.954Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:07.955Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:07.955Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2995): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 51
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:24:13.131Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:13.131Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:13.131Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:24:18.131Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:18.132Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:24:23.135Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:23.135Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:23.136Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:24:23.136Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2995): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 52
I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:24:28.313Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:28.313Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:28.314Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:24:33.314Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:33.315Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:24:38.321Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:38.321Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:38.322Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:24:38.322Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2995): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 4 peers.
I/SS      ( 2995): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9856, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9856, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x41
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 53
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:25:09.742Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:09.743Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:09.744Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/jxcore-log( 2995): 2015-12-02T20:25:14.745Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:14.745Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-12-02T20:25:19.751Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:19.751Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:19.752Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:19.752Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 2995): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 54
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:25:51.890Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:51.890Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:3F:54:73:64:C0 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:25:51.907Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:51.910Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:51.913Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:51.913Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:51.914Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: Connection to 58:3F:54:73:64:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 55
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:25:52.498Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:52.499Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:52.500Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT7503, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT7503, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:25:57.500Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:25:57.501Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2995): 2015-12-02T20:26:02.505Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:02.505Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:02.506Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:02.506Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 11 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2995): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2995): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 56
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:26:04.258Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:04.259Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:04.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:26:09.260Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:09.261Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:14.266Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:14.266Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:14.271Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:14.274Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 57
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:26:14.906Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:14.906Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:14.910Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:26:19.913Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:19.913Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:24.914Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:24.914Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:24.914Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:24.914Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 58
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:26:25.600Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:25.600Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:25.601Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:26:30.603Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:30.603Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:35.609Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:35.609Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:35.610Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:35.610Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 2995): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 59
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:26:37.390Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:37.391Z SendDataConnector.js: CLIENT Can not Connect: Connection to 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:37.408Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:37.410Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:37.413Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:37.414Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:37.415Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Connection to 00:F4:6F:30:E0:6C failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 60
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:26:38.725Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:38.726Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:38.726Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-12-02T20:26:43.731Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:43.732Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:48.733Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:48.733Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:48.733Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:48.733Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:76:27]: 6, f, 410d
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 61
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:26:50.593Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:50.594Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:26:50.595Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:26:55.595Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:26:55.596Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:00.601Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:00.601Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:00.601Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:00.601Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 62
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:27:03.023Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:03.024Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:03.025Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 11 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(6): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 2995): Peer(7): A3-1 0a:ec:a9:50:75:42
I/SS      ( 2995): Peer(8): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 2995): Peer(9): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2995): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:27:08.025Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:08.026Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:13.031Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:13.031Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:13.031Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:13.031Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
,W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 63
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:27:13.248Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:13.248Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:13.249Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:27:18.250Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:18.250Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:23.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:23.254Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:23.255Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:23.255Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 2995): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 64
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:27:23.495Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:23.495Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:23.511Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:23.514Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:23.524Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:23.527Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:23.528Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 65
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:27:24.411Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:24.411Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:24.412Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:27:29.412Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:29.413Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2995): 2015-12-02T20:27:34.414Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:34.414Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:34.414Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:34.414Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 66
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:27:35.669Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:35.670Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:35.671Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:27:40.673Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:40.673Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:45.674Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:45.674Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:45.674Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:45.674Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 67
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:27:46.208Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:46.209Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:46.209Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:27:51.210Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:51.211Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:56.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:56.215Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:56.216Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:27:56.216Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 68
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:27:57.133Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:57.133Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:27:57.134Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2995): 2015-12-02T20:28:02.135Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:02.136Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT5728"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT5728, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT5728, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 2995): 2015-12-02T20:28:07.141Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:28:07.141Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:07.142Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:07.142Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 2995): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-btif ( 3054): info:x10
,D/        ( 3054): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3054): process_service_search_attr_rsp
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 69
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:28:08.153Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:08.154Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:28:08.170Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:08.173Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- round done--------
I/jxcore-log( 2995): 
I/jxcore-log( 2995): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): do fake peer & start
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:08.176Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:28:08.182Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:08.183Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2995): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3054): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3054): aclStateChangeCallback: Device is NULL
,I/        ( 2995): Cleared service requests
,I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x43
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 70
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:28:39.050Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:39.051Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:39.052Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:28:44.053Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:44.054Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:28:49.058Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:49.059Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:49.060Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:28:49.060Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2995): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/jxcore-log( 2995): timeout now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): dun
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): done, now sending data to server
I/jxcore-log( 2995): 
I/jxcore-log( 2995): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): -- RESULT DATA {"name:":"LGE-Nexus 5_PT5777","time":1000088,"result":"TIMEOUT","sendList":[{"connections":1,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":1,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":1,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":1,"name":"58:2A:F7:ED:96:BE","time":0,"result":"Fail"},{"connections":1,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":1,"name
,I/jxcore-log( 2995): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 2995): 
I/jxcore-log( 2995): Results list does not contain any items
I/jxcore-log( 2995): 
I/jxcore-log( 2995): sendList failed peers count : 11 [100 %]
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 58:3F:54:73:64:C0, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 2995): 
I/jxcore-log( 2995): sendList never tried peers count : 7 [38.888888888888886 %]
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 2995): 
I/jxcore-log( 2995): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:29:05.986Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:29:05.989Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(6): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x44
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 71
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:29:39.694Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:29:39.694Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:29:39.695Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:29:44.696Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:29:44.697Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:29:49.700Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:29:49.701Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:29:49.701Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:29:49.702Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2995): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 5 peers.
I/SS      ( 2995): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x47
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3054): invalid rfc slot id: 72
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 2995): 2015-12-02T20:30:21.427Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:30:21.427Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:30:21.427Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2995): 2015-12-02T20:30:26.427Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:30:26.429Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/jxcore-log( 2995): 2015-12-02T20:30:31.432Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:30:31.433Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:30:31.434Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:30:31.434Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2995): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x40
,E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 73
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:31:02.406Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:31:02.407Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:31:02.408Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:31:07.409Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:31:07.410Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:31:12.412Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:31:12.413Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:31:12.414Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:31:12.414Z SendDataConnector.js: do connect now
I/jxcore-log( 2995): 
,I/        ( 2995): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 2995): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 2995): Starting to connect
W/BluetoothAdapter( 2995): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3054): service_uuid: 0bbfc6ef-14cc-4ab2-af63-b92e887227ae
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 6 peers.
I/SS      ( 2995): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 2995): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 2995): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3054): SDP - Rcvd conn cnf with error: 0x8  CID 0x45
E/bt-btif ( 3054): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3054): invalid rfc slot id: 74
,I/BTConnectToThread( 2995): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 2995): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 2995): 2015-12-02T20:31:43.356Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:31:43.359Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:31:43.368Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2995): 
I/jxcore-log( 2995): 2015-12-02T20:31:43.371Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2995): 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT785","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT785, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT785, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT2788","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT2788, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT2788, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 2995): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT7267"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT7267, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT7267, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 2995): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT7503","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT7503, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT7503, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 2995): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7328"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7328, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7328, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 10 peers.
I/SS      ( 2995): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 2995): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-smp  ( 3054): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3054): Plain text(LSB ~ MSB) = 40 a0 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3054): Encrypted text(LSB ~ MSB) = 69 e2 a2 ca da c9 8d c6 61 1c 42 5f 62 01 fc 1a 
,W/bt-btm  ( 3054): Stopping oneshot timer
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3064): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 7 peers.
I/SS      ( 2995): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(2): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(7): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 2995): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3384","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3384","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3384, peerAddress: 58:3F:54:73:64:C0
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3384, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 2995): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT1414","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT1414, peerAddress: B0:C5:59:3F:75:69
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT1414, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 2995): Cleared service requests
I/        ( 2995): Started peer discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 2995): Found 8 peers.
I/SS      ( 2995): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 2995): Peer(2): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 2995): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 2995): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 2995): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 2995): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 2995): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 2995): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2995): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 2995): Added service request
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 2995): Started service discovery
,I/wpa_supplicant( 3064): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3064): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3064): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 2995): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"}, typeCordovap2p._tcp.local.:
I/        ( 2995): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9856"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT9856, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT9856, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 2995): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT8756","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT8756, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT8756, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 2995): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3384","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
,I/        ( 2995): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3384","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3384, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 2995): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3384, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 2995): DBG, CoordinatorConnector command called
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
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
,I/        ( 2995): Stop Bluetooth
,I/        ( 2995): Stop Bluetooth
I/BTListenerThread( 2995): Stopped
,I/jxcore-log( 2995): StopBroadcasting went ok,
I/jxcore-log( 2995): 
,I/jxcore-log( 2995): 2015-12-02T20:33:25.811Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2995): 
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 2995): DBG, CoordinatorConnector command called
I/jxcore-log( 2995): 
I/jxcore-log( 2995): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"F8:95:C7:87:3C:51\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:14:E2:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:9D:93:0B\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:3F:54:73:64:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"
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
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3c6b0cdc mBinding = false
,D/BluetoothManagerService(  760): Message: 2
,D/BluetoothManagerService(  760): Sending off request.
,D/BluetoothAdapterState( 3054): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3054): Setting state to 13
I/BluetoothAdapterState( 3054): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3054): onBluetoothDisable()
I/BluetoothAdapterState( 3054): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3054): Scan Mode:20
,D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3054): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3054): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3054): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3054): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3054): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3054): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3054): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3054): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3054): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3054): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3054): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3054): onReceive
D/BluetoothMapService( 3054): STATE_TURNING_OFF
V/BluetoothMapService( 3054): Handler(): got msg=4
D/BluetoothMapService( 3054): MAP Service closeService in
D/BluetoothMapMasInstance( 3054): MAP Service shutdown
V/BluetoothMapService( 3054): MAP Service closeService out
,I/BtOppRfcommListener( 3054): stopping Accept Thread
,I/BtOppRfcommListener( 3054): BluetoothSocket listen thread finished
,D/WifiService(  760): setWifiEnabled: false pid=2995, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
W/ContextImpl( 3065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/jxcore-log( 2995): Radios toggled
I/jxcore-log( 2995): 
I/chromium( 2995): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
D/DockEventReceiver( 3065): finishStartingService: stopping service
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/AuthorizationBluetoothService( 1446): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 3065): Proxy object disconnected
D/PbapServerProfile( 3065): Bluetooth service disconnected
,D/bt_userial( 3054): RX termination
W/bt_userial( 3054): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3054): Leaving userial_read_thread()
W/bt-btif ( 3054): ag scb idx 1 not allocated
E/bt-btif ( 3054): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3054): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3054): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3054): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3054): hw_epilog_process
I/bt_userial_vendor( 3054): device fd = 53 close
,I/GKI_LINUX( 3054): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3054): GKI_exit_task 0 done
I/GKI_LINUX( 3054): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3054): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,D/HeadsetStateMachine( 3054): Exit Disconnected: -1
,D/BluetoothHeadset(  760): Proxy object disconnected
,D/BluetoothHeadset( 1179): Proxy object disconnected
,D/BluetoothHeadset( 1208): Proxy object disconnected
D/BluetoothHeadset( 3065): Proxy object disconnected
D/HeadsetProfile( 3065): Bluetooth service disconnected
D/BluetoothHeadset( 1179): Proxy object disconnected
,D/A2dpService( 3054): Received stop request...Stopping profile...
D/A2dpStateMachine( 3054): Exit Disconnected: -1
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,D/BluetoothAdapterState( 3054): Stopping profile services that were post enabled
D/BluetoothA2dp(  760): Proxy object disconnected
,D/HidService( 3054): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
D/BluetoothA2dp( 3065): Proxy object disconnected
D/A2dpProfile( 3065): Bluetooth service disconnected
,D/HealthService( 3054): Received stop request...Stopping profile...
D/BluetoothInputDevice( 3065): Proxy object disconnected
D/HidProfile( 3065): Bluetooth service disconnected
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,D/HeadsetStateMachine( 3054): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3054): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3054): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 3054): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,D/BtGatt.DebugUtils( 3054): handleDebugAction() action=null
,D/BluetoothPan( 3065): BluetoothPAN Proxy object disconnected
,D/PanProfile( 3065): Bluetooth service disconnected
D/BtGatt.GattService( 3054): Received stop request...Stopping profile...
D/BtGatt.GattService( 3054): stop()
D/BtGatt.AdvertiseManager( 3054): advertise clients cleared
,D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,D/BluetoothMapService( 3054): Received stop request...Stopping profile...
,D/BluetoothMapService( 3054): stop()
,D/BluetoothMapEmailAppObserver( 3054): deinitObservers()
D/BluetoothMapEmailAppObserver( 3054): removeReceiver()
D/BluetoothAdapterService( 3054): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3df99c76
,D/BluetoothMap( 3065): Proxy object disconnected
D/MapProfile( 3065): Bluetooth service disconnected
,I/GKI_LINUX( 3054): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3054): GKI_exit_task 2 done
I/GKI_LINUX( 3054): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3054): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 3054): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3054): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3054): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3054): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3054): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3054): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3054): Handler(): got msg=4
D/BluetoothMapService( 3054): MAP Service closeService in
V/BluetoothMapService( 3054): MAP Service closeService out
,D/BluetoothAdapterState( 3054): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3054): Setting state to 10
I/BluetoothAdapterState( 3054): Bluetooth adapter state changed: 13-> 10
,D/BluetoothMapService( 3054): cleanup()
,D/BluetoothMapService( 3054): MAP Service closeService in
,V/BluetoothMapService( 3054): MAP Service closeService out
D/BluetoothManagerService(  760): Message: 60
,D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
,D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothPbap( 3065): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3054): Entering OffState
D/BluetoothMap( 3065): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1179): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1179): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1208): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3065): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  760): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3065): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3065): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  760): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  760): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3c6b0cdc mBinding = false
,D/BluetoothManagerService(  760): Sending unbind request.
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  895): 147086507: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  895): 147086507: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  895): 147086507: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3054): gki_task task_id=1 [BTIF] terminating
,D/BluetoothAdapter( 1287): 693758403: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1287): 693758403: getState() :  mService = null. Returning STATE_OFF
I/GKI_LINUX( 3054): GKI_exit_task 1 done
I/GKI_LINUX( 3054): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 3054): cleanupNative: return from cleanup
,W/ContextImpl( 3065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/art     ( 3054): System.exit called, status: 0
I/AndroidRuntime( 3054): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 3065): finishStartingService: stopping service
,D/AndroidRuntime( 3895): 
D/AndroidRuntime( 3895): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3895): CheckJNI is OFF
,I/ActivityManager(  760): Process com.android.bluetooth (pid 3054) has died
,D/AndroidRuntime( 3895): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 2995:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  760): Skipping PackageSetting{1465edd9 com.example.hello/10277} due to missing metadata
,I/WindowState(  760): WIN DEATH: Window{b52569e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{2066534a u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{19268761 2995:com.test.thalitest/u0a270}, curProc for 2995: null
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1354): Explicit concurrent mark sweep GC freed 50986(2MB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 19MB/25MB, paused 323us total 40.926ms
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1287): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1069): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1069): run()
,I/art     ( 1226): Explicit concurrent mark sweep GC freed 3946(293KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.350ms total 61.564ms
,D/BluetoothAdapter( 3065): 400077585: getState() :  mService = null. Returning STATE_OFF
I/Decoder ( 1069): createOrResetDecoder
,I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  945): Initialized EGL, version 1.4
,I/art     (  760): Explicit concurrent mark sweep GC freed 76982(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/42MB, paused 1.079ms total 94.722ms
,I/ActivityManager(  760): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3956 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/art     (  760): WaitForGcToComplete blocked for 74.798ms for cause Explicit
D/OpenGLRenderer(  945): Enabling debug mode 0
,I/ConfigService( 1446): onCreate
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@1e29e940 (uid=10034 pid=945)
,W/ResourcesManager( 3956): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1069): run()
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2995 uid 10270
I/Keyboard.Facilitator( 1069): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1069): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1069): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1069): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1069): run()
I/StatsUtilsManager( 1069): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1069): shouldRecordStats() = Too Soon
,I/Launcher( 1226): Deferring update until onResume
,D/AdapterServiceConfig( 3956): Adding HeadsetService
D/AdapterServiceConfig( 3956): Adding A2dpService
D/AdapterServiceConfig( 3956): Adding HidService
D/AdapterServiceConfig( 3956): Adding HealthService
D/AdapterServiceConfig( 3956): Adding PanService
D/AdapterServiceConfig( 3956): Adding GattService
D/AdapterServiceConfig( 3956): Adding BluetoothMapService
,I/ActivityManager(  760): Killing 1429:com.google.android.partnersetup/u0a13 (adj 15): empty #17
W/ResourcesManager( 1226): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  760): Explicit concurrent mark sweep GC freed 18003(943KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.196ms total 152.766ms
,W/ResourcesManager( 1226): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1226): Deferring update until onResume
,D/AuthorizationBluetoothService( 1446): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_1429/cgroup.procs: No such file or directory
,D/AndroidRuntime( 3895): Shutting down VM
,I/ActivityManager(  760): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3981 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,D/VoicemailCleanupService( 3981): Cleaning up data for package: com.test.thalitest
,I/UpdateIcingCorporaServi( 1354): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1226): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3df99c76 new=com.google.android.velvet.VelvetApplication@3df99c76
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4003 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ContactLocale( 3981): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/UpdateIcingCorporaServi( 1354): UpdateCorporaTask done [took 93 ms] updated apps [took 93 ms] 
,I/art     ( 1553): Explicit concurrent mark sweep GC freed 26636(1748KB) AllocSpace objects, 19(304KB) LOS objects, 25% free, 22MB/29MB, paused 493us total 38.832ms
,W/ContextImpl( 4003): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1553): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1553): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1553): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1553): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1553): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1553): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1553): Removing dialog suppression flag for package com.test.thalitest
,I/ActivityManager(  760): Killing 2902:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1553): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1553): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1553): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1553): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1553): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1553): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1553): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1553): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1553): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1553): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1553): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1553): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1553): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/libprocessgroup(  760): failed to open /acct/uid_10040/pid_2902/cgroup.procs: No such file or directory
,E/NetworkScheduler.SchedulerReceiver( 1446): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1446): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,E/SQLiteLog( 3981): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 3981): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 3981): Process: android.process.acore, PID: 3981
E/AndroidRuntime( 3981): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3981): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3981): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 3981): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3981): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3981): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 3981): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 3981): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 3981): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 3981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3981): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3981): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4043 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Process ( 3981): Sending signal. PID: 3981 SIG: 9
,E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  760): Process android.process.acore (pid 3981) has died
,W/BaseAppContext( 1553): Using Auth Proxy for data requests.

```
