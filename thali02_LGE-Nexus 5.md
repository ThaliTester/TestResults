#### Test 52971095c1e9930_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2846): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2846):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2846):   adb logcat -s GAv4
W/GAv4    ( 2846): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2846): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2846): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2846): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2376): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  754): Killing 2189:com.google.android.youtube/u0a80 (adj 15): empty #17
W/ResourcesManager( 2846): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2846): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 2889): 
D/AndroidRuntime( 2889): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2889): CheckJNI is OFF
W/libprocessgroup(  754): failed to open /acct/uid_10080/pid_2189/cgroup.procs: No such file or directory
V/JNIHelp ( 2846): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2846): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2846): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2889): Calling main entry com.android.commands.am.Am
I/ActivityManager(  754): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  754): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2924 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2889): Shutting down VM
V/ActivityManager(  754): Display changed displayId=0
I/Icing   ( 1560): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1560): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1560): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2924): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2924): Time to load native libraries: 1 ms (timestamps 5424-5425)
I/LibraryLoader( 2924): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2924): Binding Chromium to main looper Looper (main, tid 1) {21884f8e}
I/LibraryLoader( 2924): Expected native library version number "",actual native library version number ""
I/chromium( 2924): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2924): Initializing chromium process, singleProcess=true
,W/art     ( 2924): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2924): ApplicationContext is null in ApplicationStatus
,W/chromium( 2924): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2924): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2924): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2924): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2924): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  754): Message: 20
D/BluetoothManagerService(  754): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@125ab063:true
D/BluetoothAdapter( 2924): 449167272: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2924): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2924): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2924): CordovaWebView is running on device made by: LGE
,W/art     ( 2924): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2924): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2924): Render dirty regions requested: true
,D/Atlas   ( 2924): Validating map...
,W/chromium( 2924): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2924): Initialized EGL, version 1.4
D/OpenGLRenderer( 2924): Enabling debug mode 0
,W/BindingManager( 2924): Cannot call determinedVisibility() - never saw a connection for the pid: 2924
,W/IInputConnectionWrapper( 2924): showStatusIcon on inactive InputConnection
,I/ActivityManager(  754): Displayed com.test.thalitest/.MainActivity: +427ms (total +53s955ms)
,D/JsMessageQueue( 2924): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2924): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 2924): jxcore cordova android initializing
,I/ActivityManager(  754): Killing 2290:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  754): failed to open /acct/uid_10038/pid_2290/cgroup.procs: No such file or directory
,W/jxcore-log( 2924): Initializing JXcore engine
W/jxcore-log( 2924): JXcore engine is ready
,W/jxcore-log( 2924): Starting JXcore engine
,W/.test.thalitest( 2924): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6531]" dev="sockfs" ino=6531 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2924): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2924): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9442]" dev="sockfs" ino=9442 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2924): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17867]" dev="sockfs" ino=17867 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2924): Platform android
W/jxcore-log( 2924): 
,W/jxcore-log( 2924): Process ARCH arm
W/jxcore-log( 2924): 
,I/jxcore-log( 2924): JXcore Cordova bridge is ready!
I/jxcore-log( 2924): 
W/jxcore-log( 2924): JXcore engine is started
I/Choreographer( 2924): Skipped 107 frames!  The application may be doing too much work on its main thread.
I/chromium( 2924): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/jxcore-log( 2924): Toggling radios to true
I/jxcore-log( 2924): 
D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  754): enable():  mBluetooth =null mBinding = false
D/BluetoothManagerService(  754): Message: 1
D/BluetoothManagerService(  754): MESSAGE_ENABLE: mBluetooth = null
D/WifiService(  754): setWifiEnabled: true pid=2924, uid=10270
E/WifiService(  754): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  754): New client listening to asynchronous messages
D/SoftapController(  179): Softap fwReload - Ok
I/jxcore-log( 2924): Radios toggled
I/jxcore-log( 2924): 
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
I/ActivityManager(  754): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2982 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/WifiMonitor(  754): startMonitoring(wlan0) with mConnected = false
I/ActivityManager(  754): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2998 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/wpa_supplicant( 2988): Successfully initialized wpa_supplicant
W/ResourcesManager( 2982): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
I/wpa_supplicant( 2988): rfkill: Cannot open RFKILL control device
D/BluetoothManagerService(  754): Message: 20
D/BluetoothManagerService(  754): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@294c8166:true
D/AdapterServiceConfig( 2982): Adding HeadsetService
D/AdapterServiceConfig( 2982): Adding A2dpService
D/AdapterServiceConfig( 2982): Adding HidService
D/AdapterServiceConfig( 2982): Adding HealthService
D/AdapterServiceConfig( 2982): Adding PanService
D/AdapterServiceConfig( 2982): Adding GattService
D/AdapterServiceConfig( 2982): Adding BluetoothMapService
D/BluetoothAdapter( 2998): 562581390: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  754): Message: 30
D/BluetoothManagerService(  754): Message: 30
D/LocalBluetoothProfileManager( 2998): Adding local MAP profile
D/BluetoothMap( 2998): Create BluetoothMap proxy object
D/BluetoothManagerService(  754): Message: 30
D/BluetoothManagerService(  754): Message: 30
D/LocalBluetoothProfileManager( 2998): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 2998): 562581390: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2998): 562581390: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  754): Message: 20
D/BluetoothManagerService(  754): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f99eb84:true
D/BluetoothAdapterState( 2982): make
I/bluedroid( 2982): init
I/BluetoothAdapterState( 2982): Entering OffState
I/ActivityManager(  754): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3032 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  754): Killing 2342:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
I/bte_conf( 2982): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 2982): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2982): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2982): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 2982): get_profile_interface socket
I/bluedroid( 2982): get_profile_interface map_client
I/GKI_LINUX( 2982): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 2982): Address is:34:FC:EF:11:AE:67
W/libprocessgroup(  754): failed to open /acct/uid_10069/pid_2342/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 2982): Name is: Nexus 5
D/BluetoothManagerService(  754): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  754): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  754): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  754): Message: 40
D/BluetoothManagerService(  754): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 2982): config_hci_snoop_log
D/BluetoothManagerService(  754): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  754): Broadcasting onBluetoothServiceUp() to 10 receivers.
D/BluetoothAdapterState( 2982): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2982): Setting state to 11
I/BluetoothAdapterState( 2982): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  754): Message: 60
D/BluetoothManagerService(  754): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  754): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 2982): make
I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
D/BluetoothHeadset(  754): Proxy object connected
D/BluetoothHeadset( 1232): Proxy object connected
D/BluetoothHeadset( 1204): Proxy object connected
D/BluetoothHeadset( 1204): Proxy object connected
D/HeadsetService( 2982): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 2982): classInitNative: succeeds
D/HeadsetStateMachine( 2982): make
I/BluetoothAdapterState( 2982): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 2982): max_hf_connections = 1
I/bluedroid( 2982): get_profile_interface handsfree
,D/HeadsetStateMachine( 2982): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
,D/BluetoothA2dp(  754): Proxy object connected
,D/A2dpService( 2982): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2982): classInitNative: succeeds
,I/bluedroid( 2982): get_profile_interface avrcp
,E/RemoteController( 2982): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2982): classInitNative: succeeds
D/A2dpStateMachine( 2982): make
,I/bluedroid( 2982): get_profile_interface a2dp
I/GKI_LINUX( 2982): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
I/BluetoothHidServiceJni( 2982): classInitNative: succeeds
,D/A2dpStateMachine( 2982): Enter Disconnected: -2
,D/HidService( 2982): Received start request. Starting profile...
I/bluedroid( 2982): get_profile_interface hidhost
D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
I/BluetoothHealthServiceJni( 2982): classInitNative: succeeds
,D/HealthService( 2982): Received start request. Starting profile...
,I/bluedroid( 2982): get_profile_interface health
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
I/BluetoothPanServiceJni( 2982): classInitNative(L105): succeeds
,D/BluetoothInputDevice( 2998): Proxy object connected
D/HidProfile( 2998): Bluetooth service connected
D/PanService( 2982): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2982): initializeNative(L110): pan
I/bluedroid( 2982): get_profile_interface pan
D/BluetoothPan( 2998): BluetoothPAN Proxy object connected
D/PanProfile( 2998): Bluetooth service connected
D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
I/BtGatt.JNI( 2982): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 2982): handleDebugAction() action=null
D/BtGatt.GattService( 2982): Received start request. Starting profile...
D/BtGatt.GattService( 2982): start()
I/bluedroid( 2982): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2982): advertise manager created
D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
V/BluetoothMapService( 2982): BluetoothMapBinder()
D/BluetoothMapService( 2982): Received start request. Starting profile...
D/BluetoothMapService( 2982): start()
D/BluetoothMap( 2998): Proxy object connected
D/MapProfile( 2998): Bluetooth service connected
D/BluetoothMap( 2998): getConnectedDevices()
D/BluetoothMap( 2998): Bluetooth is Not enabled
D/BluetoothMapEmailSettingsLoader( 2982): Found 0 applications
D/BluetoothMapEmailAppObserver( 2982): createReceiver()
,I/art     (  754): Explicit concurrent mark sweep GC freed 12229(601KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 894us total 50.176ms
,D/BluetoothMapEmailAppObserver( 2982): initObservers()
D/BluetoothMapEmailAppObserver( 2982): getEnabledAccountItems()
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
,D/HeadsetStateMachine( 2982): Proxy object connected
V/BluetoothMapService( 2982): Handler(): got msg=1
D/HeadsetStateMachine( 2982): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2982): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
D/HeadsetStateMachine( 2982): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 2982): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2982): enable
,I/bt_hci_bdroid( 2982): init
,I/bt_vendor( 2982): init
I/bt_vnd_conf( 2982): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2982): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2982): userial_init
,I/GKI_LINUX( 2982): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2982): btu_task pending for preload complete event
,I/bt_userial_vendor( 2982): userial vendor open: opening /dev/ttyHS99
I/bt_userial_vendor( 2982): device fd = 53 open
D/bt_userial( 2982): Entering userial_read_thread()
,I/art     ( 1354): Explicit concurrent mark sweep GC freed 7904(436KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 758us total 21.861ms
,I/bt_hwcfg( 2982): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2982): Chipset BCM4335C0
D/bt_hwcfg( 2982): Target name = [BCM4335C0]
,I/bt_hwcfg( 2982): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/ActivityManager(  754): Killing 1765:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/wpa_supplicant( 2988): rfkill: Cannot open RFKILL control device
,W/libprocessgroup(  754): failed to open /acct/uid_10045/pid_1765/cgroup.procs: No such file or directory
,D/Tethering(  754): sendTetherStateChangedBroadcast 1, 0, 0
,D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/wpa_supplicant( 2988): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  754): Loading config and enabling all networks 
,D/WifiService(  754): New client listening to asynchronous messages
,E/WifiConfigStore(  754): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 1789): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  754): Setting external_sim to 1
,D/WifiStateMachine(  754): Setting OUI to DA-A1-19
I/WifiNative-HAL(  754): startHal
,D/wifi    (  754): setting scan oui 0x9c04b388
D/WifiHAL (  754): Sending mac address OUI
E/WifiHAL (  754): failed to set scanning mac OUI; result = -95
,E/native  (  754): do suspend true
,D/CommandListener(  179): Setting iface cfg
D/WifiScanningService(  754): SCAN_AVAILABLE : 3
D/CommandListener(  179): Trying to bring up p2p0
D/RttService(  754): SCAN_AVAILABLE : 3
D/WifiScanningService(  754): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  754): startHal
,D/wifi    (  754): getting scan capabilities on interface[1] = 0x9c04b388
,D/WifiHAL (  754): Creating message to get scan capablities; iface = 21
D/WifiHAL (  754): In GetCapabilities::handleResponse
D/WifiHAL (  754): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  754): StartedState
D/RttService(  754): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor(  754): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  754): p2pGetDeviceAddress
,D/WifiNative-HAL(  754): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2988): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 2982): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2982): Settlement delay -- 100 ms
I/bt_hwcfg( 2982): Setting fw settlement delay to 100 
,I/bt_hwcfg( 2982): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2982): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 2982): vendor lib fwcfg completed
,I/bt-btu  ( 2982): btu_task received preload complete event
,I/        ( 2982): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2982): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 2982): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2982): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2982): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2982): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2982): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 2982): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2982): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2982): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2982): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2982): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2982): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2982): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2982): BTE_InitTraceLevels -- TRC_BTIF
,W/ProcessCpuTracker(  754): Skipping unknown process pid 3007
W/ProcessCpuTracker(  754): Skipping unknown process pid 3008
W/ProcessCpuTracker(  754): Skipping unknown process pid 3015
W/ProcessCpuTracker(  754): Skipping unknown process pid 3016
W/ProcessCpuTracker(  754): Skipping unknown process pid 3027
W/ProcessCpuTracker(  754): Skipping unknown process pid 3090
,I/ActivityManager(  754): Killing 2424:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,E/bt-btm  ( 2982): BTM_SecRegister:p_cb_info->p_le_callback == 0xa408b9d5 
E/bt-btm  ( 2982): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa408b9d5 
,W/libprocessgroup(  754): failed to open /acct/uid_10003/pid_2424/cgroup.procs: No such file or directory
,E/bt-btif ( 2982): Calling BTA_HhEnable
E/bt-btif ( 2982): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 2982): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  754): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  754): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 2982): Name is: Nexus 5
,D/BluetoothAdapterProperties( 2982): Scan Mode:20
D/BluetoothAdapterProperties( 2982): Discoverable Timeout:120
D/bte_conf( 2982): Device ID record 1 : primary
D/bte_conf( 2982):   vendorId            = 000f
D/bte_conf( 2982):   vendorIdSource      = 0001
D/bte_conf( 2982):   product             = 1200
D/bte_conf( 2982):   version             = 1436
D/bte_conf( 2982):   clientExecutableURL = 
D/bte_conf( 2982):   serviceDescription  = 
D/bte_conf( 2982):   documentationURL    = 
D/bte_conf( 2982): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2982): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2982): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2982): ScanMode =  20
D/BluetoothAdapterProperties( 2982): State =  11
D/BluetoothAdapterProperties( 2982): Setting state to 12
I/BluetoothAdapterState( 2982): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterProperties( 2982): Scan Mode:21
D/BluetoothAdapterProperties( 2982): Discoverable Timeout:120
D/BluetoothManagerService(  754): Message: 60
D/BluetoothManagerService(  754): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  754): Broadcasting onBluetoothStateChange(true) to 9 receivers.
I/BluetoothAdapterState( 2982): Entering On State
D/BluetoothA2dp(  754): onBluetoothStateChange: up=true
D/BluetoothPbap( 2998): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=true
D/BluetoothMap( 2998): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 2998): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=true
D/BluetoothHeadset(  754): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1232): onBluetoothStateChange: up=true
D/BluetoothPan( 2998): onBluetoothStateChange(on) call bindService
,D/BluetoothManagerService(  754): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  754): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  754): Message: 40
,D/BluetoothManagerService(  754): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 2982): onReceive
D/BluetoothMapService( 2982): STATE_ON
V/BluetoothMapService( 2982): Handler(): got msg=1
D/BluetoothMapMasInstance( 2982): Map Service startRfcommSocketListener
,W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = f2 23 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = f5 d9 59 98 40 37 3c 1b f5 91 89 9e c6 bb 81 bf 
W/bt-btm  ( 2982): Stopping oneshot timer
,E/bt_h4   ( 2982): vendor lib postload completed
,I/Telecom ( 1204): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapMasInstance( 2982): MAS initSocket()
D/BluetoothMapMasInstance( 2982):   masId = 00
D/BluetoothMapMasInstance( 2982):   msgTypes = 0e
D/BluetoothMapMasInstance( 2982):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2982):   SDP string = 000eSMS/MMS
,W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = 88 6e 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = fa 87 ee b5 01 ea ec 83 c9 57 da f5 f3 43 68 01 
W/bt-btm  ( 2982): Stopping oneshot timer
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = a7 e6 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = 07 d1 e0 dd 33 ae a4 2a 13 7e ca 34 2e 93 4a 04 
W/bt-btm  ( 2982): Stopping oneshot timer
W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = 4a d7 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = e3 05 f6 c6 7a cb 30 f6 a3 83 78 b9 25 ee 1d b5 
W/bt-btm  ( 2982): Stopping oneshot timer
D/HeadsetStateMachine( 2982): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2982): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2982): mNumber:  mType: 128
D/HeadsetStateMachine( 2982): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2982): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = e0 4b 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = a0 a8 41 99 9e 47 df 0b ab 18 58 39 be e3 70 1c 
W/bt-btm  ( 2982): Stopping oneshot timer
,W/BluetoothAdapter( 2982): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 2982): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2982): Accepting socket connection...
D/LocalBluetoothProfileManager( 2998): Adding local A2DP profile
D/BluetoothManagerService(  754): Message: 30
,W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = ed 49 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = 45 a7 3a 4a 1c 51 f4 fe bd 86 4b 6c f0 72 f1 38 
W/bt-btm  ( 2982): Stopping oneshot timer
D/LocalBluetoothProfileManager( 2998): Adding local HEADSET profile
W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = 77 74 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = 18 dd b6 59 82 02 49 d6 23 e3 27 e0 69 7d 8e e7 
W/bt-btm  ( 2982): Stopping oneshot timer
,D/BluetoothManagerService(  754): Message: 30
,W/ContextImpl( 2998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
D/BluetoothA2dp( 2998): Proxy object connected
D/A2dpProfile( 2998): Bluetooth service connected
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2982): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothHeadset( 2998): Proxy object connected
D/HeadsetProfile( 2998): Bluetooth service connected
,D/DockEventReceiver( 2998): finishStartingService: stopping service
D/BluetoothPbap( 2998): Proxy object connected
D/PbapServerProfile( 2998): Bluetooth service connected
,D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2982): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2982): Accept thread started.
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2924): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): my name is : LGE-Nexus 5_PT5860
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): attempting to connect to test coordinator
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): check test folder
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): found test : ./testFindPeers.js
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): found test : ./testReConnect.js
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): found test : ./testSendData.js
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): Test app app.js loaded
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/chromium( 2924): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  754): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  754): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  754): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  754): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  754): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  754): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  754): will read network variables netId=1
,E/WifiStateMachine(  754): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  754): will read network variables netId=1
,I/wpa_supplicant( 2988): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
E/WifiConfigStore(  754): setLastSelectedConfiguration -1
,E/wpa_supplicant( 2988): PNO: In assoc process
,I/wpa_supplicant( 2988): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 2988): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2988): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  754): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  754): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  754): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  754): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  754): Start Dhcp Watchdog 1
,E/native  (  754): do suspend false
,E/WifiStateMachine(  754): scanCount==0 - aborting
,I/dhcpcd  ( 3146): version 5.5.6 starting
,E/dhcpcd  ( 3146): get_duid: Read-only file system
,I/dhcpcd  ( 3146): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3146): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3146): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  754): do suspend true
,D/ConnectivityService(  754): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  754): Adding iface wlan0 to network 100
,E/WifiStateMachine(  754): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  754): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  754): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  754): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  754): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  754): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  754): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  754): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  754): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  754): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  754):    accepting network in place of null
,D/ConnectivityService(  754): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  754): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  754): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  754): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  754): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 08 Dec 2015 16:46:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449593199634], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449593199618]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Validated
D/ConnectivityService(  754): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  754): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  754): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  754): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  754): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1232): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524290
,D/Nat464Xlat(  754): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  754): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524295
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,D/ConnectivityService(  754): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  754): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  754): Setting time of day to sec=1449593203
,W/AlarmManagerService(  754): Unable to set rtc to 1449593203: Invalid argument
,I/NetworkMonitor( 2454): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2454): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/iu.SyncManager( 1560): SYNC; picasa accounts
,E/GpsLocationProvider(  754): No APN found to select.
,D/NetworkLogImpl( 1560): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1560): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1560): num queued entries: 0
,I/iu.UploadsManager( 1560): num updated entries: 0
,I/iu.SyncManager( 1560): NEXT; no task
,D/GpsLocationProvider(  754): NTP server returned: 1449593200276 (Tue Dec 08 17:46:40 GMT+01:00 2015) reference: 81376 certainty: 12 system time offset: -3083
E/LocSvc_eng(  754): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1560): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1560): onCreate
,D/SystemUpdateService( 1560): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SystemUpdateService( 1560): active receiver: enabled
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1560): showing system update notification
,I/ValidateNoPeople(  754): skipping global notification
,V/SystemUpdateService( 1560): retry (wakeup: false) in 3599983 ms
,I/ActivityManager(  754): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3278 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SystemUpdateService( 1560): onDestroy
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1560): [CredentialSyncAdapter] Unknown sync event.
,I/Babel   ( 1789): connection state changed from UNKNOWN to CONNECTED
,I/GAv4    ( 3278): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3278):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3278):   adb logcat -s GAv4
,I/GCM     ( 1354): GCM config loaded
,W/GAv4    ( 3278): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3278): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3278): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  754): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  754): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  754): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1560): CM callback handler got msg 524290
,I/jxcore-log( 2924): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2924): 
,W/AbstractGoogleClient( 2008): Application name is not set. Call Builder#setApplicationName.
,I/WebViewFactory( 3278): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/AnalyticsLogBase( 2008): PlayLogger.onLoggerConnected
,I/LibraryLoader( 3278): Time to load native libraries: 1 ms (timestamps 4857-4858)
I/LibraryLoader( 3278): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3278): Binding Chromium to main looper Looper (main, tid 1) {29c16b50}
,I/LibraryLoader( 3278): Expected native library version number "",actual native library version number ""
I/chromium( 3278): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3278): Initializing chromium process, singleProcess=true
,W/art     ( 3278): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3278): ApplicationContext is null in ApplicationStatus
,W/chromium( 3278): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3278): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/art     (  754): Explicit concurrent mark sweep GC freed 49851(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 1.840ms total 61.094ms
,W/AudioManagerAndroid( 3278): Requires BLUETOOTH permission
,I/NSApplication( 3278): Starting up...
,W/DriveInitializer( 1560): Awaiting to be initialized
,W/DriveInitializer( 1560): Background init thread started
,I/ActivityManager(  754): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3364 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 177us total 9.156ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.836ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 254us total 7.922ms
W/DriveInitializer( 1560): Background init thread ended
,D/TimeService( 3364): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449593204008
D/        ( 3364): TimeServiceNative: User Time to be set is 1449593204009
D/QC-time-services( 3364): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3364): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3364): Lib:time_genoff_operation: pargs->ts_val = 1449593204009
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449593204009
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1449593204009, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/11/70 22:37:28
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 8721448000
D/QC-time-services(  198): Daemon:new time 1449593204009 
D/QC-time-services(  198): Daemon: delta 1440871756009 genoff 1440871756009 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871756009 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 3364): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871756009 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1133628404009
,E/QC-time-services( 3364): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1560): Checkin interval check for package: unspecified last checkin: 1449576468976 min interval config: 0 actual interval: 16735066
I/art     ( 1354): Explicit concurrent mark sweep GC freed 10695(633KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 19MB/32MB, paused 627us total 42.847ms
,W/art     ( 2574): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  754): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3396 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3396): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3396):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3396):   adb logcat -s GAv4
,W/GAv4    ( 3396): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3396): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3396): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CalendarSyncAdapter( 2008): Found no pending settings
,I/ActivityManager(  754): Killing 2734:com.google.android.gms:car/u0a8 (adj 15): empty #17
,I/ActivityManager(  754): Killing 2316:com.google.android.gm/u0a70 (adj 15): empty #18
,W/libprocessgroup(  754): failed to open /acct/uid_10008/pid_2734/cgroup.procs: No such file or directory
,W/libprocessgroup(  754): failed to open /acct/uid_10070/pid_2316/cgroup.procs: No such file or directory
,D/DelayedSyncController(  940): Delaying sync.
,I/SyncAdapterService( 3278): Ignoring sync request for non-current account
,I/CalendarSyncAdapter( 2008): Found no pending settings
,I/ActivityManager(  754): Killing 1383:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  754): failed to open /acct/uid_10004/pid_1383/cgroup.procs: No such file or directory
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,D/Finsky  ( 2376): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2376): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1354): Vacuum at: now=1449593216970 tag=VacuumService
,D/UdcCache:FPQuery( 1560): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1354): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1354): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1354):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1354): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/ClearcutLoggerApiImpl( 1337): disconnect managed GoogleApiClient
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Coordinator is now connected to the server!
I/jxcore-log( 2924): 
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  754): Explicit concurrent mark sweep GC freed 30950(1294KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.005ms total 71.060ms
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1354): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 2924): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector command called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":22,"addressList":[{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"90:E7:C4:F6:69
,I/jxcore-log( 2924): Start now : testSendData.js
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 22
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): check server
I/jxcore-log( 2924): 
I/jxcore-log( 2924): serverPort is 46361
I/jxcore-log( 2924): 
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT5860
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 2924): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): setState: INITIALIZED
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 2924): start: OK
I/jxcore-log( 2924): StartBroadcasting started ok
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:36.286Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:36.287Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:36.287Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null B4:CE:F6:AB:A4:6A
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: B4:CE:F6:AB:A4:6A)
,I/jxcore-log( 2924): 2015-12-08T16:52:36.298Z SendDataTCPServer.js: TCP/IP server is bound to port: 46361
I/jxcore-log( 2924): 
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 2924): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 2924): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address B4:CE:F6:AB:A4:6A (thread ID: 273)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 5
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:6, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 6
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 273)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 273)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 7
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 8
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 273)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 273)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 9
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 10
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 273)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 273)
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:11, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 11
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:12, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 12
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 273)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 273)
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4202ebc rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device B4:CE:F6:AB:A4:6A not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for B4:CE:F6:AB:A4:6A, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [B4:CE:F6:AB:A4:6A B4:CE:F6:AB:A4:6A B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 5 (thread ID: 273)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 275)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 275)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 273)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 275)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 83 bytes successfully (thread ID: 275)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 275)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT685, Bluetooth address: B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID B4:CE:F6:AB:A4:6A, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 276)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 50661
I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 50661 (peer ID: B4:CE:F6:AB:A4:6A)
I/jxcore-log( 2924): 2015-12-08T16:52:41.722Z SendDataConnector.js: CLIENT connected to 50661, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:41.723Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 50661
,D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 276)
,I/jxcore-log( 2924): 2015-12-08T16:52:41.757Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 277, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 278, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:52:42.557Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:42.943Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/jxcore-log( 2924): 2015-12-08T16:52:43.090Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.157Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.225Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.445Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.598Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.741Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.814Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.901Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:43.903Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:52:43.923Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:43.923Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 278
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 277
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 277, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 278, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: B4:CE:F6:AB:A4:6A
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 277, name: Sender)
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID B4:CE:F6:AB:A4:6A
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 278, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:52:43.953Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:43.954Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:43.954Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:52:43.954Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 279)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4202ebc rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4202ebc rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,D/BluetoothManagerService(  754): Message: 20
D/BluetoothManagerService(  754): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29808f13:true
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: HTC Desire 820
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6013"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6013"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT6013, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: , Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:B1:66
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4679 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4679, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420324c rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 280)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 280)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 77 bytes successfully (thread ID: 280)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 280)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 280
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 280)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 280)
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0xd  CID 0x4c
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 14
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420324c rs_disc_pending=1
,W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): invalid rfc slot id: 4
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x4f
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x1f  CID 0x41
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 16
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 279)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 279)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: 34:FC:EF:9D:93:0B, name: LGE-LG-D802_PT7603, Bluetooth address: 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID 34:FC:EF:9D:93:0B, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,I/jxcore-log( 2924): 2015-12-08T16:53:14.005Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:14.005Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:14.005Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 281)
,I/jxcore-log( 2924): 2015-12-08T16:53:14.014Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 281)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 283, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:53:14.020Z SendDataTCPServer.js: TCP/IP server has received 49152 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 282, name: Sender)
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 282, thread name: Sender): Broken pipe
E/io.jxcore.node.IncomingSocketThread( 2924): The sending thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
,I/jxcore-log( 2924): 2015-12-08T16:53:14.024Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 283, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 281
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 283
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 282
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 283, name: Receiver)
,W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 282, name: Sender)
I/jxcore-log( 2924): 2015-12-08T16:53:14.030Z SendDataTCPServer.js: TCP/IP server got error : Error: write ECONNRESET
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 279)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test's G2
,I/jxcore-log( 2924): 2015-12-08T16:53:19.008Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:19.009Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test's G2
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 284)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 77 bytes successfully (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 284)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 284
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: 34:FC:EF:9D:93:0B, name: LGE-LG-D802_PT7603, Bluetooth address: 34:FC:EF:9D:93:0B
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID 34:FC:EF:9D:93:0B, created successfully
,D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 284)
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 285)
,I/jxcore-log( 2924): 2015-12-08T16:53:21.993Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 285)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 287, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 286, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:53:23.080Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.122Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.144Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.190Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.197Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.205Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.219Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.301Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.307Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.317Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.321Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.333Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.373Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.383Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.424Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.452Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.491Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.506Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.562Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.601Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.771Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.907Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:23.936Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:53:24.018Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:24.018Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.019Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.024Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 2924): 2015-12-08T16:53:24.043Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 288)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2924): 2015-12-08T16:53:24.078Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.091Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420324c rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2924): 2015-12-08T16:53:24.283Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.325Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.387Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.473Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.556Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.625Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.820Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:24.919Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.004Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.101Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.111Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.153Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.171Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.203Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.214Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:25.545Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,W/bt-btif ( 2982): invalid rfc slot id: 15
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 287, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 285
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 287
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 286
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 286, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 34:FC:EF:9D:93:0B disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 286, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 287, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:53:25.759Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420324c rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x44
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 18
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 2982): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420324c rs_disc_pending=2
E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test's G2
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 289)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 289)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 77 bytes successfully (thread ID: 289)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 289)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 289
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 289)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: 34:FC:EF:11:B1:66, name: LGE-Nexus 5_PT6013, Bluetooth address: 34:FC:EF:11:B1:66
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID 34:FC:EF:11:B1:66, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 290)
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
,I/jxcore-log( 2924): 2015-12-08T16:53:38.664Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 290)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 292, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 291, name: Sender)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203084 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,I/jxcore-log( 2924): 2015-12-08T16:53:40.401Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 288)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 288)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/jxcore-log( 2924): 2015-12-08T16:53:40.434Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.447Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:40.447Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:40.447Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.460Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.500Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.506Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.513Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.579Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.649Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.701Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.739Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.756Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.792Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.807Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.843Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.849Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.891Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:40.987Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.027Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.061Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.079Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.110Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.124Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.162Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.170Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:41.296Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): invalid rfc slot id: 17
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 292, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 290
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 292
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 291
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203084 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 292, name: Receiver)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 291, thread name: Sender): Socket closed
,E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 291, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:53:41.625Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x4b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2924): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2924): 2015-12-08T16:53:45.448Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:53:45.449Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Nexus 5
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:53:50.456Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:50.457Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:50.457Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:53:50.458Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 293)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [08:ec:a9:50:76:27]: 6, f, 6109
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 293)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/jxcore-log( 2924): 2015-12-08T16:54:14.500Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:14.500Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:14.500Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/jxcore-log( 2924): 2015-12-08T16:54:19.500Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:19.501Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:54:24.506Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:24.506Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:24.507Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:24.508Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 294)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9318"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9318"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9318, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 22
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 23
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 294)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 294)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 24
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 25
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 294)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 294)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
I/jxcore-log( 2924): 2015-12-08T16:54:45.423Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:45.424Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:76:27 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:45.425Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 294)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 295)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 295)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 295)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3802 E0:DB:10:1F:C9:5E]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 295)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 295
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 295)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3802 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 295)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3802 E0:DB:10:1F:C9:5E]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT3802, Bluetooth address: E0:DB:10:1F:C9:5E
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID E0:DB:10:1F:C9:5E, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 296)
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 2924): 2015-12-08T16:54:47.235Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 296)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 298, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 297, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3802 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3802, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/jxcore-log( 2924): 2015-12-08T16:54:48.125Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.130Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.152Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.168Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.216Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.221Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.243Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.281Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.287Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.323Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.361Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.377Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.400Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.438Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.446Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.487Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.495Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.503Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.513Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.524Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.560Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.579Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2924): 2015-12-08T16:54:48.602Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.630Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.636Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.646Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.695Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.700Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.731Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.738Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.767Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.786Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.794Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T16:54:48.836Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 298, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 296
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 298
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 297
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 298, name: Receiver)
,W/bt-btif ( 2982): invalid rfc slot id: 20
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 297, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID E0:DB:10:1F:C9:5E disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 297, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:54:48.933Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
,W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x45
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT742 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT742, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
I/jxcore-log( 2924): 2015-12-08T16:54:50.432Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:50.433Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Note3-1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT9671 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT9671, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:76:27), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:54:55.438Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:55.438Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:54:55.439Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:54:55.444Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 299)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 27
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [08:EC:A9:50:76:27 08:EC:A9:50:76:27 08:EC:A9:50:76:27]
,W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 299)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 300)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 300)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 83 bytes successfully (thread ID: 300)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 300)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT6268, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 301)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 48245
,I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 48245 (peer ID: 08:EC:A9:50:76:27)
I/jxcore-log( 2924): 2015-12-08T16:55:10.295Z SendDataConnector.js: CLIENT connected to 48245, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:10.296Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 48245
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 301)
,I/jxcore-log( 2924): 2015-12-08T16:55:10.327Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 302, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 303, name: Receiver)
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2924): 2015-12-08T16:55:10.923Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:10.970Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2924): 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2924): 2015-12-08T16:55:11.092Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.219Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2924): 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 2924): 2015-12-08T16:55:11.258Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.265Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.347Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.584Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.662Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2924): 2015-12-08T16:55:11.780Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:11.781Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.791Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.791Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 303
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 302
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 302, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 303, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 302, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 303, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:55:11.810Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:11.811Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:11.811Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:11.811Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 304)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203084 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203084 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203084 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa42037a4 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203084 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa42037a4 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
W/bt-l2cap( 2982): L2CAP got sec_comp for unknown BD_ADDR
,W/bt-btif ( 2982): invalid rfc slot id: 29
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2982): onReceive
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x10  CID 0x4d
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 30
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 304)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T16:55:31.586Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:31.586Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 00:F4:6F:30:E0:6C failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:31.586Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 305)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1171 B0:C5:59:3F:75:69]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 305)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 305
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 305)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1171 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 305)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1171 B0:C5:59:3F:75:69]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: B0:C5:59:3F:75:69, name: samsung-SM-G900F_PT1171, Bluetooth address: B0:C5:59:3F:75:69
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID B0:C5:59:3F:75:69, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 306)
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
,I/jxcore-log( 2924): 2015-12-08T16:55:35.417Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 306)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 308, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 307, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:55:36.454Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.461Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.529Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.537Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.561Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.587Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.588Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:36.595Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.605Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.644Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.667Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.701Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.744Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.768Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.785Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.795Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.878Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.882Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.916Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.923Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.931Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.970Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:36.993Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.031Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.037Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.071Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.082Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.128Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.138Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.156Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.206Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/jxcore-log( 2924): 2015-12-08T16:55:37.244Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.281Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:37.311Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,W/bt-btif ( 2982): invalid rfc slot id: 26,
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 308, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 306
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 308
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 307
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 307, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID B0:C5:59:3F:75:69 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 308, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 307, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:55:37.391Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x4b
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:F4:6F:30:E0:6C), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:55:41.594Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:41.594Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:41.594Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:41.594Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 309)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [00:f4:6f:30:e0:6c]: 7, f, 610c
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 309)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 310)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 310)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 310)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 310)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT9318, Bluetooth address: 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 311)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 50933
I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 50933 (peer ID: 00:F4:6F:30:E0:6C)
I/jxcore-log( 2924): 2015-12-08T16:55:50.215Z SendDataConnector.js: CLIENT connected to 50933, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:50.216Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 50933
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 311)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 313, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 312, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:55:50.239Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:50.904Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2924): 2015-12-08T16:55:51.280Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:51.583Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:51.734Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:52.399Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:52.748Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:54.083Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:54.373Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:54.858Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:55.272Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:55.273Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:55:55.292Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:55.293Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 313
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 312
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 312, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 313, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:55:55.328Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:55.329Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:55.329Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:55:55.329Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 314)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa42037a4 rs_disc_pending=1
,W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203b34 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203b34 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: S5mini-1
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.,
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 314)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 315)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 314)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 315)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 315)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1766 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1766 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 315)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1766 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT1766, Bluetooth address: E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID E0:DB:10:14:E2:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 316)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 57440
I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 57440 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 2924): 2015-12-08T16:56:05.018Z SendDataConnector.js: CLIENT connected to 57440, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:05.019Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 57440
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 316)
,I/jxcore-log( 2924): 2015-12-08T16:56:05.042Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 318, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 317, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:56:06.059Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2924): 2015-12-08T16:56:06.367Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:06.772Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 2924): 2015-12-08T16:56:07.203Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/jxcore-log( 2924): 2015-12-08T16:56:08.353Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:08.860Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT2881, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-btif ( 2982): dm_pm_timer expires
W/bt-btif ( 2982): dm_pm_timer expires 0
,W/bt-btif ( 2982): proc dm_pm_timer expires
,I/jxcore-log( 2924): 2015-12-08T16:56:14.901Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT866 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT866, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 2924): 2015-12-08T16:56:15.386Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:15.386Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:15.406Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:15.407Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 318
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 317
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 317, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 318, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:56:15.454Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:15.461Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:15.462Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:15.462Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 319)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203b34 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203b34 rs_disc_pending=0,
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 34
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4679 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4679, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 08:EC:A9:50:75:41 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 319)
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 319)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 83 bytes successfully (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT7957, Bluetooth address: 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 321)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 40035
,I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 40035 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 2924): 2015-12-08T16:56:26.006Z SendDataConnector.js: CLIENT connected to 40035, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:26.007Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 40035
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 321)
,I/jxcore-log( 2924): 2015-12-08T16:56:26.012Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 323, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 322, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2389","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT2389 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2389","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2389","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT2389, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: XT1072_23d5, Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2924): 2015-12-08T16:56:27.383Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 2924): 2015-12-08T16:56:27.701Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2924): 2015-12-08T16:56:29.230Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:30.140Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2924): 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 2924): 2015-12-08T16:56:30.225Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:30.318Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:30.328Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:30.549Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2924): 2015-12-08T16:56:31.503Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:32.048Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:32.049Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:56:32.066Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:32.067Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
,I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 323
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 322
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:75:41
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 322, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 323, name: Receiver)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,I/jxcore-log( 2924): 2015-12-08T16:56:32.115Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:32.116Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:32.116Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:32.116Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203cfc rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 36
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 37
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 38
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 39
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 40
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 41
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203cfc rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 42
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 43
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 324)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 44
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 45
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Maximum number of retries (5) reached, giving up... (thread ID: 324)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 324)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
I/jxcore-log( 2924): 2015-12-08T16:56:35.365Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:35.365Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:35.365Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT7957, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT685, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T16:56:40.366Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:40.366Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3616"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3616"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3616"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3616, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:56:45.373Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:45.374Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:45.376Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:45.376Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 46
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 47
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 48
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 49
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 50
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 51
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 52
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 53
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 54
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 55
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 325)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Maximum number of retries (5) reached, giving up... (thread ID: 325)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 325)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
I/jxcore-log( 2924): 2015-12-08T16:56:48.767Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:48.768Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:48.768Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2924): 2015-12-08T16:56:53.775Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:53.775Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:56:58.783Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:58.784Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:58.784Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:56:58.785Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:56, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 56
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 57
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 326)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:58, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 58
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 326)
,W/bt-btif ( 2982): invalid rfc slot id: 59
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 60
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 61
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 62
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 63
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 64
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 65
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Maximum number of retries (5) reached, giving up... (thread ID: 326)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 326)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
I/jxcore-log( 2924): 2015-12-08T16:57:01.434Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:01.435Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:01.435Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 2924): 2015-12-08T16:57:06.437Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:06.437Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 2924): 2015-12-08T16:57:11.447Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:11.448Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:11.448Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:11.449Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 66
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 67
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:68, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 68
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 69
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 70
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 71
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 72
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 73
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 327)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 74
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:75, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 75
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 327)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Maximum number of retries (5) reached, giving up... (thread ID: 327)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 327)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
I/jxcore-log( 2924): 2015-12-08T16:57:13.514Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:13.515Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:13.516Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT866 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT866, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 2924): 2015-12-08T16:57:18.517Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:18.518Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2389","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT2389 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2389","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 44:80:EB:7B:5A:05, peer name: motorola-XT1072_PT2389, peer ID: 44:80:EB:7B:5A:05, Wi-Fi Direct device name: XT1072_23d5, Wi-Fi Direct address: 44:80:eb:7b:5a:07
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 44:80:EB:7B:5A:05 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:57:23.533Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:23.534Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:23.534Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:23.535Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 328)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 76
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 77
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 78
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 79
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 80
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 81
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 82
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 83
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 84
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 85
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 328)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Maximum number of retries (5) reached, giving up... (thread ID: 328)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 328)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2 F4:F1:E1:5C:3B:E2]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
I/jxcore-log( 2924): 2015-12-08T16:57:28.178Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:28.182Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:28.198Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:57:28.202Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:28.205Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:28.206Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:28.206Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 329)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203ec4 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [34:fc:ef:11:b1:66]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 329)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 329)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 330)
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 77 bytes successfully (thread ID: 330)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 330)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:B1:66, name: LGE-Nexus 5_PT6013, Bluetooth address: 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 34:FC:EF:11:B1:66, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 331)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 51166
,I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 51166 (peer ID: 34:FC:EF:11:B1:66)
I/jxcore-log( 2924): 2015-12-08T16:57:32.181Z SendDataConnector.js: CLIENT connected to 51166, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:32.182Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 51166
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 331)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 333, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:57:32.222Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 332, name: Sender)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 2924): 2015-12-08T16:57:37.721Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:38.193Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2924): 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 2924): 2015-12-08T16:57:38.305Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:38.507Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2924): 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 2924): 2015-12-08T16:57:38.665Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:38.828Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:39.048Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:39.334Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:39.651Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:39.817Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:39.817Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:39.839Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:39.839Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:B1:66
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 333
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 332
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 332, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 333, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:B1:66
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 332, name: Sender)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 333, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:57:39.876Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:39.877Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:57:39.877Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:57:39.877Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4203414 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4679 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4679, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 87
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 88
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 89
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 90
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 334)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
,I/jxcore-log( 2924): 2015-12-08T16:58:00.968Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:58:00.971Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:58:00.976Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 334)
,I/jxcore-log( 2924): 2015-12-08T16:58:05.978Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:58:05.979Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:58:10.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:58:10.987Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:58:10.988Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:58:10.988Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 91
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 92
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 335)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 2924): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 93
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 94
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
I/jxcore-log( 2924): 2015-12-08T16:58:31.887Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:58:31.887Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:58:31.888Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 335)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9318"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9318, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 2924): 2015-12-08T16:58:36.891Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:58:36.893Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
,I/jxcore-log( 2924): 2015-12-08T16:58:41.899Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:58:41.905Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:58:41.908Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:58:41.911Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 95
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 96
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 336)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 336)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 97
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2982): invalid rfc slot id: 98
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 336)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
,I/jxcore-log( 2924): 2015-12-08T16:59:02.843Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:02.844Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:02.845Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 336)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT2881, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
,I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT1766","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT1766 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT1766, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2924): 2015-12-08T16:59:07.846Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:07.847Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T16:59:12.853Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:12.853Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:12.854Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:12.854Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 337)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 99
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 100
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 337)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 101
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 338)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 338)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 83 bytes successfully (thread ID: 338)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 338)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 338
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 338)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 338)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 102
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 337)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT6268, Bluetooth address: 08:EC:A9:50:76:27
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID 08:EC:A9:50:76:27, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,I/jxcore-log( 2924): 2015-12-08T16:59:33.810Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:33.811Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:33.811Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 339)
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 2924): 2015-12-08T16:59:33.827Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 339)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 341, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 340, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T16:59:33.832Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/jxcore-log( 2924): 2015-12-08T16:59:33.968Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.091Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.201Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.278Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.296Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.333Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.416Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.610Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.643Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.705Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T16:59:34.724Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 2924): 2015-12-08T16:59:34.837Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 2924): 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/jxcore-log( 2924): 2015-12-08T16:59:34.932Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4679 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4679, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/jxcore-log( 2924): 2015-12-08T16:59:35.161Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.246Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.331Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.433Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.445Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.481Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.683Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.896Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.974Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.983Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:35.997Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.008Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.074Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.176Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.195Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.202Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.212Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.402Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.587Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.605Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.717Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.841Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.938Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.945Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:36.951Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:37.046Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:37.154Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:37.572Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:37.647Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:37.656Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T16:59:37.662Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,W/bt-btif ( 2982): invalid rfc slot id: 31
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 341, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 339
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 341
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 340
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 340, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 08:EC:A9:50:76:27 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 340, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 341, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T16:59:38.145Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 2924): 2015-12-08T16:59:38.813Z SendDataConnector.js: re-try now : 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:38.814Z SendDataConnector.js: ReStart called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
,I/jxcore-log( 2924): 2015-12-08T16:59:43.824Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:43.825Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:9D:93:0B with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:43.826Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T16:59:43.826Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 34:FC:EF:9D:93:0B
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Thali Test's G2 34:FC:EF:9D:93:0B
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Thali Test's G2 in address 34:FC:EF:9D:93:0B
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 34:FC:EF:9D:93:0B)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 34:FC:EF:9D:93:0B (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 104
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 105
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 342)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 106
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/EventLogService( 1560): Aggregate from 1449592173161 (log), 1449592173161 (data)
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:107, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 107
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 342)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
,I/jxcore-log( 2924): 2015-12-08T17:00:04.745Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:04.746Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:9D:93:0B failed
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:00:04.762Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:9D:93:0B
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:9D:93:0B
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:9D:93:0B), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:00:04.765Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- gotta redo : 34:FC:EF:9D:93:0B, try count now: 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:04.768Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:04.769Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:00:04.769Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: Connection to peer with ID 34:FC:EF:9D:93:0B failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 343)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:108, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 108
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:109, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 109
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 343)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 343)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:110, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 110
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:111, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 111
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 343)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
I/jxcore-log( 2924): 2015-12-08T17:00:25.654Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:25.655Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:25.655Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 343)
,I/jxcore-log( 2924): 2015-12-08T17:00:30.656Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:30.656Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_63cc 82:01:84:6b:e8:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
,I/jxcore-log( 2924): 2015-12-08T17:00:35.670Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:35.670Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:35.671Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:00:35.671Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-16ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT6268, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x1f  CID 0x42
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:112, failed to find channle,                                       status:1, scn:0
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-btif ( 2982): invalid rfc slot id: 112
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:113, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 113
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:114, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 114
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.,
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 2 (thread ID: 344)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 344)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,I/jxcore-log( 2924): 2015-12-08T17:01:07.405Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:07.405Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:07.405Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420408c rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4204254 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,E/BluetoothEventManager( 2998): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 345)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420408c rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 345
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT2881, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 345)
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 346)
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 346)
,I/jxcore-log( 2924): 2015-12-08T17:01:09.592Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 348, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 347, name: Sender)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4204254 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2924): 2015-12-08T17:01:10.519Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.563Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.572Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.576Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.613Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.622Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.644Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.683Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.697Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.703Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.737Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.772Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.854Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.861Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.871Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.901Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.924Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:10.931Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.005Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.050Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.081Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.095Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.125Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.163Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.243Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.271Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.295Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.364Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.375Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.414Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.424Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.455Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.473Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.513Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.523Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.531Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.559Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.594Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:01:11.608Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,I/jxcore-log( 2924): 2015-12-08T17:01:11.647Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 2924): 
,D/BluetoothMapService( 2982): onReceive
,I/jxcore-log( 2924): 2015-12-08T17:01:11.679Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A5-1
,W/bt-btif ( 2982): invalid rfc slot id: 103
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 348, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 346
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 348
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 347
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 348, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 347, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T17:01:11.724Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4204254 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 2924): 2015-12-08T17:01:12.406Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:12.406Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Nexus 6
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
,I/jxcore-log( 2924): 2015-12-08T17:01:17.416Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:17.417Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:17.417Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:17.418Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:117, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 117
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:118, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 118
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 349)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 350)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 83 bytes successfully (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 350
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 350)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 350)
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/ActivityManager(  754): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3657 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 3657): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3657): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3657): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 3657): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3657): Installed default security provider GmsCore_OpenSSL
,I/dex2oat ( 3692): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads647246741.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads647246741.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/YouTube MDX( 3657): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3692): dex2oat took 38.009ms (threads: 4)
,W/InstanceID/Rpc( 3657): Found 10008
,I/ActivityManager(  754): Killing 1490:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  754): failed to open /acct/uid_10013/pid_1490/cgroup.procs: No such file or directory
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x1f  CID 0x49
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:119, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 119
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [7c:f9:0e:37:96:ab]: 7, f, 230f
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A5-1
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420408c rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 2 (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT685, Bluetooth address: B4:CE:F6:AB:A4:6A
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID B4:CE:F6:AB:A4:6A, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
I/jxcore-log( 2924): 2015-12-08T17:01:48.832Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:48.832Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:37:96:AB failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:48.832Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 351)
,I/jxcore-log( 2924): 2015-12-08T17:01:48.848Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 351)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 352, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 353, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T17:01:48.858Z SendDataTCPServer.js: TCP/IP server has received 49152 bytes of data
I/jxcore-log( 2924): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/jxcore-log( 2924): 2015-12-08T17:01:48.863Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
,W/bt-btif ( 2982): invalid rfc slot id: 116
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 353, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 351
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 353
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 352
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 353, name: Receiver)
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 352, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID B4:CE:F6:AB:A4:6A disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 352, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T17:01:49.530Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4202ebc rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 2924): 2015-12-08T17:01:53.833Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:53.834Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:01:58.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:58.838Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:58.838Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:01:58.839Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 354)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT9671 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT9671, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
,I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:122, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 122
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4202ebc rs_disc_pending=1
W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x4e
E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 354)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 355)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 355)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 83 bytes successfully (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT1753, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 356)
D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 51630
I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 51630 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 2924): 2015-12-08T17:02:11.697Z SendDataConnector.js: CLIENT connected to 51630, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:11.698Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 51630
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 356)
,I/jxcore-log( 2924): 2015-12-08T17:02:11.726Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 358, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 357, name: Sender)
,W/bt-btif ( 2982): info:x10
D/        ( 2982): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420408c rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:946
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
D/BluetoothAdapterProperties( 2982): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 58:2A:F7:ED:96:BE not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 58:2A:F7:ED:96:BE, but we have no record of that device.
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Incoming connection initialized (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 359)
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420441c rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesRead: Read 80 bytes successfully (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Got valid identity from [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9893 58:2A:F7:ED:96:BE]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 359)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): removeThreadFromList: Removing thread with ID 359
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Handshake thread disposed (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9893 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [58:2A:F7:ED:96:BE HUAWEI-ALE-L21_PT9893 58:2A:F7:ED:96:BE]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming connection, peer ID: 58:2A:F7:ED:96:BE, name: HUAWEI-ALE-L21_PT9893, Bluetooth address: 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Incoming socket thread, for peer with ID 58:2A:F7:ED:96:BE, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 2924): Entering thread (ID: 360)
,I/jxcore-log( 2924): 2015-12-08T17:02:13.836Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 2924): 
,I/io.jxcore.node.IncomingSocketThread( 2924): Local host address: localhost/127.0.0.1, port: 46361
D/io.jxcore.node.IncomingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 2924): Exiting thread (ID: 360)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 362, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 361, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T17:02:14.556Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.561Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.566Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.570Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.595Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.603Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.610Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.652Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.660Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.664Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.704Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.713Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.741Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.782Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.860Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.862Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.866Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.910Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:14.951Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 2924): 
,W/bt-btif ( 2982): invalid rfc slot id: 120
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 362, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 360
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 362
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 361
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 362, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 361, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Incoming connection, peer with ID 58:2A:F7:ED:96:BE disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 361, name: Sender)
I/jxcore-log( 2924): 2015-12-08T17:02:14.982Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420441c rs_disc_pending=1
,W/bt-btif ( 2982): bta_dm_check_av:0
W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 2982): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0,
,W/bt-rfcomm( 2982): RFCOMM_DisconnectInd LCID:0x45
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): dm_pm_timer expires
W/bt-btif ( 2982): dm_pm_timer expires 0
W/bt-btif ( 2982): proc dm_pm_timer expires
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT7957, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 2924): 2015-12-08T17:02:22.182Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:22.183Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:22.185Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:22.185Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:22.186Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2924): 
,E/io.jxcore.node.StreamCopyingThread( 2924): Input stream got -1 on read (thread ID: 357, thread name: Sender)
,E/io.jxcore.node.IncomingSocketThread( 2924): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.IncomingSocketThread( 2924): close
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 358
I/io.jxcore.node.IncomingSocketThread( 2924): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 357
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 358, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 358, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 357, name: Sender)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T17:02:27.186Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:27.187Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2198","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2198 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2198","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT2198, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:37:96:AB), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:02:32.193Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:32.193Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:32.194Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:32.194Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: A5-1 7C:F9:0E:37:96:AB
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:37:96:AB)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:37:96:AB (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 363)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 364)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 364)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 364)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 83 bytes successfully (thread ID: 364)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT1753, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
,D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 365)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 44003
I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 44003 (peer ID: 7C:F9:0E:37:96:AB)
I/jxcore-log( 2924): 2015-12-08T17:02:36.041Z SendDataConnector.js: CLIENT connected to 44003, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:36.042Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 44003
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 365)
,I/jxcore-log( 2924): 2015-12-08T17:02:36.066Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 366, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 367, name: Receiver)
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 2982): dm_pm_timer expires
W/bt-btif ( 2982): dm_pm_timer expires 0
W/bt-btif ( 2982): proc dm_pm_timer expires
,I/jxcore-log( 2924): 2015-12-08T17:02:46.485Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:46.486Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:46.487Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:46.505Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:46.506Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:46.507Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 367
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 366
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 367, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: 7C:F9:0E:37:96:AB
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 366, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 367, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T17:02:46.547Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:46.548Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:46.549Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:46.549Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: Android_50a5
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Nexus 6 F8:CF:C5:D9:E5:61
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Nexus 6 in address F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: F8:CF:C5:D9:E5:61)
I/jxcore-log( 2924): 2015-12-08T17:02:46.551Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2924): 
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address F8:CF:C5:D9:E5:61 (thread ID: 368)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa420408c rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [f8:cf:c5:d9:e5:61]: 6, 10f, 608
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa4204254 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: A5-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 368)
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 369)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 368)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 369)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 369)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 369)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT2881, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 370)
D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 39810
I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 39810 (peer ID: F8:CF:C5:D9:E5:61)
,I/jxcore-log( 2924): 2015-12-08T17:02:51.156Z SendDataConnector.js: CLIENT connected to 39810, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:51.164Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 39810
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 370)
,I/jxcore-log( 2924): 2015-12-08T17:02:51.194Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 371, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 372, name: Receiver)
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 2924): 2015-12-08T17:02:51.705Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 2924): 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19756
,I/jxcore-log( 2924): 2015-12-08T17:02:51.765Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:51.894Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 2924): 
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 2924): 2015-12-08T17:02:51.985Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:52.028Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:52.070Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:52.077Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:52.118Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:52.174Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:52.181Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:52.181Z SendDataConnector.js: got all data for this round
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:02:52.184Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:52.184Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:CF:C5:D9:E5:61
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 372
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 371
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 372, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:CF:C5:D9:E5:61
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 371, name: Sender)
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 372, name: Receiver)
,I/jxcore-log( 2924): 2015-12-08T17:02:52.193Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 2924): 
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:52.201Z SendDataConnector.js: Start called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:52.201Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:02:52.201Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 373)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:127, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 127
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:128, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 128
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 373)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 373)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 2982): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 1
E/bt-btif ( 2982): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:38:94:96:B5:06:DC OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 2982): Entering PendingCommandState State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 38:94:96:B5:06:DC not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 38:94:96:B5:06:DC, but we have no record of that device.
,I/BluetoothBondStateMachine( 2982): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 0
,D/BluetoothAdapterProperties( 2982): Failed to remove device: 38:94:96:B5:06:DC
,I/BluetoothBondStateMachine( 2982): Bond State Change Intent:38:94:96:B5:06:DC OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 2982): StableState(): Entering Off State
,W/BluetoothEventManager( 2998): CachedBluetoothDevice for device 38:94:96:B5:06:DC not found, calling readPairedDevices().
,E/BluetoothEventManager( 2998): Got bonding state changed for 38:94:96:B5:06:DC, but we have no record of that device.
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 2 (thread ID: 373)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 373)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/jxcore-log( 2924): 2015-12-08T17:03:31.989Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:03:31.989Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:03:31.989Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 15 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: S5mini-1 02:f4:6f:30:e0:6d
D/WifiP2pManager( 2924): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-8ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-6ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-5ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 16 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 9: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 10: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 13: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 14: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 15: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 16: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/jxcore-log( 2924): 2015-12-08T17:03:36.990Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:03:36.991Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Galaxy S5-2
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:03:41.996Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:03:41.996Z SendDataConnector.js: Connect (retry count 1) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:03:41.997Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:03:42.005Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:130, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 130
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:131, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 131
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 374)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:132, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2982): invalid rfc slot id: 132
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:133, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 133
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 374)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 374)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/jxcore-log( 2924): 2015-12-08T17:04:02.976Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:02.976Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:02.976Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 374)
,I/jxcore-log( 2924): 2015-12-08T17:04:07.976Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:07.977Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:04:12.983Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:12.983Z SendDataConnector.js: Connect (retry count 2) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:12.984Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:12.984Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 375)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:134, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 134
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Galaxy S5-2
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 375)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 376)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 375)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 376)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT3616, Bluetooth address: 38:94:96:B5:06:DC
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 38:94:96:B5:06:DC, created successfully
,D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 377)
,D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 54516
I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 54516 (peer ID: 38:94:96:B5:06:DC)
I/jxcore-log( 2924): 2015-12-08T17:04:23.116Z SendDataConnector.js: CLIENT connected to 54516, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:23.116Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 54516
D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 377)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 379, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 378, name: Sender)
,I/jxcore-log( 2924): 2015-12-08T17:04:23.154Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT794 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT794, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:946
,W/bt-btif ( 2982): dm_pm_timer expires
W/bt-btif ( 2982): dm_pm_timer expires 0
W/bt-btif ( 2982): proc dm_pm_timer expires
,I/jxcore-log( 2924): 2015-12-08T17:04:33.594Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:33.594Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:33.596Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:33.596Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:33.597Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2924): 
,E/io.jxcore.node.StreamCopyingThread( 2924): Input stream got -1 on read (thread ID: 378, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 2924): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 38:94:96:B5:06:DC disconnected: Input stream got -1 on read
,I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 379
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 378
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 379, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 38:94:96:B5:06:DC disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 379, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 378, name: Sender)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,I/jxcore-log( 2924): 2015-12-08T17:04:38.598Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:38.599Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Galaxy S5-2
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:04:43.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:43.608Z SendDataConnector.js: Connect (retry count 3) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:43.608Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): 2015-12-08T17:04:43.609Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 380)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Galaxy S5-2
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT685, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 380)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesWritten: 77 bytes successfully written (thread ID: 381)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Outgoing connection initialized (*handshake* thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 380)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Entering thread (ID: 381)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): onBytesRead: Read 82 bytes successfully (thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onAuthenticated: Fully connected: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 2924): Exiting thread (ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT3616, Bluetooth address: 38:94:96:B5:06:DC
,D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
,I/io.jxcore.node.ConnectionHelper( 2924): onConnected: Outgoing socket thread, for peer with ID 38:94:96:B5:06:DC, created successfully
D/io.jxcore.node.ConnectionHelper( 2924): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 2924): Entering thread (ID: 382)
D/io.jxcore.node.OutgoingSocketThread( 2924): Server socket local port: 43664
,I/io.jxcore.node.OutgoingSocketThread( 2924): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 2924): onListeningForIncomingConnections: Outgoing connection is using port 43664 (peer ID: 38:94:96:B5:06:DC)
I/jxcore-log( 2924): 2015-12-08T17:04:47.457Z SendDataConnector.js: CLIENT connected to 43664, error: null
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:47.457Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 2924): 
,I/io.jxcore.node.OutgoingSocketThread( 2924): Incoming data from address: /127.0.0.1, port: 43664
,D/io.jxcore.node.OutgoingSocketThread( 2924): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 2924): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 2924): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 2924): Exiting thread (ID: 382)
,I/jxcore-log( 2924): 2015-12-08T17:04:47.488Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 2924): 
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 384, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Entering thread (ID: 383, name: Sender)
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/        ( 2982): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11836
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T17:04:57.912Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:57.913Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:57.914Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:57.915Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:04:57.916Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 2924): 
,E/io.jxcore.node.StreamCopyingThread( 2924): Input stream got -1 on read (thread ID: 383, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 2924): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 38:94:96:B5:06:DC disconnected: Input stream got -1 on read
,I/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 2924): close
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 384
I/io.jxcore.node.OutgoingSocketThread( 2924): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 2924): doStop: Thread ID: 383
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing...
,I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 2924): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 2924): Either failed to read from the output stream or write to the input stream (thread ID: 384, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 2924): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 2924): onDisconnected: Outgoing connection, peer with ID 38:94:96:B5:06:DC disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 384, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 2924): Exiting thread (ID: 383, name: Sender)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): 2015-12-08T17:05:02.917Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:02.917Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:05:07.923Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:07.923Z SendDataConnector.js: Connect (retry count 4) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:07.924Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:07.924Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 38:94:96:B5:06:DC)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 38:94:96:B5:06:DC (thread ID: 385)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:137, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 2982): invalid rfc slot id: 137
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 2982): onReceive
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Galaxy S5-2
,W/bt-btif ( 2982): info:x10
,D/        ( 2982): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Galaxy S5-2
,W/bt-sdp  ( 2982): process_service_search_attr_rsp
,W/bt-btif ( 2982): new conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2982): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onSocketConnected: Authenticating next: [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [38:94:96:B5:06:DC samsung-SM-G800H_PT3616 38:94:96:B5:06:DC]
,I/jxcore-log( 2924): 2015-12-08T17:05:39.729Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:39.735Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 38:94:96:B5:06:DC failed
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 385)
,I/jxcore-log( 2924): 2015-12-08T17:05:39.767Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:39.768Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 38:94:96:B5:06:DC
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 38:94:96:B5:06:DC
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 38:94:96:B5:06:DC), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:05:39.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- round done--------
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ---- gotta redo : 38:94:96:B5:06:DC, try count now: 1
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): do fake peer & start
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:39.788Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:39.788Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:05:39.788Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 38:94:96:B5:06:DC done with result: Connection to peer with ID 38:94:96:B5:06:DC failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 386)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/UsageStatsService(  754): User[0] Flushing usage stats to disk
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa42045e4 rs_disc_pending=1
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 2982): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,E/bt-btm  ( 2982): tBTM_SEC_DEV:0xa42045e4 rs_disc_pending=0
W/bt-btif ( 2982): bta_dm_check_av:0
,W/bt-btif ( 2982): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 2982): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 2982): onReceive
,I/BTConnectionReceiver( 1419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1419): Bluetooth Device Name: Galaxy S5-2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6013"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6013 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6013"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT6013, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: , Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x22  CID 0x4b
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:139, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 2982): invalid rfc slot id: 139
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 2982): No ag scb for peer addr
,E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:140, failed to find channle,                                       status:1, scn:0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 386)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 386)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
,W/bt-btif ( 2982): invalid rfc slot id: 140
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT9671 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT866 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4679 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2198","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2198 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2198","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT742 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3802 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT9671, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT866, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4679, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT2198, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT7957, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT742, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3802, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
I/jxcore-log( 2924): 2015-12-08T17:07:14.083Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:07:14.083Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:07:14.083Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 386)
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 2924): 2015-12-08T17:07:19.083Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:07:19.083Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT794 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT794, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: Thali Test (Galaxy A5), Wi-Fi Direct address: 7e:f9:0e:51:18:23
,I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT794","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:07:24.087Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:07:24.087Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:07:24.088Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:07:24.088Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
,I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
,W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 387)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     (  754): Explicit concurrent mark sweep GC freed 112819(5MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/43MB, paused 1.246ms total 71.303ms
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:141, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 141
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x22  CID 0x4c
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:142, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 142
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 387)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 387)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/jxcore-log( 2924): 2015-12-08T17:08:02.666Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:02.667Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:02.668Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 387),
,I/jxcore-log( 2924): 2015-12-08T17:08:07.669Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:07.669Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:08:12.674Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:12.674Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:12.675Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:12.675Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 388)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 2924): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): The Coordinator has disconnected!
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): DBG, CoordinatorConnector connect called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Coordinator is now connected to the server!
I/jxcore-log( 2924): 
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:143, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 143
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:144, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 144
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 388)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 388)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:145, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 145
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:146, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 146
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 388)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect again in 300 ms... (thread ID: 388)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
I/jxcore-log( 2924): 2015-12-08T17:08:33.581Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:33.582Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:33.582Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 388)
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/jxcore-log( 2924): 2015-12-08T17:08:38.584Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:38.585Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
,I/jxcore-log( 2924): 2015-12-08T17:08:43.595Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:43.596Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:43.596Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:08:43.597Z SendDataConnector.js: do connect now
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): connect: Trying to connect to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): hasConnection: No connection with peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2924): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Trying to start connecting to null in address 7C:F9:0E:34:8A:A0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnecting: null 7C:F9:0E:34:8A:A0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): connect: Started connecting to null in address 7C:F9:0E:34:8A:A0
I/io.jxcore.node.ConnectionHelper( 2924): connect: Connection process successfully started (peer ID: 7C:F9:0E:34:8A:A0)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Trying to connect to peer with address 7C:F9:0E:34:8A:A0 (thread ID: 389)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 2924): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Connection timeout
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:147, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 147
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onConnectionFailed: Cancelled: Connection timeout
,W/BluetoothAdapter( 2924): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2982): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0 7C:F9:0E:34:8A:A0]
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/jxcore-log( 2924): 2015-12-08T17:09:14.569Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:09:14.570Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:34:8A:A0 failed
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:09:14.570Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 2924): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 2924): timeout now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): dun
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): weAreDoneNow , resultArray.length: 7
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): done, now sending data to server
I/jxcore-log( 2924): 
I/jxcore-log( 2924): DBG, CoordinatorConnector sendData called
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): -- RESULT DATA {"name:":"LGE-Nexus 5_PT5860","time":1000064,"result":"TIMEOUT","sendList":[{"name":"B4:CE:F6:AB:A4:6A","time":7619,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":147827,"result":"OK","connections":5,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"00:F4:6F:30:E0:6C","time":43462,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":20058,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":16590,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:B1:66","time":11613,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:CF:C5:D9:E5:61","time":5632,"result":"OK","connections":1,"tryCount"
I/jxcore-log( 2924): sendList : 100% : 147827 ms, 99% : 147827 ms, 95 : 147827 ms, 90% : 43462 ms.
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Result count 7, range 5632 ms to  147827 ms.
I/jxcore-log( 2924): 
I/jxcore-log( 2924): sendList failed peers count : 5 [41.666666666666664 %]
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 7C:F9:0E:34:8A:A0, Tried : 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 34:FC:EF:9D:93:0B, Tried : 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 38:94:96:B5:06:DC, Tried : 1
I/jxcore-log( 2924): 
I/jxcore-log( 2924): sendList never tried peers count : 10 [45.45454545454545 %]
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 80:01:84:8A:B3:68
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 90:E7:C4:F6:69:77
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 2924): 
I/jxcore-log( 2924): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:09:16.362Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:09:16.362Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 2924): 
D/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:34:8A:A0
E/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:34:8A:A0
D/io.jxcore.node.ConnectionHelper( 2924): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 2924): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:34:8A:A0), either no such connection or failed to close the connection
I/jxcore-log( 2924): 2015-12-08T17:09:16.362Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 2924): 
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,W/bt-sdp  ( 2982): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 2982): DISCOVERY_COMP_EVT slot id:148, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 2982): invalid rfc slot id: 148
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 2924): Exiting thread (thread ID: 389)
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT2881, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6268 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT6268","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT6268, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:76:27 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7603"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT7603, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: , Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7603"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7603"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT2881 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2881","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT2881, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: Android_50a5, Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-smp  ( 2982): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2982): Plain text(LSB ~ MSB) = b4 eb 55 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2982): Encrypted text(LSB ~ MSB) = a8 12 0f bd 07 3a 06 7e 37 e6 e2 2f 3c 07 7b 7b 
,W/bt-btm  ( 2982): Stopping oneshot timer
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT685, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT7957, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/HeadsetStateMachine( 2982): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1753","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 4 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1753","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1753","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT1753, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Galaxy S5-2 3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT866 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT866, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 0 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2198","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT2198 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2198","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT2198","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT2198, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Galaxy S5-2 3a:94:96:b5:06:dd
,D/WifiP2pManager( 2924): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7957 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7957","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local.",
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers,
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT7957, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: , Wi-Fi Direct address: 0a:ec:a9:50:75:42,
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list,
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4679 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4679, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT742 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT742, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT5860","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): start: Starting peer discovery...
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: 7 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 5: Thali Test's G2 36:fc:ef:de:0a:e2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onP2pDeviceListChanged: Peer 7: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
D/WifiP2pManager( 2924): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: Got empty list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9688","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9688 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9688","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9688","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT9688","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT9688, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT866 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT866"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT866, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
,I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1753","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1753 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1753","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1753","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1753","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT1753, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT685 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT685"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT685, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9318"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9318 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9318"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9318"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9318"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9318, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT9671 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT9671","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT9671, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT3802 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT3802","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT3802, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: , Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7603"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7603 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7603"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7603"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7603"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT7603, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:9D:93:0B already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT742 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 9 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT742","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT742, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
,I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
,W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 9 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT4679 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): onServiceListChanged: 10 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT4679","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 2924): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT4679, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 2924): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 2924): onPeerListChanged: Got a list containing 10 peer(s), but doing nothing with that list
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 2924): DBG, CoordinatorConnector command called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): stop tests now !
I/jxcore-log( 2924): 
I/jxcore-log( 2924): stop current!
I/jxcore-log( 2924): 
I/jxcore-log( 2924): testSendData stopped
I/jxcore-log( 2924): 
I/io.jxcore.node.ConnectionHelper( 2924): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 2924): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 2924): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 2924): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): stopServiceDiscovery
I/wpa_supplicant( 2988): P2P-FIND-STOPPED 
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): setState: NOT_INITIALIZED
I/jxcore-log( 2924): StopBroadcasting went ok
I/jxcore-log( 2924): 
I/jxcore-log( 2924): 2015-12-08T17:13:36.283Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 2924): 
I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 2924): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 2924): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 2924): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 2924): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 2924): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 2924): DBG, CoordinatorConnector command called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":5632,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":7619,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"34:FC:EF:11:B1:66\",\"time\":11613,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"08:EC:A9:50:75:41\",\"time\":16590,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":20058,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\":43462,\"result\":\"OK\",\"connections\":2,\"tryCount\":1,\"doneRounds\":1,\"da
I/jxcore-log( 2924): ****TEST TOOK:  ms ****
I/jxcore-log( 2924): 
I/jxcore-log( 2924): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2924): 
I/jxcore-log( 2924): stop tests now !
I/jxcore-log( 2924): 
I/jxcore-log( 2924): end, event received
I/jxcore-log( 2924): 
I/jxcore-log( 2924): CoordinatorConnector close called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 2924): 
I/jxcore-log( 2924): The Coordinator has disconnected!
I/jxcore-log( 2924): 
I/jxcore-log( 2924): The Coordinator has closed!
I/jxcore-log( 2924): 
I/jxcore-log( 2924): stop tests now !
I/jxcore-log( 2924): 
,I/jxcore-log( 2924): turning Radios off
I/jxcore-log( 2924): 
I/jxcore-log( 2924): Toggling radios to false
I/jxcore-log( 2924): 
D/BluetoothManagerService(  754): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  754): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@343f3f6c mBinding = false
,D/BluetoothManagerService(  754): Message: 2
,D/BluetoothManagerService(  754): Sending off request.
,D/BluetoothAdapterState( 2982): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2982): Setting state to 13
I/BluetoothAdapterState( 2982): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2982): onBluetoothDisable()
I/BluetoothAdapterState( 2982): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2982): Scan Mode:20
,D/BluetoothAdapterState( 2982): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2982): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2982): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2982): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2982): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2982): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2982): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2982): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2982): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2982): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2982): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2982): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 2982): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2982): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  754): Message: 60
,D/BluetoothManagerService(  754): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  754): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2982): onReceive
D/BluetoothMapService( 2982): STATE_TURNING_OFF
V/BluetoothMapService( 2982): Handler(): got msg=4
D/BluetoothMapService( 2982): MAP Service closeService in
D/BluetoothMapMasInstance( 2982): MAP Service shutdown
V/BluetoothMapService( 2982): MAP Service closeService out
,I/BtOppRfcommListener( 2982): stopping Accept Thread
,I/BtOppRfcommListener( 2982): BluetoothSocket listen thread finished
,I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 2988): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/WifiService(  754): setWifiEnabled: false pid=2924, uid=10270
E/WifiService(  754): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 2998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  754): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  754): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/native  (  754): do suspend true
,I/jxcore-log( 2924): Radios toggled
I/jxcore-log( 2924): 
I/chromium( 2924): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/DockEventReceiver( 2998): finishStartingService: stopping service
,D/BluetoothPbap( 2998): Proxy object disconnected
D/PbapServerProfile( 2998): Bluetooth service disconnected
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,E/WifiConfigStore(  754): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  754): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  754): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/bt_userial( 2982): RX termination
W/bt_userial( 2982): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2982): Leaving userial_read_thread()
W/bt-btif ( 2982): ag scb idx 1 not allocated
E/bt-btif ( 2982): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2982): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2982): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2982): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2982): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2982): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2982): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2982): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2982): hw_epilog_process
I/bt_userial_vendor( 2982): device fd = 53 close
,D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/GKI_LINUX( 2982): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2982): GKI_exit_task 0 done
I/GKI_LINUX( 2982): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2982): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,V/NativeCrypto( 1354): Read error: ssl=0xaffe7400: I/O error during system call, Connection timed out
,D/HeadsetService( 2982): Received stop request...Stopping profile...
V/NativeCrypto( 1354): SSL shutdown failed: ssl=0xaffe7400: I/O error during system call, Broken pipe
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
D/HeadsetStateMachine( 2982): Exit Disconnected: -1
,D/BluetoothHeadset(  754): Proxy object disconnected
D/BluetoothHeadset( 1204): Proxy object disconnected
,D/A2dpService( 2982): Received stop request...Stopping profile...
,D/A2dpStateMachine( 2982): Exit Disconnected: -1
,D/ConnectivityService(  754): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/BluetoothHeadset( 1232): Proxy object disconnected
,D/BluetoothHeadset( 2998): Proxy object disconnected
D/HeadsetProfile( 2998): Bluetooth service disconnected
,D/BluetoothHeadset( 1204): Proxy object disconnected
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
,D/BluetoothA2dp(  754): Proxy object disconnected
,D/BluetoothA2dp( 2998): Proxy object disconnected
,D/A2dpProfile( 2998): Bluetooth service disconnected
,D/HidService( 2982): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
,D/HeadsetStateMachine( 2982): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2982): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2982): Cleaning up Bluetooth Handsfree callback object
,D/HealthService( 2982): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
,D/PanService( 2982): Received stop request...Stopping profile...
D/BluetoothAdapterState( 2982): Stopping profile services that were post enabled
,E/WifiStateMachine(  754): scanCount==0 - aborting
,D/BluetoothInputDevice( 2998): Proxy object disconnected
D/HidProfile( 2998): Bluetooth service disconnected
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
,D/WifiNetworkAgent(  754): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService(  754): SCAN_AVAILABLE : 1
D/RttService(  754): SCAN_AVAILABLE : 1
,D/RttService(  754): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  754): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  754): DefaultState
,E/native  (  754): do suspend true
,D/BluetoothPan( 2998): BluetoothPAN Proxy object disconnected
D/PanProfile( 2998): Bluetooth service disconnected
,I/GKI_LINUX( 2982): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2982): GKI_exit_task 2 done
I/GKI_LINUX( 2982): GKI_shutdown(): task [A2DP-MEDIA] terminated
D/BtGatt.DebugUtils( 2982): handleDebugAction() action=null
,D/BtGatt.GattService( 2982): Received stop request...Stopping profile...
D/BtGatt.GattService( 2982): stop()
D/BtGatt.AdvertiseManager( 2982): advertise clients cleared
,D/ConnectivityService(  754): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
D/Nat464Xlat(  754): requiresClat: netType=1, connected=false, hasIPv4Address=true
W/BluetoothHidServiceJni( 2982): Cleaning up Bluetooth HID Interface...
D/CSLegacyTypeTracker(  754): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
W/bt-btif ( 2982): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2982): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 2982): Cleaning up Bluetooth Health Interface...
D/ConnectivityService(  754): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/BluetoothHealthServiceJni( 2982): Cleaning up Bluetooth Health object
D/ConnectivityManager.CallbackHandler(  895): CM callback handler got msg 524292
D/ConnectivityService(  754): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  754): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1232): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1560): CM callback handler got msg 524292
D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): EvaluatingState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): DefaultState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  754): Disconnected - quitting
D/BluetoothMapService( 2982): Received stop request...Stopping profile...
D/BluetoothMapService( 2982): stop()
,D/BluetoothMapEmailAppObserver( 2982): deinitObservers()
D/BluetoothMapEmailAppObserver( 2982): removeReceiver()
,D/BluetoothAdapterService( 2982): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@251b53af
,W/BluetoothPanServiceJni( 2982): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2982): Cleaning up Bluetooth PAN callback object
,D/AndroidRuntime( 3910): 
D/AndroidRuntime( 3910): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/BluetoothMapService( 2982): Handler(): got msg=4
D/BluetoothMapService( 2982): MAP Service closeService in
V/BluetoothMapService( 2982): MAP Service closeService out
,D/BluetoothAdapterState( 2982): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 2982): cleanup()
D/BluetoothAdapterProperties( 2982): Setting state to 10
D/BluetoothMapService( 2982): MAP Service closeService in
V/BluetoothMapService( 2982): MAP Service closeService out
I/BluetoothAdapterState( 2982): Bluetooth adapter state changed: 13-> 10
D/AndroidRuntime( 3910): CheckJNI is OFF
D/BluetoothManagerService(  754): Message: 60
D/BluetoothManagerService(  754): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  754): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothA2dp(  754): onBluetoothStateChange: up=false
D/BluetoothPbap( 2998): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1204): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 2982): Entering OffState
D/BluetoothMap( 2998): onBluetoothStateChange: up=false
,D/BluetoothMap( 2998): Proxy object disconnected
D/MapProfile( 2998): Bluetooth service disconnected
,D/BluetoothHeadset( 2998): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 2998): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1204): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  754): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1232): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2998): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  754): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  754): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/BluetoothManagerService(  754): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@343f3f6c mBinding = false
,D/BluetoothManagerService(  754): Sending unbind request.
,D/BluetoothManagerService(  754): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  895): 682745952: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  895): 682745952: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  895): 682745952: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2982): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2982): GKI_exit_task 1 done
I/GKI_LINUX( 2982): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2982): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1337): 250906642: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1337): 250906642: getState() :  mService = null. Returning STATE_OFF
I/art     ( 2982): System.exit called, status: 0
,I/AndroidRuntime( 2982): VM exiting with result code 0, cleanup skipped.
,W/ContextImpl( 2998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 2998): finishStartingService: stopping service
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 2988): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/AndroidRuntime( 3910): Calling main entry com.android.commands.pm.Pm
,I/wpa_supplicant( 2988): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2988): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  754): Process com.android.bluetooth (pid 2982) has died
,I/ActivityManager(  754): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  754): Killing 2924:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  754): Skipping PackageSetting{10f8dbb6 com.example.hello/10277} due to missing metadata
,I/WindowState(  754): WIN DEATH: Window{5887853 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  754): Client connection lost with reason: 4
,D/Tethering(  754): InitialState.processMessage what=4
,I/wpa_supplicant( 2988): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  754):   Force finishing activity ActivityRecord{12c7be5c u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  754): Spurious death for ProcessRecord{ad5a417 2924:com.test.thalitest/u0a270}, curProc for 2924: null
,I/ActivityManager(  754): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
I/ActivityManager(  754):   Force finishing activity ActivityRecord{12c7be5c u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  754): Duplicate finish request for ActivityRecord{12c7be5c u0 com.test.thalitest/.MainActivity t214 f}
,D/Tethering(  754): sendTetherStateChangedBroadcast 0, 0, 0
,I/Keyboard.Facilitator( 1094): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1337): Ignoring removeGeofence because network location is disabled.
I/InputReader(  754): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1297): Explicit concurrent mark sweep GC freed 3950(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.813ms total 39.382ms
,D/BluetoothAdapter( 2998): 562581390: getState() :  mService = null. Returning STATE_OFF
,W/Settings( 1789): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1419): Explicit concurrent mark sweep GC freed 83760(3MB) AllocSpace objects, 17(295KB) LOS objects, 25% free, 19MB/25MB, paused 312us total 65.272ms
W/Settings( 1337): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator.DecoderInitializer( 1094): run()
,I/Decoder ( 1094): createOrResetDecoder
,I/Adreno-EGL(  940): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  940): Initialized EGL, version 1.4
,I/art     (  754): Explicit concurrent mark sweep GC freed 69463(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 1.375ms total 88.392ms
D/OpenGLRenderer(  940): Enabling debug mode 0
I/art     (  754): WaitForGcToComplete blocked for 68.027ms for cause Explicit
,I/ActivityManager(  754): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3963 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/ConfigService( 1354): onCreate
,W/ResourcesManager( 3963): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/BackupManagerService(  754): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  754): Receieved: android.intent.action.PACKAGE_REMOVED
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
W/InputMethodManagerService(  754): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@254233df (uid=10034 pid=940)
,D/TaskPersister(  754): removeObsoleteFile: deleting file=214_task.xml
,D/AdapterServiceConfig( 3963): Adding HeadsetService
D/AdapterServiceConfig( 3963): Adding A2dpService
D/AdapterServiceConfig( 3963): Adding HidService
D/AdapterServiceConfig( 3963): Adding HealthService
D/AdapterServiceConfig( 3963): Adding PanService
D/AdapterServiceConfig( 3963): Adding GattService
D/AdapterServiceConfig( 3963): Adding BluetoothMapService
I/ActivityManager(  754): Killing 2817:com.android.musicfx/u0a15 (adj 15): empty #17
,I/art     (  754): Explicit concurrent mark sweep GC freed 9705(508KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 1.428ms total 142.899ms
,D/AuthorizationBluetoothService( 1354): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  754): failed to open /acct/uid_10015/pid_2817/cgroup.procs: No such file or directory
,W/FetchTask( 1354): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,I/ActivityManager(  754): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=3988 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/Launcher( 1297): Deferring update until onResume
,W/FetchTask( 1354): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 1297): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3910): Shutting down VM
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,W/FetchTask( 1354): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,W/ResourcesManager( 1297): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1297): Deferring update until onResume
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,W/FetchTask( 1354): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1354): Classify the device as Phone.
,W/FetchTask( 1354): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1094): run()
,D/VoicemailCleanupService( 3988): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1094): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1094): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1094): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1094): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1094): run()
I/StatsUtilsManager( 1094): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1094): shouldRecordStats() = Too Soon
,I/ActivityManager(  754): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4013 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1419): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1297): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@251b53af new=com.google.android.velvet.VelvetApplication@251b53af
,I/ActivityManager(  754): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4033 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ContactLocale( 3988): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  754): Killing 2846:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,I/art     ( 1560): Explicit concurrent mark sweep GC freed 26188(1723KB) AllocSpace objects, 19(304KB) LOS objects, 24% free, 22MB/29MB, paused 818us total 52.884ms
,W/libprocessgroup(  754): failed to open /acct/uid_10040/pid_2846/cgroup.procs: No such file or directory
,W/ContextImpl( 4033): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1560): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1560): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
,E/SQLiteDatabase( 4033): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 4033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4033): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 4033): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 4033): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4033): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4033): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 4033): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4033): Process: com.android.keychain, PID: 4033
E/AndroidRuntime( 4033): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4033): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 4033): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4033): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4033): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 4033): 	at com.android.keychain.KeyChainService.onHandleI,ntent(KeyChainService.java:396)
E/AndroidRuntime( 4033): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4033): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4033): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4033): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 1560): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1560): Module APK com.google.android.play.games already loaded
I/Process ( 4033): Sending signal. PID: 4033 SIG: 9
E/Icing   ( 1560): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1560): Writing status failed
E/DropBoxManagerService(  754): Can't write: system_app_crash
E/DropBoxManagerService(  754): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  754): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  754): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  754): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  754): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  754): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  754): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  754): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  754): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  754): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  754): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  754): 	... 5 more
E/SQLiteLog( 3988): (3850) statement aborts at 22: [DELETE FROM deleted_contacts WHERE contact_deleted_timestamp < ?] disk I/O error
E/AndroidRuntime( 3988): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 3988): Process: android.process.acore, PID: 3988
E/AndroidRuntime( 3988): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3988): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3988): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 3988): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3988): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3988): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 3988): 	at com.android.providers.contacts.database.DeletedContactsTableUtil.deleteOldLogs(DeletedContactsTableUtil.java:78)
E/AndroidRuntime( 3988): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1730)
E/AndroidRuntime( 3988): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1492)
E/AndroidRuntime( 3988): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3988): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3988): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing   ( 1560): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
I/ActivityManager(  754): Process com.android.keychain (pid 4033) has died
I/Process ( 3988): Sending signal. PID: 3988 SIG: 9
W/ActivityManager(  754): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
E/SQLiteLog( 1354): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteLog( 1560): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/AndroidRuntime( 1354): Shutting down VM
E/DropBoxManagerService(  754): Can't write: system_app_crash
E/DropBoxManagerService(  754): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  754): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  754): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  754): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  754): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  754): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  754): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  754): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  754): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  754): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  754): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  754): 	... 5 more
E/AndroidRuntime( 1354): FATAL EXCEPTION: main
E/AndroidRuntime( 1354): Process: com.google.process.gapps, PID: 1354
E/AndroidRuntime( 1354): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/AndroidRuntime( 1354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1354): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/AndroidRuntime( 1354): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1354): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1354): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/AndroidRuntime( 1354): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/AndroidRuntime( 1354): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1354): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1354): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1354): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/AndroidRuntime( 1354): 	... 9 more
I/Process ( 1354): Sending signal. PID: 1354 SIG: 9
E/DropBoxManagerService(  754): Can't write: system_app_crash
E/DropBoxManagerService(  754): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  754): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  754): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  754): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  754): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  754): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  754): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  754): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  754): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  754): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  754): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  754): 	... 5 more
I/LocationSettingsChecker( 1560): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 1560): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1560): disk I/O error (code 3850)
E/DriveAsyncService( 1560): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1560): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1560): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1560): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1560): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1560): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1560): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1560): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1560): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 1560): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1560): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1560): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1560): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1560): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1560): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1560): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1560): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1560): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1560): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/GAv4-SVC( 1560): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteOpenHelper( 1560): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1560): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1560): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1560): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1560): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1560): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1560): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1560): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1560): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1560): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SharedPreferencesImpl( 1560): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/SQLiteOpenHelper( 1560): Opened phenotype.db in read-only mode
E/SharedPreferencesImpl( 1560): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 1560): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1560): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/WifiService(  754): Client connection lost with reason: 4
E/SQLiteDatabase( 1560): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1560): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1560): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1560): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1560): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1560): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1560): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1560): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1560): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1560): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1560): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1560): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1560): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1560): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1560): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1560): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1560): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1560): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1560): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1560): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1560): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1560): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1560): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1560): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1560): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1560): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1560): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1560): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1560): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1560): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  754): Process android.process.acore (pid 3988) has died
I/ActivityManager(  754): Process com.google.process.gapps (pid 1354) has died
W/ActivityManager(  754): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 1000ms
W/ActivityManager(  754): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
W/ActivityManager(  754): Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 21000ms
W/ActivityManager(  754): Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
W/ActivityManager(  754): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 41000ms
W/ActivityManager(  754): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService in 51000ms

```
