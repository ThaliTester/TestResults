#### Test 51986340a77003b_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2967): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2967):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2967):   adb logcat -s GAv4
W/GAv4    ( 2967): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2967): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2967): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2967): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/AndroidRuntime( 3008): 
D/AndroidRuntime( 3008): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3008): CheckJNI is OFF
--------- beginning of system
W/ResourcesManager( 2967): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2967): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2466): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  760): Killing 2380:com.google.android.deskclock/u0a38 (adj 15): empty #17
D/AndroidRuntime( 3008): Calling main entry com.android.commands.am.Am
V/JNIHelp ( 2967): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2967): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2967): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  760): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3043 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3008): Shutting down VM
W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2380/cgroup.procs: No such file or directory
V/ActivityManager(  760): Display changed displayId=0
I/Icing   ( 1617): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/art     ( 1373): Explicit concurrent mark sweep GC freed 10199(590KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 1.869ms total 53.589ms
V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Icing   ( 1617): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1617): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 3043): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3043): Time to load native libraries: 1 ms (timestamps 617-618)
I/LibraryLoader( 3043): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3043): Binding Chromium to main looper Looper (main, tid 1) {8dc0920}
I/LibraryLoader( 3043): Expected native library version number "",actual native library version number ""
I/chromium( 3043): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3043): Initializing chromium process, singleProcess=true
W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3043): ApplicationContext is null in ApplicationStatus
W/chromium( 3043): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3043): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3043): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3043): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3043): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d4ae5e:true
D/BluetoothAdapter( 3043): 515759274: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3043): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3043): CordovaWebView is running on device made by: LGE
W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3043): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3043): Render dirty regions requested: true
D/Atlas   ( 3043): Validating map...
W/chromium( 3043): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3043): Initialized EGL, version 1.4
D/OpenGLRenderer( 3043): Enabling debug mode 0
W/IInputConnectionWrapper( 3043): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1064): onFinishInput()
I/ActivityManager(  760): Displayed com.test.thalitest/.MainActivity: +438ms (total +58s234ms)
W/BindingManager( 3043): Cannot call determinedVisibility() - never saw a connection for the pid: 3043
D/JsMessageQueue( 3043): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3043): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
D/JX-Cordova( 3043): jxcore cordova android initializing
,W/jxcore-log( 3043): Initializing JXcore engine
W/jxcore-log( 3043): JXcore engine is ready
,W/jxcore-log( 3043): Starting JXcore engine
,W/.test.thalitest( 3043): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9312]" dev="sockfs" ino=9312 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3043): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3097 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3043): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7527]" dev="sockfs" ino=7527 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3043): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18467]" dev="sockfs" ino=18467 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3043): Platform android
W/jxcore-log( 3043): 
W/jxcore-log( 3043): Process ARCH arm
W/jxcore-log( 3043): 
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3043): JXcore Cordova bridge is ready!
I/jxcore-log( 3043): 
V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 3043): JXcore engine is started
I/Choreographer( 3043): Skipped 110 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3043): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/NetworkUtils( 1342): OkHttp exception
W/EventLoggerService( 1342): Unable to send logs Error code: 262146
W/Search.LoginHelper( 1342): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1342): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/jxcore-log( 3043): Toggling radios to true
I/jxcore-log( 3043): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  760): Message: 1
D/BluetoothManagerService(  760): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  760): New client listening to asynchronous messages
D/WifiService(  760): setWifiEnabled: true pid=3043, uid=10270
,E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3043): Radios toggled
I/jxcore-log( 3043): 
,D/SoftapController(  179): Softap fwReload - Ok
D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring down wlan0
D/CommandListener(  179): Clearing all IP addresses on wlan0
I/ActivityManager(  760): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3119 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,W/ResourcesManager( 3119): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3136): Successfully initialized wpa_supplicant
,D/AdapterServiceConfig( 3119): Adding HeadsetService
D/AdapterServiceConfig( 3119): Adding A2dpService
D/AdapterServiceConfig( 3119): Adding HidService
D/AdapterServiceConfig( 3119): Adding HealthService
D/AdapterServiceConfig( 3119): Adding PanService
D/AdapterServiceConfig( 3119): Adding GattService
D/AdapterServiceConfig( 3119): Adding BluetoothMapService
,I/wpa_supplicant( 3136): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  760): startMonitoring(wlan0) with mConnected = false
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a89f017:true
D/BluetoothAdapterState( 3119): make
I/bluedroid( 3119): init
I/BluetoothAdapterState( 3119): Entering OffState
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3142 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/bte_conf( 3119): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3119): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3119): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3119): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3119): get_profile_interface socket
I/bluedroid( 3119): get_profile_interface map_client
,I/GKI_LINUX( 3119): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3119): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3119): Name is: Nexus 5
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,I/bluedroid( 3119): config_hci_snoop_log
,D/BluetoothManagerService(  760): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3119): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3119): Setting state to 11
I/BluetoothAdapterState( 3119): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3119): make
,D/BluetoothHeadset( 1180): Proxy object connected
,D/BluetoothHeadset(  760): Proxy object connected
D/BluetoothHeadset( 1156): Proxy object connected
I/BluetoothBondStateMachine( 3119): StableState(): Entering Off State
D/HeadsetService( 3119): Received start request. Starting profile...
,D/BluetoothHeadset( 1156): Proxy object connected
I/BluetoothHeadsetServiceJni( 3119): classInitNative: succeeds
,D/HeadsetStateMachine( 3119): make
,D/HeadsetStateMachine( 3119): max_hf_connections = 1
I/bluedroid( 3119): get_profile_interface handsfree
,D/HeadsetStateMachine( 3119): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3119): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37d2d9
,D/BluetoothA2dp(  760): Proxy object connected
D/A2dpService( 3119): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3119): classInitNative: succeeds
I/bluedroid( 3119): get_profile_interface avrcp
,I/BluetoothAdapterState( 3119): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,E/RemoteController( 3119): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3119): classInitNative: succeeds
D/A2dpStateMachine( 3119): make
I/bluedroid( 3119): get_profile_interface a2dp
,I/GKI_LINUX( 3119): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3119): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37d2d9
D/A2dpStateMachine( 3119): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3119): classInitNative: succeeds
,D/HidService( 3119): Received start request. Starting profile...
I/bluedroid( 3119): get_profile_interface hidhost
D/BluetoothAdapterService( 3119): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37d2d9
D/HeadsetStateMachine( 3119): Proxy object connected
,I/BluetoothHealthServiceJni( 3119): classInitNative: succeeds
,D/HealthService( 3119): Received start request. Starting profile...
,I/bluedroid( 3119): get_profile_interface health
D/BluetoothAdapterService( 3119): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37d2d9
,I/BluetoothPanServiceJni( 3119): classInitNative(L105): succeeds
,D/PanService( 3119): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3119): initializeNative(L110): pan
I/bluedroid( 3119): get_profile_interface pan
,D/BluetoothAdapterService( 3119): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37d2d9
,I/BtGatt.JNI( 3119): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3119): handleDebugAction() action=null
D/BtGatt.GattService( 3119): Received start request. Starting profile...
D/BtGatt.GattService( 3119): start()
I/bluedroid( 3119): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3119): advertise manager created
,D/BluetoothAdapterService( 3119): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37d2d9
D/HeadsetStateMachine( 3119): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3119): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3119): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3119): BluetoothMapBinder()
,D/BluetoothMapService( 3119): Received start request. Starting profile...
D/BluetoothMapService( 3119): start()
,D/BluetoothMapEmailSettingsLoader( 3119): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3119): createReceiver()
D/BluetoothMapEmailAppObserver( 3119): initObservers()
,D/BluetoothMapEmailAppObserver( 3119): getEnabledAccountItems()
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@326931b:true
D/BluetoothAdapterService( 3119): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f37d2d9
V/BluetoothMapService( 3119): Handler(): got msg=1
,D/BluetoothAdapterState( 3119): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3119): enable
,I/GKI_LINUX( 3119): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3119): btu_task pending for preload complete event
I/bt_hci_bdroid( 3119): init
,I/bt_vendor( 3119): init
I/bt_vnd_conf( 3119): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3119): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3119): userial_init
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3142): Adding local MAP profile
,D/BluetoothMap( 3142): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 3142): LocalBluetoothProfileManager construction complete
,D/BluetoothInputDevice( 3142): Proxy object connected
,D/HidProfile( 3142): Bluetooth service connected
,D/BluetoothPan( 3142): BluetoothPAN Proxy object connected
,D/PanProfile( 3142): Bluetooth service connected
,D/BluetoothMap( 3142): Proxy object connected
D/MapProfile( 3142): Bluetooth service connected
D/BluetoothMap( 3142): getConnectedDevices()
,D/BluetoothMap( 3142): Bluetooth is Not enabled
,I/bt_userial_vendor( 3119): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3119): device fd = 53 open
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3184 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2430:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
D/bt_userial( 3119): Entering userial_read_thread()
,I/art     (  760): Explicit concurrent mark sweep GC freed 14556(717KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.021ms total 55.830ms
D/BluetoothManagerService(  760): Message: 30
,I/bt_hwcfg( 3119): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3119): Chipset BCM4335C0
D/bt_hwcfg( 3119): Target name = [BCM4335C0]
I/bt_hwcfg( 3119): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2430/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1373): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/bt_hwcfg( 3119): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3119): Settlement delay -- 100 ms
I/bt_hwcfg( 3119): Setting fw settlement delay to 100 
,I/ActivityManager(  760): Killing 1838:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_1838/cgroup.procs: No such file or directory
,D/Tethering(  760): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 3119): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3119): Setting local bd addr to 34:FC:EF:11:AE:67
,I/wpa_supplicant( 3136): rfkill: Cannot open RFKILL control device
,I/bt_hwcfg( 3119): vendor lib fwcfg completed
I/bt-btu  ( 3119): btu_task received preload complete event
,I/        ( 3119): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3119): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3119): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3119): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3119): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3119): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3119): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3119): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3119): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3119): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3119): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3119): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3119): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3119): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3119): BTE_InitTraceLevels -- TRC_BTIF
,I/wpa_supplicant( 3136): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  760): Loading config and enabling all networks 
,D/WifiService(  760): New client listening to asynchronous messages
,E/WifiConfigStore(  760): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  760): Setting external_sim to 1
W/Settings( 1856): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  760): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  760): startHal
D/wifi    (  760): setting scan oui 0x92a65850
D/WifiHAL (  760): Sending mac address OUI
,E/WifiHAL (  760): failed to set scanning mac OUI; result = -95
,E/native  (  760): do suspend true
,D/CommandListener(  179): Setting iface cfg
D/CommandListener(  179): Trying to bring up p2p0
D/WifiScanningService(  760): SCAN_AVAILABLE : 3
D/RttService(  760): SCAN_AVAILABLE : 3
,D/WifiScanningService(  760): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  760): startHal
D/WifiMonitor(  760): startMonitoring(p2p0) with mConnected = true
D/RttService(  760): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  760): getting scan capabilities on interface[1] = 0x92a65850
,D/WifiHAL (  760): Creating message to get scan capablities; iface = 21
,D/WifiHAL (  760): In GetCapabilities::handleResponse
,D/WifiHAL (  760): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  760): StartedState
,I/wpa_supplicant( 3136): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  760): p2pGetDeviceAddress
,D/WifiNative-HAL(  760): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,E/bt-btm  ( 3119): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 3119): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3119): Calling BTA_HhEnable
E/bt-btif ( 3119): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3119): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3119): Name is: Nexus 5
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothAdapterProperties( 3119): Scan Mode:20
D/BluetoothAdapterProperties( 3119): Discoverable Timeout:120
,D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
D/bte_conf( 3119): Device ID record 1 : primary
D/bte_conf( 3119):   vendorId            = 000f
D/bte_conf( 3119):   vendorIdSource      = 0001
D/bte_conf( 3119):   product             = 1200
D/bte_conf( 3119):   version             = 1436
D/bte_conf( 3119):   clientExecutableURL = 
D/bte_conf( 3119):   serviceDescription  = 
D/bte_conf( 3119):   documentationURL    = 
D/bte_conf( 3119): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3119): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3119): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3119): ScanMode =  20
D/BluetoothAdapterProperties( 3119): State =  11
D/BluetoothAdapterProperties( 3119): Setting state to 12
I/BluetoothAdapterState( 3119): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothAdapterProperties( 3119): Scan Mode:21
D/BluetoothAdapterProperties( 3119): Discoverable Timeout:120
D/BluetoothHeadset( 1156): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3119): Entering On State
D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1156): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1180): onBluetoothStateChange: up=true
,D/BluetoothPan( 3142): onBluetoothStateChange(on) call bindService
,D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
D/BluetoothMap( 3142): onBluetoothStateChange: up=true
,D/BluetoothPbap( 3142): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3142): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothMapService( 3119): onReceive
,D/BluetoothMapService( 3119): STATE_ON
,V/BluetoothMapService( 3119): Handler(): got msg=1
D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapMasInstance( 3119): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3119): MAS initSocket()
D/BluetoothMapMasInstance( 3119):   masId = 00
D/BluetoothMapMasInstance( 3119):   msgTypes = 0e
D/BluetoothMapMasInstance( 3119):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3119):   SDP string = 000eSMS/MMS
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/Telecom ( 1156): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothAdapter( 3119): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 3142): Adding local A2DP profile
,E/bt_h4   ( 3119): vendor lib postload completed
D/HeadsetStateMachine( 3119): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 3119): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3119): mNumber:  mType: 128
D/HeadsetStateMachine( 3119): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3119): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/bt-smp  ( 3119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = 99 b1 79 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = 9f a1 70 93 16 7a ee 2b 5e 72 4a fa b4 c1 56 6c 
,W/bt-btm  ( 3119): Stopping oneshot timer
,V/BluetoothMapMasInstance( 3119): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3119): Accepting socket connection...
D/BluetoothManagerService(  760): Message: 30
D/LocalBluetoothProfileManager( 3142): Adding local HEADSET profile
W/bt-smp  ( 3119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = 1b e5 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = 02 90 58 9a f3 d5 80 6a bc 52 e1 3c 7d 50 0c 27 
W/bt-btm  ( 3119): Stopping oneshot timer
D/BluetoothManagerService(  760): Message: 30
W/bt-smp  ( 3119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = 9c e3 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = e6 5e 9c 2c f8 fc 58 71 c2 aa fe 70 29 a3 eb cd 
W/bt-btm  ( 3119): Stopping oneshot timer
,W/bt-smp  ( 3119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = a4 cd 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = c5 c5 10 45 ef 16 61 16 a3 29 bc f7 cf 9d 07 da 
W/bt-btm  ( 3119): Stopping oneshot timer
,W/ContextImpl( 3142): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3142): Proxy object connected
D/A2dpProfile( 3142): Bluetooth service connected
,D/BluetoothHeadset( 3142): Proxy object connected
D/HeadsetProfile( 3142): Bluetooth service connected
,W/bt-smp  ( 3119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = e5 3f 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = 8a c3 1f cb 26 69 c3 94 49 fb 41 10 ba 8f ea 53 
W/bt-btm  ( 3119): Stopping oneshot timer
,D/DockEventReceiver( 3142): finishStartingService: stopping service
,W/bt-smp  ( 3119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = 75 02 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = e3 18 86 1f 0b a3 4a 5c 73 5c 05 d3 6a af e4 90 
W/bt-btm  ( 3119): Stopping oneshot timer
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/bt-smp  ( 3119): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3119): Plain text(LSB ~ MSB) = c2 2f 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3119): Encrypted text(LSB ~ MSB) = 02 2b 58 d5 0b 69 53 94 0e 09 26 b7 6f 89 07 a9 
W/bt-btm  ( 3119): Stopping oneshot timer
,W/BluetoothAdapter( 3119): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbap( 3142): Proxy object connected
,D/PbapServerProfile( 3142): Bluetooth service connected
,D/AuthorizationBluetoothService( 1373): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3119): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3119): Accept thread started.
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3043): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): my name is : LGE-Nexus 5_PT7441
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): attempting to connect to test coordinator
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): check test folder
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): found test : ./testFindPeers.js
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): found test : ./testReConnect.js
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): found test : ./testSendData.js
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): Test app app.js loaded
I/jxcore-log( 3043): 
,I/Choreographer( 3043): Skipped 127 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/chromium( 3043): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3136): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  760): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  760): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  760): will read network variables netId=1
,E/WifiStateMachine(  760): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  760): will read network variables netId=1
,I/wpa_supplicant( 3136): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  760): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3136): PNO: In assoc process
,I/wpa_supplicant( 3136): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3136): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3136): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  760): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  179): Setting iface cfg
,E/WifiStateMachine(  760): Start Dhcp Watchdog 1
,E/native  (  760): do suspend false
,E/WifiStateMachine(  760): scanCount==0 - aborting
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/dhcpcd  ( 3249): version 5.5.6 starting
E/dhcpcd  ( 3249): get_duid: Read-only file system
,I/dhcpcd  ( 3249): wlan0: broadcasting for a lease
,I/dhcpcd  ( 3249): wlan0: offered 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3249): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3249): wlan0: leased 192.168.1.114 for 86400 seconds
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,E/native  (  760): do suspend true
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  760): Adding iface wlan0 to network 100
,E/WifiStateMachine(  760): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  760): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  760): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  760): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  760): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  760): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=true, hasIPv4Address=true
,D/ConnectivityService(  760): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760):    accepting network in place of null
,D/ConnectivityService(  760): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  760): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 30 Nov 2015 09:47:28 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448876848018], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448876847999]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1180): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,I/jxcore-log( 3043): BLE advertisement not supported: Not supported
I/jxcore-log( 3043): 
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  760): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2556): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2556): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  760): Setting time of day to sec=1448876851
,W/AlarmManagerService(  760): Unable to set rtc to 1448876851: Invalid argument
,I/iu.SyncManager( 1617): SYNC; picasa accounts
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3327 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NetworkLogImpl( 1617): Loaded NetworkSpeedPredictor
,I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 181us total 8.289ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 8.102ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 189us total 8.335ms
,I/iu.Environment( 1617): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1617): num queued entries: 0
,I/iu.UploadsManager( 1617): num updated entries: 0
,I/iu.SyncManager( 1617): NEXT; no task
,E/GpsLocationProvider(  760): No APN found to select.
,D/GpsLocationProvider(  760): NTP server returned: 1448876851161 (Mon Nov 30 10:47:31 GMT+01:00 2015) reference: 91181 certainty: 5 system time offset: -172
E/LocSvc_eng(  760): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1617): Checkin interval check for package: unspecified last checkin: 1448626247415 min interval config: 0 actual interval: 250603943
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1617): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1617): onCreate
,E/Auth.Api.Credentials( 1617): [CredentialSyncAdapter] Unknown sync event.
,D/SystemUpdateService( 1617): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PeopleSync( 1617): onPerformSync() [5005f081]
,I/SystemUpdateService( 1617): active receiver: enabled
,W/ResourcesManager( 3327): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3327): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SystemUpdateService( 1617): showing system update notification
,I/CheckinService( 1617): Checking schedule, now: 1448876851391 next: 1448668414372
I/CheckinService( 1617): active receiver: enabled
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1617): Preparing to send checkin request
I/EventLogService( 1617): Accumulating logs since 1448876136883
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1617): retry (wakeup: false) in 3599971 ms
,V/JNIHelp ( 3327): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/ActivityManager(  760): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3367 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 3327): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3327): Installed default security provider GmsCore_OpenSSL
,D/SystemUpdateService( 1617): onDestroy
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1856): connection state changed from UNKNOWN to CONNECTED
,I/PeopleDatabaseHelper( 1617): cleanUpNonGplusAccounts done.
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ConnectivityChangeReceiver( 1617): Ignoring connectivity change
,I/art     ( 1373): Explicit concurrent mark sweep GC freed 17120(868KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 19MB/32MB, paused 1.121ms total 69.876ms
,I/GCM     ( 1373): GCM config loaded
,D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  760): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  760): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524290
,E/YouTube MDX( 3327): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/GAv4    ( 3367): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3367):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3367):   adb logcat -s GAv4
,W/GAv4    ( 3367): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3367): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1617): Explicit concurrent mark sweep GC freed 24533(1823KB) AllocSpace objects, 18(288KB) LOS objects, 25% free, 21MB/29MB, paused 640us total 55.479ms
,W/GAv4    ( 3367): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinRequestBuilder( 1617): Checkin reason type: 12 attempt count: 1
,I/GCM     ( 1373): Ack for not saved message 23
,D/WifiService(  760): New client listening to asynchronous messages
,E/ActivityThread( 1617): Failed to find provider info for com.google.android.wearable.settings
,I/dex2oat ( 3428): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1865296290.jar --oat-fd=37 --oat-location=/data/data/com.google.android.youtube/cache/ads-1865296290.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3428): dex2oat took 63.627ms (threads: 4)
,I/art     (  760): Explicit concurrent mark sweep GC freed 49582(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 1.139ms total 63.085ms
,W/InstanceID/Rpc( 3327): Found 10008
,I/PeopleSync( 1617): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1617): Starting sync, feed=null [5005f081]
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,I/WebViewFactory( 3367): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/DriveInitializer( 1617): Awaiting to be initialized
,W/DriveInitializer( 1617): Background init thread started
,I/LibraryLoader( 3367): Time to load native libraries: 7 ms (timestamps 2060-2067)
I/LibraryLoader( 3367): Expected native library version number "",actual native library version number ""
,W/AbstractGoogleClient( 2090): Application name is not set. Call Builder#setApplicationName.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WebViewChromiumFactoryProvider( 3367): Binding Chromium to main looper Looper (main, tid 1) {27594412}
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,I/LibraryLoader( 3367): Expected native library version number "",actual native library version number ""
I/chromium( 3367): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,V/AccountUtils( 1617): 0 accounts found with uca feature
I/GamesSyncAdapter( 1617): Starting sync for 3a3529a
I/AnalyticsLogBase( 2090): PlayLogger.onLoggerConnected
I/BrowserStartupController( 3367): Initializing chromium process, singleProcess=true
W/art     ( 3367): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3367): ApplicationContext is null in ApplicationStatus
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/chromium( 3367): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3367): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,W/GamesSyncAdapter( 1617): User is not G+ enabled. Aborting sync
I/GamesSyncAdapter( 1617): Sync duration for 3a3529a: 39
,I/PeopleSync( 1617): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,W/AudioManagerAndroid( 3367): Requires BLUETOOTH permission
,I/art     ( 1373): Explicit concurrent mark sweep GC freed 9521(562KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 19MB/32MB, paused 815us total 50.552ms
,W/DriveInitializer( 1617): Background init thread ended
,I/NSApplication( 3367): Starting up...
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3532 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,D/TimeService( 3532): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448876852386
D/        ( 3532): TimeServiceNative: User Time to be set is 1448876852386
,D/QC-time-services( 3532): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3532): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3532): Lib:time_genoff_operation: pargs->ts_val = 1448876852386
D/QC-time-services( 3532): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448876852386
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1448876852386, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/3/70 15:38:20
,D/QC-time-services(  199): Daemon:Value read from RTC seconds = 8005100000
D/QC-time-services(  199): Daemon:new time 1448876852386 
D/QC-time-services(  199): Daemon: delta 1440871752386 genoff 1440871752386 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871752386 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871752386 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1132912052386
,E/QC-time-services( 3532): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1617): Checkin interval check for package: unspecified last checkin: 1448626247415 min interval config: 0 actual interval: 250605023
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3561 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2521:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10003/pid_2521/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3584 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GAv4    ( 3561): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3561):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3561):   adb logcat -s GAv4
,W/ResourcesManager( 3584): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3584): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 3561): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 3584): VM with version 2.1.0 has multidex support
I/MultiDex( 3584): install
I/MultiDex( 3584): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3584): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/GAv4    ( 3561): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3561): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 3584): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3584): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b907e62: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3584): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  760): Killing 2404:com.google.android.gm/u0a70 (adj 15): empty #17
,I/art     ( 3584): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3584): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_2404/cgroup.procs: No such file or directory
,D/NativeLibraryUtils( 3584): Install completed successfully. count=13 extracted=0
,D/WVCdm   (  183): Instantiating CDM.
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,I/GoogleURLConnFactory( 3584): Using platform SSLCertificateSocketFactory
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xbed13500
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb520c070, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60aa600, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb49be440, idLength=0xb46ff710
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
D/WVCdm   (  183): PrepareKeyRequest: nonce=2838502367
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1b01600
D/DrmWidevineDash(  183): message_length=1597, signature=0xb451e280, signature_length=3027236596
,I/art     (  760): Explicit concurrent mark sweep GC freed 23199(1054KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.536ms total 103.894ms
,I/art     ( 1617): Explicit concurrent mark sweep GC freed 27343(1760KB) AllocSpace objects, 12(192KB) LOS objects, 24% free, 22MB/30MB, paused 1.251ms total 40.551ms
,D/WearableService( 1269): callingUid 10008, callindPid: 1269
,E/MDM     ( 1269): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
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
,W/SQLiteConnectionPool( 1617): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/LocationInitializer( 1617): Restart initialization of location
,D/AuthorizationBluetoothService( 1373): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1617): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/GCoreFlp( 1269): No location to return for getLastLocation()
W/FusedLocationProvider( 1373): location=null
,I/CalendarSyncAdapter( 2090): Found no pending settings
,I/ActivityManager(  760): Killing 2824:com.google.android.gms:car/u0a8 (adj 15): empty #17
,I/dex2oat ( 3639): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads1776645688.jar --oat-fd=97 --oat-location=/data/data/com.google.android.gms/cache/ads1776645688.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3642): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=35 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3639): dex2oat took 29.620ms (threads: 4)
,I/dex2oat ( 3642): dex2oat took 29.168ms (threads: 4)
,I/Adreno-EGL( 3584): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_2824/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 1301:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10004/pid_1301/cgroup.procs: No such file or directory
,I/WVCdm   (  183): CdmEngine::OpenSession
I/WVCdm   (  183): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  183): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  183): Service_Initialize: starts!
D/QSEECOMAPI: (  183): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  183): App is not loaded in QSEE
,D/QSEECOMAPI: (  183): Loaded image: APP id = 3
,D/DrmWidevineDash(  183): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  183): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
E/DrmWidevineDash(  183): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
,D/DrmWidevineDash(  183): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  183): hlos api version =  9
D/DrmWidevineDash(  183): tz api version =  9
D/DrmWidevineDash(  183): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  183): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  183): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: starts! SID=0xbed13500
,D/DrmWidevineDash(  183): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  183): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_GetRandom: starts! randomData=0xb60722a0, dataLength=8
,D/DrmWidevineDash(  183): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb60aa000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  183): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  183): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  183): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  183): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  183): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  183): OEMCrypto_GetDeviceID: starts! deviceID=0xb49be480, idLength=0xb48ff710
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
D/WVCdm   (  183): PrepareKeyRequest: nonce=474142169
D/DrmWidevineDash(  183): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb47d2600
D/DrmWidevineDash(  183): message_length=1632, signature=0xb471e280, signature_length=3029333748
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
,D/DrmWidevineDash(  183): OEMCrypto_Terminate: ends! returns 0
,I/PeopleSync( 1617): Sync finished, successful=true, took 1913ms
,I/art     ( 1373): Explicit concurrent mark sweep GC freed 38405(2MB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 19MB/33MB, paused 814us total 30.579ms
,I/Adreno-EGL( 3584): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/PeopleSync( 1617): ***Sync finished***, duration: 2803 [5005f081]
,I/Adreno-EGL( 3584): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/GoogleURLConnFactory( 1617): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1617): Classify the device as Phone.
,I/VacuumService( 1373): Vacuum at: now=1448876854530 tag=VacuumService
,I/CheckinTask( 1617): Sending checkin request (9624 bytes)
,W/art     ( 2654): Attempt to remove local handle scope entry from IRT, ignoring
,I/CheckinRequestBuilder( 1617): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1617): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  760): Explicit concurrent mark sweep GC freed 25202(1081KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.173ms total 70.367ms
,I/CheckinRequestBuilder( 1617): Classify the device as Phone.
,I/CheckinTask( 1617): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1617): Checking schedule, now: 1448876855148 next: 1448919022143
I/CheckinService( 1617): active receiver: disabled
,D/CheckinService( 1617): Recording last checkin time for package unspecified as 1448876855187
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1373): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2466): [236] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2466): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/GetConfigurationSnapshotOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1373): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1373): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/BaseAppContext( 1269): Using Auth Proxy for data requests.
,I/art     ( 1269): Explicit concurrent mark sweep GC freed 16575(1042KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 19MB/32MB, paused 1.154ms total 29.376ms
,E/DataBuffer( 1269): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8afe693)
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1373):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ActivityManager(  760): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3739 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Gmail   ( 3739): getAccountsCursor
,D/ActivityThread( 3739): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/art     ( 1373): Explicit concurrent mark sweep GC freed 70864(3MB) AllocSpace objects, 15(263KB) LOS objects, 40% free, 21MB/35MB, paused 983us total 38.518ms
,I/ActivityManager(  760): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=3768 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 3739): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/GCoreUlr( 1269): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,W/Gmail   ( 3739): Sync started for account: account:61035162
I/GCoreUlr( 1269): DispatchingService.onCreate()
,I/Gmail   ( 3739): getAccountsCursor
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 3768): EasService.onCreate
,I/Gmail   ( 3739): Observing account changes for notifications
,I/Exchange( 3768): RestartPingTask
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/art     (  760): Explicit concurrent mark sweep GC freed 27427(1138KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 981us total 54.637ms
,I/Exchange( 3768): RestartPingsTask did not start any pings.
,I/Exchange( 3768): PSS stopIfIdle
I/Exchange( 3768): PSS has no active accounts; stopping service.
,I/Exchange( 3768): onDestroy
,I/ActivityManager(  760): Killing 1464:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,E/SQLiteLog( 3739): (283) recovered 25 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/Gmail   ( 3739): notifyAccountChanged
,I/Gmail   ( 3739): getAccountsCursor
,I/Gmail   ( 3739): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3739): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3739): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3739): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  760): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=3820 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,W/libprocessgroup(  760): failed to open /acct/uid_10013/pid_1464/cgroup.procs: No such file or directory
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1269): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1269): Unbound from all location providers
,I/GCoreUlr( 1269): DispatchingService.onDestroy()
I/GCoreUlr( 1269): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1269): Unbound from all location providers
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Gmail   ( 3739): notifyAccountChanged
,I/ContactLocale( 3820): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Gmail   ( 3739): getAccountsCursor
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/Gmail   ( 3739): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11496, normalSync: true
,W/ResourcesManager( 3739): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3739): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,V/JNIHelp ( 3739): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 3739): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3739): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1373): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/ValidateNoPeople(  760): mEvictionCount: 0
,E/SQLiteLog( 3820): (284) automatic index on sqlite_sq_A3828C40(STAT_DATA_ID)
,E/SQLiteLog( 3820): (284) automatic index on sqlite_sq_A38281F0(STAT_DATA_ID)
,E/SQLiteLog( 3820): (284) automatic index on sqlite_sq_A3E18D30(STAT_DATA_ID)
,E/SQLiteLog( 3820): (284) automatic index on sqlite_sq_A3E182E0(STAT_DATA_ID)
,I/ActivityManager(  760): Killing 2916:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10015/pid_2916/cgroup.procs: No such file or directory
,I/art     ( 1617): Explicit concurrent mark sweep GC freed 40609(2MB) AllocSpace objects, 27(455KB) LOS objects, 40% free, 23MB/39MB, paused 796us total 53.773ms
,I/art     ( 1373): Explicit concurrent mark sweep GC freed 49320(2MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 20MB/33MB, paused 707us total 29.760ms
,I/GHttpClientFactory( 2556): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2556): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2556): Sync started
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NQFileLogger( 1373): [200] e.a: about to write to file
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/ProcessReports( 1373): [200] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,I/art     (  760): Explicit concurrent mark sweep GC freed 18128(729KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 827us total 50.240ms
,I/MusicSyncAdapter( 2556): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 2556): Periodic update
,W/MusicApiClient( 2556): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 2556): Sync ended
,I/MusicLeanback( 2556): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2556): Stop autocaching.
,W/ResourcesManager( 2967): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2967): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WearableService( 1269): callingUid 10008, callindPid: 1269
,D/WifiService(  760): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@29fbda2c}
,E/GmsUtils( 2556): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2556): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/Flag    ( 2967): Duration spec must be at least 2 characters long
,I/art     ( 3739): Explicit concurrent mark sweep GC freed 149343(5MB) AllocSpace objects, 15(263KB) LOS objects, 24% free, 18MB/25MB, paused 723us total 66.029ms
,E/DefaultHttpIssuer( 2967): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 2967): java.io.IOException
E/DefaultHttpIssuer( 2967): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 2967): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 2967): 	at dlq.a(PG:18080)
E/DefaultHttpIssuer( 2967): 	at dlt.run(PG:9611)
E/DefaultHttpIssuer( 2967): 	at dlr.run(PG:3031)
,E/BaseSyncManager( 2967): ClientFlagSyncException
E/BaseSyncManager( 2967): ccd$a: IO Exception opening: https://ssl.gstatic.com/docs/android/drive/client_flags?1448876859564= stream was reset: CANCEL
E/BaseSyncManager( 2967): 	at ccd.a(PG:1108)
E/BaseSyncManager( 2967): 	at dlq.a(PG:18060)
E/BaseSyncManager( 2967): 	at dlt.run(PG:9611)
E/BaseSyncManager( 2967): 	at dlr.run(PG:3031)
E/BaseSyncManager( 2967): Caused by: java.io.IOException: stream was reset: CANCEL
E/BaseSyncManager( 2967): 	at hzd.b(PG:145)
E/BaseSyncManager( 2967): 	at hya.b(PG:104)
E/BaseSyncManager( 2967): 	at hxn.d(PG:917)
E/BaseSyncManager( 2967): 	at hxn.a(PG:95)
E/BaseSyncManager( 2967): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 2967): 	at hvz.a(PG:50089)
E/BaseSyncManager( 2967): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 2967): 	at hvz.a(PG:3201)
E/BaseSyncManager( 2967): 	at clz.a(PG:127)
E/BaseSyncManager( 2967): 	at cjr.a(PG:47)
E/BaseSyncManager( 2967): 	at cjq.a(PG:22)
E/BaseSyncManager( 2967): 	at cjs.a(PG:68)
E/BaseSyncManager( 2967): 	at cjw.b(PG:92)
E/BaseSyncManager( 2967): 	at cjw.a(PG:80)
E/BaseSyncManager( 2967): 	at cju.b(PG:5140)
E/BaseSyncManager( 2967): 	at cju.a(PG:1096)
E/BaseSyncManager( 2967): 	at ccd.a(PG:2062)
E/BaseSyncManager( 2967): 	... 3 more
,I/Gmail   ( 3739): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 11566, normalSync: true
I/Gmail   ( 3739): lowestBackward conversation id 0
,I/Gmail   ( 3739): notifyAccountChanged
,I/Gmail   ( 3739): getAccountsCursor
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3739): notifyAccountChanged
,W/Gmail   ( 3739): Sync complete for account: account:61035162
,I/Gmail   ( 3739): getAccountsCursor
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 2791:com.android.defcontainer/u0a5 (adj 15): empty #17
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3739): getAccountsCursor
,W/libprocessgroup(  760): failed to open /acct/uid_10005/pid_2791/cgroup.procs: No such file or directory
,I/SyncAdapterService( 3367): Ignoring sync request for non-current account
,D/DelayedSyncController(  949): Delaying sync.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,W/BaseAppContext( 1617): Using Auth Proxy for data requests.
,I/ActivityManager(  760): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=3926 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 3926): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/Icing   ( 1617): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/Gmail   ( 3739): Backfilling search sequence table
,I/Icing   ( 1617): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,D/PlayMovies( 3926): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,D/PlayMovies( 3926): TransferService.onCreate:52 creating transfer service
,W/VideoCapabilities( 3926): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 3926): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 1617): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,D/WifiService(  760): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@29fbda2c}
,I/ActivityManager(  760): Killing 3142:com.android.settings/1000 (adj 15): empty #17
,I/art     ( 1373): Explicit concurrent mark sweep GC freed 16286(960KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 20MB/33MB, paused 793us total 34.046ms
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_3142/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=3981 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  760): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=3998 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3981): Sync request not initiated by GCP app. Dropping
,I/ActivityManager(  760): Killing 3532:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10076/pid_3532/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 3561:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_3561/cgroup.procs: No such file or directory
,E/Auth.Api.Credentials( 1617): [CredentialSyncAdapter] Unknown sync event.
,I/PlayMovies( 3926): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/art     (  760): Explicit concurrent mark sweep GC freed 31373(1367KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 1.197ms total 53.469ms
,I/CalendarSyncAdapter( 2090): Found no pending settings
,I/PlayMovies( 3926): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 3926): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  760): Killing 1856:com.google.android.talk/u0a54 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10054/pid_1856/cgroup.procs: No such file or directory
,I/GAV2    ( 3739): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/UpdateIcingCorporaServi( 1342): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,W/Launcher( 1236): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f37d2d9 new=com.google.android.velvet.VelvetApplication@3f37d2d9
,D/PackageBroadcastService( 1617): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/PeopleContactsSync( 1617): CP2 sync disabled
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  760): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/UpdateIcingCorporaServi( 1342): UpdateCorporaTask done [took 57 ms] updated apps [took 57 ms] 
,I/ActivityManager(  760): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=4063 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/BackupManagerService(  760): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 181us total 9.825ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.338ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.644ms
,V/BackupManagerService(  760): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  760): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37d85846
,I/GCoreNlp( 1269): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,V/GmsNetworkLocationProvi( 1269): DISABLE
,W/ResourcesManager( 4063): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1236): Deferring update until onResume
,W/ResourcesManager( 1236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1236): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1236): Deferring update until onResume
,I/Babel_SMS( 4063): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4063): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4063): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 4063): MmsConfig.loadFromDatabase
,I/Launcher( 1236): Deferring update until onResume
,I/Launcher( 1236): Deferring update until onResume
,E/Babel_SMS( 4063): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4063): MmsConfig.loadFromResources
,E/Babel_SMS( 4063): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4063): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4063): ApnsOta: OTA version -1
,I/Babel   ( 4063): deleted: false for 0
,W/Settings( 4063): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4063): startup - clean
,I/UpdateIcingCorporaServi( 1342): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1236): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f37d2d9 new=com.google.android.velvet.VelvetApplication@3f37d2d9
,D/PackageBroadcastService( 1617): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1617): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1617): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 4063): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4063): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4063): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4063): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4063): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4063): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4063): onServiceConnected
W/Babel   ( 4063): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4063): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4063): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4063): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/UpdateIcingCorporaServi( 1342): UpdateCorporaTask done [took 233 ms] updated apps [took 233 ms] 
,W/System  ( 4063): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4063): Installed default security provider GmsCore_OpenSSL
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/ActivityManager(  760): Killing 3327:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_3327/cgroup.procs: No such file or directory
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1064): run(),
I/Keyboard.Facilitator( 1064): flushDynamicLanguageModels()
,I/ConfigService( 1373): onCreate
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/ConfigService( 1373): onDestroy
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/ClearcutLoggerApiImpl( 1269): disconnect managed GoogleApiClient
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,E/DataBuffer( 1373): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@67b1156)
,E/DataBuffer( 1373): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32c5d7)
E/DataBuffer( 1373): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@292feec4)
,E/DataBuffer( 1373): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13c091ad)
E/DataBuffer( 1373): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e2eece2)
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/ClearcutLoggerApiImpl( 1617): disconnect managed GoogleApiClient
,I/ClearcutLoggerApiImpl( 1373): disconnect managed GoogleApiClient
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector connect called
I/jxcore-log( 3043): 
I/jxcore-log( 3043): Coordinator is now connected to the server!
I/jxcore-log( 3043): 
,I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 3184:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10071/pid_3184/cgroup.procs: No such file or directory
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1373): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UdcCache:FPQuery( 1617): Bootstrapping UDC settings cache for all accounts
,I/ActivityManager(  760): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=4157 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 4157): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4157): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4157): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/art     (  760): Explicit concurrent mark sweep GC freed 29394(1322KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 949us total 55.278ms
,W/System  ( 4157): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4157): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 4157): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4218): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1865296290.jar --oat-fd=27 --oat-location=/data/data/com.google.android.youtube/cache/ads-1865296290.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4218): dex2oat took 40.920ms (threads: 4)
,W/InstanceID/Rpc( 4157): Found 10008
,I/ActivityManager(  760): Killing 3768:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_3768/cgroup.procs: No such file or directory
,I/jxcore-log( 3043): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector command called
I/jxcore-log( 3043): 
I/jxcore-log( 3043): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"B4:CE:F6:AB:A4
,I/jxcore-log( 3043): Start now : testSendData.js
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): check server
I/jxcore-log( 3043): 
I/jxcore-log( 3043): serverPort is 50737
I/jxcore-log( 3043): 
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT7441
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3043): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): setState: INITIALIZED
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT7441","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): start: OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): setState: RUNNING
I/jxcore-log( 3043): StartBroadcasting started ok
I/jxcore-log( 3043): 
I/jxcore-log( 3043): do fake peer & start
I/jxcore-log( 3043): 
I/jxcore-log( 3043): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:53:32.230Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:53:32.231Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:53:32.231Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to null in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: null 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to null in address 50:2E:6C:AC:21:50
,I/jxcore-log( 3043): 2015-11-30T09:53:32.236Z SendDataTCPServer.js: TCP/IP server is bound to port: 50737
I/jxcore-log( 3043): 
I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3119): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3119): Entering PendingCommandState State
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest: pid=4283 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3119): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32421c20:true
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
I/ActivityManager(  760): Killing 3584:com.google.android.gms.unstable/u0a8 (adj 15): empty #17
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 280)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 280)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 280)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 80 bytes successfully (thread ID: 280)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 280)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4944
,I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 44516
I/BtConnectorHelper( 3043): Request socket is using : 44516
I/BtToRequestSocket( 3043): Now accepting connections
,W/libprocessgroup(  760): failed to open /acct/uid_10008/pid_3584/cgroup.procs: No such file or directory
,I/BluetoothBondStateMachine( 3119): StableState(): Entering Off State
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :44516
,I/jxcore-log( 3043): 2015-11-30T09:53:35.645Z SendDataConnector.js: CLIENT connected to 44516, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:53:35.646Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 44516
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T09:53:35.695Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3043): 2015-11-30T09:53:36.251Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 3043): 2015-11-30T09:53:36.295Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14806
,I/jxcore-log( 3043): 2015-11-30T09:53:36.311Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:36.352Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2926
,I/jxcore-log( 3043): 2015-11-30T09:53:36.398Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:36.403Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:36.446Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:36.450Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:36.490Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3043): 
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3119): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
,E/bt-btif ( 3119): check_cod: remote_cod = 0x5a020c
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
,W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3119): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 3119): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3119): StableState(): Entering Off State
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 284)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 77 bytes successfully (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 284
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 284)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 284)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT9919 34:FC:EF:11:B1:66]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, LGE-Nexus 5_PT9919
,I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/jxcore-log( 3043): 2015-11-30T09:53:38.856Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T09:53:39.768Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:39.778Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:39.898Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:39.967Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.013Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.028Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.036Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.044Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.084Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.097Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.103Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.133Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.142Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.162Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.184Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.222Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.230Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.265Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.278Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.311Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.328Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.361Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.364Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.401Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.424Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:53:40.463Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3043): 
,W/bt-btif ( 3119): invalid rfc slot id: 4
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT9919
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT9919
I/BtToSocketBase( 3043): Close LocalOutputStream
,I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/jxcore-log( 3043): 2015-11-30T09:53:40.528Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3119): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3119): RFCOMM_DisconnectInd LCID:0x44
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@224df9e:true
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/chromium(  949): [WARNING:server_connection_manager.cc(296)] ServerConnectionManager forcing SYNC_AUTH_ERROR
W/chromium(  949): [WARNING:syncer_proto_util.cc(280)] Error posting from syncer: Response Code (bogus on error): -1 Content-Length (bogus on error): -1 Server Status: SYNC_AUTH_ERROR
,E/chromium(  949): [ERROR:get_updates_processor.cc(243)] PostClientToServerMessage() failed during GetUpdates
,I/jxcore-log( 3043): 2015-11-30T09:54:26.493Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:26.495Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:26.497Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:26.498Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:26.499Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3043): 2015-11-30T09:54:31.500Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:54:31.505Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3043): 2015-11-30T09:54:36.513Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:36.514Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:36.514Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:36.515Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 289)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 80 bytes successfully (thread ID: 289)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 289)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 57549
I/BtConnectorHelper( 3043): Request socket is using : 57549
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :57549
I/jxcore-log( 3043): 2015-11-30T09:54:38.103Z SendDataConnector.js: CLIENT connected to 57549, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:54:38.103Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:54:38.106Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 57549
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
,W/bt-btif ( 3119): proc dm_pm_timer expires
,I/jxcore-log( 3043): 2015-11-30T09:55:28.199Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:55:28.200Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:55:28.206Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:55:28.207Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:55:28.208Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3043): 2015-11-30T09:55:33.208Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:55:33.209Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3043): 2015-11-30T09:55:38.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:55:38.215Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:55:38.216Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:55:38.216Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 294)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 80 bytes successfully (thread ID: 294)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 294)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4944
,I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 53245
I/BtConnectorHelper( 3043): Request socket is using : 53245
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :53245
I/jxcore-log( 3043): 2015-11-30T09:55:39.937Z SendDataConnector.js: CLIENT connected to 53245, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:55:39.938Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 53245
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T09:55:39.962Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,I/jxcore-log( 3043): 2015-11-30T09:56:30.027Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:56:30.028Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:56:30.029Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:56:30.030Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:56:30.038Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3043): Disconnect outgoing peer: HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3043): Stop ReceivingThread
,I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 3043): 2015-11-30T09:56:35.037Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:56:35.037Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3043): 2015-11-30T09:56:40.041Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:56:40.041Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:56:40.042Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:56:40.042Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 299)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 80 bytes successfully (thread ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 299)
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 47391
I/BtConnectorHelper( 3043): Request socket is using : 47391
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :47391
I/jxcore-log( 3043): 2015-11-30T09:56:40.984Z SendDataConnector.js: CLIENT connected to 47391, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:56:40.985Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 47391
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T09:56:40.988Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
,W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): invalid rfc slot id: 9
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,I/BtConnectorHelper( 3043): Disconnect outgoing peer: HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3043): 2015-11-30T09:57:31.071Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:31.072Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:31.072Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:31.073Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:31.074Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:57:36.074Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:36.075Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:57:36.076Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:57:41.084Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:41.085Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:41.086Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:41.086Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC One_M8 50:2E:6C:AC:21:50
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC One_M8 in address 50:2E:6C:AC:21:50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 80 bytes successfully (thread ID: 304)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 304)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [50:2E:6C:AC:21:50 HTC-HTC One_M8_PT4944 50:2E:6C:AC:21:50]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC One_M8_PT4944
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 50248
I/BtConnectorHelper( 3043): Request socket is using : 50248
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :50248
I/jxcore-log( 3043): 2015-11-30T09:57:42.427Z SendDataConnector.js: CLIENT connected to 50248, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:57:42.427Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 50248
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T09:57:42.429Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
,W/bt-btif ( 3119): proc dm_pm_timer expires
,I/jxcore-log( 3043): 2015-11-30T09:58:32.505Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:32.505Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:32.507Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:32.527Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:32.528Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:32.529Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/BtConnectorHelper( 3043): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3043): Close LocalOutputStream
,I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToRequestSocket( 3043): Close server socket
,I/jxcore-log( 3043): 2015-11-30T09:58:32.559Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): ---- round done--------
I/jxcore-log( 3043): 
I/jxcore-log( 3043): ---- gotta redo : 50:2E:6C:AC:21:50, try count now: 1
I/jxcore-log( 3043): 
I/jxcore-log( 3043): do fake peer & start
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:32.561Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:32.561Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:32.561Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: null E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 2015-11-30T09:58:32.564Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 50:2E:6C:AC:21:50 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3119): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3119): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3119): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3119): StableState(): Entering Off State
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 309)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 82 bytes successfully (thread ID: 309)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 309)
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 35561
I/BtConnectorHelper( 3043): Request socket is using : 35561
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :35561
I/jxcore-log( 3043): 2015-11-30T09:58:34.859Z SendDataConnector.js: CLIENT connected to 35561, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:58:34.859Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 35561
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T09:58:34.885Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC One_M8
,I/jxcore-log( 3043): 2015-11-30T09:58:37.968Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:38.015Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:38.987Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:38.994Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:39.145Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:39.220Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:39.301Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:39.394Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:39.402Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
,W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3119): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3119): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3119): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3119): StableState(): Entering Off State
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 313)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 313
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 313)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 313)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, motorola-XT1072_PT8991
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
,I/jxcore-log( 3043): 2015-11-30T09:58:58.458Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T09:58:59.265Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.275Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.281Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.295Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.301Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.308Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.318Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.353Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.361Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.378Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.412Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.426Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.437Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.472Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.478Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.496Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.535Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.548Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.585Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.597Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.637Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.647Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.691Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.707Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.744Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.751Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:58:59.757Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3043): 
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3043): 2015-11-30T09:59:29.402Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:29.403Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:29.404Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:29.405Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:59:29.406Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3043): Disconnect outgoing peer: samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3043): 2015-11-30T09:59:34.407Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:34.407Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3043): 2015-11-30T09:59:39.414Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:39.415Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:39.416Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:39.416Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 82 bytes successfully (thread ID: 318)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 318)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 33034
I/BtConnectorHelper( 3043): Request socket is using : 33034
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :33034
I/jxcore-log( 3043): 2015-11-30T09:59:40.524Z SendDataConnector.js: CLIENT connected to 33034, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T09:59:40.525Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T09:59:40.535Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 33034
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
,W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
,W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): invalid rfc slot id: 6
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
,I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/jxcore-log( 3043): 2015-11-30T09:59:50.104Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,W/bt-rfcomm( 3119): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3119): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
,W/bt-btif ( 3119): proc dm_pm_timer expires
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4405 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 4405): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4405):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4405):   adb logcat -s GAv4
,W/GAv4    ( 4405): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4405): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4405): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  760): Killing 2556:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2556/cgroup.procs: No such file or directory
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 322)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 322
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 322)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 322)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, motorola-XT1072_PT8991
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/jxcore-log( 3043): 2015-11-30T10:00:03.737Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T10:00:04.132Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:00:04.140Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:00:04.149Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:00:04.157Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3043): 2015-11-30T10:00:30.624Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:30.624Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:00:30.626Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:30.626Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:30.627Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): Stop ReceivingThread
,I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
,I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
,I/BtToSocketBase( 3043): Close bt socket
,I/BtToRequestSocket( 3043): Close server socket
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3043): 2015-11-30T10:00:35.627Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:35.628Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3043): 2015-11-30T10:00:40.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:40.633Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:40.633Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:40.634Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 327)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 82 bytes successfully (thread ID: 327)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 327)
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 35754
I/BtConnectorHelper( 3043): Request socket is using : 35754
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :35754
I/jxcore-log( 3043): 2015-11-30T10:00:41.959Z SendDataConnector.js: CLIENT connected to 35754, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:00:41.959Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:00:41.966Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 35754
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): invalid rfc slot id: 12
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3043): 2015-11-30T10:00:54.596Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,W/bt-rfcomm( 3119): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3119): RFCOMM_DisconnectInd LCID:0x41
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
,W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 331)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 331
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 331)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, motorola-XT1072_PT8991
,I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
,I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
,I/jxcore-log( 3043): 2015-11-30T10:01:06.167Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T10:01:06.545Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:01:06.554Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:01:06.562Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:01:06.568Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data,
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3043): 2015-11-30T10:01:32.041Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:01:32.042Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:32.047Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:32.048Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:32.049Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3043): Disconnect outgoing peer: samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): Stop ReceivingThread
,I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3043): 2015-11-30T10:01:37.049Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:37.050Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3043): 2015-11-30T10:01:42.058Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:42.059Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:42.059Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:42.060Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 82 bytes successfully (thread ID: 336)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 336)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
,I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 52023
I/BtConnectorHelper( 3043): Request socket is using : 52023
,I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :52023
I/jxcore-log( 3043): 2015-11-30T10:01:43.627Z SendDataConnector.js: CLIENT connected to 52023, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:01:43.627Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 52023
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T10:01:43.651Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): invalid rfc slot id: 14
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
,I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
,I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/jxcore-log( 3043): 2015-11-30T10:01:58.011Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,W/bt-rfcomm( 3119): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3119): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 340)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 340
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 340)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, motorola-XT1072_PT8991
,I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
,I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/jxcore-log( 3043): 2015-11-30T10:02:08.043Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
,I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T10:02:08.446Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:02:08.455Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:02:08.462Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:02:08.469Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3043): 2015-11-30T10:02:33.716Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:33.717Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:33.718Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:33.719Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:02:33.720Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
,I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3043): 2015-11-30T10:02:38.724Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:38.725Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:02:43.728Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:43.728Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:43.729Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:43.729Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: Note3-1 E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to Note3-1 in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 345)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 345)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 82 bytes successfully (thread ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT4028 E0:DB:10:1F:C9:5E]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, samsung-SM-N9005_PT4028
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 43798
I/BtConnectorHelper( 3043): Request socket is using : 43798
,I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :43798
I/jxcore-log( 3043): 2015-11-30T10:02:46.123Z SendDataConnector.js: CLIENT connected to 43798, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:02:46.123Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 43798
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T10:02:46.146Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 1
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): invalid rfc slot id: 16
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Stop ReceivingThread
,I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Close bt socket
,I/jxcore-log( 3043): 2015-11-30T10:02:58.603Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,W/bt-rfcomm( 3119): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
W/bt-rfcomm( 3119): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 349)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 349
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 349)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 349)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, motorola-XT1072_PT8991
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
,I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T10:03:10.037Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:10.411Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:10.415Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:10.420Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:10.429Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:10.436Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): invalid rfc slot id: 18
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,D/BluetoothMapService( 3119): onReceive
,I/jxcore-log( 3043): 2015-11-30T10:03:28.706Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/GCM     ( 1373): Heartbeat timeout, GCM connection reset -31
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 30 Nov 2015 10:03:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448877811995], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448877811980]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Validated
,D/ConnectivityService(  760): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  760): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524290
,I/jxcore-log( 3043): 2015-11-30T10:03:36.216Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:36.217Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:36.218Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:36.236Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:36.237Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:36.238Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/BtConnectorHelper( 3043): Disconnect outgoing peer: E0:DB:10:1F:C9:5E
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3043): Close LocalOutputStream
,I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,I/jxcore-log( 3043): 2015-11-30T10:03:36.280Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3043): 
I/jxcore-log( 3043): ---- round done--------
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3043): 
I/jxcore-log( 3043): do fake peer & start
I/jxcore-log( 3043): 
I/jxcore-log( 3043): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:36.281Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:36.281Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:36.281Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/jxcore-log( 3043): 2015-11-30T10:03:36.283Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3119): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3119): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3119): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3119): StableState(): Entering Off State
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 354)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 84 bytes successfully (thread ID: 354)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 354)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT5686
,I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 49429
,I/BtConnectorHelper( 3043): Request socket is using : 49429
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :49429
I/jxcore-log( 3043): 2015-11-30T10:03:40.738Z SendDataConnector.js: CLIENT connected to 49429, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:03:40.739Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 49429
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T10:03:40.762Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.343Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3043): 2015-11-30T10:03:41.468Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.523Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.565Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.632Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.687Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.709Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.799Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:03:41.848Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,I/jxcore-log( 3043): 2015-11-30T10:04:31.850Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:04:31.853Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:04:31.859Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:04:31.860Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:04:31.863Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: HTC-HTC Desire 820_PT5686
,I/BtToSocketBase( 3043): Stop ReceivingThread
,I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,I/jxcore-log( 3043): 2015-11-30T10:04:36.863Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:04:36.864Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3043): 2015-11-30T10:04:41.868Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:04:41.869Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:04:41.874Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:04:41.874Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 84 bytes successfully (thread ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 359)
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 36600
,I/BtConnectorHelper( 3043): Request socket is using : 36600
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :36600
I/jxcore-log( 3043): 2015-11-30T10:04:44.397Z SendDataConnector.js: CLIENT connected to 36600, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:04:44.397Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 36600
I/BtToRequestSocket( 3043): Set local streams
,I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T10:04:44.430Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3043): 2015-11-30T10:05:34.486Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:34.487Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:34.488Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:34.489Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:34.490Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3043): 2015-11-30T10:05:39.490Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:39.492Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:05:44.496Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:44.496Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:44.497Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:44.497Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 364)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 364)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 84 bytes successfully (thread ID: 364)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 364)
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 59161
I/BtConnectorHelper( 3043): Request socket is using : 59161
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :59161
I/jxcore-log( 3043): 2015-11-30T10:05:46.184Z SendDataConnector.js: CLIENT connected to 59161, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:05:46.184Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:05:46.186Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 59161
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,I/UsageStatsService(  760): User[0] Flushing usage stats to disk
,I/jxcore-log( 3043): 2015-11-30T10:06:36.266Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:36.267Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:36.268Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:36.269Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:36.270Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: HTC-HTC Desire 820_PT5686
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
,I/BtToSocketBase( 3043): Close bt socket
,I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/jxcore-log( 3043): 2015-11-30T10:06:41.273Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:41.275Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3043): 2015-11-30T10:06:46.282Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:46.283Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:46.284Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:06:46.284Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3119): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:24, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnectionFailed: Cancelled: Connection timeout [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/jxcore-log( 3043): 2015-11-30T10:07:16.325Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:16.326Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:07:16.327Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
W/jxcore-log( 3043): $$jxcore_callback_32 wasn't registered
W/jxcore-log( 3043): 
,W/bt-sdp  ( 3119): SDP - Rcvd conn cnf with error: 0x22  CID 0x49
E/bt-btif ( 3119): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3119): invalid rfc slot id: 24
,I/jxcore-log( 3043): 2015-11-30T10:07:21.335Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:21.336Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:07:26.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:26.341Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:26.341Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:26.342Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: HTC Desire 820 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to HTC Desire 820 in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3119): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:25, channel:-1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnectionFailed: Cancelled: Connection timeout [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT5686 80:01:84:8A:B3:68]
I/jxcore-log( 3043): 2015-11-30T10:07:56.374Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:56.375Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:07:56.397Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:56.398Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:07:56.404Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3043): 
I/jxcore-log( 3043): ---- round done--------
I/jxcore-log( 3043): 
I/jxcore-log( 3043): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3043): 
I/jxcore-log( 3043): do fake peer & start
I/jxcore-log( 3043): 
I/jxcore-log( 3043): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:56.407Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:56.408Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:56.408Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 2015-11-30T10:07:56.422Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:56.423Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:07:56.424Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3119): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:2, scn:-410251085
W/bt-btif ( 3119): invalid rfc slot id: 26
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): shutdown
W/jxcore-log( 3043): $$jxcore_callback_36 wasn't registered
W/jxcore-log( 3043): 
,W/bt-sdp  ( 3119): SDP - Rcvd conn cnf with error: 0x8  CID 0x4c
E/bt-btif ( 3119): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3119): invalid rfc slot id: 25
,I/jxcore-log( 3043): 2015-11-30T10:08:01.424Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:08:01.425Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:06.429Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:08:06.430Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:06.433Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:06.434Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, motorola-XT1072_PT8991
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 56847
I/BtConnectorHelper( 3043): Request socket is using : 56847
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :56847
I/jxcore-log( 3043): 2015-11-30T10:08:10.077Z SendDataConnector.js: CLIENT connected to 56847, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:08:10.077Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 56847
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T10:08:10.097Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3043): 2015-11-30T10:08:10.780Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:16786
,I/jxcore-log( 3043): 2015-11-30T10:08:10.811Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:10.815Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3043): 2015-11-30T10:08:10.894Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3043): 
,D/        ( 3119): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1936
,I/jxcore-log( 3043): 2015-11-30T10:08:10.918Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:10.964Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:10.970Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:11.025Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3119): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3119): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3119): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3119): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3119): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3119): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3119): StableState(): Entering Off State
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 376)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 82 bytes successfully (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 376
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, samsung-SM-A300FU_PT406
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
,I/jxcore-log( 3043): 2015-11-30T10:08:35.945Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T10:08:36.664Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:36.676Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:36.747Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:36.757Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:36.766Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:36.770Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:36.862Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:36.923Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.003Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.081Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.090Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.125Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.162Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.227Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.237Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.245Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.327Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.362Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.424Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.587Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.596Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.673Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.712Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.751Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.759Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.768Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.848Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.884Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.925Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:37.934Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.006Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.036Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.184Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.272Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.285Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.365Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.450Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.484Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.618Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.627Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.807Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.886Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:38.922Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:39.162Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3043): 
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,I/jxcore-log( 3043): 2015-11-30T10:08:39.327Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:39.337Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:39.406Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:39.444Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:39.704Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:39.764Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:08:39.773Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3043): 2015-11-30T10:09:01.024Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:01.025Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:01.026Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:01.027Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:01.028Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,I/jxcore-log( 3043): 2015-11-30T10:09:06.027Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:06.027Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:09:11.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:11.031Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:11.031Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:11.032Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 381)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 381)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 381)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
,I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, motorola-XT1072_PT8991
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 381)
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 36667
I/BtConnectorHelper( 3043): Request socket is using : 36667
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :36667
I/jxcore-log( 3043): 2015-11-30T10:09:14.204Z SendDataConnector.js: CLIENT connected to 36667, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:09:14.204Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 36667
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,I/jxcore-log( 3043): 2015-11-30T10:09:14.226Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 1
W/bt-btif ( 3119): proc dm_pm_timer expires
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): invalid rfc slot id: 20
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT406
,I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3043): 2015-11-30T10:09:29.604Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
,W/bt-btif ( 3119): bta_dm_check_av:0
W/bt-rfcomm( 3119): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3119): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: A3-1
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: A3-1
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Incoming connection initialized (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 385)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesRead: Read 82 bytes successfully (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Got valid identity from [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): removeThreadFromList: Removing thread with ID 385
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Handshake thread disposed (thread ID: 385)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 385)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT406 08:EC:A9:50:75:41]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : true, samsung-SM-A300FU_PT406
,I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BTConnectedThread
,I/BtConnectorHelper( 3043): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3043): --DoOneRunRound started
,I/jxcore-log( 3043): 2015-11-30T10:09:41.885Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): LocalHost address: localhost/127.0.0.1, port: 50737
,I/BtToRequestSocket( 3043): --DoOneRunRound ended
,I/jxcore-log( 3043): 2015-11-30T10:09:42.449Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:09:42.461Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:09:42.468Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:09:42.661Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3043): 
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,I/jxcore-log( 3043): 2015-11-30T10:10:04.304Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:04.305Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:04.306Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:04.307Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:04.307Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3043): 
,I/BtToSocketBase( 3043): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3043): Disconnect outgoing peer: motorola-XT1072_PT8991
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToRequestSocket( 3043): Close server socket
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=0
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,I/art     (  760): Explicit concurrent mark sweep GC freed 25974(1380KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.069ms total 110.490ms
,I/jxcore-log( 3043): 2015-11-30T10:10:09.307Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:09.308Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): timeout now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): dun
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): done, now sending data to server
I/jxcore-log( 3043): 
I/jxcore-log( 3043): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): -- RESULT DATA {"name:":"LGE-Nexus 5_PT7441","time":1000072,"result":"TIMEOUT","sendList":[{"connections":1,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"F8:CF:C5:D9:E5:61","time":0,"result":"Fail"},{"connections":0,"name":"F4:F1:E1:5C:3B:E2","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name
I/jxcore-log( 3043): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 3043): 
I/jxcore-log( 3043): Results list does not contain any items
I/jxcore-log( 3043): 
I/jxcore-log( 3043): sendList failed peers count : 4 [100 %]
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 44:80:EB:7B:5A:05, Tried : 1
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): - Peer ID : 50:2E:6C:AC:21:50, Tried : 1
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
I/jxcore-log( 3043): 
I/jxcore-log( 3043): sendList never tried peers count : 17 [80.95238095238095 %]
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 08:EC:A9:50:75:41
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 00:F4:6F:30:E0:6C
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): - Peer ID : 34:FC:EF:11:B1:66
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 58:2A:F7:ED:96:BE
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 7C:F9:0E:51:18:22
I/jxcore-log( 3043): 
I/jxcore-log( 3043): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:10:12.304Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:12.305Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:10:12.306Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
,I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3119): invalid rfc slot id: 28
,I/BtToSocketBase( 3043): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3043): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT406
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3043): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3043): 2015-11-30T10:10:12.836Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3043): 
,W/bt-rfcomm( 3119): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0
W/bt-rfcomm( 3119): RFCOMM_DisconnectInd LCID:0x45
,I/jxcore-log( 3043): 2015-11-30T10:10:14.313Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:14.314Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:14.315Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:14.315Z SendDataConnector.js: do connect now
I/jxcore-log( 3043): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Trying to start connecting to XT1072 in address 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnecting: XT1072 44:80:EB:7B:5A:05
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): connect: Started connecting to XT1072 in address 44:80:EB:7B:5A:05
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Trying to connect...
W/BluetoothAdapter( 3043): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3119): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3119): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3119): bta_dm_check_av:0
,W/bt-btif ( 3119): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3119): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3119): onReceive
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: A3-1
,W/bt-btif ( 3119): info:x10
,D/        ( 3119): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1342): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1342): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3119): process_service_search_attr_rsp
,W/bt-btif ( 3119): new conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3119): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Outgoing connection initialized (thread ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesWritten: 77 bytes successfully written (thread ID: 390)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Entering thread (ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): onBytesRead: Read 81 bytes successfully (thread ID: 390)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3043): Handshake succeeded with [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3043): Exiting thread (ID: 390)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT8991 44:80:EB:7B:5A:05]
I/BtConnectorHelper( 3043): Starting the connected thread incoming : false, motorola-XT1072_PT8991
I/BtToSocketBase( 3043): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3043): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3043): mHTTPPort  set to : 47120
I/BtConnectorHelper( 3043): Request socket is using : 47120
I/BtToRequestSocket( 3043): Now accepting connections
,I/BtConnectorHelper( 3043): Calling ConnectionStatusUpdate with port :47120
I/jxcore-log( 3043): 2015-11-30T10:10:17.570Z SendDataConnector.js: CLIENT connected to 47120, error: null
I/jxcore-log( 3043): 
I/jxcore-log( 3043): 2015-11-30T10:10:17.570Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:10:17.579Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3043): 
,I/BtToRequestSocket( 3043): incoming data from: /127.0.0.1, port: 47120
I/BtToRequestSocket( 3043): Set local streams
I/BtToRequestSocket( 3043): rin ended ---------------------------;
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3119): dm_pm_timer expires
W/bt-btif ( 3119): dm_pm_timer expires 0
W/bt-btif ( 3119): proc dm_pm_timer expires
,I/jxcore-log( 3043): DBG, CoordinatorConnector command called
I/jxcore-log( 3043): 
I/jxcore-log( 3043): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): stop tests now !
I/jxcore-log( 3043): 
I/jxcore-log( 3043): stop current!
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): testSendData stopped
I/jxcore-log( 3043): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Shutting down...
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3043): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3043): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): setState: INITIALIZED
I/BtConnectorHelper( 3043): Disconnect:::Stop : BtToRequestSocket :Thread-391
I/BtToSocketBase( 3043): Stop ReceivingThread
I/BtToSocketBase( 3043): Stop SendingThread
I/BtToSocketBase( 3043): Close local in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3043): Close LocalOutputStream
I/BtToSocketBase( 3043): Close localHostSocket
I/BtToSocketBase( 3043): Close bt in
,I/BtToSocketBase( 3043): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3043): Close bt out
I/BtToSocketBase( 3043): Close bt socket
,I/BtToRequestSocket( 3043): Close server socket
,I/jxcore-log( 3043): StopBroadcasting went ok
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): 2015-11-30T10:10:45.906Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3043): 
I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onConnectionFailed: Socket is null
,W/jxcore-log( 3043): $$jxcore_callback_43 wasn't registered
W/jxcore-log( 3043): 
W/jxcore-log( 3043): $$jxcore_callback_43 wasn't registered
W/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector command called
I/jxcore-log( 3043): 
I/jxcore-log( 3043): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"44:80:EB:7B:5A:05\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"50:2E:6C:AC:21:50\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"E0:DB:10:1F:C9:5E\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"}],\"notTriedList\":[{\"connections\":0,\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"08:EC:A9:50:76:27\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"E0:DB:10:14:E2:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"F8:95:C7:87:85:54\",\"time\":0,\"result\":\"Fail\"},{\"connections\":0,\"name\":\"34:FC:EF:9D:93:0B\",\"tim
I/jxcore-log( 3043): ****TEST TOOK:  ms ****
I/jxcore-log( 3043): 
I/jxcore-log( 3043): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3043): 
I/jxcore-log( 3043): stop tests now !
I/jxcore-log( 3043): 
I/jxcore-log( 3043): end, event received
I/jxcore-log( 3043): 
I/jxcore-log( 3043): CoordinatorConnector close called
I/jxcore-log( 3043): 
,I/jxcore-log( 3043): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3043): 
I/jxcore-log( 3043): The Coordinator has disconnected!
I/jxcore-log( 3043): 
I/jxcore-log( 3043): The Coordinator has closed!
I/jxcore-log( 3043): 
I/jxcore-log( 3043): stop tests now !
I/jxcore-log( 3043): 
I/jxcore-log( 3043): turning Radios off
I/jxcore-log( 3043): 
I/jxcore-log( 3043): Toggling radios to false
I/jxcore-log( 3043): 
D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@217cda4c mBinding = false
,D/BluetoothManagerService(  760): Message: 2
D/BluetoothManagerService(  760): Sending off request.
D/BluetoothAdapterState( 3119): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3119): Setting state to 13
I/BluetoothAdapterState( 3119): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3119): onBluetoothDisable()
I/BluetoothAdapterState( 3119): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3119): Scan Mode:20
,D/BluetoothAdapterState( 3119): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,E/BtOppRfcommListener( 3119): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3119): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothMapMasInstance( 3119): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3119): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3119): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3119): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3119): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3119): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3119): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3119): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,W/bt-l2cap( 3119): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3119): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3119): onReceive
D/BluetoothMapService( 3119): STATE_TURNING_OFF
V/BluetoothMapService( 3119): Handler(): got msg=4
D/BluetoothMapService( 3119): MAP Service closeService in
D/BluetoothMapMasInstance( 3119): MAP Service shutdown
,V/BluetoothMapService( 3119): MAP Service closeService out
,I/BtOppRfcommListener( 3119): stopping Accept Thread
,I/BtOppRfcommListener( 3119): BluetoothSocket listen thread finished
,W/bt-btif ( 3119): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,D/WifiService(  760): setWifiEnabled: false pid=3043, uid=10270
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 4283): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  760): Message: 30
,I/jxcore-log( 3043): Radios toggled
I/jxcore-log( 3043): 
I/chromium( 3043): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onBluetoothAdapterScanModeChanged: Mode changed to 20
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onBluetoothAdapterScanModeChanged: Bluetooth disabled, stopping...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): setState: WAITING_FOR_SERVICES_TO_BE_ENABLED
,D/BluetoothManagerService(  760): Message: 30
E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/LocalBluetoothProfileManager( 4283): Adding local MAP profile
D/BluetoothMap( 4283): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,E/native  (  760): do suspend true
,D/BluetoothManagerService(  760): Message: 30
,D/CommandListener(  179): Clearing all IP addresses on wlan0
,D/LocalBluetoothProfileManager( 4283): LocalBluetoothProfileManager construction complete
D/DockEventReceiver( 4283): finishStartingService: stopping service
,V/NativeCrypto( 1373): Read error: ssl=0x9a5de200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1373): SSL shutdown failed: ssl=0x9a5de200: I/O error during system call, Broken pipe
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,E/WifiStateMachine(  760): scanCount==0 - aborting
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/WifiScanningService(  760): SCAN_AVAILABLE : 1
D/RttService(  760): SCAN_AVAILABLE : 1
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/native  (  760): do suspend true
,D/WifiService(  760): New client listening to asynchronous messages
,D/RttService(  760): EnabledState got{ when=-11ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3043): onWifiStateChanged: State changed to 1
,D/WifiScanningService(  760): StartedState got{ when=-17ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  760): DefaultState
,D/CommandListener(  179): Clearing all IP addresses on wlan0
D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524292
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1180): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1617): CM callback handler got msg 524292
D/AuthorizationBluetoothService( 1373): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/BluetoothInputDevice( 4283): Proxy object connected
,D/HidProfile( 4283): Bluetooth service connected
,D/BluetoothPan( 4283): BluetoothPAN Proxy object connected
,D/PanProfile( 4283): Bluetooth service connected
D/BluetoothMap( 4283): Proxy object connected
,D/MapProfile( 4283): Bluetooth service connected
D/BluetoothMap( 4283): getConnectedDevices()
,D/BluetoothMap( 4283): Bluetooth is Not enabled
,D/AndroidRuntime( 4554): 
D/AndroidRuntime( 4554): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4554): CheckJNI is OFF
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=4590 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 3136): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3136): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/AndroidRuntime( 4554): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 3043:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  760): Skipping PackageSetting{91a9d08 com.example.hello/10277} due to missing metadata
,I/WindowState(  760): WIN DEATH: Window{3376b0e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,D/Tethering(  760): InitialState.processMessage what=4
,I/wpa_supplicant( 3136): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{287fb74f u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  760): Spurious death for ProcessRecord{392fb726 3043:com.test.thalitest/u0a270}, curProc for 3043: null
D/Tethering(  760): sendTetherStateChangedBroadcast 0, 0, 0
,I/ActivityManager(  760): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  760):   Force finishing activity ActivityRecord{287fb74f u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  760): Duplicate finish request for ActivityRecord{287fb74f u0 com.test.thalitest/.MainActivity t214 f}
,W/GeofencerStateMachine( 1269): Ignoring removeGeofence because network location is disabled.
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1064): resetDictionaries() : en_US
,W/Settings( 4063): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1236): Explicit concurrent mark sweep GC freed 9358(597KB) AllocSpace objects, 3(288KB) LOS objects, 37% free, 26MB/42MB, paused 716us total 55.921ms
,I/LibraryLoader( 1441): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/art     (  760): Explicit concurrent mark sweep GC freed 19051(1241KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.130ms total 71.632ms
I/art     (  760): WaitForGcToComplete blocked for 60.374ms for cause Explicit
W/Settings( 1269): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1342): Explicit concurrent mark sweep GC freed 47003(2MB) AllocSpace objects, 6(96KB) LOS objects, 25% free, 19MB/25MB, paused 342us total 89.115ms
,I/Keyboard.Facilitator.DecoderInitializer( 1064): run()
,I/OpenGLRenderer(  949): Initialized EGL, version 1.4
I/Decoder ( 1064): createOrResetDecoder
,D/OpenGLRenderer(  949): Enabling debug mode 0
,I/LibraryLoader( 1441): Time to load native libraries: 69 ms (timestamps 6650-6719)
I/LibraryLoader( 1441): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1441): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ConfigService( 1373): onCreate
,W/art     ( 1441): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1441): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     (  949): Attempt to remove local handle scope entry from IRT, ignoring
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,W/InputMethodManagerService(  760): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@a256041 (uid=10034 pid=949)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): run()
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 3043 uid 10270
,I/Keyboard.Facilitator( 1064): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1064): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = contacts
,I/art     (  760): Explicit concurrent mark sweep GC freed 6246(334KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.720ms total 184.859ms
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Missing File = Contacts.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1064): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1064): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1064): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1064): run()
I/StatsUtilsManager( 1064): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1064): shouldRecordStats() = Too Soon
,I/Launcher( 1236): Deferring update until onResume
,D/VoicemailCleanupService( 3820): Cleaning up data for package: com.test.thalitest
W/ResourcesManager( 1236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1236): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4641 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/Launcher( 1236): Deferring update until onResume
,D/AndroidRuntime( 4554): Shutting down VM
,I/ActivityManager(  760): Killing 3739:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10070/pid_3739/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1342): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1236): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3f37d2d9 new=com.google.android.velvet.VelvetApplication@3f37d2d9
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4662 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 3367:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10061/pid_3367/cgroup.procs: No such file or directory
,W/ContextImpl( 4662): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1342): UpdateCorporaTask done [took 264 ms] updated apps [took 264 ms] 
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 1617): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1617): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1617): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1617): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1373): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1373): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1617): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 4662): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/ActivityManager(  760): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,W/FileUtils( 1617): Failed to chmod(/data/data/com.google.android.gms/databases/phenotype.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,--------- beginning of crash
E/AndroidRuntime( 4662): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4662): Process: com.android.keychain, PID: 4662
E/AndroidRuntime( 4662): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4662): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4662): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4662): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4662): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4662): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4662): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:404)
E/AndroidRuntime( 4662): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4662): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4662): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4662): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4662): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
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
,I/Process ( 4662): Sending signal. PID: 4662 SIG: 9
,E/SQLiteLog( 1617): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1617): disk I/O error (code 3850)
E/DriveAsyncService( 1617): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1617): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1617): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1617): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1617): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1617): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1617): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1617): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1617): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1617): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1617): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1617): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1617): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1617): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1617): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1617): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  760): Resuming delayed broadcast
E/SQLiteDatabase( 1617): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1617): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1617): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1617): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1617): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1617): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1617): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1617): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1617): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1617): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1617): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1617): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1617): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1617): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1617): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1617): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  760): Process com.android.keychain (pid 4662) has died
W/ActivityManager(  760): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/SQLiteOpenHelper( 1617): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1617): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1617): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1617): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1617): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/SQLiteLog( 1617): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GAv4-SVC( 1617): Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SharedPreferencesImpl( 1617): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 1617): Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
E/SharedPreferencesImpl( 1617): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 1617): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/ActivityManager(  760): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4698 uid=10039 gids={50039, 9997} abi=armeabi-v7a

```
