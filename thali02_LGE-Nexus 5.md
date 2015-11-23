#### Test 51517283acd5ddf_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2924): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2924): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
V/JNIHelp ( 2924): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/Finsky  ( 2449): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  734): Killing 2270:com.google.android.youtube/u0a80 (adj 15): empty #17
W/System  ( 2924): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2924): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  734): failed to open /acct/uid_10080/pid_2270/cgroup.procs: No such file or directory
V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1624): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1624): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1624): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 2976): 
D/AndroidRuntime( 2976): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2976): CheckJNI is OFF
D/AndroidRuntime( 2976): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  734): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3000 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2976): Shutting down VM
V/ActivityManager(  734): Display changed displayId=0
I/WebViewFactory( 3000): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3000): Time to load native libraries: 2 ms (timestamps 9021-9023)
I/LibraryLoader( 3000): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3000): Binding Chromium to main looper Looper (main, tid 1) {277dcd07}
I/LibraryLoader( 3000): Expected native library version number "",actual native library version number ""
I/chromium( 3000): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3000): Initializing chromium process, singleProcess=true
W/art     ( 3000): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3000): ApplicationContext is null in ApplicationStatus
W/chromium( 3000): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3000): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3000): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3000): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3000): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10a98b70:true
,D/BluetoothAdapter( 3000): 590145881: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3000): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3000): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3000): CordovaWebView is running on device made by: LGE
,W/art     ( 3000): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3000): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3000): Render dirty regions requested: true
,D/Atlas   ( 3000): Validating map...
,W/chromium( 3000): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3000): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3000): Enabling debug mode 0
,W/IInputConnectionWrapper( 3000): showStatusIcon on inactive InputConnection
,W/BindingManager( 3000): Cannot call determinedVisibility() - never saw a connection for the pid: 3000
,I/ActivityManager(  734): Displayed com.test.thalitest/.MainActivity: +435ms (total +56s957ms)
,D/JsMessageQueue( 3000): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3000): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3000): jxcore cordova android initializing
,I/ActivityManager(  734): Killing 2362:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10038/pid_2362/cgroup.procs: No such file or directory
,W/jxcore-log( 3000): Initializing JXcore engine
W/jxcore-log( 3000): JXcore engine is ready
,W/jxcore-log( 3000): Starting JXcore engine
,W/.test.thalitest( 3000): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6444]" dev="sockfs" ino=6444 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3000): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3000): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9608]" dev="sockfs" ino=9608 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3000): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18401]" dev="sockfs" ino=18401 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3000): Platform android
W/jxcore-log( 3000): 
W/jxcore-log( 3000): Process ARCH arm
W/jxcore-log( 3000): 
,I/jxcore-log( 3000): JXcore Cordova bridge is ready!
I/jxcore-log( 3000): 
W/jxcore-log( 3000): JXcore engine is started
I/Choreographer( 3000): Skipped 102 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3000): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3000): Turning radios to true
I/jxcore-log( 3000): 
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  734): Message: 1
D/BluetoothManagerService(  734): MESSAGE_ENABLE: mBluetooth = null
,I/jxcore-log( 3000): toggleBluetooth - 
I/jxcore-log( 3000): 
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: true pid=3000, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  181): Softap fwReload - Ok
,I/ActivityManager(  734): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3058 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring down wlan0
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/WifiMonitor(  734): startMonitoring(wlan0) with mConnected = false
,I/jxcore-log( 3000): toggleWiFi
I/jxcore-log( 3000): 
,I/ActivityManager(  734): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3069 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3065): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3065): rfkill: Cannot open RFKILL control device
,W/ResourcesManager( 3058): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@168498f7:true
,D/BluetoothAdapter( 3069): 662555911: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  734): Message: 30
,D/BluetoothManagerService(  734): Message: 30
,D/LocalBluetoothProfileManager( 3069): Adding local MAP profile
,D/BluetoothMap( 3069): Create BluetoothMap proxy object
,D/BluetoothManagerService(  734): Message: 30
,D/BluetoothManagerService(  734): Message: 30
,D/LocalBluetoothProfileManager( 3069): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3069): 662555911: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3069): 662555911: getState() :  mService = null. Returning STATE_OFF
,D/AdapterServiceConfig( 3058): Adding HeadsetService
D/AdapterServiceConfig( 3058): Adding A2dpService
D/AdapterServiceConfig( 3058): Adding HidService
D/AdapterServiceConfig( 3058): Adding HealthService
,D/AdapterServiceConfig( 3058): Adding PanService
D/AdapterServiceConfig( 3058): Adding GattService
D/AdapterServiceConfig( 3058): Adding BluetoothMapService
,I/ActivityManager(  734): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3106 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2411:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@339d603d:true
,D/BluetoothAdapterState( 3058): make
,I/bluedroid( 3058): init
,I/BluetoothAdapterState( 3058): Entering OffState
,I/bte_conf( 3058): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3058): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3058): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3058): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3058): get_profile_interface socket
I/bluedroid( 3058): get_profile_interface map_client
,I/GKI_LINUX( 3058): gki_task_entry task_id=1 [BTIF] starting
,W/libprocessgroup(  734): failed to open /acct/uid_10069/pid_2411/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 3058): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3058): Name is: Nexus 5
,D/BluetoothManagerService(  734): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  734): Message: 40
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3058): config_hci_snoop_log
,D/BluetoothManagerService(  734): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  734): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 3058): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3058): Setting state to 11
I/BluetoothAdapterState( 3058): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3058): make
D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  734): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,D/BluetoothManagerService(  734): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  734): Stored Bluetooth name: Nexus 5
,D/BluetoothHeadset(  734): Proxy object connected
D/HeadsetService( 3058): Received start request. Starting profile...
D/BluetoothHeadset( 1181): Proxy object connected
D/BluetoothHeadset( 1181): Proxy object connected
D/BluetoothHeadset( 1235): Proxy object connected
I/BluetoothHeadsetServiceJni( 3058): classInitNative: succeeds
D/HeadsetStateMachine( 3058): make
,D/HeadsetStateMachine( 3058): max_hf_connections = 1
I/bluedroid( 3058): get_profile_interface handsfree
,I/BluetoothAdapterState( 3058): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3058): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
,D/BluetoothA2dp(  734): Proxy object connected
,D/A2dpService( 3058): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3058): classInitNative: succeeds
,I/bluedroid( 3058): get_profile_interface avrcp
,E/RemoteController( 3058): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3058): classInitNative: succeeds
D/A2dpStateMachine( 3058): make
,I/bluedroid( 3058): get_profile_interface a2dp
I/GKI_LINUX( 3058): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
I/BluetoothHidServiceJni( 3058): classInitNative: succeeds
,D/A2dpStateMachine( 3058): Enter Disconnected: -2
,D/BluetoothInputDevice( 3069): Proxy object connected
D/HidService( 3058): Received start request. Starting profile...
I/bluedroid( 3058): get_profile_interface hidhost
D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
D/HidProfile( 3069): Bluetooth service connected
I/BluetoothHealthServiceJni( 3058): classInitNative: succeeds
,D/HealthService( 3058): Received start request. Starting profile...
,I/bluedroid( 3058): get_profile_interface health
,D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
I/BluetoothPanServiceJni( 3058): classInitNative(L105): succeeds
,D/BluetoothPan( 3069): BluetoothPAN Proxy object connected
D/PanService( 3058): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 3058): initializeNative(L110): pan
I/bluedroid( 3058): get_profile_interface pan
D/PanProfile( 3069): Bluetooth service connected
,D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
I/BtGatt.JNI( 3058): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3058): handleDebugAction() action=null
D/BtGatt.GattService( 3058): Received start request. Starting profile...
D/BtGatt.GattService( 3058): start()
I/bluedroid( 3058): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3058): advertise manager created
D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
V/BluetoothMapService( 3058): BluetoothMapBinder()
D/HeadsetStateMachine( 3058): Proxy object connected
D/BluetoothMap( 3069): Proxy object connected
D/BluetoothMapService( 3058): Received start request. Starting profile...
D/BluetoothMapService( 3058): start()
D/MapProfile( 3069): Bluetooth service connected
D/BluetoothMap( 3069): getConnectedDevices()
D/BluetoothMap( 3069): Bluetooth is Not enabled
D/BluetoothMapEmailSettingsLoader( 3058): Found 0 applications
D/BluetoothMapEmailAppObserver( 3058): createReceiver()
,D/BluetoothMapEmailAppObserver( 3058): initObservers()
D/BluetoothMapEmailAppObserver( 3058): getEnabledAccountItems()
D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
D/HeadsetStateMachine( 3058): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3058): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 3058): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3058): Handler(): got msg=1
D/BluetoothAdapterState( 3058): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3058): enable
,I/bt_hci_bdroid( 3058): init
I/GKI_LINUX( 3058): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3058): btu_task pending for preload complete event
I/bt_vendor( 3058): init
I/bt_vnd_conf( 3058): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3058): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3058): userial_init
,I/bt_userial_vendor( 3058): userial vendor open: opening /dev/ttyHS99
I/bt_userial_vendor( 3058): device fd = 53 open
D/bt_userial( 3058): Entering userial_read_thread()
,I/art     ( 1362): Explicit concurrent mark sweep GC freed 9535(554KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 752us total 21.015ms
,I/bt_hwcfg( 3058): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3058): Chipset BCM4335C0
D/bt_hwcfg( 3058): Target name = [BCM4335C0]
,I/bt_hwcfg( 3058): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1362): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  734): Killing 1818:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10045/pid_1818/cgroup.procs: No such file or directory
,D/Tethering(  734): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3065): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3065): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  734): Loading config and enabling all networks 
,D/WifiService(  734): New client listening to asynchronous messages
,E/WifiConfigStore(  734): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/art     (  734): Explicit concurrent mark sweep GC freed 17699(886KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.142ms total 84.093ms
,D/WifiNative-HAL(  734): Setting external_sim to 1
W/Settings( 1843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  734): Setting OUI to DA-A1-19
I/WifiNative-HAL(  734): startHal
,D/wifi    (  734): setting scan oui 0x9687ead8
D/WifiHAL (  734): Sending mac address OUI
E/WifiHAL (  734): failed to set scanning mac OUI; result = -95
,E/native  (  734): do suspend true
,D/WifiScanningService(  734): SCAN_AVAILABLE : 3
,D/RttService(  734): SCAN_AVAILABLE : 3
D/WifiScanningService(  734): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  734): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  734): startHal
,D/CommandListener(  181): Setting iface cfg
D/CommandListener(  181): Trying to bring up p2p0
D/WifiMonitor(  734): startMonitoring(p2p0) with mConnected = true
D/wifi    (  734): getting scan capabilities on interface[1] = 0x9687ead8
D/WifiHAL (  734): Creating message to get scan capablities; iface = 21
D/WifiHAL (  734): In GetCapabilities::handleResponse
D/WifiHAL (  734): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  734): StartedState
,D/WifiNative-HAL(  734): p2pGetDeviceAddress
,D/WifiNative-HAL(  734): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3058): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3058): Settlement delay -- 100 ms
I/bt_hwcfg( 3058): Setting fw settlement delay to 100 
,I/wpa_supplicant( 3065): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3058): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 3058): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3058): vendor lib fwcfg completed
,I/bt-btu  ( 3058): btu_task received preload complete event
,I/        ( 3058): BTE_InitTraceLevels -- TRC_HCI,
I/        ( 3058): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3058): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3058): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3058): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3058): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3058): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3058): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3058): BTE_InitTraceLevels -- TRC_GAP
,I/        ( 3058): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3058): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3058): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3058): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3058): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3058): BTE_InitTraceLevels -- TRC_BTIF
,W/NetworkUtils( 1344): OkHttp exception
W/EventLoggerService( 1344): Unable to send logs Error code: 262146
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/bt-btm  ( 3058): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ad99d5 
,E/bt-btm  ( 3058): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ad99d5 
,E/bt-btif ( 3058): Calling BTA_HhEnable
E/bt-btif ( 3058): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3058): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3058): Name is: Nexus 5
D/BluetoothManagerService(  734): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  734): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3058): Scan Mode:20
D/BluetoothAdapterProperties( 3058): Discoverable Timeout:120
,D/bte_conf( 3058): Device ID record 1 : primary
D/bte_conf( 3058):   vendorId            = 000f
D/bte_conf( 3058):   vendorIdSource      = 0001
D/bte_conf( 3058):   product             = 1200
D/bte_conf( 3058):   version             = 1436
D/bte_conf( 3058):   clientExecutableURL = 
D/bte_conf( 3058):   serviceDescription  = 
D/bte_conf( 3058):   documentationURL    = 
,D/bte_conf( 3058): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3058): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3058): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3058): ScanMode =  20
D/BluetoothAdapterProperties( 3058): State =  11
D/BluetoothAdapterProperties( 3058): Setting state to 12
I/BluetoothAdapterState( 3058): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  734): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothMap( 3069): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3058): Entering On State
,D/BluetoothAdapterProperties( 3058): Scan Mode:21
D/BluetoothAdapterProperties( 3058): Discoverable Timeout:120
D/BluetoothHeadset( 1235): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1181): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3069): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  734): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1181): onBluetoothStateChange: up=true
D/BluetoothPbap( 3069): onBluetoothStateChange: up=true
D/BluetoothHeadset(  734): onBluetoothStateChange: up=true
D/BluetoothPan( 3069): onBluetoothStateChange(on) call bindService
D/BluetoothManagerService(  734): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  734): Bluetooth State Change Intent: 11 -> 12
,E/bt_h4   ( 3058): vendor lib postload completed
,W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = 7d 74 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = c1 24 9e 22 5d eb c4 56 d2 64 c8 1d 20 75 5c c8 
W/bt-btm  ( 3058): Stopping oneshot timer
,D/BluetoothMapService( 3058): onReceive
,D/BluetoothMapService( 3058): STATE_ON
V/BluetoothMapService( 3058): Handler(): got msg=1
D/BluetoothMapMasInstance( 3058): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3058): MAS initSocket()
D/BluetoothMapMasInstance( 3058):   masId = 00
D/BluetoothMapMasInstance( 3058):   msgTypes = 0e
D/BluetoothMapMasInstance( 3058):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3058):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = 9c be 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = d0 b9 d0 ff 2b 61 36 60 cd 2a ee 33 5d b6 34 de 
W/bt-btm  ( 3058): Stopping oneshot timer
W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = aa c1 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = 74 76 5d 5c de 78 43 56 77 28 9c 0d 6e 44 3b c4 
W/bt-btm  ( 3058): Stopping oneshot timer
D/BluetoothManagerService(  734): Message: 40
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = bb 4c 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = ac 73 48 d6 a0 73 3d 79 a1 03 98 bb 99 dc b7 2c 
W/bt-btm  ( 3058): Stopping oneshot timer
I/Telecom ( 1181): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = ea f5 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = 01 0d 49 9b d1 b7 85 64 d7 d5 2b 27 a8 1f 36 48 
W/bt-btm  ( 3058): Stopping oneshot timer
W/BluetoothAdapter( 3058): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 3058): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3058): Accepting socket connection...
D/HeadsetStateMachine( 3058): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 3058): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3058): mNumber:  mType: 128
D/HeadsetStateMachine( 3058): terminateScoUsingVirtualVoiceCall: Received
,E/HeadsetStateMachine( 3058): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/LocalBluetoothProfileManager( 3069): Adding local A2DP profile
D/BluetoothManagerService(  734): Message: 30
D/LocalBluetoothProfileManager( 3069): Adding local HEADSET profile
W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = 18 98 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = 1b 40 ae 03 cc 45 3a bf d7 24 67 bd 16 49 c3 4a 
W/bt-btm  ( 3058): Stopping oneshot timer
D/BluetoothManagerService(  734): Message: 30
W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = c4 97 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = 61 ab 8e 01 57 f5 27 a6 cf b5 89 2a d5 0c e2 b8 
,W/bt-btm  ( 3058): Stopping oneshot timer
,W/ContextImpl( 3069): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothA2dp( 3069): Proxy object connected
,D/A2dpProfile( 3069): Bluetooth service connected
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3058): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothHeadset( 3069): Proxy object connected
D/HeadsetProfile( 3069): Bluetooth service connected
,D/DockEventReceiver( 3069): finishStartingService: stopping service
,D/BluetoothPbap( 3069): Proxy object connected
D/PbapServerProfile( 3069): Bluetooth service connected
,D/AuthorizationBluetoothService( 1362): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3058): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3058): Accept thread started.
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3000): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): my name is : LGE-Nexus 5_PT566
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): attempting to connect to test coordinator
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): check test folder
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found test : ./testFindPeers.js
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found test : ./testReConnect.js
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found test : ./testSendData.js
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Test app app.js loaded
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): LogCallback not set !!!!
I/jxcore-log( 3000): 
,I/Choreographer( 3000): Skipped 126 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3000): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  734): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  734): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  734): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  734): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  734): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  734): will read network variables netId=1
E/WifiStateMachine(  734): CMD_AUTO_CONNECT did save config ->  nid=1
E/WifiConfigStore(  734): will read network variables netId=1
,I/wpa_supplicant( 3065): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  734): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3065): PNO: In assoc process
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ENETUNREACH","errno":"ENETUNREACH","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3065): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3065): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  734): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  181): Setting iface cfg
,E/WifiStateMachine(  734): Start Dhcp Watchdog 1
,E/native  (  734): do suspend false
,E/WifiStateMachine(  734): scanCount==0 - aborting
,I/dhcpcd  ( 3243): version 5.5.6 starting
,E/dhcpcd  ( 3243): get_duid: Read-only file system
,I/dhcpcd  ( 3243): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3243): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3243): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  734): do suspend true
,E/WifiStateMachine(  734): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  734): Adding iface wlan0 to network 100
,E/ConnectivityService(  734): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  734): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  734): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  734): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  734): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  734): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  734): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  734):    accepting network in place of null
,D/ConnectivityService(  734): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  734): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 23 Nov 2015 15:37:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448293058235], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448293058218]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Validated
D/ConnectivityService(  734): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  734): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  734): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  734): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
D/TelephonyNetworkFactory( 1235): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3000): 
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  734): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2538): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2538): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  734): Setting time of day to sec=1448293061
,W/AlarmManagerService(  734): Unable to set rtc to 1448293061: Invalid argument
,I/iu.SyncManager( 1624): SYNC; picasa accounts
,E/GpsLocationProvider(  734): No APN found to select.
,D/NetworkLogImpl( 1624): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1624): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1624): num queued entries: 0
,I/iu.UploadsManager( 1624): num updated entries: 0
I/iu.SyncManager( 1624): NEXT; no task
,D/ChimeraCfgMgr( 1624): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1624): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1624): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1624): onCreate
,D/SystemUpdateService( 1624): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1624): active receiver: enabled
,D/GpsLocationProvider(  734): NTP server returned: 1448293061828 (Mon Nov 23 16:37:41 GMT+01:00 2015) reference: 88971 certainty: 12 system time offset: -66
E/LocSvc_eng(  734): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/SystemUpdateService( 1624): showing system update notification
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  734): skipping global notification
,V/SystemUpdateService( 1624): retry (wakeup: false) in 3599972 ms
,I/ActivityManager(  734): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3348 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1624): onDestroy
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 387us total 18.177ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 360us total 15.185ms
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 364us total 15.117ms
,I/Babel   ( 1843): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1624): [CredentialSyncAdapter] Unknown sync event.
,I/GAv4    ( 3348): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3348):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3348):   adb logcat -s GAv4
,E/ConnectivityChangeReceiver( 1624): Ignoring connectivity change
,W/GAv4    ( 3348): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  734): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  734): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  734): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1624): CM callback handler got msg 524290
,W/GAv4    ( 3348): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3348): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1362): GCM config loaded
,W/DriveInitializer( 1624): Awaiting to be initialized
,W/DriveInitializer( 1624): Background init thread started
,I/art     ( 1362): Explicit concurrent mark sweep GC freed 14125(759KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 19MB/32MB, paused 725us total 26.930ms
,I/WebViewFactory( 3348): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3348): Time to load native libraries: 2 ms (timestamps 9448-9450)
I/LibraryLoader( 3348): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3348): Binding Chromium to main looper Looper (main, tid 1) {262face1}
,I/LibraryLoader( 3348): Expected native library version number "",actual native library version number ""
I/chromium( 3348): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3348): Initializing chromium process, singleProcess=true
,W/art     ( 3348): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3348): ApplicationContext is null in ApplicationStatus
,W/chromium( 3348): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3348): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3348): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3348): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
W/DriveInitializer( 1624): Background init thread ended
,W/AudioManagerAndroid( 3348): Requires BLUETOOTH permission
,I/NSApplication( 3348): Starting up...
,W/art     ( 2625): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  734): Explicit concurrent mark sweep GC freed 44857(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.055ms total 52.155ms
,I/ActivityManager(  734): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3445 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3445): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448293062589
D/        ( 3445): TimeServiceNative: User Time to be set is 1448293062589
D/QC-time-services( 3445): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3445): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3445): Lib:time_genoff_operation: pargs->ts_val = 1448293062589
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3445): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448293062589
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1448293062589, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/27/70 21:28:34
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 7421314000
D/QC-time-services(  199): Daemon:new time 1448293062589 
D/QC-time-services(  199): Daemon: delta 1440871748589 genoff 1440871748589 
,D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871748589 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871748589 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
,D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1132328262589
E/QC-time-services( 3445): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  734): Killing 2507:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  734): failed to open /acct/uid_10003/pid_2507/cgroup.procs: No such file or directory
,I/CheckinService( 1624): Checkin interval check for package: unspecified last checkin: 1448260896395 min interval config: 0 actual interval: 32166268
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3468 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3468): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3468):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3468):   adb logcat -s GAv4
,W/GAv4    ( 3468): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3468): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3468): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Killing 2384:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10070/pid_2384/cgroup.procs: No such file or directory
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ActivityManager(  734): Killing 1982:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10002/pid_1982/cgroup.procs: No such file or directory
,D/Finsky  ( 2449): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2449): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  734): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3509 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3509): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3509): Created com.android.providers.calendar.CalendarAlarmManager@385df746(com.android.providers.calendar.CalendarProvider2@277dcd07)
,E/SQLiteLog( 3509): (284) automatic index on view_events(_id)
,I/CalendarProvider2( 3509): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3509): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1362): Vacuum at: now=1448293071741 tag=VacuumService
,D/UdcCache:FPQuery( 1624): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1362): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1362): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  734): Killing 2805:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10008/pid_2805/cgroup.procs: No such file or directory
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1362):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1362): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/ClearcutLoggerApiImpl( 1317): disconnect managed GoogleApiClient
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
,I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Killing 1382:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10004/pid_1382/cgroup.procs: No such file or directory
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Error:{"type":"connect_error","data":{"type":"TransportError","description":{"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","type":"error","target":{"domain":null,"_events":{},"_maxListeners":10,"_socket":null,"_ultron":null,"_closeReceived":false,"bytesReceived":0,"readyState":0,"supports":{"binary":true},"extensions":{},"_isServer":false,"url":"ws://31.179.131.238:3000/socket.io/?EIO=3&transport=websocket","protocolVersion":13,"binaryType":"arraybuffer"}}}} : connect_error : [object Object]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback Client error: connect_error", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector connect called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Coordinator is now connected to the server!
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): printNetworkInfo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: lo
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : true, has ip: 127.0.0.1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): found interfaceName: wlan0
I/jxcore-log( 3000): 
I/jxcore-log( 3000): -iface: IPv4 is internal : false, has ip: 192.168.1.114
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): DBG, CoordinatorConnector command called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":\"1000000\",\"rounds\":\"1\",\"dataTimeout\":\"10000\",\"dataAmount\":\"100000\",\"conReTryTimeout\":\"4000\",\"conReTryCount\":\"1\"}","devices":19,"addressList":[{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"
I/jxcore-log( 3000): Start now : testSendData.js
I/jxcore-log( 3000): 
I/jxcore-log( 3000): stop tests now !
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): testSendData created {"timeout":"1000000","rounds":"1","dataTimeout":"10000","dataAmount":"100000","conReTryTimeout":"4000","conReTryCount":"1"}, bt-address lenght : 19
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): check server
I/jxcore-log( 3000): 
I/jxcore-log( 3000): serverPort is 58757
I/jxcore-log( 3000): 
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3000): Stoping All
I/        ( 3000): Stopping services
I/        ( 3000): Stop Bluetooth
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3000): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3000):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT566","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3000): All stuff available and enabled
I/        ( 3000): Stoping All
I/        ( 3000): Stopping services
I/        ( 3000): Stop Bluetooth
I/        ( 3000): Starting All
I/        ( 3000): Stopping services
I/        ( 3000): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT566","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@b5d30c5
I/        ( 3000): Stopping services
I/        ( 3000): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT566","ra":"34:FC:EF:11:AE:67"}
I/        ( 3000): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT566","ra":"34:FC:EF:11:AE:67"}, length : 76
,I/        ( 3000): peerDiscoveryTimer timeout value:6950
,I/        ( 3000): Stop Bluetooth
I/        ( 3000): StartBluetooth listener
I/        ( 3000): StartBluetooth listener
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3000): StartBroadcasting started ok
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server  is bound to : undefined
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3000): We already were running, thus doing nothing
,I/        ( 3000): Added local service
I/        ( 3000): Cleared service requests
I/        ( 3000): Stopped peer discovery
I/        ( 3000): Started peer discovery
,I/        ( 3000): Discovery state changed to Started.
,I/BTListenerThread( 3000): starting to listen
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3000): Found 2 peers.
I/SS      ( 3000): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3000): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3000): Connect (retry count 0) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 7C:F9:0E:37:96:AB, name: null
,I/        ( 3000): Connecting to null, at 7C:F9:0E:37:96:AB
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5861","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT5861
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, samsung-SM-A300FU_PT5861
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): Creating BTConnectedThread
,I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81724 bytes of data,
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 4
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5861
,I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5861
I/BtToSocketBase( 3000): Close LocalOutputStream
,I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Close bt out
,I/BtToSocketBase( 3000): Close bt socket
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e8bcdd7:true
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: A3-1
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c50ebc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
I/BluetoothBondStateMachine( 3058): sspRequestCallback: [B@15ce6f56 name: [B@2155cbd7 cod: 5898764 pairingVariant 0 passkey: 477555
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c50ebc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3000): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-A500FU_PT5540
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-A500FU_PT5540
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-A500FU_PT5540
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 35631
I/BtConnectorHelper( 3000): Request socket is using : 35631
,I/BtToRequestSocket( 3000): Now accepting connections
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :35631
,I/jxcore-log( 3000): CLIENT connected to 35631, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 35631
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51414 rs_disc_pending=0
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 27495 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-A500FU_PT5540
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3000): Connect (retry count 0) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3000): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 7
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9185 ms, rnd: 1, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3000): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c517a4 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c517a4 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3058): invalid rfc slot id: 8
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 10069 ms, rnd: 1, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
E/bt-btif ( 3058): Do not find the bg connection mask for the remote device
,E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 9 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: B4:CE:F6:AB:A4:6A
,D/BluetoothMapService( 3058): onReceive
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3000): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-A300FU_PT7297
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-A300FU_PT7297
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-A300FU_PT7297
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 58475
I/BtConnectorHelper( 3000): Request socket is using : 58475
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :58475
I/jxcore-log( 3000): CLIENT connected to 58475, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 58475
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16787
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3058): dm_pm_timer expires
W/bt-btif ( 3058): dm_pm_timer expires 0
W/bt-btif ( 3058): proc dm_pm_timer expires
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 7 peers.
I/SS      ( 3000): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3000): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3000): Peer(7): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3000): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: , WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3000): Receiving data timeout now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-A300FU_PT7297
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Stop data retrieving timer
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ----------------- closeClientSocket
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 18108 ms, rnd: 1, ex: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3000): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7297
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7297
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 44376 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3000): 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 10
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3000): 
I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9188 ms, rnd: 1, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 6
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7297
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x4d
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3000): Found 8 peers.
I/SS      ( 3000): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3000): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3000): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3000): Peer(7): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 3000): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 3000): Connect (retry count 0) to peer F8:CF:C5:D9:E5:61 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: F8:CF:C5:D9:E5:61, name: null
,I/        ( 3000): Connecting to null, at F8:CF:C5:D9:E5:61
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT7032","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : motorola-Nexus 6_PT7032
I/HS      ( 3000): Hand Shake finished outgoing for : motorola-Nexus 6_PT7032
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, motorola-Nexus 6_PT7032
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 55452
,I/BtConnectorHelper( 3000): Request socket is using : 55452
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :55452
,I/jxcore-log( 3000): CLIENT connected to 55452, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 55452
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 7668 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: motorola-Nexus 6_PT7032
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Nexus 6
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1820"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : LGE-Nexus 5_PT1820
I/HS      ( 3000): Hand Shake finished outgoing for : LGE-Nexus 5_PT1820
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, LGE-Nexus 5_PT1820
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 55691
I/BtConnectorHelper( 3000): Request socket is using : 55691
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :55691
,I/jxcore-log( 3000): CLIENT connected to 55691, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 55691
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:27677
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 8817 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: LGE-Nexus 5_PT1820
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3000): Connect (retry count 0) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3000): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-G900F_PT2552
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-G900F_PT2552
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-G900F_PT2552
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 52499
,I/BtConnectorHelper( 3000): Request socket is using : 52499
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :52499
I/jxcore-log( 3000): CLIENT connected to 52499, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 52499
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:3237
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 11152 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-G900F_PT2552
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2795","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : LGE-LG-D722_PT2795
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, LGE-LG-D722_PT2795
,I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
,I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect (retry count 0) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: F8:95:C7:87:85:54, name: G3s-1
,I/        ( 3000): Connecting to G3s-1, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=1
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectToThread( 3000): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT2795","ra":"F8:95:C7:87:85:54"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : LGE-LG-D722_PT2795
,I/HS      ( 3000): Hand Shake finished outgoing for : LGE-LG-D722_PT2795
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, LGE-LG-D722_PT2795
,I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 54404
I/BtConnectorHelper( 3000): Request socket is using : 54404
I/BtToRequestSocket( 3000): Now accepting connections
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: S5-1
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :54404
I/jxcore-log( 3000): CLIENT connected to 54404, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 54404
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2247
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 5113 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: LGE-LG-D722_PT2795
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,E/bt-btif ( 3058): unknown send() error, sent:-1, p_buf->len:3,  errno:32
,W/bt-btif ( 3058): invalid rfc slot id: 16
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): Connect (retry count 0) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3000): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109,
E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5208c rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-N9005_PT6254
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-N9005_PT6254
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-N9005_PT6254
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 55959
I/BtConnectorHelper( 3000): Request socket is using : 55959
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :55959
I/jxcore-log( 3000): CLIENT connected to 55959, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 55959
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:3237
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 6411 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-N9005_PT6254
,I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
,I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,W/bt-btif ( 3058): invalid rfc slot id: 11
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D722_PT2795
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5208c rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Note3-1
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): Connect (retry count 0) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3000): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51ec4 rs_disc_pending=0
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: G3s-1
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 18
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9165 ms, rnd: 1, ex: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3000): Connecting to null, at 50:2E:6C:AC:21:50
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [7c:f9:0e:37:96:ab]: 7, f, 6109
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: A5-1
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT5540
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, samsung-SM-A500FU_PT5540
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5241c rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5241c rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3000): 
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3000): 
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/jxcore-log( 3000): TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/jxcore-log( 3000): TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3000): 
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/jxcore-log( 3000): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 15
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT5540
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5241c rs_disc_pending=1
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3000): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3699","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : HTC-HTC One_M8_PT3699
I/HS      ( 3000): Hand Shake finished outgoing for : HTC-HTC One_M8_PT3699
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, HTC-HTC One_M8_PT3699
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 48510
I/BtConnectorHelper( 3000): Request socket is using : 48510
,I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :48510
I/jxcore-log( 3000): CLIENT connected to 48510, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 48510
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: HTC-HTC One_M8_PT3699
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 12489 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5241c rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/        ( 3000): Cleared service requests
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3000): Peer(5): A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3000): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3000): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3000): Connect (retry count 0) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3000): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3000): Starting to connect
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/        ( 3000): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,E/BluetoothEventManager( 3069): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-N910C_PT1968
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-N910C_PT1968
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-N910C_PT1968
,I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 40402
I/BtConnectorHelper( 3000): Request socket is using : 40402
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :40402
I/jxcore-log( 3000): CLIENT connected to 40402, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 40402
,I/BtToRequestSocket( 3000): Set local streams
,I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:1121
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-N910C_PT1968
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
,I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 8795 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Note4-1
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): Connect (retry count 0) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3000): Connecting to null, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/BTConnectToThread( 3000): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : LGE-LG-D855_PT3303
,I/HS      ( 3000): Hand Shake finished outgoing for : LGE-LG-D855_PT3303
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, LGE-LG-D855_PT3303
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 49065
I/BtConnectorHelper( 3000): Request socket is using : 49065
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :49065
I/jxcore-log( 3000): CLIENT connected to 49065, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 49065
I/BtToRequestSocket( 3000): Set local streams
,I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:27677
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : motorola-XT1072_PT5629
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, motorola-XT1072_PT5629
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3000): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/jxcore-log( 3000): TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3000): 
I/        ( 3000): Started service discovery
,I/jxcore-log( 3000): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 20
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5629
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT5629
I/BtToSocketBase( 3000): Close LocalOutputStream
,I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,W/bt-btif ( 3058): dm_pm_timer expires
W/bt-btif ( 3058): dm_pm_timer expires 0
,W/bt-btif ( 3058): proc dm_pm_timer expires
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x44
,I/        ( 3000): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9628, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9628, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c525e4 rs_disc_pending=1
E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: Connection reset by peer
I/BtConnectorHelper( 3000): Disconnect outgoing peer: LGE-LG-D855_PT3303
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: G3-1
,I/art     (  734): Explicit concurrent mark sweep GC freed 36291(1598KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.671ms total 89.700ms
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/        ( 3000): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/BTListenerThread( 3000): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : motorola-XT1039_PT9468
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, motorola-XT1039_PT9468
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/        ( 3000): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
I/        ( 3000): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT2552, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT2552, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26556 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46356 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 68136 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 23
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT9468
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT9468
I/BtToSocketBase( 3000): Close LocalOutputStream
,I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x47
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c515dc rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: XT1072
,I/jxcore-log( 3000): Receiving data timeout now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Stop data retrieving timer
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ----------------- closeClientSocket
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 19844 ms, rnd: 1, ex: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: XT1039
,I/jxcore-log( 3000): Connect (retry count 0) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3000): Connecting to null, at 00:F4:6F:30:E0:6C
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectToThread( 3000): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3000): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-G800F_PT9628
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-G800F_PT9628
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-G800F_PT9628
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 43556
I/BtConnectorHelper( 3000): Request socket is using : 43556
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :43556
I/jxcore-log( 3000): CLIENT connected to 43556, error: null
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 43556
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2247
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 10282 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-G800F_PT9628
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,I/jxcore-log( 3000): Connect (retry count 0) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3000): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52974 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3000): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : HTC-HTC Desire 820_PT9217
I/HS      ( 3000): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT9217
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT9217
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 56332
I/BtConnectorHelper( 3000): Request socket is using : 56332
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :56332
I/jxcore-log( 3000): CLIENT connected to 56332, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 56332
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2247
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9814 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: HTC-HTC Desire 820_PT9217
,I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52b3c rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820,
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 27
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 1
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9187 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [e0:db:10:1f:c9:5e]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5208c rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT6254
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, samsung-SM-N9005_PT6254
,I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
,I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT6254
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,W/bt-btif ( 3058): invalid rfc slot id: 24
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x41
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): Connect (retry count 0) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3000): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5208c rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52ecc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5208c rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52ecc rs_disc_pending=0
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,I/BTConnectToThread( 3000): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : LGE-LG-H815_PT1675
I/HS      ( 3000): Hand Shake finished outgoing for : LGE-LG-H815_PT1675
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,D/BluetoothMapService( 3058): onReceive
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, LGE-LG-H815_PT1675
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 41524
I/BtConnectorHelper( 3000): Request socket is using : 41524
I/BtToRequestSocket( 3000): Now accepting connections
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Note3-1
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :41524
I/jxcore-log( 3000): CLIENT connected to 41524, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 41524
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2247
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 10565 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: LGE-LG-H815_PT1675
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [80:01:84:8a:b3:68]: 7, f, 6109
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT9217"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT9217
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT9217
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52ecc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/jxcore-log( 3000): TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect (retry count 0) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: F4:F1:E1:5C:3B:E2, name: XT1039
,I/        ( 3000): Connecting to XT1039, at F4:F1:E1:5C:3B:E2
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3000): TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52ecc rs_disc_pending=0
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3000): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1675
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, LGE-LG-H815_PT1675
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 2205
,I/jxcore-log( 3000): TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3000): 
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: XT1039
,I/jxcore-log( 3000): TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 28
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT9217
,I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x45
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52ecc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/jxcore-log( 3000): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3000): 
,I/BTConnectToThread( 3000): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : motorola-XT1039_PT9468
I/HS      ( 3000): Hand Shake finished outgoing for : motorola-XT1039_PT9468
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, motorola-XT1039_PT9468
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 52158
I/BtConnectorHelper( 3000): Request socket is using : 52158
I/BtToRequestSocket( 3000): Now accepting connections
,I/jxcore-log( 3000): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34476 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36456 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42396 bytes of data
I/jxcore-log( 3000): 
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :52158
,I/jxcore-log( 3000): CLIENT connected to 52158, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 52158
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 78036 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 80016 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52ecc rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 30
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1675
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1675
I/BtToSocketBase( 3000): Close LocalOutputStream
,I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x48
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [e0:db:10:14:e2:c0]: 0, 0, 0
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Note4-1
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52ecc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : samsung-SM-N910C_PT1968
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, samsung-SM-N910C_PT1968
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 7374 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: motorola-XT1039_PT9468
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c527ac rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1968
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,W/bt-btif ( 3058): invalid rfc slot id: 31
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N910C_PT1968
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive,
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: G4-1
,I/jxcore-log( 3000): Connect (retry count 0) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3000): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3000): Starting to connect
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 3058): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c527ac rs_disc_pending=2
E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 34
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 2
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9192 ms, rnd: 1, ex: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [58:2a:f7:ed:96:be]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9956","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT9956
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3000): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24576 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28536 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30516 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32496 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/jxcore-log( 3000): TCP/IP server has received 38436 bytes of data
I/jxcore-log( 3000): 
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/jxcore-log( 3000): TCP/IP server has received 40416 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 44376 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50316 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52296 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 56256 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 58236 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 60216 bytes of data
I/jxcore-log( 3000): 
,I/BTConnectToThread( 3000): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9956","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : HUAWEI-ALE-L21_PT9956
I/HS      ( 3000): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT9956
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/jxcore-log( 3000): TCP/IP server has received 62196 bytes of data
I/jxcore-log( 3000): 
I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 56735
,I/BtConnectorHelper( 3000): Request socket is using : 56735
I/BtToRequestSocket( 3000): Now accepting connections
,I/jxcore-log( 3000): TCP/IP server has received 64176 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 66156 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 70116 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 72096 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 74076 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 76056 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/jxcore-log( 3000): TCP/IP server has received 81996 bytes of data
I/jxcore-log( 3000): 
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: S5-1
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :56735
I/jxcore-log( 3000): CLIENT connected to 56735, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 56735
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83976 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85956 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87936 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c517a4 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 89916 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91896 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93876 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 95856 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 97836 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 99816 bytes of data
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28939
,I/jxcore-log( 3000): CLIENT is data received : 0
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 33
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51cfc rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT2552","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT2552
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, samsung-SM-G900F_PT2552
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 35
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT2552
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x41
,I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): dm_pm_timer expires
W/bt-btif ( 3058): dm_pm_timer expires 0
W/bt-btif ( 3058): proc dm_pm_timer expires
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 4 peers.
I/SS      ( 3000): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3000): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3000): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: S5-1
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3000): Receiving data timeout now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Stop data retrieving timer
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 2
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ----------------- closeClientSocket
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 14997 ms, rnd: 1, ex: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3000): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 38
I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 2
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9138 ms, rnd: 1, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [34:fc:ef:11:b1:66]: 7, f, 610c
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT1820"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT1820
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, LGE-Nexus 5_PT1820
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3000): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3000): TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3000): 
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3000): TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: ALE-L21
,I/jxcore-log( 3000): TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=1
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 40
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 2
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 10072 ms, rnd: 1, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): Connect (retry count 0) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: B4:CE:F6:AB:A4:6A, name: HTC Desire 820
,I/        ( 3000): Connecting to HTC Desire 820, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3000): Starting to connect
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52254 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52254 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3000): got MESSAGE_READ 84 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : HTC-HTC Desire 820_PT2743
,I/HS      ( 3000): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT2743
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2743
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 36190
I/BtConnectorHelper( 3000): Request socket is using : 36190
I/BtToRequestSocket( 3000): Now accepting connections
,W/bt-btif ( 3058): invalid rfc slot id: 37
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT1820
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :36190
I/jxcore-log( 3000): CLIENT connected to 36190, error: null
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 36190
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51b34 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52254 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 15052 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: HTC-HTC Desire 820_PT2743
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [00:f4:6f:30:e0:6c]: 6, f, 6109
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : samsung-SM-G800F_PT9628
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, samsung-SM-G800F_PT9628
,I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
,I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
,I/BtToRequestSocket( 3000): --DoOneRunRound ended
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c52254 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 39
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT9628
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G800F_PT9628
I/BtToSocketBase( 3000): Close LocalOutputStream
,I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/jxcore-log( 3000): TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x4a
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): Connect (retry count 0) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 58:3F:54:73:64:C0, name: G3-1
,I/        ( 3000): Connecting to G3-1, at 58:3F:54:73:64:C0
,I/BTConnectToThread( 3000): Starting to connect
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : LGE-LG-D855_PT3303
I/HS      ( 3000): Hand Shake finished outgoing for : LGE-LG-D855_PT3303
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, LGE-LG-D855_PT3303
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 59730
I/BtConnectorHelper( 3000): Request socket is using : 59730
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :59730
I/jxcore-log( 3000): CLIENT connected to 59730, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 59730
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17777
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1937
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 19967 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: LGE-LG-D855_PT3303
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c525e4 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3000): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 44
I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 2
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9134 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/jxcore-log( 3000): Connect (retry count 0) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 3000): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: XT1072
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : motorola-XT1072_PT5629
I/HS      ( 3000): Hand Shake finished outgoing for : motorola-XT1072_PT5629
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, motorola-XT1072_PT5629
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 53766
I/BtConnectorHelper( 3000): Request socket is using : 53766
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :53766
I/jxcore-log( 3000): CLIENT connected to 53766, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 53766
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:28939
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11119
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 8206 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: motorola-XT1072_PT5629
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c515dc rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3000): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 3058): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c515dc rs_disc_pending=2
E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 46
I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 3
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 15176 ms, rnd: 1, ex: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3000): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 47
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 3
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9192 ms, rnd: 1, ex: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC One_M8
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3699","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT3699
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, HTC-HTC One_M8_PT3699
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 42
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT3699
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x46
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3000): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5241c rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [b4:ce:f6:ab:a4:6a]: 6, f, 410d
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 84 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : HTC-HTC Desire 820_PT2743
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, HTC-HTC Desire 820_PT2743
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5241c rs_disc_pending=0
,W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3058): invalid rfc slot id: 49
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 3
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9363 ms, rnd: 1, ex: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 48
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :HTC-HTC Desire 820_PT2743
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x42
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 51
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 3
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9147 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 58:2A:F7:ED:96:BE, name: ALE-L21
,I/        ( 3000): Connecting to ALE-L21, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [58:2a:f7:ed:96:be]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c517a4 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 2 peers.
I/SS      ( 3000): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(2): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,W/bt-l2cap( 3058): L2CAP - con rsp - bad ID. Exp: 6 Got: 4
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT9956","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : HUAWEI-ALE-L21_PT9956
I/HS      ( 3000): Hand Shake finished outgoing for : HUAWEI-ALE-L21_PT9956
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 46953
,I/BtConnectorHelper( 3000): Request socket is using : 46953
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :46953
,I/jxcore-log( 3000): CLIENT connected to 46953, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 46953
I/BtToRequestSocket( 3000): Set local streams
,I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29929
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19039
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:9139
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 14326 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: HUAWEI-ALE-L21_PT9956
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,I/        ( 3000): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c517a4 rs_disc_pending=1
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [08:ec:a9:50:76:27]: 6, 10f, 608
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5124c rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-A300FU_PT7297
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-A300FU_PT7297
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-A300FU_PT7297
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 52215
I/BtConnectorHelper( 3000): Request socket is using : 52215
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :52215
I/jxcore-log( 3000): CLIENT connected to 52215, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 52215
I/BtToRequestSocket( 3000): Set local streams
,I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17777
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2927
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 18038 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-A300FU_PT7297
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): Connect (retry count 0) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3000): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 3058): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c5124c rs_disc_pending=2
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT5861","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : samsung-SM-A300FU_PT5861
I/HS      ( 3000): Hand Shake finished outgoing for : samsung-SM-A300FU_PT5861
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, samsung-SM-A300FU_PT5861
,I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 38494
,I/BtConnectorHelper( 3000): Request socket is using : 38494
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :38494
I/jxcore-log( 3000): CLIENT connected to 38494, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 38494
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:28667
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18767
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8867
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 11948 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: samsung-SM-A300FU_PT5861
,I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
,I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket,
I/BtToRequestSocket( 3000): Close server socket
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c51084 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: A3-1
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [58:3f:54:73:64:c0]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: G3-1
,E/bt-btm  ( 3058): tBTM_SEC_DEV:0xa3c525e4 rs_disc_pending=0
W/bt-btif ( 3058): bta_dm_check_av:0
,W/bt-btif ( 3058): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : LGE-LG-D855_PT3303
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, LGE-LG-D855_PT3303
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3000): --DoOneRunRound started
,I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
I/BtToRequestSocket( 3000): --DoOneRunRound ended
,I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3000): 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3000): TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT3303
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,W/bt-btif ( 3058): invalid rfc slot id: 50
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: G3-1
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x22  CID 0x4f
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 55
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 4
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 29849 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 57
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 5
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9189 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 58
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 6
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9192 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 59
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 7
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9186 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 60
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 8
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9190 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 61
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 9
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9188 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 62
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 10
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9213 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 3 peers.
I/SS      ( 3000): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
,E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 63
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 11
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9204 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6254","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT6254, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT6254, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 64
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 12
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9197 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 4 peers.
I/SS      ( 3000): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 65
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 13
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9187 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 66
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 14
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9199 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 67
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 15
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9190 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED ,
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 68
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 16
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9207 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/UsageStatsService(  734): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3000): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3000): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7297","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT7297, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT7297, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 69
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 17
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9199 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 7 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3000): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 70
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 18
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9194 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9628, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9628, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 71
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 19
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9191 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3000): Found 7 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3000): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 72
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 20
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9209 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 73
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 21
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9195 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 74
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 22
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9193 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 75
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 23
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9187 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 76
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 24
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9193 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 77
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 25
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9189 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3058): invalid rfc slot id: 78
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 26
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9195 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3000): Found 8 peers.
I/SS      ( 3000): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3000): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 79
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 27
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9189 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
,I/        ( 3000): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 80
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 28
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9204 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 81
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 29
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9190 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3000): Found 8 peers.
I/SS      ( 3000): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT5540","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT5540, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT5540, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 82
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 30
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9195 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 83
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 31
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9197 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 8 peers.
I/SS      ( 3000): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3000): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 84
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 32
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9202 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 85
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 33
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9187 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3000): Found 8 peers.
I/SS      ( 3000): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3000): Peer(3): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(5): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(8): Note3-1 ea:50:8b:de:28:a3
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 86
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 34
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9197 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 87
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 35
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9190 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 7 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(6): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 88
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 36
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9201 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 89
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now,
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 37
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9183 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3000): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 90
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 38
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9199 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 91
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 39
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9189 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 92
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 40
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9190 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3000): Found 6 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3699","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3699","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3699, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3699, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 93
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 41
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9201 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 6 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 94
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 42
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9200 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3000): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3000): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: Android_1950, WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3000): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9628, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9628, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3000): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3000): Connecting to null, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,W/bt-sdp  ( 3058): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3058): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3058): invalid rfc slot id: 95
,I/BTConnectToThread( 3000): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3000): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3000): CLIENT connected to -1, error: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Can not Connect: Connection to 34:FC:EF:9D:93:0B failed
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 43
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do fake peer & start
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 9192 ms, rnd: 1, ex: Connection to 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3058): info:x10
,D/        ( 3058): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3058): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3058): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3058): Entering PendingCommandState State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3058): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3058): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3058): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3058): StableState(): Entering Off State
,W/BluetoothEventManager( 3069): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3069): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3000): we got incoming connection
I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
I/BTListenerThread( 3000): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTListenerThread( 3000): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3000): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3000): MESSAGE_WRITE 76 bytes.
I/HS      ( 3000): Incoming connection Hand Shake finished for : LGE-LG-D802_PT7492
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3000): Starting the connected thread incoming : true, LGE-LG-D802_PT7492
I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BTConnectedThread
I/BtConnectorHelper( 3000): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3000): --DoOneRunRound started
I/BtToRequestSocket( 3000): LocalHost address: localhost/127.0.0.1, port: 58757
I/BtToRequestSocket( 3000): --DoOneRunRound ended
I/jxcore-log( 3000): TCP/IP server connected
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3000): 
,W/bt-btif ( 3058): invalid rfc slot id: 56
,I/BtToSocketBase( 3000): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3000): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT7492
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3000): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3000): TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server is ended
I/jxcore-log( 3000): 
I/jxcore-log( 3000): TCP/IP server is close
I/jxcore-log( 3000): 
,W/bt-rfcomm( 3058): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3058): RFCOMM_DisconnectInd LCID:0x4a
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): Connect (retry count 0) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 3000): 
I/jxcore-log( 3000): do connect now
I/jxcore-log( 3000): 
,I/        ( 3000): Selected device address: 34:FC:EF:9D:93:0B, name: Thali Test's G2
,I/        ( 3000): Connecting to Thali Test's G2, at 34:FC:EF:9D:93:0B
,I/BTConnectToThread( 3000): Starting to connect
W/BluetoothAdapter( 3000): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3058): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3058): process_service_search_attr_rsp
,W/bt-btif ( 3058): new conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3058): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3000): Starting to Handshake
,I/BTHandshakeSocketThread( 3000): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3000): MESSAGE_WRITE 76 bytes.
,I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread started
,I/BTConnectToThread( 3000): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3000): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3000): HandshakeOk : LGE-LG-D802_PT7492
I/HS      ( 3000): Hand Shake finished outgoing for : LGE-LG-D802_PT7492
I/BTHandshakeSocketThread( 3000): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3000): Starting the connected thread incoming : false, LGE-LG-D802_PT7492
,I/BtToSocketBase( 3000): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3000): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3000): mHTTPPort  set to : 33977
I/BtConnectorHelper( 3000): Request socket is using : 33977
I/BtToRequestSocket( 3000): Now accepting connections
,I/BtConnectorHelper( 3000): Calling ConnectionStatusUpdate with port :33977
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT connected to 33977, error: null
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT starting client 
I/jxcore-log( 3000): 
,I/BtToRequestSocket( 3000): incoming data from: /127.0.0.1, port: 33977
I/BtToRequestSocket( 3000): Set local streams
I/BtToRequestSocket( 3000): rin ended ---------------------------;
,I/jxcore-log( 3000): CLIENT now sending 100000 bytes of data
I/jxcore-log( 3000): 
,D/        ( 3058): PORT_WriteDataCO: tx queue is full,tx.queue_size:10036,tx.queue.count:11,available:3237
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 20000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 30000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 40000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 50000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 60000
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT is data received : 70000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 80000
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3000): CLIENT is data received : 90000
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT is data received : 100000
I/jxcore-log( 3000): 
I/jxcore-log( 3000): got all data for this round
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT closeClientSocket
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ---- round done--------
I/jxcore-log( 3000): 
I/jxcore-log( 3000): weAreDoneNow , resultArray.length: 19
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3000): done, now sending data to server
I/jxcore-log( 3000): 
I/jxcore-log( 3000): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): -- RESULT DATA {"name:":"LGE-Nexus 5_PT566","time":790021,"result":"OK","sendList":[{"name":"7C:F9:0E:37:96:AB","time":27495,"result":"OK","connections":1,"tryCount":1},{"name":"F8:CF:C5:D9:E5:61","time":7668,"result":"OK","connections":1,"tryCount":1},{"name":"34:FC:EF:11:B1:66","time":8817,"result":"OK","connections":1,"tryCount":1},{"name":"7C:F9:0E:34:8A:A0","time":11152,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:85:54","time":5113,"result":"OK","connections":1,"tryCount":1},{"name":"E0:DB:10:1F:C9:5E","time":6411,"result":"OK","connections":1,"tryCount":1},{"name":"50:2E:6C:AC:21:50","time":12489,"result":"OK","connections":1,"tryCount":1},{"name":"E0:DB:10:14:E2:C0","time":8795,"result":"OK","connections":1,"tryCount":1},{"name":"00:F4:6F:30:E0:6C","time":10282,"result":"OK","connections":1,"tryCount":1},{"name":"80:01:84:8A:B3:68","time":9814,"result":"OK","connections":1,"tryCount":1},{"name":"F8:95:C7:87:3C:51","time":10565,"result":"OK","connections":1,"tryCount":1},{"name":"F
I/jxcore-log( 3000): sendList : 100% : 27495 ms, 99% : 27495 ms, 95 : 19967 ms, 90% : 18038 ms.
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Result count 19, range 5113 ms to  27495 ms.
I/jxcore-log( 3000): 
I/jxcore-log( 3000): sendList failed peers count : 0 [0 %]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CLIENT Stop now
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback round[0] time: 6349 ms, rnd: 1, ex: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3000): CLIENT is data received : 10000
I/jxcore-log( 3000): 
,I/BtToSocketBase( 3000): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3000): Disconnect outgoing peer: LGE-LG-D802_PT7492
I/BtToSocketBase( 3000): Stop ReceivingThread
I/BtToSocketBase( 3000): Stop SendingThread
I/BtToSocketBase( 3000): Close local in
I/BtToSocketBase( 3000): Close LocalOutputStream
I/BtToSocketBase( 3000): Close localHostSocket
I/BtToSocketBase( 3000): Close bt in
,I/BtToSocketBase( 3000): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3000): Close bt out
I/BtToSocketBase( 3000): Close bt socket
I/BtToRequestSocket( 3000): Close server socket
,I/SS      ( 3000): Found 6 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3000): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,W/bt-btif ( 3058): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 3000): CLIENT is closed
I/jxcore-log( 3000): 
D/WifiP2pManager( 3000): Ignored { when=-23ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3058): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3058): onReceive
,I/BTConnectionReceiver( 1344): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1344): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 3000): Receiving data timeout now
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ----------------- closeClientSocket
I/jxcore-log( 3000): 
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 3 peers.
,I/SS      ( 3000): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/        ( 3000): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/        ( 3000): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 6 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT5629","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT5629, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT5629, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3000): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1968","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT1968, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT1968, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3000): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3000): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT2743"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT2743, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT2743, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3000): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9628"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT9628, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT9628, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 6 peers.
I/SS      ( 3000): Peer(1): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3000): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(3): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/SS      ( 3000): Found 4 peers.
I/SS      ( 3000): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3000): Peer(3): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3000): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3000): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1675","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1675, peerAddress: F8:95:C7:87:3C:51
,I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1675, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3000): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT3303","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT3303, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT3303, WifiDirectName: G3-1, WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3000): Found 5 peers.
I/SS      ( 3000): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3000): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3000): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7492"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7492, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7492, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3000): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9468"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9468, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9468, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 9 peers.
I/SS      ( 3000): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3000): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3000): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3000): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3000): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3000): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-smp  ( 3058): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3058): Plain text(LSB ~ MSB) = 8a 0d 4d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3058): Encrypted text(LSB ~ MSB) = 88 dd c9 be d8 da 83 d5 47 0d f9 a2 e1 6f 9e c3 
,W/bt-btm  ( 3058): Stopping oneshot timer
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 9 peers.
I/SS      ( 3000): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3000): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3000): Peer(3): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3000): Peer(7): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3000): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3000): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3000): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 7 peers.
I/SS      ( 3000): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3000): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3000): Started service discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3065): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/        ( 3000): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3699","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3000): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT3699","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT3699, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3000): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT3699, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3000): Cleared service requests
I/        ( 3000): Started peer discovery
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3000): Found 7 peers.
I/SS      ( 3000): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3000): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3000): Peer(3): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3000): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3000): Peer(5): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3000): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3000): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3000): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3000): Added service request
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 3065): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3000): Started service discovery
,I/jxcore-log( 3000): DBG, CoordinatorConnector command called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): stop tests now !
I/jxcore-log( 3000): 
I/jxcore-log( 3000): stop current!
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): testSendData stopped
I/jxcore-log( 3000): 
,I/        ( 3000): Stoping All
I/        ( 3000): Stopping services
I/        ( 3000): Stopping services
,I/wpa_supplicant( 3065): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3065): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3000): Stop Bluetooth
I/        ( 3000): Stop Bluetooth
I/BTListenerThread( 3000): Stopped
,I/jxcore-log( 3000): StopBroadcasting went ok
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): TCP/IP server  socket is disconnected
I/jxcore-log( 3000): 
,I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/        ( 3000): Cleared local services
I/        ( 3000): Cleared service requests
I/        ( 3000): Stopped peer discovery
,I/jxcore-log( 3000): DBG, CoordinatorConnector command called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F8:95:C7:87:85:54\",\"time\":5113,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":6349,\"result\":\"OK\",\"connections\":1,\"tryCount\":44},{\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":6411,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F4:F1:E1:5C:3B:E2\",\"time\":7374,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":7668,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"44:80:EB:7B:5A:05\",\"time\":8206,\"result\":\"OK\",\"connections\":1,\"tryCount\":3},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":8795,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"34:FC:EF:11:B1:66\",\"time\":8817,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"80:01:84:8A:B3:68\",\"time\":9814,\"result\":\"OK\",\"connections\":1,\"tryCount\":1},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\":102
I/jxcore-log( 3000): ****TEST TOOK:  ms ****
I/jxcore-log( 3000): 
I/jxcore-log( 3000): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3000): 
I/jxcore-log( 3000): stop tests now !
I/jxcore-log( 3000): 
I/jxcore-log( 3000): end, event received
I/jxcore-log( 3000): 
I/jxcore-log( 3000): CoordinatorConnector close called
I/jxcore-log( 3000): 
,I/jxcore-log( 3000): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3000): 
I/jxcore-log( 3000): The Coordinator has disconnected!
I/jxcore-log( 3000): 
I/jxcore-log( 3000): The Coordinator has closed!
I/jxcore-log( 3000): 
I/jxcore-log( 3000): stop tests now !
I/jxcore-log( 3000): 
I/jxcore-log( 3000): turning Radios off
I/jxcore-log( 3000): 
I/jxcore-log( 3000): Turning radios to false
I/jxcore-log( 3000): 
D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@10f1dee1 mBinding = false
D/BluetoothManagerService(  734): Message: 2
D/BluetoothManagerService(  734): Sending off request.
D/BluetoothAdapterState( 3058): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3058): Setting state to 13
I/BluetoothAdapterState( 3058): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3058): onBluetoothDisable()
I/BluetoothAdapterState( 3058): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3058): Scan Mode:20
D/BluetoothAdapterState( 3058): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothMapMasInstance( 3058): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3058): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3058): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3058): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3058): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3058): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3058): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3058): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/btif_config_util( 3058): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
E/BtOppRfcommListener( 3058): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3058): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3058): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3058): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  734): Message: 60
D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3058): onReceive
D/BluetoothMapService( 3058): STATE_TURNING_OFF
V/BluetoothMapService( 3058): Handler(): got msg=4
D/BluetoothMapService( 3058): MAP Service closeService in
D/BluetoothMapMasInstance( 3058): MAP Service shutdown
V/BluetoothMapService( 3058): MAP Service closeService out
,I/BtOppRfcommListener( 3058): stopping Accept Thread
,I/BtOppRfcommListener( 3058): BluetoothSocket listen thread finished
,I/ProcessStatsService(  734): Prepared write state in 3ms
,I/jxcore-log( 3000): toggleBluetooth - 
I/jxcore-log( 3000): 
,W/ContextImpl( 3069): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiService(  734): setWifiEnabled: false pid=3000, uid=10270
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/ProcessStatsService(  734): Pruning old procstats: /data/system/procstats/state-2015-11-22-23-01-01.bin
,E/WifiStateMachine(  734): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  734): do suspend true
,I/jxcore-log( 3000): toggleWiFi
I/jxcore-log( 3000): 
I/chromium( 3000): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,W/bt-btif ( 3058): ag scb idx 1 not allocated
E/bt-btif ( 3058): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3058): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3058): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3058): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3058): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3058): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3058): L2CAP - PSM: 0x0017 not found for deregistration
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  734): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
V/NativeCrypto( 1362): Read error: ssl=0xafce0200: I/O error during system call, Connection timed out
,E/WifiConfigStore(  734): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  734): scanCount==0 - aborting
,D/bt_userial( 3058): RX termination
W/bt_userial( 3058): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3058): Leaving userial_read_thread()
D/bt_userial( 3058): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3058): hw_epilog_process
,I/bt_userial_vendor( 3058): device fd = 53 close
,V/NativeCrypto( 1362): SSL shutdown failed: ssl=0xafce0200: I/O error during system call, Broken pipe
,D/ConnectivityService(  734): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): ValidatedState{ when=-2ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=-2ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,I/GKI_LINUX( 3058): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3058): GKI_exit_task 0 done
I/GKI_LINUX( 3058): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3058): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/ConnectivityService(  734): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524292
,D/WifiScanningService(  734): SCAN_AVAILABLE : 1
D/RttService(  734): SCAN_AVAILABLE : 1
D/WifiScanningService(  734): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  734): DefaultState
D/RttService(  734): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/Nat464Xlat(  734): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/WifiNetworkAgent(  734): NetworkAgent: NetworkAgent channel lost
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  734): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  734): Disconnected - quitting
E/native  (  734): do suspend true
,D/ConnectivityManager.CallbackHandler( 1624): CM callback handler got msg 524292
D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/HeadsetService( 3058): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
,D/HeadsetStateMachine( 3058): Exit Disconnected: -1
D/BluetoothHeadset(  734): Proxy object disconnected
,D/BluetoothHeadset( 1235): Proxy object disconnected
,D/A2dpService( 3058): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
,D/BluetoothHeadset( 1181): Proxy object disconnected
D/BluetoothHeadset( 1181): Proxy object disconnected
,D/CommandListener(  181): Clearing all IP addresses on wlan0
,D/ConnectivityService(  734): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  734): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/BluetoothA2dp(  734): Proxy object disconnected
E/ConnectivityService(  734): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/HidService( 3058): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
,D/TelephonyNetworkFactory( 1235): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/HeadsetStateMachine( 3058): Unbinding service...
,D/A2dpStateMachine( 3058): Exit Disconnected: -1
,W/BluetoothHeadsetServiceJni( 3058): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3058): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3058): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
D/DockEventReceiver( 3069): finishStartingService: stopping service
D/BluetoothPbap( 3069): Proxy object disconnected
D/PbapServerProfile( 3069): Bluetooth service disconnected
D/BluetoothAdapterState( 3058): Stopping profile services that were post enabled
D/PanService( 3058): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
I/GKI_LINUX( 3058): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3058): GKI_exit_task 2 done
I/GKI_LINUX( 3058): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtGatt.DebugUtils( 3058): handleDebugAction() action=null
D/BtGatt.GattService( 3058): Received stop request...Stopping profile...
D/BtGatt.GattService( 3058): stop()
D/BtGatt.AdvertiseManager( 3058): advertise clients cleared
,D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
,W/BluetoothHidServiceJni( 3058): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3058): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3058): Cleaning up Bluetooth GID callback object
D/BluetoothMapService( 3058): Received stop request...Stopping profile...
D/BluetoothMapService( 3058): stop()
,D/BluetoothMapEmailAppObserver( 3058): deinitObservers()
,D/BluetoothMapEmailAppObserver( 3058): removeReceiver()
,D/BluetoothAdapterService( 3058): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f729e34
,W/BluetoothHealthServiceJni( 3058): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3058): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3058): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3058): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3058): Handler(): got msg=4
D/BluetoothMapService( 3058): MAP Service closeService in
V/BluetoothMapService( 3058): MAP Service closeService out
D/BluetoothMapService( 3058): cleanup()
D/BluetoothMapService( 3058): MAP Service closeService in
V/BluetoothMapService( 3058): MAP Service closeService out
D/BluetoothAdapterState( 3058): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3058): Setting state to 10
I/BluetoothAdapterState( 3058): Bluetooth adapter state changed: 13-> 10
,I/BluetoothAdapterState( 3058): Entering OffState
,D/BluetoothManagerService(  734): Message: 60
,D/BluetoothManagerService(  734): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  734): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothMap( 3069): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3069): Proxy object disconnected
,D/HeadsetProfile( 3069): Bluetooth service disconnected
D/BluetoothA2dp( 3069): Proxy object disconnected
D/A2dpProfile( 3069): Bluetooth service disconnected
D/BluetoothInputDevice( 3069): Proxy object disconnected
D/HidProfile( 3069): Bluetooth service disconnected
D/BluetoothPan( 3069): BluetoothPAN Proxy object disconnected
D/PanProfile( 3069): Bluetooth service disconnected
,D/BluetoothA2dp( 3069): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1235): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3069): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1181): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3069): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  734): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1181): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3069): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  734): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  734): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  734): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  734): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@10f1dee1 mBinding = false
,D/BluetoothManagerService(  734): Sending unbind request.
,D/BluetoothManagerService(  734): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  901): 384423601: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  901): 384423601: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  901): 384423601: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3058): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3058): GKI_exit_task 1 done
I/GKI_LINUX( 3058): GKI_shutdown(): task [BTIF] terminated
D/BluetoothAdapter( 1317): 445509513: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1317): 445509513: getState() :  mService = null. Returning STATE_OFF
,I/BluetoothServiceJni( 3058): cleanupNative: return from cleanup
,I/art     ( 3058): System.exit called, status: 0
I/AndroidRuntime( 3058): VM exiting with result code 0, cleanup skipped.
,D/AndroidRuntime( 3939): 
D/AndroidRuntime( 3939): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3939): CheckJNI is OFF
,D/AndroidRuntime( 3939): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Process com.android.bluetooth (pid 3058) has died
,I/wpa_supplicant( 3065): p2p0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 3000:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
I/wpa_supplicant( 3065): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  734): Skipping PackageSetting{3195b70f com.example.hello/10277} due to missing metadata
,I/WindowState(  734): WIN DEATH: Window{2af22459 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  734): Client connection lost with reason: 4
,D/AuthorizationBluetoothService( 1362): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/Tethering(  734): InitialState.processMessage what=4
I/wpa_supplicant( 3065): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  734):   Force finishing activity ActivityRecord{3829f035 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  734): Spurious death for ProcessRecord{2c7b5c63 3000:com.test.thalitest/u0a270}, curProc for 3000: null
,I/ActivityManager(  734): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  734):   Force finishing activity ActivityRecord{3829f035 u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  734): Duplicate finish request for ActivityRecord{3829f035 u0 com.test.thalitest/.MainActivity t214 f}
,I/Keyboard.Facilitator( 1073): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1073): run()
,W/GeofencerStateMachine( 1317): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
D/Tethering(  734): sendTetherStateChangedBroadcast 0, 0, 0
,I/Decoder ( 1073): createOrResetDecoder
,I/art     ( 1281): Explicit concurrent mark sweep GC freed 3956(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 878us total 37.499ms
,W/Settings( 1317): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 1344): Explicit concurrent mark sweep GC freed 8438(362KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 19MB/25MB, paused 317us total 64.415ms
,W/Settings( 1843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/LibraryLoader( 1483): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,I/ConfigService( 1362): onCreate
,I/art     (  734): Explicit concurrent mark sweep GC freed 78286(3MB) AllocSpace objects, 10(232KB) LOS objects, 33% free, 28MB/42MB, paused 1.748ms total 112.510ms
,I/art     (  734): WaitForGcToComplete blocked for 100.885ms for cause Explicit
,I/OpenGLRenderer(  951): Initialized EGL, version 1.4
,D/OpenGLRenderer(  951): Enabling debug mode 0
,I/LibraryLoader( 1483): Time to load native libraries: 67 ms (timestamps 6530-6597)
,I/LibraryLoader( 1483): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
,I/chromium( 1483): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1483): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 1483): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     (  951): Attempt to remove local handle scope entry from IRT, ignoring
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1073): run()
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,I/EventLogService( 1624): Aggregate from 1448292759778 (log), 1448292759778 (data)
,W/InputMethodManagerService(  734): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@2536344d (uid=10034 pid=951)
,D/TaskPersister(  734): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1073): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loading LM = contacts
,I/art     (  734): Explicit concurrent mark sweep GC freed 14455(736KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.285ms total 140.915ms
I/art     (  734): WaitForGcToComplete blocked for 40.810ms for cause Explicit
,I/art     (  734): Explicit concurrent mark sweep GC freed 4998(238KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 857us total 56.759ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1073): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1073): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1073): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1073): run()
I/StatsUtilsManager( 1073): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1073): shouldRecordStats() = Too Soon
,V/NativeCrypto( 1362): SSL shutdown failed: ssl=0x9b203000: I/O error during system call, Connection timed out
W/ContextImpl( 3069): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/AndroidRuntime( 3939): Shutting down VM
,I/ActivityManager(  734): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=4007 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 3069): finishStartingService: stopping service
,I/Launcher( 1281): Deferring update until onResume
,W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4007): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 1281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 1624): Explicit concurrent mark sweep GC freed 26197(1698KB) AllocSpace objects, 18(288KB) LOS objects, 25% free, 22MB/29MB, paused 510us total 48.372ms
,I/Launcher( 1281): Deferring update until onResume
,D/AdapterServiceConfig( 4007): Adding HeadsetService
D/AdapterServiceConfig( 4007): Adding A2dpService
,D/AdapterServiceConfig( 4007): Adding HidService
D/AdapterServiceConfig( 4007): Adding HealthService
D/AdapterServiceConfig( 4007): Adding PanService
D/AdapterServiceConfig( 4007): Adding GattService
D/AdapterServiceConfig( 4007): Adding BluetoothMapService
,D/BluetoothAdapter( 3069): 662555911: getState() :  mService = null. Returning STATE_OFF
,D/AuthorizationBluetoothService( 1362): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  734): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4030 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 1464:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10013/pid_1464/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1344): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/VoicemailCleanupService( 4030): Cleaning up data for package: com.test.thalitest
,W/Launcher( 1281): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f729e34 new=com.google.android.velvet.VelvetApplication@3f729e34
,E/SQLiteLog( 1281): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,E/SQLiteLog( 1344): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/FileUtils( 4030): Failed to chmod(/data/data/com.android.providers.contacts/databases/contacts2.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,--------- beginning of crash
E/AndroidRuntime( 1344): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 1344): Process: com.google.android.googlequicksearchbox:search, PID: 1344
E/AndroidRuntime( 1344): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1344): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1344): 	at csx.d(PG:186)
E/AndroidRuntime( 1344): 	at cun.g(PG:594)
E/AndroidRuntime( 1344): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 1344): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 1344): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 1344): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 1344): 	at cuy.ub(PG:301)
E/AndroidRuntime( 1344): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 1344): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 1344): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1344): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1344): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 4030): (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
E/AndroidRuntime( 4030): FATAL EXCEPTION: IntentService[VoicemailCleanupService]
E/AndroidRuntime( 4030): Process: android.process.acore, PID: 4030
E/AndroidRuntime( 4030): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4030): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4030): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4030): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4030): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4030): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4030): 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:156)
E/AndroidRuntime( 4030): 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:209)
E/AndroidRuntime( 4030): 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:130)
E/AndroidRuntime( 4030): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 4030): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 4030): 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
E/AndroidRuntime( 4030): 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
E/AndroidRuntime( 4030): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4030): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4030): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4030): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4055 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/ContactLocale( 4030): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Process ( 4030): Sending signal. PID: 4030 SIG: 9
I/Process ( 1344): Sending signal. PID: 1344 SIG: 9
E/DropBoxManagerService(  734): Can't write: system_app_crash
E/DropBoxManagerService(  734): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  734): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  734): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  734): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  734): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  734): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  734): 	... 5 more
E/DropBoxManagerService(  734): Can't write: system_app_crash
E/DropBoxManagerService(  734): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  734): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  734): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  734): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  734): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  734): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  734): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  734): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  734): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  734): 	... 5 more
D/WifiService(  734): Client connection lost with reason: 4
,I/ActivityManager(  734): Process android.process.acore (pid 4030) has died
W/ActivityManager(  734): Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
I/ActivityManager(  734): Process com.google.android.googlequicksearchbox:search (pid 1344) has died
W/ActivityManager(  734): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  734): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms

```
