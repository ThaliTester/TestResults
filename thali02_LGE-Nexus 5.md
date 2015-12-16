#### Test 50650278dbf8a2a_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1558): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1558): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2945): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2945):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2945):   adb logcat -s GAv4
W/GAv4    ( 2945): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2945): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2945): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2945): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2380): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2945): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2945): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 2989): 
D/AndroidRuntime( 2989): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2989): CheckJNI is OFF
V/JNIHelp ( 2945): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  761): Killing 2161:com.google.android.youtube/u0a80 (adj 15): empty #17
W/System  ( 2945): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2945): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2989): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  761): failed to open /acct/uid_10080/pid_2161/cgroup.procs: No such file or directory
I/ActivityManager(  761): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  761): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3023 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2989): Shutting down VM
V/ActivityManager(  761): Display changed displayId=0
I/WebViewFactory( 3023): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3023): Time to load native libraries: 2 ms (timestamps 6906-6908)
I/LibraryLoader( 3023): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3023): Binding Chromium to main looper Looper (main, tid 1) {3b76bcf1}
I/LibraryLoader( 3023): Expected native library version number "",actual native library version number ""
I/chromium( 3023): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3023): Initializing chromium process, singleProcess=true
W/art     ( 3023): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3023): ApplicationContext is null in ApplicationStatus
W/chromium( 3023): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3023): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Icing   ( 1558): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Adreno-EGL( 3023): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae799b2:true
D/BluetoothAdapter( 3023): 888064499: getState() :  mService = null. Returning STATE_OFF
I/Icing   ( 1558): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
W/art     ( 3023): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3023): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3023): CordovaWebView is running on device made by: LGE
W/art     ( 3023): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3023): Attempt to remove local handle scope entry from IRT, ignoring
I/Icing   ( 1558): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1558): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
D/OpenGLRenderer( 3023): Render dirty regions requested: true
D/Atlas   ( 3023): Validating map...
W/chromium( 3023): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3023): Initialized EGL, version 1.4
D/OpenGLRenderer( 3023): Enabling debug mode 0
I/Keyboard.Facilitator( 1072): onFinishInput()
W/BindingManager( 3023): Cannot call determinedVisibility() - never saw a connection for the pid: 3023
W/IInputConnectionWrapper( 3023): showStatusIcon on inactive InputConnection
I/ActivityManager(  761): Displayed com.test.thalitest/.MainActivity: +425ms (total +54s207ms)
D/JsMessageQueue( 3023): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3023): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3023): jxcore cordova android initializing
I/ActivityManager(  761): Killing 2288:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  761): failed to open /acct/uid_10038/pid_2288/cgroup.procs: No such file or directory
,W/jxcore-log( 3023): Initializing JXcore engine
W/jxcore-log( 3023): JXcore engine is ready
,W/jxcore-log( 3023): Starting JXcore engine
,W/.test.thalitest( 3023): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6479]" dev="sockfs" ino=6479 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3023): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3023): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6568]" dev="sockfs" ino=6568 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3023): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18751]" dev="sockfs" ino=18751 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3023): Platform android
W/jxcore-log( 3023): 
W/jxcore-log( 3023): Process ARCH arm
W/jxcore-log( 3023): 
,I/jxcore-log( 3023): JXcore Cordova bridge is ready!
I/jxcore-log( 3023): 
,W/jxcore-log( 3023): JXcore engine is started
I/Choreographer( 3023): Skipped 110 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3023): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3023): Toggling radios to true
I/jxcore-log( 3023): 
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  761): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  761): Message: 1
D/BluetoothManagerService(  761): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  761): New client listening to asynchronous messages
,D/WifiService(  761): setWifiEnabled: true pid=3023, uid=10270
E/WifiService(  761): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
I/jxcore-log( 3023): Radios toggled
I/jxcore-log( 3023): 
D/CommandListener(  179): Clearing all IP addresses on wlan0
I/ActivityManager(  761): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3089 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3023): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3023): 
,I/jxcore-log( 3023): Perf Test app loaded loaded
I/jxcore-log( 3023): 
,I/jxcore-log( 3023): check test folder
I/jxcore-log( 3023): 
I/jxcore-log( 3023): found test : ./testFindPeers.js
I/jxcore-log( 3023): 
,I/jxcore-log( 3023): found test : ./testSendData.js
I/jxcore-log( 3023): 
,W/ResourcesManager( 3089): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Choreographer( 3023): Skipped 70 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3023): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/AdapterServiceConfig( 3089): Adding HeadsetService
D/AdapterServiceConfig( 3089): Adding A2dpService
D/AdapterServiceConfig( 3089): Adding HidService
D/AdapterServiceConfig( 3089): Adding HealthService
D/AdapterServiceConfig( 3089): Adding PanService
D/AdapterServiceConfig( 3089): Adding GattService
D/AdapterServiceConfig( 3089): Adding BluetoothMapService
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cad9f61:true
,D/BluetoothAdapterState( 3089): make
,I/bluedroid( 3089): init
,I/BluetoothAdapterState( 3089): Entering OffState
,I/wpa_supplicant( 3118): Successfully initialized wpa_supplicant
,I/bte_conf( 3089): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3089): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3089): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3089): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 3089): get_profile_interface socket
I/bluedroid( 3089): get_profile_interface map_client
,D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/GKI_LINUX( 3089): gki_task_entry task_id=1 [BTIF] starting
,I/bluedroid( 3089): config_hci_snoop_log
D/BluetoothAdapterProperties( 3089): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3089): Name is: Nexus 5
D/BluetoothManagerService(  761): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  761): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterState( 3089): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3089): Setting state to 11
I/BluetoothAdapterState( 3089): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  761): Message: 60
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3089): make
,I/BluetoothBondStateMachine( 3089): StableState(): Entering Off State
,I/ActivityManager(  761): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3126 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/WifiMonitor(  761): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3118): rfkill: Cannot open RFKILL control device
,D/BluetoothHeadset(  761): Proxy object connected
,D/HeadsetService( 3089): Received start request. Starting profile...
,D/BluetoothHeadset( 1157): Proxy object connected
,D/BluetoothHeadset( 1157): Proxy object connected
,D/BluetoothHeadset( 1196): Proxy object connected
,I/BluetoothHeadsetServiceJni( 3089): classInitNative: succeeds
,I/BluetoothAdapterState( 3089): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3089): make
,D/HeadsetStateMachine( 3089): max_hf_connections = 1
I/bluedroid( 3089): get_profile_interface handsfree
,D/HeadsetStateMachine( 3089): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128610d6
,D/BluetoothA2dp(  761): Proxy object connected
,D/A2dpService( 3089): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3089): classInitNative: succeeds
I/bluedroid( 3089): get_profile_interface avrcp
,E/RemoteController( 3089): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3089): classInitNative: succeeds
D/A2dpStateMachine( 3089): make
,I/bluedroid( 3089): get_profile_interface a2dp
I/GKI_LINUX( 3089): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128610d6
,I/BluetoothHidServiceJni( 3089): classInitNative: succeeds
D/A2dpStateMachine( 3089): Enter Disconnected: -2
,D/HidService( 3089): Received start request. Starting profile...
I/bluedroid( 3089): get_profile_interface hidhost
D/BluetoothAdapterService( 3089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128610d6
I/BluetoothHealthServiceJni( 3089): classInitNative: succeeds
,D/HealthService( 3089): Received start request. Starting profile...
,I/bluedroid( 3089): get_profile_interface health
D/BluetoothAdapterService( 3089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128610d6
,I/BluetoothPanServiceJni( 3089): classInitNative(L105): succeeds
,D/PanService( 3089): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3089): initializeNative(L110): pan
I/bluedroid( 3089): get_profile_interface pan
,D/BluetoothAdapterService( 3089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128610d6
I/BtGatt.JNI( 3089): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3089): handleDebugAction() action=null
,D/BtGatt.GattService( 3089): Received start request. Starting profile...
D/BtGatt.GattService( 3089): start()
I/bluedroid( 3089): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3089): advertise manager created
,I/ActivityManager(  761): Killing 1759:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10045/pid_1759/cgroup.procs: No such file or directory
,D/BluetoothAdapterService( 3089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128610d6
,V/BluetoothMapService( 3089): BluetoothMapBinder()
,D/BluetoothMapService( 3089): Received start request. Starting profile...
D/BluetoothMapService( 3089): start()
,D/BluetoothMapEmailSettingsLoader( 3089): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3089): createReceiver()
,D/BluetoothMapEmailAppObserver( 3089): initObservers()
D/BluetoothMapEmailAppObserver( 3089): getEnabledAccountItems()
,D/BluetoothAdapterService( 3089): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@128610d6
,D/HeadsetStateMachine( 3089): Proxy object connected
,D/HeadsetStateMachine( 3089): Disconnected process message: 10, size: 0
,V/BluetoothMapService( 3089): Handler(): got msg=1
,D/BluetoothAdapterState( 3089): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3089): enable
,D/HeadsetPhoneState( 3089): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,I/GKI_LINUX( 3089): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3089): btu_task pending for preload complete event
I/bt_hci_bdroid( 3089): init
D/HeadsetStateMachine( 3089): Disconnected process message: 11, size: 0
I/bt_vendor( 3089): init
I/bt_vnd_conf( 3089): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3089): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3089): userial_init
D/WifiService(  761): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1280): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_userial_vendor( 3089): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3089): device fd = 53 open
D/bt_userial( 3089): Entering userial_read_thread()
,I/ActivityManager(  761): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3161 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/bt_hwcfg( 3089): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3089): Chipset BCM4335C0
D/bt_hwcfg( 3089): Target name = [BCM4335C0]
,I/bt_hwcfg( 3089): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 1381(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 219us total 9.960ms
,I/art     (  761): Explicit concurrent mark sweep GC freed 14614(732KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.063ms total 55.556ms
,I/ActivityManager(  761): Killing 2439:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10003/pid_2439/cgroup.procs: No such file or directory
,I/bt_hwcfg( 3089): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3089): Settlement delay -- 100 ms
I/bt_hwcfg( 3089): Setting fw settlement delay to 100 
,D/Tethering(  761): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3118): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  761): Loading config and enabling all networks 
,I/bt_hwcfg( 3089): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 3089): Setting local bd addr to 34:FC:EF:11:AE:67
,E/WifiConfigStore(  761): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2250): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  761): Setting external_sim to 1
,D/WifiStateMachine(  761): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  761): startHal
D/wifi    (  761): setting scan oui 0x929f8f28
,D/WifiHAL (  761): Sending mac address OUI
,E/WifiHAL (  761): failed to set scanning mac OUI; result = -95
,I/bt_hwcfg( 3089): vendor lib fwcfg completed
,I/bt-btu  ( 3089): btu_task received preload complete event
,I/wpa_supplicant( 3118): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  761): do suspend true
,I/        ( 3089): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3089): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3089): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3089): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3089): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3089): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3089): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3089): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3089): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3089): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3089): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3089): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3089): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3089): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3089): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiScanningService(  761): SCAN_AVAILABLE : 3
D/RttService(  761): SCAN_AVAILABLE : 3
,D/WifiScanningService(  761): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  179): Setting iface cfg
D/RttService(  761): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  761): startHal
,D/CommandListener(  179): Trying to bring up p2p0
,D/WifiMonitor(  761): startMonitoring(p2p0) with mConnected = true
,D/wifi    (  761): getting scan capabilities on interface[1] = 0x929f8f28
D/WifiHAL (  761): Creating message to get scan capablities; iface = 21
D/WifiHAL (  761): In GetCapabilities::handleResponse
D/WifiHAL (  761): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  761): StartedState
,I/wpa_supplicant( 3118): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  761): p2pGetDeviceAddress
,D/WifiNative-HAL(  761): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,E/bt-btm  ( 3089): BTM_SecRegister:p_cb_info->p_le_callback == 0xa40799d5 
E/bt-btm  ( 3089): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40799d5 
,E/bt-btif ( 3089): Calling BTA_HhEnable
E/bt-btif ( 3089): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3089): Address is:34:FC:EF:11:AE:67
,W/bt-smp  ( 3089): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3089): Plain text(LSB ~ MSB) = e8 70 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3089): Encrypted text(LSB ~ MSB) = fd 13 1e f3 4e e3 f1 14 c7 ea 25 f4 44 94 6d bf 
,W/bt-btm  ( 3089): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3089): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3089): Scan Mode:20
,D/BluetoothAdapterProperties( 3089): Discoverable Timeout:120
,D/BluetoothManagerService(  761): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  761): Stored Bluetooth name: Nexus 5
,D/bte_conf( 3089): Device ID record 1 : primary
D/bte_conf( 3089):   vendorId            = 000f
D/bte_conf( 3089):   vendorIdSource      = 0001
D/bte_conf( 3089):   product             = 1200
D/bte_conf( 3089):   version             = 1436
D/bte_conf( 3089):   clientExecutableURL = 
D/bte_conf( 3089):   serviceDescription  = 
D/bte_conf( 3089):   documentationURL    = 
D/bte_conf( 3089): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3089): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterState( 3089): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3089): ScanMode =  20
D/BluetoothAdapterProperties( 3089): State =  11
D/BluetoothAdapterProperties( 3089): Setting state to 12
I/BluetoothAdapterState( 3089): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  761): Message: 60
,I/BluetoothAdapterState( 3089): Entering On State
,D/BluetoothAdapterProperties( 3089): Scan Mode:21
D/BluetoothAdapterProperties( 3089): Discoverable Timeout:120
,D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  761): Broadcasting onBluetoothStateChange(true) to 5 receivers.
D/BluetoothHeadset(  761): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1157): onBluetoothStateChange: up=true
D/BluetoothA2dp(  761): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1196): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1157): onBluetoothStateChange: up=true
E/bt_h4   ( 3089): vendor lib postload completed
D/BluetoothManagerService(  761): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  761): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3089): onReceive
D/BluetoothMapService( 3089): STATE_ON
V/BluetoothMapService( 3089): Handler(): got msg=1
D/BluetoothMapMasInstance( 3089): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  761): Message: 40
D/BluetoothManagerService(  761): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/Telecom ( 1157): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 3089): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3089): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3089): mNumber:  mType: 128
D/HeadsetStateMachine( 3089): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3089): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/BluetoothMapMasInstance( 3089): MAS initSocket()
D/BluetoothMapMasInstance( 3089):   masId = 00
D/BluetoothMapMasInstance( 3089):   msgTypes = 0e
D/BluetoothMapMasInstance( 3089):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3089):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3089): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3089): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3089): Accepting socket connection...
,W/ContextImpl( 3126): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3089): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  761): Message: 20
D/BluetoothManagerService(  761): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@30b373ca:true
,D/LocalBluetoothProfileManager( 3126): Adding local A2DP profile
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3126): Adding local HEADSET profile
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3126): Adding local MAP profile
,D/BluetoothMap( 3126): Create BluetoothMap proxy object
,D/BluetoothManagerService(  761): Message: 30
,D/BluetoothManagerService(  761): Message: 30
,D/LocalBluetoothProfileManager( 3126): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3126): finishStartingService: stopping service
,D/BluetoothA2dp( 3126): Proxy object connected
,D/A2dpProfile( 3126): Bluetooth service connected
,D/BluetoothHeadset( 3126): Proxy object connected
,D/HeadsetProfile( 3126): Bluetooth service connected
,D/BluetoothInputDevice( 3126): Proxy object connected
D/HidProfile( 3126): Bluetooth service connected
,D/BluetoothPan( 3126): BluetoothPAN Proxy object connected
D/PanProfile( 3126): Bluetooth service connected
,D/AuthorizationBluetoothService( 1280): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothMap( 3126): Proxy object connected
,D/MapProfile( 3126): Bluetooth service connected
D/BluetoothMap( 3126): getConnectedDevices()
,V/BluetoothMapService( 3089): getConnectedDevices()
,D/BluetoothPbap( 3126): Proxy object connected
,D/PbapServerProfile( 3126): Bluetooth service connected
,D/BluetoothManagerService(  761): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3089): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3089): Accept thread started.
,I/wpa_supplicant( 3118): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  761): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  761): will read network variables netId=1
,E/WifiStateMachine(  761): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  761): will read network variables netId=1
,I/wpa_supplicant( 3118): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  761): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3118): PNO: In assoc process
,I/wpa_supplicant( 3118): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3118): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3118): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  761): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  761): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  761): Start Dhcp Watchdog 1
,E/native  (  761): do suspend false
,E/WifiStateMachine(  761): scanCount==0 - aborting
,I/dhcpcd  ( 3243): version 5.5.6 starting
,E/dhcpcd  ( 3243): get_duid: Read-only file system
,I/dhcpcd  ( 3243): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3243): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3243): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  761): do suspend true
,E/WifiStateMachine(  761): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService(  761): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  761): Adding iface wlan0 to network 100
,E/ConnectivityService(  761): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  761): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  761): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  761): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  761): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Connected
D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  761): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  761): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  761): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 00:39:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450226352865], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450226352853]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  761): Validated
D/ConnectivityService(  761): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  761): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1196): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Nat464Xlat(  761): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  761): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  901): CM callback handler got msg 524295
,I/jxcore-log( 3023): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 3023): 
,D/ConnectivityService(  761): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  761): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  761): Setting time of day to sec=1450226356
,W/AlarmManagerService(  761): Unable to set rtc to 1450226356: Invalid argument
,I/GoogleURLConnFactory( 1280): Using platform SSLCertificateSocketFactory
,I/NetworkMonitor( 2460): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2460): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1558): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1558): onCreate
,D/SystemUpdateService( 1558): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1558): active receiver: enabled
,I/SystemUpdateService( 1558): showing system update notification
,I/ValidateNoPeople(  761): skipping global notification
,V/SystemUpdateService( 1558): retry (wakeup: false) in 3599984 ms
,I/iu.SyncManager( 1558): SYNC; picasa accounts
,E/GpsLocationProvider(  761): No APN found to select.
,D/NetworkLogImpl( 1558): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1558): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/GpsLocationProvider(  761): NTP server returned: 1450226353029 (Wed Dec 16 01:39:13 GMT+01:00 2015) reference: 84002 certainty: 10 system time offset: -3207
,E/LocSvc_eng(  761): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,E/ActivityThread( 1558): Failed to find provider info for com.android.contacts.metadata
,I/iu.UploadsManager( 1558): num queued entries: 0
I/iu.UploadsManager( 1558): num updated entries: 0
,I/iu.SyncManager( 1558): NEXT; no task
,D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 26546, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 118686, reason: UserStart
,D/SystemUpdateService( 1558): onDestroy
,I/ActivityManager(  761): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3350 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 182us total 8.142ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 9.162ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 240us total 8.406ms
,E/Auth.Api.Credentials( 1558): [CredentialSyncAdapter] Unknown sync event.
,I/Babel   ( 2250): connection state changed from UNKNOWN to CONNECTED
,D/ConnectivityService(  761): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  761): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  761): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1558): CM callback handler got msg 524290
,I/GAv4    ( 3350): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3350):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3350):   adb logcat -s GAv4
,W/GAv4    ( 3350): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1280): GCM config loaded
,W/GAv4    ( 3350): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3350): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1558): Awaiting to be initialized
,W/DriveInitializer( 1558): Background init thread started
,I/art     (  761): Explicit concurrent mark sweep GC freed 52209(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.279ms total 60.768ms
,I/WebViewFactory( 3350): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3350): Time to load native libraries: 1 ms (timestamps 7701-7702)
,I/LibraryLoader( 3350): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3350): Binding Chromium to main looper Looper (main, tid 1) {b5a263b}
I/LibraryLoader( 3350): Expected native library version number "",actual native library version number ""
I/chromium( 3350): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/DriveInitializer( 1558): Background init thread ended
,I/BrowserStartupController( 3350): Initializing chromium process, singleProcess=true
,W/art     ( 3350): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3350): ApplicationContext is null in ApplicationStatus
,W/chromium( 3350): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3350): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3350): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3350): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3350): Requires BLUETOOTH permission
,I/NSApplication( 3350): Starting up...
,I/ActivityManager(  761): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3445 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimeService( 3445): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450226356933
D/        ( 3445): TimeServiceNative: User Time to be set is 1450226356933
D/QC-time-services( 3445): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3445): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3445): Lib:time_genoff_operation: pargs->ts_val = 1450226356933
D/QC-time-services( 3445): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1450226356933
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1450226356933, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/19/70 6:29:58
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 9354598000
D/QC-time-services(  197): Daemon:new time 1450226356933 
D/QC-time-services(  197): Daemon: delta 1440871758933 genoff 1440871758933 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871758933 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/PhenotypeConfigurator( 1280): Server returned 404
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871758933 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1134261556933
,E/QC-time-services( 3445): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  761): Killing 2318:com.google.android.gm/u0a70 (adj 15): empty #17
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  761): failed to open /acct/uid_10070/pid_2318/cgroup.procs: No such file or directory
,I/CheckinService( 1558): Checkin interval check for package: unspecified last checkin: 1450187023808 min interval config: 0 actual interval: 39333206
,W/art     ( 2636): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  761): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3475 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3475): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3475):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3475):   adb logcat -s GAv4
,W/GAv4    ( 3475): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3475): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3475): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  761): Killing 1886:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10002/pid_1886/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3500 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  761): Killing 2823:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10008/pid_2823/cgroup.procs: No such file or directory
,W/ResourcesManager( 3500): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3500): Created com.android.providers.calendar.CalendarAlarmManager@9ea6c98(com.android.providers.calendar.CalendarProvider2@3b76bcf1)
,I/CalendarProvider2( 3500): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3500): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 1633(61KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 227us total 33.657ms
,D/Finsky  ( 2380): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2380): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/VacuumService( 1280): Vacuum at: now=1450226360691 tag=VacuumService
,E/SQLiteLog( 3500): (284) automatic index on view_events(_id)
,I/ActivityManager(  761): Killing 2600:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10004/pid_2600/cgroup.procs: No such file or directory
,I/Keyboard.Facilitator.LanguageModelFlusher( 1072): run()
I/Keyboard.Facilitator( 1072): flushDynamicLanguageModels()
,I/ConfigService( 1280): onCreate
,I/ConfigService( 1280): onDestroy
,E/ActivityThread( 1558): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  761): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 118686, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  761): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 210283, reason: UserStart
,I/ClearcutLoggerApiImpl( 1280): disconnect managed GoogleApiClient
,E/DataBuffer( 1280): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19b8d224)
,E/DataBuffer( 1280): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f90a18d)
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 61899(3MB) AllocSpace objects, 28(471KB) LOS objects, 39% free, 21MB/36MB, paused 735us total 35.816ms
,E/DataBuffer( 1280): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11dbef42)
E/DataBuffer( 1280): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c972b53)
,E/DataBuffer( 1280): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20c2ec90)
,I/PhenotypeConfigurator( 1280): Scheduling Phenotype for one-off execution 9110 seconds from now (1450226467319)
,D/GetConfigurationSnapshotOperation( 1280): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1280): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1280): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ClearcutLoggerApiImpl( 1280): disconnect managed GoogleApiClient
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  761): Explicit concurrent mark sweep GC freed 33259(1401KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 908us total 89.128ms
,I/ActivityManager(  761): Killing 1445:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  761): failed to open /acct/uid_10013/pid_1445/cgroup.procs: No such file or directory
,I/jxcore-log( 3023): Connected to the server!
I/jxcore-log( 3023): 
,I/chromium( 3023): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/Finsky  ( 2380): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/bt-smp  ( 3089): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3089): Plain text(LSB ~ MSB) = d5 fa 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3089): Encrypted text(LSB ~ MSB) = bf 3f ee 9a ac 08 b2 6a 6d 94 fc 7b 88 fa 31 19 
W/bt-btm  ( 3089): Stopping oneshot timer
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2380): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2380): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2380): untagSocket(39) failed with errno -22
,D/Finsky  ( 2380): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2380): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2380): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2380): untagSocket(39) failed with errno -22
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 2380): Failed write_ctrl(u 39) res=-1 errno=22
I/qtaguid ( 2380): Untagging socket 39 failed errno=-22
W/NetworkManagementSocketTagger( 2380): untagSocket(39) failed with errno -22
,D/Finsky  ( 2380): [1] MultiWayUpdateController.collateResponses: Change varies-by-account for com.google.android.apps.magazines to true
D/Finsky  ( 2380): [1] MultiWayUpdateController.collateResponses: Change auto-acquire tags for com.google.android.apps.magazines from  to d_AAAAAAADF8w=
,W/ResourcesManager( 2380): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2380): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2380): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 2380): [1] WearSupportService.startHygiene: disabled
D/Finsky  ( 2380): [1] DailyHygiene.access$600: Logging device features
,D/DeviceConnectionService( 1280): client connected with version: 8296000
,D/Finsky  ( 2380): [245] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 2380): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2380): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/UsageStatsService(  761): User[0] Flushing usage stats to disk
,I/ActivityManager(  761): Killing 2783:com.android.defcontainer/u0a5 (adj 13): empty for 1803s
,I/ActivityManager(  761): Killing 2945:com.google.android.apps.docs/u0a40 (adj 15): empty for 1805s
,I/ActivityManager(  761): Killing 2911:com.android.musicfx/u0a15 (adj 15): empty for 1806s
,W/libprocessgroup(  761): failed to open /acct/uid_10040/pid_2945/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10015/pid_2911/cgroup.procs: No such file or directory
,I/ProcessStatsService(  761): Prepared write state in 3ms
,W/libprocessgroup(  761): failed to open /acct/uid_10005/pid_2783/cgroup.procs: No such file or directory
,I/ProcessStatsService(  761): Prepared write state in 3ms
,I/ProcessStatsService(  761): Prepared write state in 3ms
,I/ProcessStatsService(  761): Prepared write state in 2ms
,W/bt-smp  ( 3089): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3089): Plain text(LSB ~ MSB) = 45 e7 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3089): Encrypted text(LSB ~ MSB) = 4a 85 b2 f9 64 f8 7f f9 bd 9b 47 8a 63 4f 9c 6f 
W/bt-btm  ( 3089): Stopping oneshot timer
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1558): Aggregate from 1450226233308 (log), 1450226233308 (data)
,I/ProcessStatsService(  761): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-13-39.bin
,I/ActivityManager(  761): Killing 3126:com.android.settings/1000 (adj 13): empty for 1800s
,D/WifiService(  761): Client connection lost with reason: 4
,W/libprocessgroup(  761): failed to open /acct/uid_1000/pid_3126/cgroup.procs: No such file or directory
,I/ActivityManager(  761): Killing 3350:com.google.android.apps.magazines/u0a61 (adj 13): empty for 1800s
,I/ActivityManager(  761): Killing 2460:com.google.android.music:main/u0a60 (adj 15): empty for 1800s
,W/libprocessgroup(  761): failed to open /acct/uid_10061/pid_3350/cgroup.procs: No such file or directory
,W/libprocessgroup(  761): failed to open /acct/uid_10060/pid_2460/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
