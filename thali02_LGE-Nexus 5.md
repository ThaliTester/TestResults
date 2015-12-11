#### Test 5065027857de7f1_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/Finsky  ( 2390): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,--------- beginning of system
W/ResourcesManager( 2909): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2909): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  757): Killing 2189:com.google.android.youtube/u0a80 (adj 15): empty #17
V/JNIHelp ( 2909): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2909): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2909): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2189/cgroup.procs: No such file or directory
V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 2957): 
D/AndroidRuntime( 2957): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2957): CheckJNI is OFF
D/AndroidRuntime( 2957): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2972 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2957): Shutting down VM
I/Icing   ( 1554): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/ActivityManager(  757): Display changed displayId=0
I/Icing   ( 1554): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1554): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/WebViewFactory( 2972): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2972): Time to load native libraries: 1 ms (timestamps 8734-8735)
I/LibraryLoader( 2972): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2972): Binding Chromium to main looper Looper (main, tid 1) {f435583}
I/LibraryLoader( 2972): Expected native library version number "",actual native library version number ""
I/chromium( 2972): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1554): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/BrowserStartupController( 2972): Initializing chromium process, singleProcess=true
W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2972): ApplicationContext is null in ApplicationStatus
,W/chromium( 2972): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2972): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2972): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2972): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2972): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@201c83d2:true
D/BluetoothAdapter( 2972): 618039178: getState() :  mService = null. Returning STATE_OFF
W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 2972): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 2972): CordovaWebView is running on device made by: LGE
W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2972): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 2972): Render dirty regions requested: true
D/Atlas   ( 2972): Validating map...
W/chromium( 2972): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 2972): Initialized EGL, version 1.4
D/OpenGLRenderer( 2972): Enabling debug mode 0
W/BindingManager( 2972): Cannot call determinedVisibility() - never saw a connection for the pid: 2972
W/IInputConnectionWrapper( 2972): showStatusIcon on inactive InputConnection
I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +436ms (total +56s54ms)
D/JsMessageQueue( 2972): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 2972): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2972): jxcore cordova android initializing
,I/ActivityManager(  757): Killing 2312:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10038/pid_2312/cgroup.procs: No such file or directory
,W/jxcore-log( 2972): Initializing JXcore engine
W/jxcore-log( 2972): JXcore engine is ready
,W/jxcore-log( 2972): Starting JXcore engine
,W/.test.thalitest( 2972): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8058]" dev="sockfs" ino=8058 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2972): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2972): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9438]" dev="sockfs" ino=9438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2972): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18688]" dev="sockfs" ino=18688 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2972): Platform android
W/jxcore-log( 2972): 
W/jxcore-log( 2972): Process ARCH arm
W/jxcore-log( 2972): 
,I/jxcore-log( 2972): JXcore Cordova bridge is ready!
I/jxcore-log( 2972): 
,W/jxcore-log( 2972): JXcore engine is started
I/Choreographer( 2972): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2972): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2972): Toggling radios to true
I/jxcore-log( 2972): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  757): Message: 1
D/BluetoothManagerService(  757): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  757): New client listening to asynchronous messages
,D/WifiService(  757): setWifiEnabled: true pid=2972, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  757): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3037 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  179): Softap fwReload - Ok
,I/jxcore-log( 2972): Radios toggled
I/jxcore-log( 2972): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2972): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2972): 
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
I/jxcore-log( 2972): Perf Test app loaded loaded
I/jxcore-log( 2972): 
I/Choreographer( 2972): Skipped 59 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 2972): check test folder
I/jxcore-log( 2972): 
I/jxcore-log( 2972): found test : ./testFindPeers.js
I/jxcore-log( 2972): 
,W/ResourcesManager( 3037): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/jxcore-log( 2972): found test : ./testSendData.js
I/jxcore-log( 2972): 
,I/wpa_supplicant( 3054): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3054): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  757): startMonitoring(wlan0) with mConnected = false
,D/AdapterServiceConfig( 3037): Adding HeadsetService
D/AdapterServiceConfig( 3037): Adding A2dpService
D/AdapterServiceConfig( 3037): Adding HidService
D/AdapterServiceConfig( 3037): Adding HealthService
D/AdapterServiceConfig( 3037): Adding PanService
D/AdapterServiceConfig( 3037): Adding GattService
,D/AdapterServiceConfig( 3037): Adding BluetoothMapService
,I/chromium( 2972): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  757): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3069 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9938401:true
,D/BluetoothAdapterState( 3037): make
,I/bluedroid( 3037): init
,I/BluetoothAdapterState( 3037): Entering OffState
,I/bte_conf( 3037): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3037): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3037): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3037): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3037): get_profile_interface socket
I/bluedroid( 3037): get_profile_interface map_client
,I/GKI_LINUX( 3037): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothAdapterProperties( 3037): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 3037): Name is: Nexus 5
,I/bluedroid( 3037): config_hci_snoop_log
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothManagerService(  757): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothAdapterState( 3037): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3037): Setting state to 11
I/BluetoothAdapterState( 3037): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3037): make
,I/BluetoothBondStateMachine( 3037): StableState(): Entering Off State
,D/BluetoothHeadset( 1161): Proxy object connected
D/HeadsetService( 3037): Received start request. Starting profile...
D/BluetoothHeadset( 1161): Proxy object connected
,D/BluetoothHeadset(  757): Proxy object connected
,D/BluetoothHeadset( 1205): Proxy object connected
I/BluetoothHeadsetServiceJni( 3037): classInitNative: succeeds
,I/BluetoothAdapterState( 3037): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 3037): make
,D/HeadsetStateMachine( 3037): max_hf_connections = 1
I/bluedroid( 3037): get_profile_interface handsfree
,D/HeadsetStateMachine( 3037): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3037): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0b8300
,D/BluetoothA2dp(  757): Proxy object connected
,D/A2dpService( 3037): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3037): classInitNative: succeeds
I/bluedroid( 3037): get_profile_interface avrcp
,E/RemoteController( 3037): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3037): classInitNative: succeeds
D/A2dpStateMachine( 3037): make
,I/bluedroid( 3037): get_profile_interface a2dp
,I/GKI_LINUX( 3037): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3037): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0b8300
D/A2dpStateMachine( 3037): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3037): classInitNative: succeeds
,D/HidService( 3037): Received start request. Starting profile...
I/bluedroid( 3037): get_profile_interface hidhost
D/BluetoothAdapterService( 3037): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0b8300
I/BluetoothHealthServiceJni( 3037): classInitNative: succeeds
,D/BluetoothManagerService(  757): Message: 20
D/HealthService( 3037): Received start request. Starting profile...
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3439c5d7:true
,I/bluedroid( 3037): get_profile_interface health
,D/BluetoothAdapterService( 3037): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0b8300
I/BluetoothPanServiceJni( 3037): classInitNative(L105): succeeds
,D/PanService( 3037): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3037): initializeNative(L110): pan
I/bluedroid( 3037): get_profile_interface pan
,D/BluetoothAdapterService( 3037): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0b8300
,I/BtGatt.JNI( 3037): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3037): handleDebugAction() action=null
,D/BtGatt.GattService( 3037): Received start request. Starting profile...
D/BtGatt.GattService( 3037): start()
I/bluedroid( 3037): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3037): advertise manager created
D/BluetoothManagerService(  757): Message: 30
,D/BluetoothManagerService(  757): Message: 30
D/BluetoothAdapterService( 3037): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0b8300
D/LocalBluetoothProfileManager( 3069): Adding local MAP profile
D/BluetoothMap( 3069): Create BluetoothMap proxy object
D/BluetoothManagerService(  757): Message: 30
V/BluetoothMapService( 3037): BluetoothMapBinder()
D/BluetoothMapService( 3037): Received start request. Starting profile...
D/BluetoothMapService( 3037): start()
D/BluetoothMapEmailSettingsLoader( 3037): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3037): createReceiver()
,D/BluetoothMapEmailAppObserver( 3037): initObservers()
D/BluetoothManagerService(  757): Message: 30
D/BluetoothMapEmailAppObserver( 3037): getEnabledAccountItems()
D/LocalBluetoothProfileManager( 3069): LocalBluetoothProfileManager construction complete
,D/BluetoothAdapterService( 3037): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a0b8300
D/HeadsetStateMachine( 3037): Proxy object connected
,D/HeadsetStateMachine( 3037): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3037): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3037): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3037): Handler(): got msg=1
,D/BluetoothAdapterState( 3037): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3037): enable
I/GKI_LINUX( 3037): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3037): btu_task pending for preload complete event
I/bt_hci_bdroid( 3037): init
D/BluetoothInputDevice( 3069): Proxy object connected
I/bt_vendor( 3037): init
I/bt_vnd_conf( 3037): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
D/HidProfile( 3069): Bluetooth service connected
I/bt_vnd_conf( 3037): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3037): userial_init
,D/BluetoothPan( 3069): BluetoothPAN Proxy object connected
,D/PanProfile( 3069): Bluetooth service connected
,D/BluetoothMap( 3069): Proxy object connected
,D/MapProfile( 3069): Bluetooth service connected
,D/BluetoothMap( 3069): getConnectedDevices()
D/BluetoothMap( 3069): Bluetooth is Not enabled
,I/ActivityManager(  757): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3106 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager(  757): Killing 2360:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/bt_userial_vendor( 3037): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3037): device fd = 53 open
D/bt_userial( 3037): Entering userial_read_thread()
,W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2360/cgroup.procs: No such file or directory
,I/bt_hwcfg( 3037): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3037): Chipset BCM4335C0
D/bt_hwcfg( 3037): Target name = [BCM4335C0]
I/bt_hwcfg( 3037): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/art     (  757): Explicit concurrent mark sweep GC freed 14620(731KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.045ms total 86.160ms
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 1377(47KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/21MB, paused 217us total 10.282ms
,D/AuthorizationBluetoothService( 1285): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  757): Killing 1758:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_1758/cgroup.procs: No such file or directory
,I/bt_hwcfg( 3037): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3037): Settlement delay -- 100 ms
I/bt_hwcfg( 3037): Setting fw settlement delay to 100 
,D/Tethering(  757): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3054): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 3037): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3037): Setting local bd addr to 34:FC:EF:11:AE:67
,D/WifiConfigStore(  757): Loading config and enabling all networks 
,I/bt_hwcfg( 3037): vendor lib fwcfg completed
,I/bt-btu  ( 3037): btu_task received preload complete event
,D/WifiService(  757): New client listening to asynchronous messages
,I/        ( 3037): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3037): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3037): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3037): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3037): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3037): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3037): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3037): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3037): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3037): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3037): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3037): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3037): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3037): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3037): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiConfigStore(  757): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/wpa_supplicant( 3054): wlan0: CTRL-EVENT-SCAN-STARTED 
,W/Settings( 2278): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  757): Setting external_sim to 1
,D/WifiStateMachine(  757): Setting OUI to DA-A1-19
I/WifiNative-HAL(  757): startHal
D/wifi    (  757): setting scan oui 0x9ba7aad8
D/WifiHAL (  757): Sending mac address OUI
,E/WifiHAL (  757): failed to set scanning mac OUI; result = -95
,E/native  (  757): do suspend true
,D/WifiScanningService(  757): SCAN_AVAILABLE : 3
D/RttService(  757): SCAN_AVAILABLE : 3
D/WifiScanningService(  757): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  757): startHal
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
D/wifi    (  757): getting scan capabilities on interface[1] = 0x9ba7aad8
D/WifiHAL (  757): Creating message to get scan capablities; iface = 21
D/WifiHAL (  757): In GetCapabilities::handleResponse
D/WifiHAL (  757): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  757): StartedState
D/RttService(  757): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor(  757): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3054): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  757): p2pGetDeviceAddress
,D/WifiNative-HAL(  757): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,E/bt-btm  ( 3037): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ed99d5 
E/bt-btm  ( 3037): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ed99d5 
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1338): OkHttp exception
W/EventLoggerService( 1338): Unable to send logs Error code: 262146
,E/Auth    ( 1285): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1338): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth    ( 1285): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1338): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/bt-btif ( 3037): Calling BTA_HhEnable
,E/bt-btif ( 3037): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3037): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3037): Name is: Nexus 5
D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3037): Scan Mode:20
D/BluetoothAdapterProperties( 3037): Discoverable Timeout:120
D/bte_conf( 3037): Device ID record 1 : primary
D/bte_conf( 3037):   vendorId            = 000f
D/bte_conf( 3037):   vendorIdSource      = 0001
D/bte_conf( 3037):   product             = 1200
D/bte_conf( 3037):   version             = 1436
D/bte_conf( 3037):   clientExecutableURL = 
D/bte_conf( 3037):   serviceDescription  = 
D/bte_conf( 3037):   documentationURL    = 
D/bte_conf( 3037): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3037): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3037): ScanMode =  20
D/BluetoothAdapterProperties( 3037): State =  11
D/BluetoothAdapterProperties( 3037): Setting state to 12
I/BluetoothAdapterState( 3037): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothPanServiceJni( 3037): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
I/BluetoothAdapterState( 3037): Entering On State
,D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothMap( 3069): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3037): Scan Mode:21
D/BluetoothAdapterProperties( 3037): Discoverable Timeout:120
D/BluetoothHeadset( 1205): onBluetoothStateChange: up=true
D/BluetoothPbap( 3069): onBluetoothStateChange: up=true
,D/BluetoothPan( 3069): onBluetoothStateChange(on) call bindService
,D/BluetoothA2dp(  757): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1161): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3069): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1161): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  757): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  757): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 3037): onReceive
,D/BluetoothMapService( 3037): STATE_ON
V/BluetoothMapService( 3037): Handler(): got msg=1
D/BluetoothMapMasInstance( 3037): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3037): MAS initSocket()
D/BluetoothMapMasInstance( 3037):   masId = 00
D/BluetoothMapMasInstance( 3037):   msgTypes = 0e
D/BluetoothMapMasInstance( 3037):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3037):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = 48 e5 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = 19 0e e5 d1 d1 15 e7 4c c7 a6 f4 b5 1f 7b d5 f5 
W/bt-btm  ( 3037): Stopping oneshot timer
I/Telecom ( 1161): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
E/bt_h4   ( 3037): vendor lib postload completed
,W/BluetoothAdapter( 3037): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3037): Succeed to create listening socket 
,D/BluetoothMapMasInstance( 3037): Accepting socket connection...
,D/HeadsetStateMachine( 3037): Disconnected process message: 9, size: 0
D/LocalBluetoothProfileManager( 3069): Adding local A2DP profile
D/HeadsetStateMachine( 3037): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3037): mNumber:  mType: 128
D/HeadsetStateMachine( 3037): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3037): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 3069): Adding local HEADSET profile
,D/BluetoothManagerService(  757): Message: 30
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = f8 eb 74 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = 26 d5 1e 40 81 bb 8a 46 e9 41 56 3a 14 36 28 11 
W/bt-btm  ( 3037): Stopping oneshot timer
,W/ContextImpl( 3069): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = 18 b3 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = b3 fd 82 43 10 66 89 7a 61 0f da 76 29 e9 0c 1e 
W/bt-btm  ( 3037): Stopping oneshot timer
,D/BluetoothA2dp( 3069): Proxy object connected
D/A2dpProfile( 3069): Bluetooth service connected
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = 0c 23 5b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = ad bf 10 67 77 2f 61 23 8a b4 cc aa 94 f8 a4 99 
W/bt-btm  ( 3037): Stopping oneshot timer
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = 13 13 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = c3 8e b0 cc 20 62 87 88 6e 29 5f 38 d2 af a7 46 
W/bt-btm  ( 3037): Stopping oneshot timer
,D/BluetoothHeadset( 3069): Proxy object connected
,D/HeadsetProfile( 3069): Bluetooth service connected
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3037): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = 0e 72 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = 19 54 2d 5c a0 44 9f a8 40 fb 87 ef 61 ae 9b bb 
W/bt-btm  ( 3037): Stopping oneshot timer
,D/DockEventReceiver( 3069): finishStartingService: stopping service
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = 49 f0 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = 15 d2 1c 9f 9a c4 cf 21 41 96 9e 34 bb 68 fb 2e 
W/bt-btm  ( 3037): Stopping oneshot timer
,D/BluetoothPbap( 3069): Proxy object connected
,D/PbapServerProfile( 3069): Bluetooth service connected
,D/AuthorizationBluetoothService( 1285): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3037): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3037): Accept thread started.
,I/wpa_supplicant( 3054): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  757): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  757): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  757): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  757): will read network variables netId=1
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  757): will read network variables netId=1
,I/wpa_supplicant( 3054): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  757): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3054): PNO: In assoc process
,I/wpa_supplicant( 3054): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3054): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3054): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  757): Start Dhcp Watchdog 1
,E/native  (  757): do suspend false
,E/WifiStateMachine(  757): scanCount==0 - aborting
,I/dhcpcd  ( 3199): version 5.5.6 starting
,E/dhcpcd  ( 3199): get_duid: Read-only file system
,I/dhcpcd  ( 3199): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3199): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3199): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  757): do suspend true
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  757): Adding iface wlan0 to network 100
,E/ConnectivityService(  757): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  757): Adding Route [fe80::/64 -> :: wlan0] to network 100
,E/WifiStateMachine(  757): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  757): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  757): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  757): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757):    accepting network in place of null
D/ConnectivityService(  757): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 11:11:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449832301338], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449832301318]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
,D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524290
,D/TelephonyNetworkFactory( 1205): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524295
,I/jxcore-log( 2972): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2972): 
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  757): Setting time of day to sec=1449832303
,W/AlarmManagerService(  757): Unable to set rtc to 1449832303: Invalid argument
,I/NetworkMonitor( 2481): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2481): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/CheckinService( 1554): Checkin interval check for package: unspecified last checkin: 1449789118591 min interval config: 0 actual interval: 43185403
,I/GoogleURLConnFactory( 1285): Using platform SSLCertificateSocketFactory
,I/CheckinService( 1554): Checking schedule, now: 1449832304007 next: 1449831285544
I/CheckinService( 1554): active receiver: enabled
,I/CheckinService( 1554): Preparing to send checkin request
,I/EventLogService( 1554): Accumulating logs since 1449832249950
,I/SystemUpdateService( 1554): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,E/GpsLocationProvider(  757): No APN found to select.
,D/GpsLocationProvider(  757): NTP server returned: 1449832300900 (Fri Dec 11 12:11:40 GMT+01:00 2015) reference: 85631 certainty: 13 system time offset: -3145
E/LocSvc_eng(  757): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/PhenotypeConfigurator( 1285): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,E/ActivityThread( 1554): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 26511, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121523, reason: UserStart
D/SystemUpdateService( 1554): onCreate
,D/SystemUpdateService( 1554): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1554): active receiver: enabled
,I/SystemUpdateService( 1554): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,I/iu.SyncManager( 1554): SYNC; picasa accounts
,V/SystemUpdateService( 1554): retry (wakeup: false) in 3599980 ms
,E/Auth.Api.Credentials( 1554): [CredentialSyncAdapter] Unknown sync event.
,D/NetworkLogImpl( 1554): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1554): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1554): num queued entries: 0
,I/iu.UploadsManager( 1554): num updated entries: 0
,I/iu.SyncManager( 1554): NEXT; no task
,D/SystemUpdateService( 1554): onDestroy
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3305 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinRequestBuilder( 1554): Checkin reason type: 12 attempt count: 1
,D/WifiService(  757): New client listening to asynchronous messages
,E/ActivityThread( 1554): Failed to find provider info for com.google.android.wearable.settings
,I/Babel   ( 2278): connection state changed from UNKNOWN to CONNECTED
,E/ConnectivityChangeReceiver( 1554): Ignoring connectivity change
,D/ConnectivityService(  757): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  757): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  757): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1554): CM callback handler got msg 524290
,I/GAv4    ( 3305): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3305):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3305):   adb logcat -s GAv4
,W/GAv4    ( 3305): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCM     ( 1285): GCM config loaded
,W/GAv4    ( 3305): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3305): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  757): Explicit concurrent mark sweep GC freed 52466(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.185ms total 70.335ms
,W/DriveInitializer( 1554): Awaiting to be initialized
W/DriveInitializer( 1554): Background init thread started
,I/WebViewFactory( 3305): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 1720(66KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 493us total 11.263ms
,I/LibraryLoader( 3305): Time to load native libraries: 3 ms (timestamps 9305-9308)
I/LibraryLoader( 3305): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3305): Binding Chromium to main looper Looper (main, tid 1) {2c1105fd}
,I/LibraryLoader( 3305): Expected native library version number "",actual native library version number ""
I/chromium( 3305): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3305): Initializing chromium process, singleProcess=true
W/art     ( 3305): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3305): ApplicationContext is null in ApplicationStatus
,W/chromium( 3305): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3305): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3305): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3305): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1554): Background init thread ended
,W/AudioManagerAndroid( 3305): Requires BLUETOOTH permission
,I/NSApplication( 3305): Starting up...
,I/ActivityManager(  757): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3405 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 422us total 10.802ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 165us total 7.391ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.406ms
,D/TimeService( 3405): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449832304801
,D/        ( 3405): TimeServiceNative: User Time to be set is 1449832304801
D/QC-time-services( 3405): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3405): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3405): Lib:time_genoff_operation: pargs->ts_val = 1449832304801
D/QC-time-services( 3405): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449832304801
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1449832304801, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/14/70 17:2:28
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 8960548000
D/QC-time-services(  197): Daemon:new time 1449832304801 
D/QC-time-services(  197): Daemon: delta 1440871756801 genoff 1440871756801 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871756801 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871756801 to memory
,D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
,D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1133867504801
,E/QC-time-services( 3405): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  757): Killing 2460:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2460/cgroup.procs: No such file or directory
,W/PhenotypeConfigurator( 1285): Server returned 404
,I/art     ( 1554): Explicit concurrent mark sweep GC freed 16920(1234KB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 22MB/37MB, paused 7.171ms total 56.983ms
,I/ActivityManager(  757): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3425 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/CheckinService( 1554): Checkin interval check for package: unspecified last checkin: 1449789118591 min interval config: 0 actual interval: 43186349
,W/ResourcesManager( 3425): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3425): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3425): VM with version 2.1.0 has multidex support
I/MultiDex( 3425): install
,I/MultiDex( 3425): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3425): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3446 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,W/ActivityThread( 3425): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3425): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d0c1f8d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3425): Installed default security provider GmsCore_OpenSSL
,I/art     ( 3425): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3425): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/GAv4    ( 3446): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3446):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3446):   adb logcat -s GAv4
,W/GAv4    ( 3446): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/NativeLibraryUtils( 3425): Install completed successfully. count=14 extracted=0
,W/GAv4    ( 3446): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3446): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/VacuumService( 1285): Vacuum at: now=1449832305195 tag=VacuumService
,D/WVCdm   (  183): Instantiating CDM.
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,I/GoogleURLConnFactory( 3425): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  757): Killing 2334:com.google.android.gm/u0a70 (adj 15): empty #17
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,W/art     ( 2619): Attempt to remove local handle scope entry from IRT, ignoring
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xbef11500
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb6172268, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb61aa600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
W/libprocessgroup(  757): failed to open /acct/uid_10070/pid_2334/cgroup.procs: No such file or directory
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb46be440, idLength=0xb4bff710
,D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_SupportsUsageTable: starts!
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
D/WVCdm   (  183): PrepareKeyRequest: nonce=3699900034
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d01600
D/DrmWidevineDash(  183): message_length=1597, signature=0xb4a19280, signature_length=3032479476
,D/WearableService( 1285): callingUid 10008, callindPid: 1285
,E/MDM     ( 1285): [133] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1554): Restart initialization of location
D/AuthorizationBluetoothService( 1285): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1285): No location to return for getLastLocation()
W/FusedLocationProvider( 1285): location=null
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/PhenotypeConfigurator( 1285): Scheduling Phenotype for one-off execution 1754 seconds from now (1449832305717)
,D/GetConfigurationSnapshotOperation( 1285): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1285): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1285): Using platform SSLCertificateSocketFactory
,I/art     ( 1285): Explicit concurrent mark sweep GC freed 71029(4MB) AllocSpace objects, 31(519KB) LOS objects, 39% free, 22MB/36MB, paused 887us total 43.611ms
,I/ActivityManager(  757): Killing 1888:com.android.providers.calendar/u0a2 (adj 15): empty #17
,I/dex2oat ( 3497): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  757): failed to open /acct/uid_10002/pid_1888/cgroup.procs: No such file or directory
,I/dex2oat ( 3497): dex2oat took 45.119ms (threads: 4)
,I/Adreno-EGL( 3425): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3425): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb5911000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
,D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xb47ff940
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb4a28070, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb46cf600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb46be480, idLength=0xb4bff710
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
D/WVCdm   (  183): PrepareKeyRequest: nonce=4189325708
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d01600
D/DrmWidevineDash(  183): message_length=1632, signature=0xb4a19280, signature_length=3032479476
,D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  183): CdmEngine::CloseSession
D/DrmWidevineDash(  183): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  183): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  183): L3 Terminate.
D/DrmWidevineDash(  183): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  183): Service_Uninitialize: starts!
D/QSEECOMAPI: (  183): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  183): QSEECom_shutdown_app, app_id = 3
,D/DrmWidevineDash(  183): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/Adreno-EGL( 3425): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1554): Classify the device as Phone.
,I/CheckinTask( 1554): Sending checkin request (9735 bytes)
,I/CheckinResponseProcessor( 1554): From server: 2 gservices updates and 0 deletes
,I/CertBlacklister(  757): Certificate blacklist changed, updating...
,I/CertBlacklister(  757): Certificate blacklist updated
,I/GservicesProvider( 1451): main difference update completed
,I/CheckinRequestBuilder( 1554): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1554): Failed to find provider info for com.google.android.wearable.settings
,I/ContactAccountLoggerTas( 1338): canRun() : Opted Out
,I/art     (  757): Explicit concurrent mark sweep GC freed 28720(1235KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.048ms total 65.716ms
,I/ActivityManager(  757): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3525 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/Search.GservicesUpdateTask( 1338): Updating Gservices keys
,I/Babel_SMS( 2278): ApnsOta: OTA version -1
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 10052(493KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 829us total 56.910ms
,E/UpdateRequestReceiver( 3525): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3525): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3525): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3525): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 1554): Checkin interval check for package: unspecified last checkin: 1449789118591 min interval config: 0 actual interval: 43188989
,I/SystemUpdateService( 1554): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1554): onCreate
,D/SystemUpdateService( 1554): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1554): active receiver: enabled
,I/ContactAccountLoggerTas( 1338): canRun() : Opted Out
I/ContactAccountLoggerTas( 1338): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1338): canRun() : Opted Out
,I/SystemUpdateService( 1554): showing system update notification
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1554): retry (wakeup: false) in 3599927 ms
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 3816(153KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 637us total 16.206ms
,I/CheckinRequestBuilder( 1554): Classify the device as Phone.
,I/art     ( 1554): Explicit concurrent mark sweep GC freed 14503(888KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 22MB/38MB, paused 1.469ms total 51.330ms
,W/SQLiteConnectionPool( 1554): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 2814(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 645us total 11.067ms
,I/ActivityManager(  757): Killing 2791:com.google.android.gms:car/u0a8 (adj 15): empty #17
,D/SystemUpdateService( 1554): onDestroy
,W/libprocessgroup(  757): failed to open /acct/uid_10008/pid_2791/cgroup.procs: No such file or directory
,E/DynamiteModule( 1554): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1554): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1554): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1554): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1554): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1554): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1554): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1554): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1554): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1554): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1554): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1554): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/DynamiteModule( 1554): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/DynamiteModule( 1554): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/DynamiteModule( 1554): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1554): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1554): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/DynamiteModule( 1554): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1554): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1554): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/DynamiteModule( 1554): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/DynamiteModule( 1554): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1554): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1554): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1554): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1554): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1554): 		... 17 more
E/DynamiteModule( 1554): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 1554): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1554): Selected local version of com.google.android.gms.flags
,I/CheckinTask( 1554): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1554): Checking schedule, now: 1449832308099 next: 1449874475088
I/CheckinService( 1554): active receiver: disabled
,I/CheckinService( 1554): Checking schedule, now: 1449832308139 next: 1449874475088
I/CheckinService( 1554): active receiver: disabled
,D/CheckinService( 1554): Recording last checkin time for package unspecified as 1449832308159
,D/SystemEventReceiver( 1554): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1554): Updating ocr activity enabled=false
,W/ActivityManager(  757): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1554): Updating downloaded model state (gservices changed)
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 2954(114KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 840us total 21.575ms
,I/ContactAccountLoggerTas( 1338): canRun() : Opted Out
,I/art     ( 1285): Explicit concurrent mark sweep GC freed 61542(3MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 23MB/38MB, paused 690us total 40.602ms
,D/GCM     ( 1285): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1285): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1285): DispatchingService.onCreate()
,I/GCoreUlr( 1285): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1285): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1285): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/art     ( 1451): Explicit concurrent mark sweep GC freed 2698(106KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 3.902ms total 51.364ms
,I/GCoreUlr( 1285): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1285): Unbound from all location providers
I/GCoreUlr( 1285): Place inference reporting - stopped
,D/GCM     ( 1285): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  757): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3612 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1285): DispatchingService.onDestroy()
,I/GCoreUlr( 1285): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1285): Unbound from all location providers
,I/GCoreUlr( 1285): Place inference reporting - stopped
,W/ctxmgr  ( 1285): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1285): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,W/ResourcesManager( 3612): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3612): Created com.android.providers.calendar.CalendarAlarmManager@2732a432(com.android.providers.calendar.CalendarProvider2@f435583)
,E/SQLiteLog( 3612): (284) automatic index on view_events(_id)
,D/Finsky  ( 2390): [231] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2390): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/CalendarProvider2( 3612): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3612): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     (  757): Explicit concurrent mark sweep GC freed 20251(1005KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 1.122ms total 77.188ms
,I/ActivityManager(  757): Killing 2872:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10015/pid_2872/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Killing 2909:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10040/pid_2909/cgroup.procs: No such file or directory
,W/PackageSettings(  757): Skipping PackageSetting{18a62de7 com.example.hello/10277} due to missing metadata
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,W/Launcher( 1250): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2a0b8300 new=com.google.android.velvet.VelvetApplication@2a0b8300
,D/PackageBroadcastService( 1554): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1554): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 1338): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Icing   ( 1554): updateResources: need to parse f{com.google.android.gms}
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  757): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  757): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  757): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  757): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c3b23e5
,I/GCoreNlp( 1285): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/Launcher( 1250): Deferring update until onResume
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1250): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1250): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1338): UpdateCorporaTask done [took 238 ms] updated apps [took 238 ms] 
,I/Icing   ( 1554): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,D/Icing   ( 1554): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1554): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,E/ActivityThread( 1554): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  757): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 121523, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  757): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 214710, reason: UserStart
,I/ClearcutLoggerApiImpl( 1285): disconnect managed GoogleApiClient
,I/jxcore-log( 2972): Connected to the server!
I/jxcore-log( 2972): 
,I/chromium( 2972): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  757): Killing 2762:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10005/pid_2762/cgroup.procs: No such file or directory
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = be 30 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = de 27 27 64 84 96 3a e7 1f cb 71 38 5f 52 bd 10 
,W/bt-btm  ( 3037): Stopping oneshot timer
,I/UsageStatsService(  757): User[0] Flushing usage stats to disk
,I/ProcessStatsService(  757): Prepared write state in 48ms
,W/bt-smp  ( 3037): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3037): Plain text(LSB ~ MSB) = dc 3a 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3037): Encrypted text(LSB ~ MSB) = 58 89 34 c4 20 66 2c 6f e7 44 8b 45 a7 0e 21 d9 
W/bt-btm  ( 3037): Stopping oneshot timer
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1285): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1554): Aggregate from 1449832304107 (log), 1449832249950 (data)
,I/ProcessStatsService(  757): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-09-42.bin
,I/ActivityManager(  757): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3755 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 3069:com.android.settings/1000 (adj 15): empty for 1800s
,D/WifiService(  757): Client connection lost with reason: 4
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_3069/cgroup.procs: No such file or directory
,W/ResourcesManager( 3755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3755): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3755): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3755): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 3755): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3816): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1312004070.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads1312004070.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3816): dex2oat took 38.130ms (threads: 4)
,W/InstanceID/Rpc( 3755): Found 10008
,I/art     ( 1285): Explicit concurrent mark sweep GC freed 50138(2MB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 22MB/37MB, paused 857us total 38.451ms
,I/ActivityManager(  757): Killing 3305:com.google.android.apps.magazines/u0a61 (adj 15): empty for 1800s
,I/ActivityManager(  757): Killing 2481:com.google.android.music:main/u0a60 (adj 15): empty for 1800s
,W/libprocessgroup(  757): failed to open /acct/uid_10061/pid_3305/cgroup.procs: No such file or directory
,W/libprocessgroup(  757): failed to open /acct/uid_10060/pid_2481/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
