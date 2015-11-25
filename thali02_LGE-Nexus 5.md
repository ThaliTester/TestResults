#### Test 51335028c93db41_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2981): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2981):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2981):   adb logcat -s GAv4
W/GAv4    ( 2981): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2981): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2981): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2981): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
W/ResourcesManager( 2981): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2981): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 2442): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  757): Killing 2171:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
V/JNIHelp ( 2981): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 2981): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2981): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2171/cgroup.procs: No such file or directory
V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1612): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1612): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1612): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,D/AndroidRuntime( 3048): 
D/AndroidRuntime( 3048): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3048): CheckJNI is OFF
I/ActivityManager(  757): Killing 2263:com.google.android.youtube/u0a80 (adj 15): empty #17
D/AndroidRuntime( 3048): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2263/cgroup.procs: No such file or directory
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  757): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3069 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 3048): Shutting down VM
V/ActivityManager(  757): Display changed displayId=0
,I/WebViewFactory( 3069): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3069): Time to load native libraries: 2 ms (timestamps 8644-8646)
I/LibraryLoader( 3069): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3069): Binding Chromium to main looper Looper (main, tid 1) {3a661969}
,I/LibraryLoader( 3069): Expected native library version number "",actual native library version number ""
,I/chromium( 3069): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3069): Initializing chromium process, singleProcess=true
W/art     ( 3069): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3069): ApplicationContext is null in ApplicationStatus
,W/chromium( 3069): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3069): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3069): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3069): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fff25ab:true
,D/BluetoothAdapter( 3069): 592216747: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3069): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3069): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3069): CordovaWebView is running on device made by: LGE
,W/art     ( 3069): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3069): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3069): Render dirty regions requested: true
,D/Atlas   ( 3069): Validating map...
,W/chromium( 3069): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3069): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3069): Enabling debug mode 0
,I/Keyboard.Facilitator( 1091): onFinishInput()
,I/ActivityManager(  757): Displayed com.test.thalitest/.MainActivity: +460ms (total +57s508ms)
,W/IInputConnectionWrapper( 3069): showStatusIcon on inactive InputConnection
,W/BindingManager( 3069): Cannot call determinedVisibility() - never saw a connection for the pid: 3069
,D/JsMessageQueue( 3069): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3069): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1549035392
D/JX-Cordova( 3069): jxcore cordova android initializing
,W/art     ( 3069): Suspending all threads took: 5.198ms
,W/jxcore-log( 3069): Initializing JXcore engine
W/jxcore-log( 3069): JXcore engine is ready
W/jxcore-log( 3069): Starting JXcore engine
,I/art     ( 3069): Background sticky concurrent mark sweep GC freed 67125(6MB) AllocSpace objects, 2(3MB) LOS objects, 20% free, 29MB/37MB, paused 6.317ms total 66.151ms
,W/.test.thalitest( 3069): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8007]" dev="sockfs" ino=8007 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 3069): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3069): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9384]" dev="sockfs" ino=9384 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3069): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[16910]" dev="sockfs" ino=16910 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket
,W/jxcore-log( 3069): Platform android
W/jxcore-log( 3069): 
W/jxcore-log( 3069): Process ARCH arm
W/jxcore-log( 3069): 
,I/jxcore-log( 3069): JXcore Cordova bridge is ready!
I/jxcore-log( 3069): 
,W/jxcore-log( 3069): JXcore engine is started
I/Choreographer( 3069): Skipped 107 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3069): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3069): Toggling radios to true
I/jxcore-log( 3069): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  757): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  757): Message: 1
D/BluetoothManagerService(  757): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  757): New client listening to asynchronous messages
,D/WifiService(  757): setWifiEnabled: true pid=3069, uid=10270
,E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  178): Softap fwReload - Ok
,I/jxcore-log( 3069): Radios toggled
I/jxcore-log( 3069): 
D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring down wlan0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,I/ActivityManager(  757): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3121 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiMonitor(  757): startMonitoring(wlan0) with mConnected = false
I/ActivityManager(  757): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3128 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3127): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3121): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3127): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23b07b49:true
,D/BluetoothAdapter( 3128): 979769705: getState() :  mService = null. Returning STATE_OFF
,D/AdapterServiceConfig( 3121): Adding HeadsetService
,D/AdapterServiceConfig( 3121): Adding A2dpService
D/AdapterServiceConfig( 3121): Adding HidService
,D/AdapterServiceConfig( 3121): Adding HealthService
D/AdapterServiceConfig( 3121): Adding PanService
D/AdapterServiceConfig( 3121): Adding GattService
D/AdapterServiceConfig( 3121): Adding BluetoothMapService
,D/BluetoothManagerService(  757): Message: 30
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 3128): Adding local MAP profile
D/BluetoothMap( 3128): Create BluetoothMap proxy object
D/BluetoothManagerService(  757): Message: 30
,D/BluetoothManagerService(  757): Message: 30
,D/LocalBluetoothProfileManager( 3128): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3128): 979769705: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3128): 979769705: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  757): Message: 20
,D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1878b45f:true
,D/BluetoothAdapterState( 3121): make
,I/BluetoothAdapterState( 3121): Entering OffState
I/bluedroid( 3121): init
,I/bte_conf( 3121): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3121): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3121): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3121): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3121): get_profile_interface socket
,I/bluedroid( 3121): get_profile_interface map_client
,I/GKI_LINUX( 3121): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3121): Address is:34:FC:EF:11:AE:67
,I/ActivityManager(  757): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3172 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BluetoothAdapterProperties( 3121): Name is: Nexus 5
D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,I/ActivityManager(  757): Killing 2357:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10038/pid_2357/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3121): config_hci_snoop_log
,D/BluetoothManagerService(  757): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 3121): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3121): Setting state to 11
I/BluetoothAdapterState( 3121): Bluetooth adapter state changed: 10-> 11
,D/BluetoothBondStateMachine( 3121): make
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 10 -> 11
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,D/BluetoothHeadset(  757): Proxy object connected
,D/BluetoothHeadset( 1229): Proxy object connected
D/BluetoothHeadset( 1186): Proxy object connected
,D/BluetoothHeadset( 1186): Proxy object connected
,D/HeadsetService( 3121): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3121): classInitNative: succeeds
,D/HeadsetStateMachine( 3121): make
,I/BluetoothAdapterState( 3121): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3121): max_hf_connections = 1
I/bluedroid( 3121): get_profile_interface handsfree
,D/HeadsetStateMachine( 3121): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
,D/BluetoothA2dp(  757): Proxy object connected
,D/A2dpService( 3121): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3121): classInitNative: succeeds
I/bluedroid( 3121): get_profile_interface avrcp
,E/RemoteController( 3121): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3121): classInitNative: succeeds
D/A2dpStateMachine( 3121): make
,I/bluedroid( 3121): get_profile_interface a2dp
,I/GKI_LINUX( 3121): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
I/BluetoothHidServiceJni( 3121): classInitNative: succeeds
D/A2dpStateMachine( 3121): Enter Disconnected: -2
D/HidService( 3121): Received start request. Starting profile...
D/BluetoothInputDevice( 3128): Proxy object connected
I/bluedroid( 3121): get_profile_interface hidhost
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
I/BluetoothHealthServiceJni( 3121): classInitNative: succeeds
D/HidProfile( 3128): Bluetooth service connected
D/HealthService( 3121): Received start request. Starting profile...
I/bluedroid( 3121): get_profile_interface health
,D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
,I/BluetoothPanServiceJni( 3121): classInitNative(L105): succeeds
,D/BluetoothPan( 3128): BluetoothPAN Proxy object connected
D/PanService( 3121): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3121): initializeNative(L110): pan
I/bluedroid( 3121): get_profile_interface pan
D/PanProfile( 3128): Bluetooth service connected
,D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
I/BtGatt.JNI( 3121): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3121): handleDebugAction() action=null
,D/BtGatt.GattService( 3121): Received start request. Starting profile...
,D/BtGatt.GattService( 3121): start()
I/bluedroid( 3121): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3121): advertise manager created
,D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
,V/BluetoothMapService( 3121): BluetoothMapBinder()
,D/BluetoothMapService( 3121): Received start request. Starting profile...
D/BluetoothMapService( 3121): start()
D/BluetoothMap( 3128): Proxy object connected
,D/MapProfile( 3128): Bluetooth service connected
,D/BluetoothMap( 3128): getConnectedDevices()
,D/BluetoothMap( 3128): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3121): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3121): createReceiver()
D/BluetoothMapEmailAppObserver( 3121): initObservers()
D/BluetoothMapEmailAppObserver( 3121): getEnabledAccountItems()
,D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
D/HeadsetStateMachine( 3121): Proxy object connected
,D/HeadsetStateMachine( 3121): Disconnected process message: 10, size: 0
,V/BluetoothMapService( 3121): Handler(): got msg=1
,D/HeadsetPhoneState( 3121): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3121): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3121): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3121): enable
,I/GKI_LINUX( 3121): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3121): btu_task pending for preload complete event
I/bt_hci_bdroid( 3121): init
,I/bt_vendor( 3121): init
I/bt_vnd_conf( 3121): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 3121): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3121): userial_init
,I/bt_userial_vendor( 3121): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3121): device fd = 53 open
,D/bt_userial( 3121): Entering userial_read_thread()
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 9641(579KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 19MB/32MB, paused 1.077ms total 43.606ms
,I/bt_hwcfg( 3121): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3121): Chipset BCM4335C0
D/bt_hwcfg( 3121): Target name = [BCM4335C0]
I/bt_hwcfg( 3121): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,I/art     (  757): Explicit concurrent mark sweep GC freed 13441(677KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.095ms total 74.851ms
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  757): Killing 2405:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2405/cgroup.procs: No such file or directory
,D/Tethering(  757): sendTetherStateChangedBroadcast 1, 0, 0
,W/NetworkUtils( 1383): OkHttp exception
,W/EventLoggerService( 1383): Unable to send logs Error code: 262146
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/bt_hwcfg( 3121): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3121): Settlement delay -- 100 ms
I/bt_hwcfg( 3121): Setting fw settlement delay to 100 
,W/Search.LoginHelper( 1383): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/wpa_supplicant( 3127): rfkill: Cannot open RFKILL control device
,W/Search.LoginHelper( 1383): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/bt_hwcfg( 3121): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3121): Setting local bd addr to 34:FC:EF:11:AE:67
,I/wpa_supplicant( 3127): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  757): Loading config and enabling all networks 
,D/WifiService(  757): New client listening to asynchronous messages
,I/bt_hwcfg( 3121): vendor lib fwcfg completed
,I/bt-btu  ( 3121): btu_task received preload complete event
,I/        ( 3121): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3121): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3121): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3121): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3121): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3121): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3121): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3121): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3121): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3121): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3121): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3121): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3121): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3121): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3121): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiConfigStore(  757): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 1858): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  757): Setting external_sim to 1
,D/WifiStateMachine(  757): Setting OUI to DA-A1-19
,I/WifiNative-HAL(  757): startHal
,D/wifi    (  757): setting scan oui 0x9c3782e0
D/WifiHAL (  757): Sending mac address OUI
E/WifiHAL (  757): failed to set scanning mac OUI; result = -95
,E/native  (  757): do suspend true
,D/WifiScanningService(  757): SCAN_AVAILABLE : 3
,D/RttService(  757): SCAN_AVAILABLE : 3
D/WifiScanningService(  757): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  757): startHal
D/RttService(  757): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring up p2p0
,D/WifiMonitor(  757): startMonitoring(p2p0) with mConnected = true
D/wifi    (  757): getting scan capabilities on interface[1] = 0x9c3782e0
D/WifiHAL (  757): Creating message to get scan capablities; iface = 21
,D/WifiHAL (  757): In GetCapabilities::handleResponse
D/WifiHAL (  757): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  757): StartedState
,D/WifiNative-HAL(  757): p2pGetDeviceAddress
,D/WifiNative-HAL(  757): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3127): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/bt-btm  ( 3121): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 3121): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3121): Calling BTA_HhEnable
E/bt-btif ( 3121): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3121): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  757): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3121): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3121): Scan Mode:20
,D/BluetoothAdapterProperties( 3121): Discoverable Timeout:120
,D/bte_conf( 3121): Device ID record 1 : primary
D/bte_conf( 3121):   vendorId            = 000f
D/bte_conf( 3121):   vendorIdSource      = 0001
D/bte_conf( 3121):   product             = 1200
D/bte_conf( 3121):   version             = 1436
D/bte_conf( 3121):   clientExecutableURL = 
D/bte_conf( 3121):   serviceDescription  = 
,D/bte_conf( 3121):   documentationURL    = 
D/bte_conf( 3121): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3121): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3121): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3121): ScanMode =  20
D/BluetoothAdapterProperties( 3121): State =  11
D/BluetoothAdapterProperties( 3121): Setting state to 12
I/BluetoothAdapterState( 3121): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(true) to 9 receivers.
I/BluetoothAdapterState( 3121): Entering On State
,D/BluetoothAdapterProperties( 3121): Scan Mode:21
D/BluetoothAdapterProperties( 3121): Discoverable Timeout:120
D/BluetoothInputDevice( 3128): onBluetoothStateChange: up=true
,D/BluetoothA2dp(  757): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
D/BluetoothHeadset(  757): onBluetoothStateChange: up=true
D/BluetoothPan( 3128): onBluetoothStateChange(on) call bindService
,D/BluetoothMap( 3128): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1229): onBluetoothStateChange: up=true
,D/BluetoothPbap( 3128): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  757): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  757): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3121): onReceive
D/BluetoothMapService( 3121): STATE_ON
,V/BluetoothMapService( 3121): Handler(): got msg=1
D/BluetoothMapMasInstance( 3121): Map Service startRfcommSocketListener
,W/bt-smp  ( 3121): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = 1f 0b 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = ba ab 17 c2 cd c7 5d 2c a5 ea 3b 29 30 e8 9c 48 
W/bt-btm  ( 3121): Stopping oneshot timer
E/bt_h4   ( 3121): vendor lib postload completed
,D/BluetoothManagerService(  757): Message: 40
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/Telecom ( 1186): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapMasInstance( 3121): MAS initSocket()
,D/BluetoothMapMasInstance( 3121):   masId = 00
D/BluetoothMapMasInstance( 3121):   msgTypes = 0e
D/BluetoothMapMasInstance( 3121):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3121):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3121): getBluetoothService() called with no BluetoothManagerCallback
,W/bt-smp  ( 3121): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = 52 1c 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = 0b ae ff 70 3d da 2e 60 ca 50 57 12 8f 43 d1 4e 
W/bt-btm  ( 3121): Stopping oneshot timer
,V/BluetoothMapMasInstance( 3121): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3121): Accepting socket connection...
D/HeadsetStateMachine( 3121): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3121): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/HeadsetStateMachine( 3121): mNumber:  mType: 128
D/HeadsetStateMachine( 3121): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3121): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/LocalBluetoothProfileManager( 3128): Adding local A2DP profile
W/bt-smp  ( 3121): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = 91 3e 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = 18 31 21 4c 8e 07 ee 26 fb 28 b4 33 c1 62 a5 bc 
W/bt-btm  ( 3121): Stopping oneshot timer
,D/BluetoothManagerService(  757): Message: 30
,W/bt-smp  ( 3121): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = 28 6a 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = e0 4e ba f3 8a fc 36 21 a0 7f ee 25 8e a2 29 d9 
W/bt-btm  ( 3121): Stopping oneshot timer
,D/LocalBluetoothProfileManager( 3128): Adding local HEADSET profile
,D/BluetoothManagerService(  757): Message: 30
,W/bt-smp  ( 3121): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = fd 22 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = 30 b6 79 ea f0 49 92 13 61 9e ce 62 f8 74 56 d1 
W/bt-btm  ( 3121): Stopping oneshot timer
W/ContextImpl( 3128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-smp  ( 3121): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = 28 06 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = 7a 0f 29 dd 91 f9 11 c4 df 82 b4 79 76 72 db 04 
W/bt-btm  ( 3121): Stopping oneshot timer
,W/bt-smp  ( 3121): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3121): Plain text(LSB ~ MSB) = 4a 82 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3121): Encrypted text(LSB ~ MSB) = 21 a5 3e 43 91 68 8e e1 c3 dc cc 41 f6 a1 f4 e0 
W/bt-btm  ( 3121): Stopping oneshot timer
,D/BluetoothA2dp( 3128): Proxy object connected
D/A2dpProfile( 3128): Bluetooth service connected
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothHeadset( 3128): Proxy object connected
W/BluetoothAdapter( 3121): getBluetoothService() called with no BluetoothManagerCallback
D/HeadsetProfile( 3128): Bluetooth service connected
,D/DockEventReceiver( 3128): finishStartingService: stopping service
,D/BluetoothPbap( 3128): Proxy object connected
D/PbapServerProfile( 3128): Bluetooth service connected
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3121): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3121): Accept thread started.
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3069): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3069): 
I/jxcore-log( 3069): my name is : LGE-Nexus 5_PT1775
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): attempting to connect to test coordinator
I/jxcore-log( 3069): 
I/jxcore-log( 3069): check test folder
I/jxcore-log( 3069): 
I/jxcore-log( 3069): found test : ./testFindPeers.js
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): found test : ./testReConnect.js
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): found test : ./testSendData.js
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): Test app app.js loaded
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/Choreographer( 3069): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3069): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  757): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  757): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  757): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  757): will read network variables netId=1
,E/WifiStateMachine(  757): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  757): will read network variables netId=1
,I/wpa_supplicant( 3127): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  757): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3127): PNO: In assoc process
,I/wpa_supplicant( 3127): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3127): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3127): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  757): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  178): Setting iface cfg
E/WifiStateMachine(  757): Start Dhcp Watchdog 1
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,E/native  (  757): do suspend false
,E/WifiStateMachine(  757): scanCount==0 - aborting
,I/dhcpcd  ( 3282): version 5.5.6 starting
,E/dhcpcd  ( 3282): get_duid: Read-only file system
,I/dhcpcd  ( 3282): wlan0: rebinding lease of 192.168.1.114
,I/dhcpcd  ( 3282): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3282): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  757): do suspend true
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  757): Adding iface wlan0 to network 100
,E/ConnectivityService(  757): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  757): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  757): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  757): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  757): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  757):    accepting network in place of null
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  757): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  757): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  757): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
,D/Nat464Xlat(  757): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  757): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524295
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 25 Nov 2015 12:46:03 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448455563985], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448455563967]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Validated
,D/ConnectivityService(  757): Validated NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  757): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  757): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  757): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524290
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1229): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3069): 
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  757): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2526): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2526): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  757): Setting time of day to sec=1448455566
,W/AlarmManagerService(  757): Unable to set rtc to 1448455566: Invalid argument
,I/iu.SyncManager( 1612): SYNC; picasa accounts
,D/NetworkLogImpl( 1612): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1612): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,E/GpsLocationProvider(  757): No APN found to select.
,I/iu.UploadsManager( 1612): num queued entries: 0
,I/iu.UploadsManager( 1612): num updated entries: 0
,I/iu.SyncManager( 1612): NEXT; no task
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/GpsLocationProvider(  757): NTP server returned: 1448455566708 (Wed Nov 25 13:46:06 GMT+01:00 2015) reference: 88938 certainty: 8 system time offset: -110
E/LocSvc_eng(  757): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,D/SystemUpdateService( 1612): onCreate
,D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1612): active receiver: enabled
,I/SystemUpdateService( 1612): showing system update notification
V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  757): skipping global notification
,V/SystemUpdateService( 1612): retry (wakeup: false) in 3599982 ms
,I/ActivityManager(  757): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3389 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 392us total 17.827ms
,D/SystemUpdateService( 1612): onDestroy
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 376us total 20.296ms
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 462us total 17.337ms
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 1858): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1612): [CredentialSyncAdapter] Unknown sync event.
,I/GCM     ( 1355): GCM config loaded
,I/GAv4    ( 3389): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3389):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3389):   adb logcat -s GAv4
,D/ConnectivityService(  757): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  757): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  757): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524290
,W/GAv4    ( 3389): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/AbstractGoogleClient( 2069): Application name is not set. Call Builder#setApplicationName.
,W/GAv4    ( 3389): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/AnalyticsLogBase( 2069): PlayLogger.onLoggerConnected
,W/GAv4    ( 3389): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 11439(653KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 1.265ms total 34.540ms
,E/Auth.Api.Credentials( 1612): [CredentialSyncAdapter] Unknown sync event.
,I/art     (  757): Explicit concurrent mark sweep GC freed 48557(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 27MB/41MB, paused 1.367ms total 66.260ms
,W/DriveInitializer( 1612): Awaiting to be initialized
,W/DriveInitializer( 1612): Background init thread started
,I/WebViewFactory( 3389): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3389): Time to load native libraries: 2 ms (timestamps 9520-9522)
I/LibraryLoader( 3389): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3389): Binding Chromium to main looper Looper (main, tid 1) {2e5dd7f3}
,I/LibraryLoader( 3389): Expected native library version number "",actual native library version number ""
,I/chromium( 3389): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3389): Initializing chromium process, singleProcess=true
,W/art     ( 3389): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3389): ApplicationContext is null in ApplicationStatus
,W/chromium( 3389): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3389): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3389): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3389): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3389): Requires BLUETOOTH permission
,I/NSApplication( 3389): Starting up...
,W/DriveInitializer( 1612): Background init thread ended
,I/ActivityManager(  757): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3482 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3482): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448455567526
D/        ( 3482): TimeServiceNative: User Time to be set is 1448455567526
D/QC-time-services( 3482): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3482): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3482): Lib:time_genoff_operation: pargs->ts_val = 1448455567526
,D/QC-time-services(  197): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3482): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  197): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448455567526
D/QC-time-services(  197): Daemon:genoff_opr: Base = 2, val = 1448455567526, operation = 0
D/QC-time-services(  197): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/29/70 18:36:58
D/QC-time-services(  197): Daemon:Value read from RTC seconds = 7583818000
D/QC-time-services(  197): Daemon:new time 1448455567526 
D/QC-time-services(  197): Daemon: delta 1440871749526 genoff 1440871749526 
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871749526 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Updating the TOD offset
D/QC-time-services(  197): Daemon:genoff_persistent_update: Writing genoff = 1440871749526 to memory
D/QC-time-services(  197): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  197): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  197): Daemon:Update to modem bit set
D/QC-time-services(  197): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  197): Daemon: Base = 2, Value being sent to MODEM = 1132490767526
,E/QC-time-services( 3482): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  197): Daemon: Time-services: Waiting to acceptconnection
,D/QC-time-services(  197): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/CheckinService( 1612): Checkin interval check for package: unspecified last checkin: 1448443186671 min interval config: 0 actual interval: 12380897
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3503 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3503): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3503):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3503):   adb logcat -s GAv4
,W/GAv4    ( 3503): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3503): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3503): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  757): Killing 1840:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10045/pid_1840/cgroup.procs: No such file or directory
,I/CalendarSyncAdapter( 2069): Found no pending settings
,I/ActivityManager(  757): Killing 2503:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10003/pid_2503/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Killing 2379:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10070/pid_2379/cgroup.procs: No such file or directory
,I/CalendarSyncAdapter( 2069): Found no pending settings
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,D/Finsky  ( 2442): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2442): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1355): Vacuum at: now=1448455596992 tag=VacuumService
,D/UdcCache:FPQuery( 1612): Bootstrapping UDC settings cache for all accounts
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1355): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1355): Using platform SSLCertificateSocketFactory
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,W/Uploader( 1355):  no longer exists, so no auth token.
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,D/GetCommittedConfigurationOperation( 1355): no corresponding serverToken: com.google.android.gms.playlog.uploader
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1091): run()
I/Keyboard.Facilitator( 1091): flushDynamicLanguageModels()
,I/ConfigService( 1355): onCreate
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/ConfigService( 1355): onDestroy
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/ClearcutLoggerApiImpl( 1318): disconnect managed GoogleApiClient
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,E/DataBuffer( 1355): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@178bb3d1)
,E/DataBuffer( 1355): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3beb6e36)
E/DataBuffer( 1355): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32969137)
E/DataBuffer( 1355): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@31e4c6a4)
,E/DataBuffer( 1355): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39c6bc0d)
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  757): Explicit concurrent mark sweep GC freed 30301(1276KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.576ms total 74.987ms
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1355): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector connect called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): Coordinator is now connected to the server!
I/jxcore-log( 3069): 
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3069): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector command called
I/jxcore-log( 3069): 
I/jxcore-log( 3069): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"F4:F1:E1:5C:3B:E2","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"00:F4:6F:30:E0:6C","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:37:96
I/jxcore-log( 3069): Start now : testSendData.js
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): check server
I/jxcore-log( 3069): 
I/jxcore-log( 3069): serverPort is 43463
I/jxcore-log( 3069): 
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3069): Stoping All
I/        ( 3069): Stopping services
I/        ( 3069): Stop Bluetooth
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3069): Start-My BT: 34:FC:EF:11:AE:67
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/        ( 3069):  mInstanceString : {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1775","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3069): All stuff available and enabled
I/        ( 3069): Stoping All
I/        ( 3069): Stopping services
I/        ( 3069): Stop Bluetooth
I/        ( 3069): Starting All
I/        ( 3069): Stopping services
I/        ( 3069): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1775","ra":"34:FC:EF:11:AE:67"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@19850566
I/        ( 3069): Stopping services
I/        ( 3069): Starting services address: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1775","ra":"34:FC:EF:11:AE:67"}
,I/        ( 3069): Add local service :{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1775","ra":"34:FC:EF:11:AE:67"}, length : 77
,I/        ( 3069): peerDiscoveryTimer timeout value:7060
,I/        ( 3069): Stop Bluetooth
I/        ( 3069): StartBluetooth listener
I/        ( 3069): StartBluetooth listener
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3069): StartBroadcasting started ok
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:10.973Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:10.974Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:10.974Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3069): Connecting to null, at 08:EC:A9:50:76:27
,I/jxcore-log( 3069): 2015-11-25T12:53:10.979Z SendDataTCPServer.js: TCP/IP server is bound to port: 43463
I/jxcore-log( 3069): 
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/WB      ( 3069): We already were running, thus doing nothing
I/        ( 3069): Added local service
,I/        ( 3069): Cleared service requests
I/        ( 3069): Stopped peer discovery
I/        ( 3069): Started peer discovery
I/        ( 3069): Discovery state changed to Started.
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 3069): starting to listen
I/BTListenerThread( 3069): waiting to accept incoming Connection
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:5, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 5
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:53:16.120Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:16.120Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:16.120Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3069): Found 1 peers.
I/SS      ( 3069): Peer(1): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiP2pManager( 3069): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T12:53:21.125Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:21.142Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT7895","ra":"08:EC:A9:50:75:41"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT7895
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, samsung-SM-A300FU_PT7895
,I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T12:53:23.496Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,I/jxcore-log( 3069): 2015-11-25T12:53:23.858Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:23.867Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:23.877Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:23.889Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:23.906Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:23.931Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:23.934Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:23.971Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.016Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.064Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.078Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.090Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.104Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.118Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.169Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.186Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.199Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.208Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.226Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.255Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.273Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.323Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.334Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.350Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.387Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.399Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.434Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.472Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.488Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.500Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.517Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.553Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.558Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.565Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.577Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.632Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.656Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.677Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:24.709Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 4
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7895
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT7895
I/BtToSocketBase( 3069): Close LocalOutputStream
,I/BtToSocketBase( 3069): Close localHostSocket
,I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
,I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
,I/BtToSocketBase( 3069): Close bt socket
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x42
,I/BtToSocketBase( 3069): Close bt socket
,I/jxcore-log( 3069): 2015-11-25T12:53:24.856Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:26.147Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:26.148Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:26.149Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:26.150Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3069): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e51084 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f324e99:true
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A3-1
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 7
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:53:32.235Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:32.236Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:32.237Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:37.238Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:37.238Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:42.242Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:42.243Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:42.243Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:42.244Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3069): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 8
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:53:47.418Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:47.418Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:47.418Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:52.419Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:52.420Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:53:57.426Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:57.426Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:57.427Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:53:57.427Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3069): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 9
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:54:02.599Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:02.599Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:02.599Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:07.602Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:07.603Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:12.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:12.608Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:12.608Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:12.609Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:76:27, name: null
,I/        ( 3069): Connecting to null, at 08:EC:A9:50:76:27
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:10, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 10
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T12:54:17.783Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:17.784Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:76:27 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:17.786Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:17.787Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 34:FC:EF:9D:93:0B
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:17.788Z SendDataConnector.js: Start called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:17.788Z SendDataConnector.js: doConnect called with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:17.788Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 34:FC:EF:9D:93:0B, name: null
,I/        ( 3069): Connecting to null, at 34:FC:EF:9D:93:0B
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Connection to 08:EC:A9:50:76:27 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [34:fc:ef:9d:93:0b]: 6, f, 4106
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
E/BluetoothEventManager( 3128): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 4 peers.
I/SS      ( 3069): Peer(1): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3069): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 3069): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : LGE-LG-D802_PT7336
I/HS      ( 3069): Hand Shake finished outgoing for : LGE-LG-D802_PT7336
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, LGE-LG-D802_PT7336
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 38991
I/BtConnectorHelper( 3069): Request socket is using : 38991
,I/BtToRequestSocket( 3069): Now accepting connections
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :38991
I/jxcore-log( 3069): 2015-11-25T12:54:20.833Z SendDataConnector.js: CLIENT connected to 38991, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:20.834Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 38991
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T12:54:20.861Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/jxcore-log( 3069): 2015-11-25T12:54:21.114Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3069): 2015-11-25T12:54:21.517Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:21.852Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:21.952Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.096Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.436Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.511Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.667Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.849Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.976Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:22.977Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.994Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:22.995Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
,I/BtConnectorHelper( 3069): Disconnect outgoing peer: 34:FC:EF:9D:93:0B
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3069): 2015-11-25T12:54:23.030Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:9D:93:0B
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:23.039Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:23.039Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:23.039Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 00:F4:6F:30:E0:6C, name: null
,I/        ( 3069): Connecting to null, at 00:F4:6F:30:E0:6C
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:9D:93:0B done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e5124c rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e51414 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test's G2
,I/        ( 3069): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3817","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT3817","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT3817, peerAddress: E0:DB:10:14:E2:C0
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT3817, WifiDirectName: Note4-1, WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT8819"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : samsung-SM-G800F_PT8819
I/HS      ( 3069): Hand Shake finished outgoing for : samsung-SM-G800F_PT8819
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, samsung-SM-G800F_PT8819
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 38728
I/BtConnectorHelper( 3069): Request socket is using : 38728
I/BtToRequestSocket( 3069): Now accepting connections
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :38728
I/jxcore-log( 3069): 2015-11-25T12:54:27.945Z SendDataConnector.js: CLIENT connected to 38728, error: null
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:27.946Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 38728
I/BtToRequestSocket( 3069): Set local streams
,I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T12:54:27.970Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:28.198Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:28.352Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:28.472Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:28.500Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:28.644Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:28.710Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:28.768Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:29.034Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:29.144Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:29.195Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:29.196Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:29.213Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:29.214Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
I/BtConnectorHelper( 3069): Disconnect outgoing peer: 00:F4:6F:30:E0:6C
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
,I/jxcore-log( 3069): 2015-11-25T12:54:29.243Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:29.249Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:29.249Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:29.250Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3069): Connecting to null, at 44:80:EB:7B:5A:05
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: S5mini-1
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 13
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:54:34.406Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:34.407Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:34.408Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3069): Found 6 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 3069): Peer(4): Android_1950 b6:ce:f6:ad:a4:6b
,I/SS      ( 3069): Peer(5): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3069): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T12:54:39.409Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:39.409Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T12:54:44.413Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:44.414Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:44.415Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:44.415Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3069): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:14, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 14
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:54:49.588Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:49.588Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:49.588Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:54.589Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:54.589Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:54:59.594Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:59.594Z SendDataConnector.js: Connect (retry count 2) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:59.595Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:54:59.595Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3069): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:15, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 15
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:55:04.765Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:04.766Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:04.766Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:09.766Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:09.767Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:14.770Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:14.774Z SendDataConnector.js: Connect (retry count 3) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:14.777Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:14.777Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
I/        ( 3069): Selected device address: 44:80:EB:7B:5A:05, name: null
I/        ( 3069): Connecting to null, at 44:80:EB:7B:5A:05
I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/ActivityManager(  757): Killing 1479:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10013/pid_1479/cgroup.procs: No such file or directory
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:16, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 16
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:55:19.948Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:19.948Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:19.948Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:24.948Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:24.949Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:29.953Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:29.954Z SendDataConnector.js: Connect (retry count 4) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:29.955Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:29.955Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 44:80:EB:7B:5A:05, name: null
,I/        ( 3069): Connecting to null, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 17
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T12:55:35.127Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:35.127Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:35.129Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:35.129Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 44:80:EB:7B:5A:05, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: F8:CF:C5:D9:E5:61
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:35.130Z SendDataConnector.js: Start called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:35.130Z SendDataConnector.js: doConnect called with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:35.130Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:CF:C5:D9:E5:61, name: null
,I/        ( 3069): Connecting to null, at F8:CF:C5:D9:E5:61
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: Connection to 44:80:EB:7B:5A:05 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.,
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : motorola-Nexus 6_PT2615
,I/HS      ( 3069): Hand Shake finished outgoing for : motorola-Nexus 6_PT2615
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, motorola-Nexus 6_PT2615
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 40371
I/BtConnectorHelper( 3069): Request socket is using : 40371
,I/BtToRequestSocket( 3069): Now accepting connections
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :40371
I/jxcore-log( 3069): 2015-11-25T12:55:38.854Z SendDataConnector.js: CLIENT connected to 40371, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:38.855Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 40371
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T12:55:38.881Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
,I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/SS      ( 3069): Found 4 peers.
I/SS      ( 3069): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3069): Peer(2): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3069): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/jxcore-log( 3069): 2015-11-25T12:55:39.545Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T12:55:39.828Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13099
,I/jxcore-log( 3069): 2015-11-25T12:55:40.094Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:40.206Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2209
,I/jxcore-log( 3069): 2015-11-25T12:55:40.258Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/jxcore-log( 3069): 2015-11-25T12:55:40.319Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T12:55:40.460Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/jxcore-log( 3069): 2015-11-25T12:55:40.589Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:40.622Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T12:55:40.714Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:40.715Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:40.731Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:40.732Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
I/BtConnectorHelper( 3069): Disconnect outgoing peer: F8:CF:C5:D9:E5:61
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
I/jxcore-log( 3069): 2015-11-25T12:55:40.756Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:CF:C5:D9:E5:61
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:40.768Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:40.768Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:40.769Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:CF:C5:D9:E5:61 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3069): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9305, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9305, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Nexus 6
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:19, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 19
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T12:55:48.410Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:48.410Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:55:48.425Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/jxcore-log( 3069): 2015-11-25T12:55:53.427Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:53.427Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): Android_1950 b6:ce:f6:ad:a4:6b
I/SS      ( 3069): Peer(2): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3069): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T12:55:58.432Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:58.432Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:58.433Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:55:58.433Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3121): invalid rfc slot id: 20
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:56:03.606Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:03.606Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:03.606Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:08.608Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:08.608Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:13.614Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:13.614Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:13.615Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:13.615Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 21
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T12:56:18.785Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:18.786Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:18.786Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:23.787Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:23.789Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:28.796Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:28.796Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:28.797Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:28.797Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 22
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:56:33.969Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:33.969Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:33.969Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device B0:C5:59:3F:75:69 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for B0:C5:59:3F:75:69, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT4845
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, samsung-SM-G900F_PT4845
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T12:56:38.568Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T12:56:38.970Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:38.970Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:38.984Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:38.996Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.005Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.016Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.051Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.054Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.084Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.122Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.133Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.148Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.181Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.182Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.186Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.225Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.233Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.237Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.275Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.308Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.345Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.365Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.380Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.413Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.419Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.447Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.457Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.477Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.514Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.529Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:39.563Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 6
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT4845
,I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T12:56:39.679Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x49
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3069): 2015-11-25T12:56:43.978Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:43.978Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:43.978Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:43.978Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 24
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:56:49.118Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:49.118Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:49.124Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:49.127Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:49.130Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:49.135Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:49.137Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/        ( 3069): Connecting to null, at 7C:F9:0E:34:8A:A0
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: Connection to E0:DB:10:1F:C9:5E failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 7C:F9:0E:34:8A:A0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 7C:F9:0E:34:8A:A0, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3994","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : samsung-SM-G900F_PT3994
I/HS      ( 3069): Hand Shake finished outgoing for : samsung-SM-G900F_PT3994
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, samsung-SM-G900F_PT3994
,I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 60661
I/BtConnectorHelper( 3069): Request socket is using : 60661
I/BtToRequestSocket( 3069): Now accepting connections
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :60661
I/jxcore-log( 3069): 2015-11-25T12:56:50.926Z SendDataConnector.js: CLIENT connected to 60661, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:50.927Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 60661
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T12:56:50.947Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.085Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.088Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.122Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.126Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.161Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.205Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.258Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.268Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.328Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3069): 2015-11-25T12:56:51.769Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:51.770Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:51.787Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:51.787Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
I/BtConnectorHelper( 3069): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
,I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
,I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
I/jxcore-log( 3069): 2015-11-25T12:56:51.812Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:51.815Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:51.815Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:56:51.816Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 26
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:56:57.420Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:57.420Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:56:57.423Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3069): Found 3 peers.
I/SS      ( 3069): Peer(1): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3069): Peer(2): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/jxcore-log( 3069): 2015-11-25T12:57:02.426Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:02.427Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:07.430Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:07.430Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:07.435Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:07.438Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 27
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:57:12.607Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:12.607Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:12.607Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:17.607Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:17.608Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [34:fc:ef:9d:93:0b]: 7, f, 610c
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test's G2
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 1
,E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:9D:93:0B newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 34:FC:EF:9D:93:0B
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:34:FC:EF:9D:93:0B OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 34:FC:EF:9D:93:0B not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 34:FC:EF:9D:93:0B, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : LGE-LG-D802_PT7336
I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, LGE-LG-D802_PT7336
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T12:57:19.980Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T12:57:20.336Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.366Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.385Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.406Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.414Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.423Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.431Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.468Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.485Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.513Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.552Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.592Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.622Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.638Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.673Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.685Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.723Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.735Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.773Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.786Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.823Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.835Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.873Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.910Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.944Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.949Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.965Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.993Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:20.999Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:21.014Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:21.035Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 23
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D802_PT7336
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T12:57:21.149Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x41
,I/jxcore-log( 3069): 2015-11-25T12:57:22.612Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:22.612Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:22.613Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:22.613Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:9D:93:0B, alias=null, name=Thali Test's G2, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test's G2
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 29
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:57:32.078Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:32.079Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:32.080Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:37.081Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:37.082Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:42.085Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:42.086Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:42.086Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:42.087Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 30
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:57:47.260Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:47.260Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:47.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:52.260Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:52.261Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:57:57.265Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:57.266Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:57.266Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:57:57.267Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 2 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Android_63cc 82:01:84:6b:e8:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 31
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:58:02.439Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:02.439Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:02.441Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:02.441Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:02.442Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:02.442Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:02.442Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:3F:54:73:64:C0, name: null
,I/        ( 3069): Connecting to null, at 58:3F:54:73:64:C0
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 58:3F:54:73:64:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 58:3F:54:73:64:C0, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 77 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4436","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : LGE-LG-D855_PT4436
I/HS      ( 3069): Hand Shake finished outgoing for : LGE-LG-D855_PT4436
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, LGE-LG-D855_PT4436
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 39987
I/BtConnectorHelper( 3069): Request socket is using : 39987
I/BtToRequestSocket( 3069): Now accepting connections
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :39987
I/jxcore-log( 3069): 2015-11-25T12:58:03.738Z SendDataConnector.js: CLIENT connected to 39987, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:03.739Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 39987
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T12:58:03.769Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3069): 2015-11-25T12:58:03.871Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3069): 2015-11-25T12:58:03.941Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:11119
,I/jxcore-log( 3069): 2015-11-25T12:58:04.020Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:2209
,I/jxcore-log( 3069): 2015-11-25T12:58:04.117Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:04.163Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:04.172Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:04.207Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:04.255Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:04.293Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:04.294Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:04.310Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:04.310Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
,I/BtConnectorHelper( 3069): Disconnect outgoing peer: 58:3F:54:73:64:C0
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
I/jxcore-log( 3069): 2015-11-25T12:58:04.343Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:04.346Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:04.346Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:04.347Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e52254 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 33
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:58:05.925Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:05.926Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:05.927Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G3-1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/        ( 3069): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"}, typeCordovap2p._tcp.local.:
,I/        ( 3069): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9305, peerAddress: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9305, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T12:58:10.928Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:10.929Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT5188, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT5188, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T12:58:15.936Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:15.937Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:15.938Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:15.938Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:34, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 34
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T12:58:16.988Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:16.995Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:16.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,I/        ( 3069): Cleared service requests
,I/        ( 3069): Started peer discovery
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 50:2E:6C:AC:21:50 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 50:2E:6C:AC:21:50, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT2939","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : HTC-HTC One_M8_PT2939
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, HTC-HTC One_M8_PT2939
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/jxcore-log( 3069): 2015-11-25T12:58:21.222Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T12:58:21.620Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.628Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.641Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.686Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.693Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.708Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.721Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.756Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.769Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.774Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.806Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.829Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.863Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.869Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.883Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.923Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.929Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.976Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:21.996Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:21.996Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.013Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.020Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.029Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.039Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.077Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.088Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.133Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.140Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.149Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.160Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.194Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.207Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:22.244Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 28
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT2939
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :HTC-HTC One_M8_PT2939
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/jxcore-log( 3069): 2015-11-25T12:58:22.353Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x4c
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3069): Found 4 peers.
I/SS      ( 3069): Peer(1): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(3): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(4): XT1039_8c05 f4:f1:e1:5c:43:c8
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/jxcore-log( 3069): 2015-11-25T12:58:26.999Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:27.000Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:27.000Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:27.004Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 36
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:58:28.484Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:28.484Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:28.485Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T12:58:33.487Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:33.488Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7336, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7336, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3069): 2015-11-25T12:58:38.493Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:38.493Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:38.497Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:38.501Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 37
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:58:38.708Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:38.709Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:38.709Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag,
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T12:58:43.710Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:43.710Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3069): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T12:58:48.711Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:48.711Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:48.711Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:48.711Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 38
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:58:50.242Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:50.243Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:50.265Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:50.267Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:50.279Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:50.280Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:50.286Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F4:F1:E1:5C:3B:E2, name: null
,I/        ( 3069): Connecting to null, at F4:F1:E1:5C:3B:E2
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 81 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : motorola-XT1039_PT9305
I/HS      ( 3069): Hand Shake finished outgoing for : motorola-XT1039_PT9305
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, motorola-XT1039_PT9305
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 44919
I/BtConnectorHelper( 3069): Request socket is using : 44919
I/BtToRequestSocket( 3069): Now accepting connections
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :44919
,I/jxcore-log( 3069): 2015-11-25T12:58:54.906Z SendDataConnector.js: CLIENT connected to 44919, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:54.906Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 44919
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T12:58:54.927Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3069): 2015-11-25T12:58:55.089Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:55.396Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:14089
,I/jxcore-log( 3069): 2015-11-25T12:58:55.665Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:55.745Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3069): 2015-11-25T12:58:55.964Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:56.462Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:56.588Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:57.072Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:57.225Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:57.489Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:57.490Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:58:57.510Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:57.512Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
I/BtConnectorHelper( 3069): Disconnect outgoing peer: F4:F1:E1:5C:3B:E2
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
,I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
I/jxcore-log( 3069): 2015-11-25T12:58:57.543Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:57.555Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:57.555Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:58:57.556Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:85:54, name: null
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND,
,I/        ( 3069): Connecting to null, at F8:95:C7:87:85:54
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 40
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:59:00.090Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:59:00.090Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:59:00.094Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: XT1039
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T12:59:05.097Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:05.098Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T12:59:10.103Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:10.103Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:10.104Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:10.104Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 41
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:59:27.533Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:27.533Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:27.534Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T12:59:32.534Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:32.535Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
,I/jxcore-log( 3069): 2015-11-25T12:59:37.538Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:37.539Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:37.539Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:37.540Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 42
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T12:59:38.703Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:38.704Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:38.704Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T12:59:43.705Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:43.706Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 3 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-3ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T12:59:48.708Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:48.708Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:48.708Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:48.708Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 43
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T12:59:49.703Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:49.704Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:49.705Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7336, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7336, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T12:59:54.706Z SendDataConnector.js: re-try now : F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:54.706Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/jxcore-log( 3069): 2015-11-25T12:59:59.710Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:59.711Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:85:54 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:59.711Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T12:59:59.712Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:85:54, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:85:54
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 44
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:00:00.444Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:00.445Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:85:54 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:00.461Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:00.463Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : F8:95:C7:87:85:54, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:00.466Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:00.467Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:00.467Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:14:E2:C0
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:85:54 done with result: Connection to F8:95:C7:87:85:54 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 45
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:00:01.583Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:01.584Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:01.585Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 3 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e527ac rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT2615, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT2615, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3069): 2015-11-25T13:00:06.586Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:06.586Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:11.590Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:11.590Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:11.595Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:11.598Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [e0:db:10:14:e2:c0]: 6, f, 410d
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 46
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:00:12.087Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:12.088Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:12.088Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3069): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T13:00:17.089Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:17.090Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3573","ra":"7C:F9:0E:51:18:22"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3573","ra":"7C:F9:0E:51:18:22"} -- peerIdentifier:7C:F9:0E:51:18:22, peerName: samsung-SM-A500FU_PT3573, peerAddress: 7C:F9:0E:51:18:22
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 7C:F9:0E:51:18:22, Name: samsung-SM-A500FU_PT3573, WifiDirectName: , WifiDirect Address: 7e:f9:0e:51:18:23, peerId: 7C:F9:0E:51:18:22
,I/jxcore-log( 3069): 2015-11-25T13:00:22.097Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:22.097Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:22.098Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:22.098Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 47
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:00:23.334Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:23.335Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:23.336Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 2205
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3069): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : motorola-Nexus 6_PT2615
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, motorola-Nexus 6_PT2615
,I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
,I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T13:00:24.947Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:00:25.317Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.375Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.550Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.566Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.575Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.614Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.627Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.664Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.686Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.690Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.723Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.738Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.758Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.795Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.807Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.821Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.827Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.864Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.906Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.915Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.921Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.930Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.936Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.947Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:25.983Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3121): invalid rfc slot id: 35
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :motorola-Nexus 6_PT2615
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:00:26.285Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x4a
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:00:28.336Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:28.337Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3069): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e517a4 rs_disc_pending=0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Nexus 6
,I/        ( 3069): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT5188, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT5188, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3069): Found Service, :{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3573","ra":"7C:F9:0E:51:18:22"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT3573","ra":"7C:F9:0E:51:18:22"} -- peerIdentifier:7C:F9:0E:51:18:22, peerName: samsung-SM-A500FU_PT3573, peerAddress: 7C:F9:0E:51:18:22
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 7C:F9:0E:51:18:22, Name: samsung-SM-A500FU_PT3573, WifiDirectName: , WifiDirect Address: 7e:f9:0e:51:18:23, peerId: 7C:F9:0E:51:18:22
,I/jxcore-log( 3069): 2015-11-25T13:00:33.340Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:33.343Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:33.343Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:33.344Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 49
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:00:33.783Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:33.784Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:33.784Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT2615, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT2615, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:00:38.785Z SendDataConnector.js: re-try now : E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:38.786Z SendDataConnector.js: ReStart called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1856","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1856","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT1856, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT1856, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3069): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3994","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3994","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3994, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3994, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T13:00:43.793Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:43.794Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:14:E2:C0 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:43.794Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:43.795Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:14:E2:C0, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:14:E2:C0
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 50
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:00:44.519Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:44.520Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:14:E2:C0 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:44.536Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:44.538Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : E0:DB:10:14:E2:C0, try count now: 1
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:44.548Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:44.554Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:44.554Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3069): Connecting to null, at 34:FC:EF:11:B1:66
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: Connection to E0:DB:10:14:E2:C0 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 51
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:00:45.183Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:45.210Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:45.217Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3069): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:00:50.218Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:50.218Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1333","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1333","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT1333, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT1333, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/jxcore-log( 3069): 2015-11-25T13:00:55.222Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:55.223Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:55.223Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:55.224Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3069): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [34:fc:ef:11:b1:66]: 7, f, 2205
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 52
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:00:55.572Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:55.573Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:00:55.573Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/BTListenerThread( 3069): got MESSAGE_READ 81 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT1876","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : motorola-XT1072_PT1876
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, motorola-XT1072_PT1876
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T13:00:58.746Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:00:59.124Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.133Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.140Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.149Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.156Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.230Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.276Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.289Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.298Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.396Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.407Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.416Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.432Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.464Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.565Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:00:59.603Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:01:00.357Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:01:00.574Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:00.575Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3069): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T13:01:01.334Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:01:01.480Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T13:01:02.306Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9305, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9305, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/jxcore-log( 3069): 2015-11-25T13:01:02.897Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:02.933Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:03.595Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:03.727Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.067Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.089Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.510Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.734Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.776Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.830Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.839Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:04.865Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:05.000Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:05.478Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:05.534Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:05.578Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:05.579Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:05.579Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:05.580Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3069): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3069): Starting to connect
,W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 54
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:01:07.391Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:07.391Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:07.393Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
,W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3121): invalid rfc slot id: 48
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT1876
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:01:10.548Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:01:12.393Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:12.393Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3069): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3069): Peer(3): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 3069): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3069): Peer(5): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 3069): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:01:17.395Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:17.396Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:17.396Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:17.397Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3069): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 55
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:01:18.424Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:18.424Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:18.425Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2993","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : samsung-SM-A500FU_PT2993
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, samsung-SM-A500FU_PT2993
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T13:01:22.126Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:01:22.473Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.485Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.537Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.546Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.554Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.569Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:22.605Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:22.624Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.665Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.676Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.687Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.695Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.723Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.760Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.793Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.806Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.844Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.858Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.868Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.902Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.915Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.931Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.978Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:22.980Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 53
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A500FU_PT2993
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:01:23.020Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e52d04 rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3069): 2015-11-25T13:01:23.425Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:23.426Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
,W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x46
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A5-1
,I/jxcore-log( 3069): 2015-11-25T13:01:28.427Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:28.427Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:28.427Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:28.427Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 34:FC:EF:11:B1:66, name: null
,I/        ( 3069): Connecting to null, at 34:FC:EF:11:B1:66
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [34:fc:ef:11:b1:66]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:57, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 57
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:01:29.823Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:29.824Z SendDataConnector.js: CLIENT Can not Connect: Connection to 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:29.845Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:29.848Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:29.850Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:29.856Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:29.857Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 7C:F9:0E:37:96:AB, name: A5-1
,I/        ( 3069): Connecting to A5-1, at 7C:F9:0E:37:96:AB
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e52b3c rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT4845, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT4845, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [7c:f9:0e:37:96:ab]: 6, f, 6109
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2993","ra":"7C:F9:0E:37:96:AB"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : samsung-SM-A500FU_PT2993
I/HS      ( 3069): Hand Shake finished outgoing for : samsung-SM-A500FU_PT2993
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, samsung-SM-A500FU_PT2993
,I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 36279
I/BtConnectorHelper( 3069): Request socket is using : 36279
I/BtToRequestSocket( 3069): Now accepting connections
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :36279
I/jxcore-log( 3069): 2015-11-25T13:01:39.959Z SendDataConnector.js: CLIENT connected to 36279, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:39.959Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 36279
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T13:01:39.980Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT2939","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT2939","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT2939, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT2939, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3069): 2015-11-25T13:01:40.306Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:01:40.535Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13817
,I/jxcore-log( 3069): 2015-11-25T13:01:40.595Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:40.717Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3069): 2015-11-25T13:01:40.808Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:40.854Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:01:41.050Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:41.118Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:41.249Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:41.250Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:41.268Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:41.269Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
,I/BtConnectorHelper( 3069): Disconnect outgoing peer: 7C:F9:0E:37:96:AB
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
,I/jxcore-log( 3069): 2015-11-25T13:01:41.298Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:41.298Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:41.299Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:41.299Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3069): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A5-1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:59, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 59
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:01:46.446Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:46.446Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:46.447Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3069): Found 9 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 3069): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3069): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3069): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(8): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3069): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T13:01:51.448Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:51.449Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:01:56.454Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:56.454Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:56.455Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:01:56.455Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3069): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 60
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:02:00.259Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:00.260Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:00.260Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A3-1
,I/jxcore-log( 3069): 2015-11-25T13:02:05.264Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:05.265Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,I/jxcore-log( 3069): 2015-11-25T13:02:10.268Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:10.268Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:10.269Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:10.269Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3069): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 61
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:02:15.438Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:15.439Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:15.439Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:20.440Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:20.445Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:25.450Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:25.453Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:25.453Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:25.454Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3069): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 62
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:02:26.636Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:26.636Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:26.637Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A3-1
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: A3-1
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: XT1039
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3069): Got JSON from encryption:{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : motorola-XT1039_PT9305
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, motorola-XT1039_PT9305
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/jxcore-log( 3069): 2015-11-25T13:02:31.637Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:31.638Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:31.650Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:02:32.017Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.025Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.032Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.045Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.052Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.059Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.070Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.110Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.118Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.150Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.184Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.201Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.212Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.223Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.253Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.261Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.301Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.333Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.340Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.353Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.383Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.394Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.410Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.432Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.459Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.470Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.504Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.520Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.554Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.598Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.606Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.610Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.637Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:32.640Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 56
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :motorola-XT1039_PT9305
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:02:32.714Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x4f
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3069): 2015-11-25T13:02:36.645Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:36.646Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:36.646Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:36.647Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:75:41, name: A3-1
,I/        ( 3069): Connecting to A3-1, at 08:EC:A9:50:75:41
,I/BTConnectToThread( 3069): Starting to connect
,W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 3121): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e525e4 rs_disc_pending=2
E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 64
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:02:42.140Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:42.140Z SendDataConnector.js: CLIENT Can not Connect: Connection to 08:EC:A9:50:75:41 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:42.158Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:02:42.160Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:42.169Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:42.169Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:02:42.170Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:3C:51
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/SS      ( 3069): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G3-1
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4436","ra":"58:3F:54:73:64:C0"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : LGE-LG-D855_PT4436
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, LGE-LG-D855_PT4436
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/jxcore-log( 3069): 2015-11-25T13:03:03.049Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:03:03.504Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.519Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.524Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.551Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.579Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.592Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.661Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.669Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.703Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.710Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.724Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.764Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.823Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.829Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.836Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.860Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.892Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.909Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.922Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:03.965Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.002Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.014Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.043Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.057Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.069Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.102Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.139Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.149Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.157Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.183Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.224Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.235Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.240Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.289Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.330Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.379Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.391Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.425Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.443Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.473Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:04.478Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e5208c rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3121): invalid rfc slot id: 63
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :LGE-LG-D855_PT4436
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:03:04.959Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x40
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G3-1
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x22  CID 0x41
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:65, failed to find channle,                                       status:1, scn:0
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3121): invalid rfc slot id: 65
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:03:13.026Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:03:13.027Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:03:13.027Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:18.029Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:03:18.030Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:23.033Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:03:23.034Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:03:23.034Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:03:23.035Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): No ag scb for peer addr
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [7c:f9:0e:34:8a:a0]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e51cfc rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3994","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : samsung-SM-G900F_PT3994
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, samsung-SM-G900F_PT3994
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/jxcore-log( 3069): 2015-11-25T13:03:31.478Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/BtToRequestSocket( 3069): --DoOneRunRound ended,
,I/jxcore-log( 3069): 2015-11-25T13:03:31.960Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:31.979Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:31.996Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.024Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.031Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.045Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.084Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.104Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.114Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.147Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.182Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.189Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.202Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.233Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.257Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.289Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.324Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.346Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.354Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.364Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.403Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.417Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.463Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.494Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.533Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.546Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.562Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.582Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.614Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.619Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.635Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.674Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.684Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:03:32.724Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 66
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :samsung-SM-G900F_PT3994
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:03:32.820Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x46
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: S5-1
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 3 peers.
I/SS      ( 3069): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3069): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BtConnection( 3069): connectionTimeoutTimer
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,E/bt-btif ( 3121): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:67, channel:-1
,I/CONNEC  ( 3069): Error: Cancelled
I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:04:23.062Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:23.063Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:23.063Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
W/jxcore-log( 3069): $$jxcore_callback_112 wasn't registered
W/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:28.064Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:28.065Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:33.068Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:33.069Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:33.069Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:33.070Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3121): invalid rfc slot id: 69
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:04:33.118Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:33.118Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:33.119Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:38.121Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:38.122Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:43.124Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:43.125Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:43.125Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:43.126Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3121): invalid rfc slot id: 70
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:04:43.173Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:43.174Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:43.174Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:48.176Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:48.176Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 3 peers.
I/SS      ( 3069): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(2): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7336, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7336, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3069): 2015-11-25T13:04:53.179Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:53.180Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:53.180Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:53.184Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: F8:95:C7:87:3C:51, name: null
,I/        ( 3069): Connecting to null, at F8:95:C7:87:3C:51
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:71, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3121): invalid rfc slot id: 71
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:04:53.234Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:53.234Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:53.250Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:53.253Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:04:53.256Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:53.256Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:53.257Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 3069): Connecting to null, at 7C:F9:0E:51:18:22
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: Connection to F8:95:C7:87:3C:51 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:72, failed to find channle,                                       status:2, scn:-410251100
W/bt-btif ( 3121): invalid rfc slot id: 72
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:04:53.280Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:53.280Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:53.280Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/UsageStatsService(  757): User[0] Flushing usage stats to disk
,I/jxcore-log( 3069): 2015-11-25T13:04:58.280Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:04:58.280Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(2): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3069): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/jxcore-log( 3069): 2015-11-25T13:05:03.286Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:03.287Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:03.287Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:03.288Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 3069): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:73, failed to find channle,                                       status:2, scn:-410251100
,W/bt-btif ( 3121): invalid rfc slot id: 73
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:05:03.339Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:03.340Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:03.349Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:67, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3121): invalid rfc slot id: 67
E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/bt-l2cap( 3121): L2CAP got conn_comp in bad state: 5  status: 0x15
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:05:08.351Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:08.359Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4436","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4436","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4436, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4436, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 3069): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7336, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7336, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/jxcore-log( 3069): 2015-11-25T13:05:13.369Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:13.369Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:13.370Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:13.370Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 3069): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:74, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 74
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:05:15.349Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:15.350Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:15.350Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [08:ec:a9:50:76:27]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/BluetoothEventManager( 3128): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device 08:EC:A9:50:76:27 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for 08:EC:A9:50:76:27, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTListenerThread( 3069): got MESSAGE_READ 83 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : samsung-SM-A300FU_PT5188
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, samsung-SM-A300FU_PT5188
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
,I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T13:05:15.966Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:05:16.353Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.361Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.368Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.378Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.412Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.440Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.461Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.468Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.575Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.614Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.626Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2615","ra":"F8:CF:C5:D9:E5:61"} -- peerIdentifier:F8:CF:C5:D9:E5:61, peerName: motorola-Nexus 6_PT2615, peerAddress: F8:CF:C5:D9:E5:61
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F8:CF:C5:D9:E5:61, Name: motorola-Nexus 6_PT2615, WifiDirectName: Android_50a5, WifiDirect Address: fa:cf:c5:d9:e5:62, peerId: F8:CF:C5:D9:E5:61
,I/jxcore-log( 3069): 2015-11-25T13:05:16.726Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.809Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.935Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:05:16.973Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.064Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.070Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.082Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.093Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.124Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.135Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.253Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.360Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.509Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.579Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.615Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.715Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.753Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.759Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:17.918Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.052Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.112Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.186Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.196Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.203Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.214Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.254Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.294Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.307Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:18.314Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 68
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :samsung-SM-A300FU_PT5188
,I/BtToSocketBase( 3069): Stop ReceivingThread
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:05:18.403Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e50ebc rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x4b
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:05:20.355Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:20.356Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/jxcore-log( 3069): 2015-11-25T13:05:25.360Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:25.364Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:25.365Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:25.368Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 3069): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 76
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:05:29.337Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:29.338Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:29.338Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3069): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(4): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(5): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3069): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(7): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:05:34.339Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:34.340Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:39.347Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:39.347Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:39.348Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:39.348Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 3069): Connecting to null, at 7C:F9:0E:51:18:22
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 77
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:05:40.857Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:40.858Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:40.874Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:40.876Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 7C:F9:0E:51:18:22, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:40.879Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:40.879Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:40.880Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3069): Connecting to null, at B4:CE:F6:AB:A4:6A
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: Connection to 7C:F9:0E:51:18:22 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 78
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:05:44.148Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:44.149Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:44.150Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:05:49.150Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:49.155Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:54.159Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:54.160Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:05:54.160Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:54.160Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3069): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 79
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:05:55.573Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:55.576Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:05:55.579Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:06:00.580Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:00.581Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:05.581Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:05.581Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:05.582Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:05.582Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3069): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 80
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:06:07.104Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:07.105Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:07.106Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:06:12.107Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:12.107Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:17.111Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:17.112Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:17.112Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:17.113Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3069): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 81
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:06:18.633Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:18.634Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:18.635Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:06:23.635Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:23.636Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:28.637Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:28.637Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:28.637Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:28.637Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: B4:CE:F6:AB:A4:6A, name: null
,I/        ( 3069): Connecting to null, at B4:CE:F6:AB:A4:6A
,I/BTConnectToThread( 3069): Starting to connect
,W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 82
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:06:30.205Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:30.206Z SendDataConnector.js: CLIENT Can not Connect: Connection to B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:30.231Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:30.234Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:30.236Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:30.237Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:30.237Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8
,I/        ( 3069): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: Connection to B4:CE:F6:AB:A4:6A failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3069): Cleared service requests
,I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3069): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3069): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(4): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3069): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3069): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [50:2e:6c:ac:21:50]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: HTC One_M8
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e5241c rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
,I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 80 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT2939","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : HTC-HTC One_M8_PT2939
I/HS      ( 3069): Hand Shake finished outgoing for : HTC-HTC One_M8_PT2939
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, HTC-HTC One_M8_PT2939
,I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 37000
I/BtConnectorHelper( 3069): Request socket is using : 37000
I/BtToRequestSocket( 3069): Now accepting connections
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :37000
I/jxcore-log( 3069): 2015-11-25T13:06:33.878Z SendDataConnector.js: CLIENT connected to 37000, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:33.878Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 37000
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T13:06:33.882Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3069): 2015-11-25T13:06:34.212Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18049
,I/jxcore-log( 3069): 2015-11-25T13:06:34.264Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:06:34.418Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8149
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4189
,I/jxcore-log( 3069): 2015-11-25T13:06:34.478Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:34.544Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:34.615Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:34.680Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:34.707Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:34.846Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:34.847Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:34.863Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:34.864Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
I/BtConnectorHelper( 3069): Disconnect outgoing peer: 50:2E:6C:AC:21:50
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
,I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
,I/jxcore-log( 3069): 2015-11-25T13:06:34.889Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:34.898Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:34.898Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:34.898Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: B0:C5:59:3F:75:69, name: Thali Test (Galaxy S5)
,I/        ( 3069): Connecting to Thali Test (Galaxy S5), at B0:C5:59:3F:75:69
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 50:2E:6C:AC:21:50 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/        ( 3069): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT5188, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT5188, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [b0:c5:59:3f:75:69]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3069): HandshakeOk : samsung-SM-G900F_PT4845
I/HS      ( 3069): Hand Shake finished outgoing for : samsung-SM-G900F_PT4845
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, samsung-SM-G900F_PT4845
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 59660
,I/BtConnectorHelper( 3069): Request socket is using : 59660
I/BtToRequestSocket( 3069): Now accepting connections
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :59660
I/jxcore-log( 3069): 2015-11-25T13:06:36.520Z SendDataConnector.js: CLIENT connected to 59660, error: null
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:36.520Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 59660
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T13:06:36.544Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3069): 2015-11-25T13:06:38.151Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: HTC One_M8
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3069): 2015-11-25T13:06:39.422Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:40.261Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:41.378Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=02:ee:bd:dd:33:d2
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/jxcore-log( 3069): 2015-11-25T13:06:42.214Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/jxcore-log( 3069): 2015-11-25T13:06:43.030Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:43.309Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:43.421Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:43.469Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:43.506Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:43.507Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:43.522Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:43.523Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
,I/BtConnectorHelper( 3069): Disconnect outgoing peer: B0:C5:59:3F:75:69
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
I/jxcore-log( 3069): 2015-11-25T13:06:43.554Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:43.556Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:43.557Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:43.557Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 08:EC:A9:50:76:27, name: Thali Test (Galaxy A3)
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,I/        ( 3069): Connecting to Thali Test (Galaxy A3), at 08:EC:A9:50:76:27
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e51b34 rs_disc_pending=1
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 3 peers.
I/SS      ( 3069): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [08:ec:a9:50:76:27]: 7, f, 610c
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT5188","ra":"08:EC:A9:50:76:27"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3069): HandshakeOk : samsung-SM-A300FU_PT5188
I/HS      ( 3069): Hand Shake finished outgoing for : samsung-SM-A300FU_PT5188
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, samsung-SM-A300FU_PT5188
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 46980
I/BtConnectorHelper( 3069): Request socket is using : 46980
I/BtToRequestSocket( 3069): Now accepting connections
,I/        ( 3069): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT9305"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT9305, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT9305, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :46980
I/jxcore-log( 3069): 2015-11-25T13:06:49.055Z SendDataConnector.js: CLIENT connected to 46980, error: null
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:49.056Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 46980
I/BtToRequestSocket( 3069): Set local streams
,I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T13:06:49.082Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:24979
,I/jxcore-log( 3069): 2015-11-25T13:06:49.398Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:15079
,I/jxcore-log( 3069): 2015-11-25T13:06:49.441Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8149
,I/jxcore-log( 3069): 2015-11-25T13:06:49.473Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3199
,I/jxcore-log( 3069): 2015-11-25T13:06:49.548Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:49.624Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:49.745Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:49.759Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:50.056Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:50.056Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:50.074Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:50.074Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
I/BtConnectorHelper( 3069): Disconnect outgoing peer: 08:EC:A9:50:76:27
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
,I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
I/jxcore-log( 3069): 2015-11-25T13:06:50.103Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:50.105Z SendDataConnector.js: Start called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:06:50.106Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:50.115Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 3069): Connecting to XT1072, at 44:80:EB:7B:5A:05
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Thali Test (Galaxy A3)
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 86
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:06:55.263Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:55.264Z SendDataConnector.js: CLIENT Can not Connect: Connection to 44:80:EB:7B:5A:05 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:06:55.265Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:07:00.266Z SendDataConnector.js: re-try now : 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:00.266Z SendDataConnector.js: ReStart called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/        ( 3069): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT4845, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT4845, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3069): 2015-11-25T13:07:05.273Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:05.273Z SendDataConnector.js: Connect (retry count 1) to peer 44:80:EB:7B:5A:05 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:05.274Z SendDataConnector.js: doConnect called with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:05.274Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 44:80:EB:7B:5A:05, name: XT1072
,I/        ( 3069): Connecting to XT1072, at 44:80:EB:7B:5A:05
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [44:80:eb:7b:5a:05]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: XT1072
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3069): Starting to Handshake
,I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3069): MESSAGE_WRITE 77 bytes.
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTConnectToThread( 3069): got MESSAGE_READ 81 bytes.
,I/BTConnectToThread( 3069): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT1876","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3069): HandshakeOk : motorola-XT1072_PT1876
,I/HS      ( 3069): Hand Shake finished outgoing for : motorola-XT1072_PT1876
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : false, motorola-XT1072_PT1876
,I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3069): mHTTPPort  set to : 42375
I/BtConnectorHelper( 3069): Request socket is using : 42375
I/BtToRequestSocket( 3069): Now accepting connections
,I/BtConnectorHelper( 3069): Calling ConnectionStatusUpdate with port :42375
I/jxcore-log( 3069): 2015-11-25T13:07:06.610Z SendDataConnector.js: CLIENT connected to 42375, error: null
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:06.610Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): incoming data from: /127.0.0.1, port: 42375
I/BtToRequestSocket( 3069): Set local streams
I/BtToRequestSocket( 3069): rin ended ---------------------------;
,I/jxcore-log( 3069): 2015-11-25T13:07:06.643Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23717
,I/jxcore-log( 3069): 2015-11-25T13:07:06.817Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:06.948Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12827
,I/jxcore-log( 3069): 2015-11-25T13:07:07.000Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:07.180Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3069): 
,D/        ( 3121): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3917
,I/jxcore-log( 3069): 2015-11-25T13:07:07.338Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:07.428Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:07.488Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:07.528Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:07.643Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:07.644Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:07.659Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:07.660Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3069): 
,I/BtConnectorHelper( 3069): Disconnect outgoing peer: 44:80:EB:7B:5A:05
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
I/BtToRequestSocket( 3069): Close server socket
I/jxcore-log( 3069): 2015-11-25T13:07:07.693Z SendDataConnector.js: Mobile.Disconnect() callback with peer 44:80:EB:7B:5A:05
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:07.696Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:07.696Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:07.696Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 44:80:EB:7B:5A:05 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e515dc rs_disc_pending=0
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: XT1072
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 88
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:07:12.866Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:12.867Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:12.868Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3069): Peer(6): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/jxcore-log( 3069): 2015-11-25T13:07:17.869Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:17.870Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): 2015-11-25T13:07:22.874Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:22.874Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:22.875Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:22.875Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 89
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:07:28.048Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:28.048Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:28.048Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:33.049Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:33.050Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:38.055Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:38.055Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:38.056Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:38.056Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 90
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:07:43.233Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:43.233Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:43.233Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:48.234Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:48.234Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:07:53.238Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:53.238Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:53.239Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:53.239Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 91
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:07:58.413Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:58.413Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:07:58.413Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:08:03.414Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:03.414Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:08:08.417Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:08.418Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:08.418Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:08.419Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: E0:DB:10:1F:C9:5E, name: null
,I/        ( 3069): Connecting to null, at E0:DB:10:1F:C9:5E
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 92
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:08:13.594Z SendDataConnector.js: CLIENT connected to -1, error: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:13.594Z SendDataConnector.js: CLIENT Can not Connect: Connection to E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:08:13.596Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:08:13.598Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 2
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:13.599Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:13.599Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:13.599Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: Connection to E0:DB:10:1F:C9:5E failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
,W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 93
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:08:18.747Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:18.748Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:18.748Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3069): Peer(2): Android_50a5 fa:cf:c5:d9:e5:62
,I/SS      ( 3069): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2993","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT2993","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT2993, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT2993, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/        ( 3069): Found Service, :{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4436","ra":"58:3F:54:73:64:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT4436","ra":"58:3F:54:73:64:C0"} -- peerIdentifier:58:3F:54:73:64:C0, peerName: LGE-LG-D855_PT4436, peerAddress: 58:3F:54:73:64:C0
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 58:3F:54:73:64:C0, Name: LGE-LG-D855_PT4436, WifiDirectName: , WifiDirect Address: 02:9a:02:7b:60:ac, peerId: 58:3F:54:73:64:C0
,I/jxcore-log( 3069): 2015-11-25T13:08:23.749Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:23.750Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:08:28.757Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:28.758Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:28.759Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:28.759Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
,W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 94
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:08:33.944Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:33.944Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:33.945Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 6 peers.
I/SS      ( 3069): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(2): A5-1 7e:f9:0e:37:96:ac
,I/SS      ( 3069): Peer(3): Android_50a5 fa:cf:c5:d9:e5:62
I/SS      ( 3069): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3069): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/jxcore-log( 3069): 2015-11-25T13:08:38.946Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:38.947Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
,I/jxcore-log( 3069): 2015-11-25T13:08:43.949Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:43.950Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:08:43.950Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:43.956Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 95
I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:08:49.129Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:49.129Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:49.129Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:08:54.129Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:54.130Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:3c:51]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/jxcore-log( 3069): 2015-11-25T13:08:59.130Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:59.131Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:59.131Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:08:59.131Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:96, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 96
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:09:08.554Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:08.555Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:08.555Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:09:13.557Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): ,
I/jxcore-log( 3069): 2015-11-25T13:09:13.557Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:09:18.561Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:18.562Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:18.562Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:18.563Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 58:2A:F7:ED:96:BE, name: null
,I/        ( 3069): Connecting to null, at 58:2A:F7:ED:96:BE
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 97
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:09:23.740Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:09:23.740Z SendDataConnector.js: CLIENT Can not Connect: Connection to 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:09:23.759Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:09:23.770Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): ---- round done--------
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 2
I/jxcore-log( 3069): 
I/jxcore-log( 3069): do fake peer & start
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:23.777Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:23.778Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:23.778Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 98
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:09:28.923Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:28.924Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:28.924Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:09:33.925Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:33.926Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 4 peers.
I/SS      ( 3069): Peer(1): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(3): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(4): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:09:38.929Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:38.929Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:38.930Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:38.930Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
,W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3069): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT4845, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT4845, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [80:01:84:8a:b3:68]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 99
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:09:40.659Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:40.660Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:09:40.664Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3069): 2015-11-25T13:09:45.667Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:45.668Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3069): 2015-11-25T13:09:50.671Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:50.671Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:50.672Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:50.672Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3069): timeout now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): dun
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): weAreDoneNow , resultArray.length: 11
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): done, now sending data to server
I/jxcore-log( 3069): 
I/jxcore-log( 3069): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): -- RESULT DATA {"name:":"LGE-Nexus 5_PT1775","time":1000165,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:9D:93:0B","time":5189,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"00:F4:6F:30:E0:6C","time":6158,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:CF:C5:D9:E5:61","time":5586,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":2640,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":1853,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F4:F1:E1:5C:3B:E2","time":7216,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":11397,"result":"OK","connections":1,"tryCount":1,"d
I/jxcore-log( 3069): sendList : 100% : 17538 ms, 99% : 17538 ms, 95 : 11397 ms, 90% : 11397 ms.
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Result count 11, range 1853 ms to  17538 ms.
I/jxcore-log( 3069): 
I/jxcore-log( 3069): sendList failed peers count : 10 [47.61904761904762 %]
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : 80:01:84:8A:B3:68, Tried : 2
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : F8:95:C7:87:85:54, Tried : 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : E0:DB:10:14:E2:C0, Tried : 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : 7C:F9:0E:51:18:22, Tried : 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 2
I/jxcore-log( 3069): 
I/jxcore-log( 3069): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 2
I/jxcore-log( 3069): 
I/jxcore-log( 3069): sendList never tried peers count : 0 [0 %]
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:51.043Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:51.044Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3121): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 100
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3069): 2015-11-25T13:09:55.846Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:55.847Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:09:55.848Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:10:00.849Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:00.850Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/        ( 3069): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT4845","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT4845, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT4845, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e52ecc rs_disc_pending=1
E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G4-1
,I/        ( 3069): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3994","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT3994","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT3994, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT3994, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3069): 2015-11-25T13:10:05.853Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:05.853Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:05.854Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:05.854Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [80:01:84:8a:b3:68]: 7, f, 6109
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3121): process_service_search_attr_rsp
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 101
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:10:06.139Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:06.140Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:10:06.140Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:3c:51]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G4-1
,I/jxcore-log( 3069): 2015-11-25T13:10:11.144Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:11.144Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTListenerThread( 3069): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1856","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1856
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, LGE-LG-H815_PT1856
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:10:16.140Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:10:16.145Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:16.145Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:16.145Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:16.145Z SendDataConnector.js: do connect now
I/jxcore-log( 3069): 
,I/        ( 3069): Selected device address: 80:01:84:8A:B3:68, name: null
,I/        ( 3069): Connecting to null, at 80:01:84:8A:B3:68
,I/BTConnectToThread( 3069): Starting to connect
W/BluetoothAdapter( 3069): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3121): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/EventLogService( 1612): Aggregate from 1448455216749 (log), 1448455216749 (data)
,I/art     ( 1612): Explicit concurrent mark sweep GC freed 26380(1744KB) AllocSpace objects, 20(320KB) LOS objects, 24% free, 22MB/29MB, paused 460us total 34.382ms
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3069): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(4): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(5): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/        ( 3069): Started service discovery
,W/bt-btif ( 3121): dm_pm_timer expires
W/bt-btif ( 3121): dm_pm_timer expires 0
W/bt-btif ( 3121): proc dm_pm_timer expires
,E/bt-btif ( 3121): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3121): invalid rfc slot id: 103
,I/BTConnectToThread( 3069): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3069): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3069): 2015-11-25T13:10:26.067Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:26.068Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3069): 
I/jxcore-log( 3069): 2015-11-25T13:10:26.069Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:10:26.075Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3069): 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 3 peers.
I/SS      ( 3069): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}, typeCordovap2p._tcp.local.:
,I/        ( 3069): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7336, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7336, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(3): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3069): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}, typeCordovap2p._tcp.local.:
,I/        ( 3069): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7336, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7336, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(3): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3069): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3069): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"}, typeCordovap2p._tcp.local.:
I/        ( 3069): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7336"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT7336, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3069): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT7336, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3069): Found 7 peers.
,I/SS      ( 3069): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3069): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(3): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3069): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
,I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,E/bt-btm  ( 3121): tBTM_SEC_DEV:0xa3e52ecc rs_disc_pending=1
,W/bt-btif ( 3121): invalid rfc slot id: 75
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1856
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3121): bta_dm_check_av:0
,W/bt-btif ( 3121): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3121): onReceive
,I/jxcore-log( 3069): 2015-11-25T13:12:21.222Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G4-1
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G4-1
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: F8:95:C7:87:3C:51
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device F8:95:C7:87:3C:51 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,E/BluetoothEventManager( 3128): Got bonding state changed for F8:95:C7:87:3C:51, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT1856","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : LGE-LG-H815_PT1856
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, LGE-LG-H815_PT1856
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/jxcore-log( 3069): 2015-11-25T13:12:32.708Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:12:33.207Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.358Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.362Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.366Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.369Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.584Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.592Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.625Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.744Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.749Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.795Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:33.804Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.057Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.068Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.076Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.215Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.536Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.545Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.678Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.725Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:34.923Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.044Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.096Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.111Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.144Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3069): 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3069): 2015-11-25T13:12:35.434Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.439Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.485Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.523Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.547Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.665Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.717Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.770Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.785Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:35.954Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:36.013Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:36.168Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:36.173Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:36.316Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:36.409Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:36.458Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:36.466Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 102
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1856
,I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT1856
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/jxcore-log( 3069): 2015-11-25T13:12:36.616Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: G4-1
,I/art     (  757): Explicit concurrent mark sweep GC freed 67294(3MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 28MB/42MB, paused 1.037ms total 103.856ms
,W/bt-btif ( 3121): info:x10
,D/        ( 3121): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 3121): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
E/bt-btif ( 3121): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3121): Entering PendingCommandState State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,I/BluetoothBondStateMachine( 3121): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3121): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3121): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3121): StableState(): Entering Off State
,W/BluetoothEventManager( 3128): CachedBluetoothDevice for device E0:DB:10:1F:C9:5E not found, calling readPairedDevices().
,E/BluetoothEventManager( 3128): Got bonding state changed for E0:DB:10:1F:C9:5E, but we have no record of that device.
,W/bt-btif ( 3121): new conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3121): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3069): we got incoming connection
I/BTHandshakeSocketThread( 3069): Creating BTHandshakeSocketThread
I/BTListenerThread( 3069): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread started
,I/BTListenerThread( 3069): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3069): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT1333","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3069): MESSAGE_WRITE 77 bytes.
I/HS      ( 3069): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT1333
I/BTHandshakeSocketThread( 3069): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3069): Starting the connected thread incoming : true, samsung-SM-N9005_PT1333
I/BtToSocketBase( 3069): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3069): Creating BTConnectedThread
I/BtConnectorHelper( 3069): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3069): --DoOneRunRound started
,I/BtToRequestSocket( 3069): LocalHost address: localhost/127.0.0.1, port: 43463
,I/jxcore-log( 3069): 2015-11-25T13:12:57.491Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3069): 
,I/BtToRequestSocket( 3069): --DoOneRunRound ended
,I/jxcore-log( 3069): 2015-11-25T13:12:57.937Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:57.942Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:57.995Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.012Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.020Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.034Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.062Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.087Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.118Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.135Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.164Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.173Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.197Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.223Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.262Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.272Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.302Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.309Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.365Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.375Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.389Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.423Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.448Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.489Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.527Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:12:58.542Z SendDataTCPServer.js: TCP/IP server has received 100002 bytes of data
I/jxcore-log( 3069): 
,W/bt-btif ( 3121): invalid rfc slot id: 104
,I/BtToSocketBase( 3069): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3069): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT1333
I/BtToSocketBase( 3069): Stop ReceivingThread
I/BtToSocketBase( 3069): Stop SendingThread
I/BtToSocketBase( 3069): Close local in
I/BtToSocketBase( 3069): Close LocalOutputStream
I/BtToSocketBase( 3069): Close localHostSocket
I/BtToSocketBase( 3069): Close bt in
I/BtToSocketBase( 3069): Close bt out
I/BtToSocketBase( 3069): Close bt socket
,I/BtToSocketBase( 3069): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3069): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3069): 2015-11-25T13:12:58.618Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3069): 
,W/bt-rfcomm( 3121): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3121): RFCOMM_DisconnectInd LCID:0x42
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 7 peers.
I/SS      ( 3069): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3069): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(3): G3-1 02:9a:02:7b:60:ac
I/SS      ( 3069): Peer(4): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(5): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(6): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3069): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3121): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3121): onReceive
,I/BTConnectionReceiver( 1383): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1383): Bluetooth Device Name: Note3-1
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/        ( 3069): Cleared service requests
I/        ( 3069): Started peer discovery
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3069): Found 5 peers.
I/SS      ( 3069): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3069): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3069): Peer(3): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3069): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3069): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3069): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3069): Added service request
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3127): p2p0: P2P: Reject scan trigger since one is already pending
,I/        ( 3069): Started service discovery
,I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3127): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3069): DBG, CoordinatorConnector command called
I/jxcore-log( 3069): 
I/jxcore-log( 3069): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): stop tests now !
I/jxcore-log( 3069): 
I/jxcore-log( 3069): stop current!
I/jxcore-log( 3069): 
I/jxcore-log( 3069): testSendData stopped
I/jxcore-log( 3069): 
,I/        ( 3069): Stoping All
I/        ( 3069): Stopping services
I/        ( 3069): Stopping services
,I/wpa_supplicant( 3127): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3127): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/        ( 3069): Stop Bluetooth
I/        ( 3069): Stop Bluetooth
I/BTListenerThread( 3069): Stopped
,I/jxcore-log( 3069): StopBroadcasting went ok
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): 2015-11-25T13:14:10.866Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3069): 
I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3069): Cleared local services
I/        ( 3069): Cleared service requests
I/        ( 3069): Stopped peer discovery
,I/jxcore-log( 3069): DBG, CoordinatorConnector command called
I/jxcore-log( 3069): 
I/jxcore-log( 3069): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"58:3F:54:73:64:C0\",\"time\":1853,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"7C:F9:0E:34:8A:A0\",\"time\":2640,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"50:2E:6C:AC:21:50\",\"time\":4611,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"34:FC:EF:9D:93:0B\",\"time\":5189,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"F8:CF:C5:D9:E5:61\",\"time\":5586,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\":6158,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAm
I/jxcore-log( 3069): ****TEST TOOK:  ms ****
I/jxcore-log( 3069): 
I/jxcore-log( 3069): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3069): 
I/jxcore-log( 3069): stop tests now !
I/jxcore-log( 3069): 
I/jxcore-log( 3069): end, event received
I/jxcore-log( 3069): 
I/jxcore-log( 3069): CoordinatorConnector close called
I/jxcore-log( 3069): 
,I/jxcore-log( 3069): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3069): 
I/jxcore-log( 3069): The Coordinator has disconnected!
I/jxcore-log( 3069): 
I/jxcore-log( 3069): The Coordinator has closed!
I/jxcore-log( 3069): 
I/jxcore-log( 3069): stop tests now !
I/jxcore-log( 3069): 
I/jxcore-log( 3069): turning Radios off
I/jxcore-log( 3069): 
I/jxcore-log( 3069): Toggling radios to false
I/jxcore-log( 3069): 
D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@33fb596a mBinding = false
,D/BluetoothManagerService(  757): Message: 2
,D/BluetoothManagerService(  757): Sending off request.
,D/BluetoothAdapterState( 3121): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3121): Setting state to 13
I/BluetoothAdapterState( 3121): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3121): onBluetoothDisable()
I/BluetoothAdapterState( 3121): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3121): Scan Mode:20
,D/BluetoothAdapterState( 3121): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 3121): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3121): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3121): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3121): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3121): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3121): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3121): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3121): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3121): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3121): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3121): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
W/bt-l2cap( 3121): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3121): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 3121): onReceive
D/BluetoothMapService( 3121): STATE_TURNING_OFF
V/BluetoothMapService( 3121): Handler(): got msg=4
D/BluetoothMapService( 3121): MAP Service closeService in
D/BluetoothMapMasInstance( 3121): MAP Service shutdown
V/BluetoothMapService( 3121): MAP Service closeService out
,I/BtOppRfcommListener( 3121): stopping Accept Thread
,I/BtOppRfcommListener( 3121): BluetoothSocket listen thread finished
,D/WifiService(  757): setWifiEnabled: false pid=3069, uid=10270
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 3128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/DockEventReceiver( 3128): finishStartingService: stopping service
,D/BluetoothPbap( 3128): Proxy object disconnected
D/PbapServerProfile( 3128): Bluetooth service disconnected
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/bt_userial( 3121): RX termination
W/bt_userial( 3121): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3121): Leaving userial_read_thread()
,W/bt-btif ( 3121): ag scb idx 1 not allocated
E/bt-btif ( 3121): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3121): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3121): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3121): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3121): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3121): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3121): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 3121): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 3121): hw_epilog_process
I/bt_userial_vendor( 3121): device fd = 53 close
,I/GKI_LINUX( 3121): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3121): GKI_exit_task 0 done
,I/GKI_LINUX( 3121): GKI_shutdown(): task [BTU] terminated
,E/WifiStateMachine(  757): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/BluetoothAdapterState( 3121): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,E/native  (  757): do suspend true
,I/jxcore-log( 3069): Radios toggled
I/jxcore-log( 3069): 
,I/chromium( 3069): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/HeadsetService( 3121): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
D/BluetoothAdapterState( 3121): Stopping profile services that were post enabled
,D/HeadsetStateMachine( 3121): Exit Disconnected: -1
,D/BluetoothHeadset( 3128): Proxy object disconnected
D/HeadsetProfile( 3128): Bluetooth service disconnected
D/BluetoothHeadset( 1186): Proxy object disconnected
D/BluetoothHeadset( 1186): Proxy object disconnected
,D/A2dpService( 3121): Received stop request...Stopping profile...
D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/A2dpStateMachine( 3121): Exit Disconnected: -1
,D/BluetoothHeadset( 1229): Proxy object disconnected
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
D/BluetoothHeadset(  757): Proxy object disconnected
D/BluetoothA2dp(  757): Proxy object disconnected
D/HidService( 3121): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
D/HealthService( 3121): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
,D/PanService( 3121): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
D/BluetoothA2dp( 3128): Proxy object disconnected
D/A2dpProfile( 3128): Bluetooth service disconnected
D/BluetoothInputDevice( 3128): Proxy object disconnected
D/HidProfile( 3128): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 3121): handleDebugAction() action=null
D/BtGatt.GattService( 3121): Received stop request...Stopping profile...
D/BtGatt.GattService( 3121): stop()
D/BtGatt.AdvertiseManager( 3121): advertise clients cleared
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
D/BluetoothMapService( 3121): Received stop request...Stopping profile...
D/BluetoothMapService( 3121): stop()
D/BluetoothMapEmailAppObserver( 3121): deinitObservers()
D/BluetoothMapEmailAppObserver( 3121): removeReceiver()
D/BluetoothAdapterService( 3121): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@96cffee
D/HeadsetStateMachine( 3121): Unbinding service...
W/BluetoothHeadsetServiceJni( 3121): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3121): Cleaning up Bluetooth Handsfree callback object
I/GKI_LINUX( 3121): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3121): GKI_exit_task 2 done
I/GKI_LINUX( 3121): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3121): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3121): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3121): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3121): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3121): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3121): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3121): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 3121): Handler(): got msg=4
D/BluetoothMapService( 3121): MAP Service closeService in
V/BluetoothMapService( 3121): MAP Service closeService out
,D/BluetoothAdapterState( 3121): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3121): Setting state to 10
I/BluetoothAdapterState( 3121): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  757): Message: 60
D/BluetoothManagerService(  757): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  757): Broadcasting onBluetoothStateChange(false) to 11 receivers.
,D/BluetoothMapService( 3121): cleanup()
D/BluetoothMapService( 3121): MAP Service closeService in
V/BluetoothMapService( 3121): MAP Service closeService out
,I/BluetoothAdapterState( 3121): Entering OffState
,D/BluetoothInputDevice( 3128): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  757): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  757): onBluetoothStateChange: up=false
,D/BluetoothMap( 3128): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1229): onBluetoothStateChange: up=false
,V/NativeCrypto( 1355): Read error: ssl=0x9b34b200: I/O error during system call, Connection timed out
D/BluetoothA2dp( 3128): onBluetoothStateChange: up=false
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  757): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
E/WifiConfigStore(  757): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  757): scanCount==0 - aborting
,D/WifiNetworkAgent(  757): NetworkAgent: NetworkAgent channel lost
,D/BluetoothHeadset( 3128): onBluetoothStateChange: up=false
,D/BluetoothPbap( 3128): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  757): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  757): Broadcasting onBluetoothServiceDown() to 11 receivers.
,D/WifiScanningService(  757): SCAN_AVAILABLE : 1
D/RttService(  757): SCAN_AVAILABLE : 1
,D/WifiScanningService(  757): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  757): DefaultState
,D/BluetoothManagerService(  757): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@33fb596a mBinding = false
,D/BluetoothManagerService(  757): Sending unbind request.
D/BluetoothManagerService(  757): Bluetooth State Change Intent: 13 -> 10
,D/RttService(  757): EnabledState got{ when=-13ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
E/native  (  757): do suspend true
,D/BluetoothAdapter(  897): 141090627: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  897): 141090627: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  897): 141090627: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1318): 687480276: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1318): 687480276: getState() :  mService = null. Returning STATE_OFF
,D/AndroidRuntime( 3848): 
D/AndroidRuntime( 3848): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,V/NativeCrypto( 1355): SSL shutdown failed: ssl=0x9b34b200: I/O error during system call, Broken pipe
D/AndroidRuntime( 3848): CheckJNI is OFF
D/CommandListener(  178): Clearing all IP addresses on wlan0
D/ConnectivityService(  757): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  757): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  897): CM callback handler got msg 524292
D/Nat464Xlat(  757): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  757): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Forcing reevaluation
D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Disconnected - quitting
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  757): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/GKI_LINUX( 3121): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3121): GKI_exit_task 1 done
,I/GKI_LINUX( 3121): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3121): cleanupNative: return from cleanup
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  757): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/ConnectivityService(  757): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1229): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  757): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,W/ContextImpl( 3128): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/art     ( 3121): System.exit called, status: 0
I/AndroidRuntime( 3121): VM exiting with result code 0, cleanup skipped.
,D/DockEventReceiver( 3128): finishStartingService: stopping service
,D/AndroidRuntime( 3848): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  757): Process com.android.bluetooth (pid 3121) has died
,D/BluetoothAdapter( 3128): 979769705: getState() :  mService = null. Returning STATE_OFF
,I/wpa_supplicant( 3127): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3127): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,I/ActivityManager(  757): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3894 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
,I/ActivityManager(  757): Killing 3069:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,W/PackageSettings(  757): Skipping PackageSetting{332ec131 com.example.hello/10277} due to missing metadata
,I/WindowState(  757): WIN DEATH: Window{1c78cf9b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  757): Client connection lost with reason: 4
,D/Tethering(  757): InitialState.processMessage what=4
,I/wpa_supplicant( 3127): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  757):   Force finishing activity ActivityRecord{39073497 u0 com.test.thalitest/.MainActivity t214}
,W/ActivityManager(  757): Spurious death for ProcessRecord{32141aa4 3069:com.test.thalitest/u0a270}, curProc for 3069: null
,I/ActivityManager(  757): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  757):   Force finishing activity ActivityRecord{39073497 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  757): Duplicate finish request for ActivityRecord{39073497 u0 com.test.thalitest/.MainActivity t214 f}
,D/Tethering(  757): sendTetherStateChangedBroadcast 0, 0, 0
,I/Keyboard.Facilitator( 1091): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1318): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1279): Explicit concurrent mark sweep GC freed 3956(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 537us total 29.218ms
,W/ResourcesManager( 3894): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
,I/LibraryLoader( 1433): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
,W/Settings( 1858): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings( 1318): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/OpenGLRenderer(  941): Initialized EGL, version 1.4
,D/OpenGLRenderer(  941): Enabling debug mode 0
,I/Keyboard.Facilitator.DecoderInitializer( 1091): run()
,I/Decoder ( 1091): createOrResetDecoder
,W/art     (  941): Attempt to remove local handle scope entry from IRT, ignoring
,D/AdapterServiceConfig( 3894): Adding HeadsetService
D/AdapterServiceConfig( 3894): Adding A2dpService
,D/AdapterServiceConfig( 3894): Adding HidService
D/AdapterServiceConfig( 3894): Adding HealthService
D/AdapterServiceConfig( 3894): Adding PanService
D/AdapterServiceConfig( 3894): Adding GattService
D/AdapterServiceConfig( 3894): Adding BluetoothMapService
,I/ActivityManager(  757): Killing 2952:com.android.musicfx/u0a15 (adj 15): empty #17
I/art     (  757): Explicit concurrent mark sweep GC freed 33078(1879KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.814ms total 136.215ms
,I/LibraryLoader( 1433): Time to load native libraries: 71 ms (timestamps 3839-3910)
,I/LibraryLoader( 1433): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/art     (  757): WaitForGcToComplete blocked for 100.962ms for cause Explicit
I/chromium( 1433): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1433): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 1433): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 1383): Explicit concurrent mark sweep GC freed 87539(3MB) AllocSpace objects, 21(336KB) LOS objects, 25% free, 19MB/25MB, paused 717us total 148.521ms
,D/AuthorizationBluetoothService( 1355): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup(  757): failed to open /acct/uid_10015/pid_2952/cgroup.procs: No such file or directory
,I/ConfigService( 1355): onCreate
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
,D/BluetoothAdapter( 3128): 979769705: getState() :  mService = null. Returning STATE_OFF
,W/InputMethodManagerService(  757): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@3691ea82 (uid=10034 pid=941)
,W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 3069 uid 10270
,I/Keyboard.Facilitator( 1091): onFinishInput()
D/TaskPersister(  757): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1091): run()
,D/VoicemailCleanupService( 1362): Cleaning up data for package: com.test.thalitest
,I/art     (  757): Explicit concurrent mark sweep GC freed 5792(313KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 2.672ms total 139.130ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1091): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1091): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1091): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1091): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1091): run()
I/StatsUtilsManager( 1091): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1091): shouldRecordStats() = Too Soon
,I/ActivityManager(  757): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=3937 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/Launcher( 1279): Deferring update until onResume
,W/ResourcesManager( 1279): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3848): Shutting down VM
,W/ResourcesManager( 1279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1383): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/Launcher( 1279): Deferring update until onResume
,W/Launcher( 1279): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@96cffee new=com.google.android.velvet.VelvetApplication@96cffee
,I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3962 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 2981:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10040/pid_2981/cgroup.procs: No such file or directory
,W/ContextImpl( 3962): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/UpdateIcingCorporaServi( 1383): UpdateCorporaTask done [took 106 ms] updated apps [took 106 ms] 
,D/PackageBroadcastService( 1612): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1612): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1612): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1612): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1612): Removing dialog suppression flag for package com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1355): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1355): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1612): 0 metrics were deleted when clearing package com.test.thalitest.
,D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  757): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3987 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1612): Using Auth Proxy for data requests.
,W/BaseAppContext( 1612): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1612): App measurement is starting up
,I/PeopleContactsSync( 1612): CP2 sync disabled
,I/Icing   ( 1612): doRemovePackageData com.test.thalitest

```
