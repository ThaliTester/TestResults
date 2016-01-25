#### Test 57132760f6ec045_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1551): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1551): Module APK com.google.android.play.games already loaded
I/GAv4    ( 2915): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2915):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2915):   adb logcat -s GAv4
W/GAv4    ( 2915): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2915): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2915): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2915): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2409): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  735): Killing 2333:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/ResourcesManager( 2915): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2915): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 2969): 
D/AndroidRuntime( 2969): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2969): CheckJNI is OFF
W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_2333/cgroup.procs: No such file or directory
V/JNIHelp ( 2915): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2915): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2915): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2969): Calling main entry com.android.commands.am.Am
V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  735): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  735): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2997 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2969): Shutting down VM
V/ActivityManager(  735): Display changed displayId=0
I/Icing   ( 1551): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/WebViewFactory( 2997): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1551): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1551): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/LibraryLoader( 2997): Time to load native libraries: 2 ms (timestamps 5700-5702)
I/LibraryLoader( 2997): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2997): Binding Chromium to main looper Looper (main, tid 1) {21fb2486}
I/LibraryLoader( 2997): Expected native library version number "",actual native library version number ""
I/chromium( 2997): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Icing   ( 1551): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
I/BrowserStartupController( 2997): Initializing chromium process, singleProcess=true
W/art     ( 2997): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2997): ApplicationContext is null in ApplicationStatus
,W/chromium( 2997): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2997): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2997): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2997): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2997): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  735): Message: 20
,D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f98fde3:true
,D/BluetoothAdapter( 2997): 1039609056: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2997): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2997): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2997): CordovaWebView is running on device made by: LGE
,W/art     ( 2997): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 2997): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2997): Render dirty regions requested: true
,D/Atlas   ( 2997): Validating map...
,W/chromium( 2997): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2997): Initialized EGL, version 1.4
D/OpenGLRenderer( 2997): Enabling debug mode 0
,W/IInputConnectionWrapper( 2997): showStatusIcon on inactive InputConnection
,I/ActivityManager(  735): Displayed com.test.thalitest/.MainActivity: +449ms (total +54s78ms)
,W/BindingManager( 2997): Cannot call determinedVisibility() - never saw a connection for the pid: 2997
,D/JsMessageQueue( 2997): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2997): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1547270016
,I/chromium( 2997): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  735): Killing 2378:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_2378/cgroup.procs: No such file or directory
,W/jxcore-log( 2997): Initializing JXcore engine
W/jxcore-log( 2997): JXcore engine is ready
,W/Thread-276( 3053): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7999]" dev="sockfs" ino=7999 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-276( 3053): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-276( 3053): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6612]" dev="sockfs" ino=6612 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/Thread-276( 3053): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17370]" dev="sockfs" ino=17370 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2997): Starting JXcore engine
,W/jxcore-log( 2997): Platform android
W/jxcore-log( 2997): 
W/jxcore-log( 2997): Process ARCH arm
W/jxcore-log( 2997): 
,I/jxcore-log( 2997): JXcore Cordova bridge is ready!
I/jxcore-log( 2997): 
,W/jxcore-log( 2997): JXcore engine is started
,I/jxcore-log( 2997): Toggling radios to true
I/jxcore-log( 2997): 
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  735): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  735): Message: 1
D/BluetoothManagerService(  735): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  735): New client listening to asynchronous messages
,D/WifiService(  735): setWifiEnabled: true pid=2997, uid=10270
E/WifiService(  735): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  180): Softap fwReload - Ok
,D/CommandListener(  180): Setting iface cfg
D/CommandListener(  180): Trying to bring down wlan0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,I/ActivityManager(  735): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3056 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/WifiMonitor(  735): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  735): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/jxcore-log( 2997): Radios toggled
I/jxcore-log( 2997): 
,I/jxcore-log( 2997): My device name is: LGE-Nexus 5
I/jxcore-log( 2997): 
I/ActivityManager(  735): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3074 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
I/wpa_supplicant( 3062): Successfully initialized wpa_supplicant
W/ResourcesManager( 3056): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
I/wpa_supplicant( 3062): rfkill: Cannot open RFKILL control device
D/AdapterServiceConfig( 3056): Adding HeadsetService
D/AdapterServiceConfig( 3056): Adding A2dpService
D/AdapterServiceConfig( 3056): Adding HidService
D/AdapterServiceConfig( 3056): Adding HealthService
D/AdapterServiceConfig( 3056): Adding PanService
D/AdapterServiceConfig( 3056): Adding GattService
D/AdapterServiceConfig( 3056): Adding BluetoothMapService
D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8c71ce6:true
D/BluetoothAdapter( 3074): 570107014: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  735): Message: 30
D/BluetoothManagerService(  735): Message: 30
D/LocalBluetoothProfileManager( 3074): Adding local MAP profile
D/BluetoothMap( 3074): Create BluetoothMap proxy object
D/BluetoothManagerService(  735): Message: 30
D/BluetoothManagerService(  735): Message: 30
D/LocalBluetoothProfileManager( 3074): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3074): 570107014: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3074): 570107014: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  735): Message: 20
D/BluetoothManagerService(  735): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19ef9304:true
D/BluetoothAdapterState( 3056): make
I/bluedroid( 3056): init
I/BluetoothAdapterState( 3056): Entering OffState
I/bte_conf( 3056): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bte_conf( 3056): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3056): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3056): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3056): get_profile_interface socket
I/bluedroid( 3056): get_profile_interface map_client
I/GKI_LINUX( 3056): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3056): Address is:34:FC:EF:11:AE:67
I/ActivityManager(  735): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3109 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  735): Killing 1765:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
W/libprocessgroup(  735): failed to open /acct/uid_10045/pid_1765/cgroup.procs: No such file or directory
D/BluetoothAdapterProperties( 3056): Name is: Nexus 5
D/BluetoothManagerService(  735): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  735): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  735): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  735): Message: 40
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3056): config_hci_snoop_log
D/BluetoothManagerService(  735): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  735): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothAdapterState( 3056): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3056): Setting state to 11
I/BluetoothAdapterState( 3056): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  735): Message: 60
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  735): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3056): make
I/BluetoothBondStateMachine( 3056): StableState(): Entering Off State
D/BluetoothHeadset( 1167): Proxy object connected
D/BluetoothHeadset( 1210): Proxy object connected
D/BluetoothHeadset( 1167): Proxy object connected
D/BluetoothHeadset(  735): Proxy object connected
D/HeadsetService( 3056): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3056): classInitNative: succeeds
I/BluetoothAdapterState( 3056): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 3056): make
D/HeadsetStateMachine( 3056): max_hf_connections = 1
I/bluedroid( 3056): get_profile_interface handsfree
D/HeadsetStateMachine( 3056): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b39147
D/BluetoothA2dp(  735): Proxy object connected
D/A2dpService( 3056): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3056): classInitNative: succeeds
I/bluedroid( 3056): get_profile_interface avrcp
E/RemoteController( 3056): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3056): classInitNative: succeeds
D/A2dpStateMachine( 3056): make
I/bluedroid( 3056): get_profile_interface a2dp
I/GKI_LINUX( 3056): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b39147
I/BluetoothHidServiceJni( 3056): classInitNative: succeeds
D/A2dpStateMachine( 3056): Enter Disconnected: -2
D/BluetoothInputDevice( 3074): Proxy object connected
D/HidService( 3056): Received start request. Starting profile...
I/bluedroid( 3056): get_profile_interface hidhost
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b39147
I/BluetoothHealthServiceJni( 3056): classInitNative: succeeds
D/HealthService( 3056): Received start request. Starting profile...
D/HidProfile( 3074): Bluetooth service connected
I/bluedroid( 3056): get_profile_interface health
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b39147
I/BluetoothPanServiceJni( 3056): classInitNative(L105): succeeds
D/BluetoothPan( 3074): BluetoothPAN Proxy object connected
D/PanService( 3056): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3056): initializeNative(L110): pan
I/bluedroid( 3056): get_profile_interface pan
D/PanProfile( 3074): Bluetooth service connected
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b39147
I/BtGatt.JNI( 3056): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3056): handleDebugAction() action=null
D/BtGatt.GattService( 3056): Received start request. Starting profile...
D/BtGatt.GattService( 3056): start()
I/bluedroid( 3056): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3056): advertise manager created
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b39147
V/BluetoothMapService( 3056): BluetoothMapBinder()
D/BluetoothMap( 3074): Proxy object connected
D/BluetoothMapService( 3056): Received start request. Starting profile...
D/BluetoothMapService( 3056): start()
D/MapProfile( 3074): Bluetooth service connected
D/BluetoothMap( 3074): getConnectedDevices()
D/BluetoothMap( 3074): Bluetooth is Not enabled
D/BluetoothMapEmailSettingsLoader( 3056): Found 0 applications
D/BluetoothMapEmailAppObserver( 3056): createReceiver()
D/BluetoothMapEmailAppObserver( 3056): initObservers()
D/BluetoothMapEmailAppObserver( 3056): getEnabledAccountItems()
D/BluetoothAdapterService( 3056): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2b39147
D/HeadsetStateMachine( 3056): Proxy object connected
D/HeadsetStateMachine( 3056): Disconnected process message: 10, size: 0
V/BluetoothMapService( 3056): Handler(): got msg=1
D/HeadsetPhoneState( 3056): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 3056): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3056): enable
D/HeadsetStateMachine( 3056): Disconnected process message: 11, size: 0
I/GKI_LINUX( 3056): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3056): btu_task pending for preload complete event
I/bt_hci_bdroid( 3056): init
I/bt_vendor( 3056): init
I/bt_vnd_conf( 3056): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3056): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3056): userial_init
I/bt_userial_vendor( 3056): userial vendor open: opening /dev/ttyHS99
I/bt_userial_vendor( 3056): device fd = 53 open
D/bt_userial( 3056): Entering userial_read_thread()
I/art     (  735): Explicit concurrent mark sweep GC freed 15923(815KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.458ms total 82.409ms
I/bt_hwcfg( 3056): bt vendor lib: set UART baud 4000000
D/bt_hwcfg( 3056): Chipset BCM4335C0
D/bt_hwcfg( 3056): Target name = [BCM4335C0]
I/bt_hwcfg( 3056): Found patchfile: /vendor/firmware//bcm4335c0.hcd
I/art     ( 1458): Explicit concurrent mark sweep GC freed 1381(47KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 224us total 10.144ms
D/AuthorizationBluetoothService( 1280): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  735): Killing 2478:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
W/libprocessgroup(  735): failed to open /acct/uid_10003/pid_2478/cgroup.procs: No such file or directory
D/Tethering(  735): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 3062): rfkill: Cannot open RFKILL control device
I/bt_hwcfg( 3056): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3056): Settlement delay -- 100 ms
I/bt_hwcfg( 3056): Setting fw settlement delay to 100 
I/wpa_supplicant( 3062): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiConfigStore(  735): Loading config and enabling all networks 
D/WifiService(  735): New client listening to asynchronous messages
E/WifiConfigStore(  735): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/Settings( 2297): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  735): Setting external_sim to 1
D/WifiStateMachine(  735): Setting OUI to DA-A1-19
I/WifiNative-HAL(  735): startHal
D/wifi    (  735): setting scan oui 0x9239e7c0
D/WifiHAL (  735): Sending mac address OUI
E/WifiHAL (  735): failed to set scanning mac OUI; result = -95
E/native  (  735): do suspend true
D/WifiScanningService(  735): SCAN_AVAILABLE : 3
D/RttService(  735): SCAN_AVAILABLE : 3
D/WifiScanningService(  735): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  735): startHal
D/RttService(  735): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  180): Setting iface cfg
I/bt_hwcfg( 3056): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3056): Setting local bd addr to 34:FC:EF:11:AE:67
D/CommandListener(  180): Trying to bring up p2p0
D/wifi    (  735): getting scan capabilities on interface[1] = 0x9239e7c0
D/WifiHAL (  735): Creating message to get scan capablities; iface = 21
D/WifiHAL (  735): In GetCapabilities::handleResponse
D/WifiHAL (  735): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  735): StartedState
D/WifiMonitor(  735): startMonitoring(p2p0) with mConnected = true
I/wpa_supplicant( 3062): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
I/bt_hwcfg( 3056): vendor lib fwcfg completed
I/bt-btu  ( 3056): btu_task received preload complete event
D/WifiNative-HAL(  735): p2pGetDeviceAddress
D/WifiNative-HAL(  735): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
I/        ( 3056): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3056): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3056): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3056): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3056): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3056): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3056): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3056): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3056): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3056): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3056): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3056): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3056): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3056): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3056): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3056): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 3056): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3056): Calling BTA_HhEnable
E/bt-btif ( 3056): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3056): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3056): Name is: Nexus 5
D/BluetoothManagerService(  735): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  735): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3056): Scan Mode:20
D/BluetoothAdapterProperties( 3056): Discoverable Timeout:120
D/bte_conf( 3056): Device ID record 1 : primary
D/bte_conf( 3056):   vendorId            = 000f
D/bte_conf( 3056):   vendorIdSource      = 0001
D/bte_conf( 3056):   product             = 1200
D/bte_conf( 3056):   version             = 1436
D/bte_conf( 3056):   clientExecutableURL = 
D/bte_conf( 3056):   serviceDescription  = 
D/bte_conf( 3056):   documentationURL    = 
D/bte_conf( 3056): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 3056): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3056): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3056): ScanMode =  20
D/BluetoothAdapterProperties( 3056): State =  11
D/BluetoothAdapterProperties( 3056): Setting state to 12
I/BluetoothAdapterState( 3056): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  735): Message: 60
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 3056): Entering On State
D/BluetoothAdapterProperties( 3056): Scan Mode:21
D/BluetoothAdapterProperties( 3056): Discoverable Timeout:120
D/BluetoothManagerService(  735): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothA2dp(  735): onBluetoothStateChange: up=true
D/BluetoothMap( 3074): onBluetoothStateChange: up=true
D/BluetoothPan( 3074): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1210): onBluetoothStateChange: up=true
D/BluetoothPbap( 3074): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1167): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1167): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3074): onBluetoothStateChange: up=true
D/BluetoothHeadset(  735): onBluetoothStateChange: up=true
D/BluetoothManagerService(  735): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  735): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  735): Message: 40
D/BluetoothManagerService(  735): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3056): onReceive
D/BluetoothMapService( 3056): STATE_ON
V/BluetoothMapService( 3056): Handler(): got msg=1
D/BluetoothMapMasInstance( 3056): Map Service startRfcommSocketListener
W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = fc a5 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 88 be d0 da 15 d0 dd 96 b6 1e a5 0d d4 5e 5d 0c 
W/bt-btm  ( 3056): Stopping oneshot timer
E/bt_h4   ( 3056): vendor lib postload completed
D/BluetoothMapMasInstance( 3056): MAS initSocket()
D/BluetoothMapMasInstance( 3056):   masId = 00
D/BluetoothMapMasInstance( 3056):   msgTypes = 0e
D/BluetoothMapMasInstance( 3056):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3056):   SDP string = 000eSMS/MMS
I/Telecom ( 1167): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HeadsetStateMachine( 3056): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3056): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3056): mNumber:  mType: 128
D/HeadsetStateMachine( 3056): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3056): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = 92 1b 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = e1 88 c3 da 22 c3 3c c8 75 21 08 78 d2 02 26 36 
W/bt-btm  ( 3056): Stopping oneshot timer
W/BluetoothAdapter( 3056): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 3056): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3056): Accepting socket connection...
W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = 17 f2 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 7e bc 31 34 6a 70 5d 30 57 24 43 84 e1 dc c2 cc 
W/bt-btm  ( 3056): Stopping oneshot timer
D/LocalBluetoothProfileManager( 3074): Adding local A2DP profile
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = ff 56 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 91 55 05 8d 52 17 c7 e7 3a 89 2d 16 e1 55 55 67 
W/bt-btm  ( 3056): Stopping oneshot timer
,D/BluetoothManagerService(  735): Message: 30
,D/LocalBluetoothProfileManager( 3074): Adding local HEADSET profile
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = 3d b5 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 36 e5 87 b5 81 c2 6a 0a 67 c5 6d a5 e9 c2 16 70 
W/bt-btm  ( 3056): Stopping oneshot timer
,D/BluetoothManagerService(  735): Message: 30
,W/ContextImpl( 3074): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = b6 53 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 86 91 54 2b c0 64 0e 84 f0 31 10 bf bc 30 3f ab 
W/bt-btm  ( 3056): Stopping oneshot timer
,W/bt-smp  ( 3056): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3056): Plain text(LSB ~ MSB) = f3 44 50 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3056): Encrypted text(LSB ~ MSB) = 7a ed 5c 52 f4 a7 a9 db 79 f0 85 59 ae b3 3c 65 
W/bt-btm  ( 3056): Stopping oneshot timer
,D/BluetoothA2dp( 3074): Proxy object connected
D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/A2dpProfile( 3074): Bluetooth service connected
,W/BluetoothAdapter( 3056): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothHeadset( 3074): Proxy object connected
,D/HeadsetProfile( 3074): Bluetooth service connected
,D/DockEventReceiver( 3074): finishStartingService: stopping service
,D/BluetoothPbap( 3074): Proxy object connected
D/PbapServerProfile( 3074): Bluetooth service connected
,D/AuthorizationBluetoothService( 1280): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  735): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3056): getBluetoothService() called with no BluetoothManagerCallback
I/BtOppRfcommListener( 3056): Accept thread started.
,I/wpa_supplicant( 3062): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  735): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  735): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  735): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  735): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  735): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  735): will read network variables netId=1
,E/WifiStateMachine(  735): CMD_AUTO_CONNECT did save config ->  nid=1
E/WifiConfigStore(  735): will read network variables netId=1
,I/wpa_supplicant( 3062): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  735): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3062): PNO: In assoc process
,I/wpa_supplicant( 3062): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3062): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3062): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  735): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  735): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  735): Start Dhcp Watchdog 1
,E/native  (  735): do suspend false
,E/WifiStateMachine(  735): scanCount==0 - aborting
,I/dhcpcd  ( 3215): version 5.5.6 starting
E/dhcpcd  ( 3215): get_duid: Read-only file system
,I/dhcpcd  ( 3215): wlan0: broadcasting for a lease
,I/jxcore-log( 2997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 2997): 
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1330): OkHttp exception
W/EventLoggerService( 1330): Unable to send logs Error code: 262146
,E/Auth    ( 1280): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1330): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth    ( 1280): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1330): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/jxcore-log( 2997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 2997): 
,I/jxcore-log( 2997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 2997): 
,I/dhcpcd  ( 3215): wlan0: offered 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3215): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/jxcore-log( 2997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 2997): 
,I/jxcore-log( 2997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 2997): 
I/dhcpcd  ( 3215): wlan0: leased 192.168.1.114 for 86400 seconds
,I/jxcore-log( 2997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 2997): 
I/jxcore-log( 2997): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 2997): 
,E/native  (  735): do suspend true
,D/ConnectivityService(  735): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  735): Adding iface wlan0 to network 100
,E/WifiStateMachine(  735): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  735): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  735): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  735): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  735): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  735): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat(  735): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  735): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): DefaultState{ when=-9ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735):    accepting network in place of null
,D/ConnectivityService(  735): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
,D/CSLegacyTypeTracker(  735): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  735): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 25 Jan 2016 21:42:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453758154235], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453758154214]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  735): Validated
,D/ConnectivityService(  735): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  735): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  735): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1210): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/jxcore-log( 2997): Test app app.js loaded
I/jxcore-log( 2997): 
,I/chromium( 2997): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 2997): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 2997): BLE advertisement is supported
I/jxcore-log( 2997): 
,D/ConnectivityService(  735): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  735): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 2500): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2500): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/AlarmManagerService(  735): Setting time of day to sec=1453758157
,W/AlarmManagerService(  735): Unable to set rtc to 1453758157: Invalid argument
,I/CheckinService( 1551): Checkin interval check for package: unspecified last checkin: 1453517974518 min interval config: 0 actual interval: 240183313
,I/SystemUpdateService( 1551): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1551): onCreate
,D/SystemUpdateService( 1551): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1551): active receiver: enabled
,I/SystemUpdateService( 1551): showing system update notification
,I/ActivityManager(  735): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=3313 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 1551): Checking schedule, now: 1453758157885 next: 1453560141386
I/CheckinService( 1551): active receiver: enabled
,I/art     (  195): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 382us total 16.018ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 357us total 15.282ms
,I/CheckinService( 1551): Preparing to send checkin request
,I/EventLogService( 1551): Accumulating logs since 1453757374406
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 365us total 15.539ms
,E/GpsLocationProvider(  735): No APN found to select.
D/GpsLocationProvider(  735): NTP server returned: 1453758157777 (Mon Jan 25 22:42:37 GMT+01:00 2016) reference: 86408 certainty: 10 system time offset: -166
E/LocSvc_eng(  735): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,I/GoogleURLConnFactory( 1280): Using platform SSLCertificateSocketFactory
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1551): retry (wakeup: false) in 3599886 ms
,E/ActivityThread( 1551): Failed to find provider info for com.android.contacts.metadata
,I/iu.SyncManager( 1551): SYNC; picasa accounts
,D/NetworkLogImpl( 1551): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1551): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SyncManager(  735): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 26191, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  735): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 117179, reason: UserStart
,D/SystemUpdateService( 1551): onDestroy
,W/ResourcesManager( 3313): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3313): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/iu.UploadsManager( 1551): num queued entries: 0
I/iu.UploadsManager( 1551): num updated entries: 0
,I/iu.SyncManager( 1551): NEXT; no task
,V/JNIHelp ( 3313): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3353 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 3313): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3313): Installed default security provider GmsCore_OpenSSL
I/Babel   ( 2297): connection state changed from UNKNOWN to CONNECTED
,I/GAv4    ( 3353): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3353):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3353):   adb logcat -s GAv4
,W/GAv4    ( 3353): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/YouTube MDX( 3313): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/CheckinRequestBuilder( 1551): Checkin reason type: 12 attempt count: 1
,W/GAv4    ( 3353): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1280): GCM config loaded
,W/GAv4    ( 3353): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WifiService(  735): New client listening to asynchronous messages
,E/ActivityThread( 1551): Failed to find provider info for com.google.android.wearable.settings
,E/ConnectivityChangeReceiver( 1551): Ignoring connectivity change
,D/ConnectivityService(  735): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  735): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  735): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1551): CM callback handler got msg 524290
,I/art     (  735): Explicit concurrent mark sweep GC freed 51585(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 1.280ms total 57.158ms
,I/dex2oat ( 3420): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-931365200.jar --oat-fd=36 --oat-location=/data/data/com.google.android.youtube/cache/ads-931365200.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/InstanceID/Rpc( 3313): Found 10008
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 3420): dex2oat took 104.401ms (threads: 4)
,I/WebViewFactory( 3353): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 1683(64KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 695us total 11.915ms
,I/LibraryLoader( 3353): Time to load native libraries: 2 ms (timestamps 7202-7204)
I/LibraryLoader( 3353): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3353): Binding Chromium to main looper Looper (main, tid 1) {3ed14188}
,I/LibraryLoader( 3353): Expected native library version number "",actual native library version number ""
I/chromium( 3353): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3353): Initializing chromium process, singleProcess=true
,W/art     ( 3353): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3353): ApplicationContext is null in ApplicationStatus
,W/DriveInitializer( 1551): Awaiting to be initialized
,W/DriveInitializer( 1551): Background init thread started
,W/chromium( 3353): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3353): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3353): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3353): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 3353): Requires BLUETOOTH permission
,I/NSApplication( 3353): Starting up...
,W/DriveInitializer( 1551): Background init thread ended
,I/ActivityManager(  735): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3516 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,W/PhenotypeConfigurator( 1280): Server returned 404
,D/TimeService( 3516): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453758158947
D/        ( 3516): TimeServiceNative: User Time to be set is 1453758158947
D/QC-time-services( 3516): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3516): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3516): Lib:time_genoff_operation: pargs->ts_val = 1453758158947
D/QC-time-services( 3516): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  198): Daemon: Connection accepted:time_genoff
D/QC-time-services(  198): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453758158947
D/QC-time-services(  198): Daemon:genoff_opr: Base = 2, val = 1453758158947, operation = 0
D/QC-time-services(  198): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/30/70 3:33:2
D/QC-time-services(  198): Daemon:Value read from RTC seconds = 12886382000
D/QC-time-services(  198): Daemon:new time 1453758158947 
D/QC-time-services(  198): Daemon: delta 1440871776947 genoff 1440871776947 
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871776947 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services(  198): Updating the TOD offset
D/QC-time-services(  198): Daemon:genoff_persistent_update: Writing genoff = 1440871776947 to memory
D/QC-time-services(  198): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  198): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  198): Daemon:Update to modem bit set
D/QC-time-services(  198): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  198): Daemon: Base = 2, Value being sent to MODEM = 1137793358947
E/QC-time-services( 3516): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager(  735): Killing 2355:com.google.android.gm/u0a70 (adj 15): empty #17
D/QC-time-services(  198): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
D/QC-time-services(  198): Daemon: Time-services: Waiting to acceptconnection
,W/libprocessgroup(  735): failed to open /acct/uid_10070/pid_2355/cgroup.procs: No such file or directory
,I/art     ( 1551): Explicit concurrent mark sweep GC freed 14591(1071KB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 22MB/37MB, paused 1.115ms total 47.583ms
,I/CheckinService( 1551): Checkin interval check for package: unspecified last checkin: 1453517974518 min interval config: 0 actual interval: 240184537
,I/PeopleSync( 1551): onPerformSync() [5005f081]
,I/ActivityManager(  735): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3545 uid=10008 gids={50008, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/ChimeraCfgMgr( 1551): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1551): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3545): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3545): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GamesSyncServiceMain( 1551): Found unexpected GCM tag when scheduling; aborting
,W/GamesSyncServiceMain( 1551): Failed to execute periodic sync, missing client context - aborting
,I/ActivityManager(  735): Killing 1892:com.android.providers.calendar/u0a2 (adj 15): empty #17
,I/MultiDex( 3545): VM with version 2.1.0 has multidex support
I/MultiDex( 3545): install
,I/MultiDex( 3545): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  735): failed to open /acct/uid_10002/pid_1892/cgroup.procs: No such file or directory
,V/JNIHelp ( 3545): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 3545): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 3545): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2d689258: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 3545): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  735): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3568 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/art     ( 3545): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 3545): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/GAv4    ( 3568): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3568):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3568):   adb logcat -s GAv4
,D/NativeLibraryUtils( 3545): Install completed successfully. count=14 extracted=0
,W/GAv4    ( 3568): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/PeopleSync( 1551): Setting subscription: result=true [5005f081]
,W/GAv4    ( 3568): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/PeopleSync( 1551): Starting sync, feed=null [5005f081]
,W/GAv4    ( 3568): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WVCdm   (  184): Instantiating CDM.
,I/WVCdm   (  184): CdmEngine::OpenSession
,I/WVCdm   (  184): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  184): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/art     ( 2652): Attempt to remove local handle scope entry from IRT, ignoring
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  184): Service_Initialize: starts!
D/QSEECOMAPI: (  184): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  184): App is not loaded in QSEE
,D/QSEECOMAPI: (  184): Loaded image: APP id = 3
,D/DrmWidevineDash(  184): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
E/DrmWidevineDash(  184): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
,I/GoogleURLConnFactory( 3545): Using platform SSLCertificateSocketFactory
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  184): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  184): OEMCrypto_OpenSession: starts! SID=0xb4aff940
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,I/ActivityManager(  735): Killing 2818:com.google.android.gms:car/u0a8 (adj 15): empty #17
,D/DrmWidevineDash(  184): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  184): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_GetRandom: starts! randomData=0xb53bf0e0, dataLength=8
,D/DrmWidevineDash(  184): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1d02000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  184): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  184): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  184): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  184): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: starts! deviceID=0xb1aba440, idLength=0xb48ff710
,D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: starts!
,W/libprocessgroup(  735): failed to open /acct/uid_10008/pid_2818/cgroup.procs: No such file or directory
D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  184): PrepareKeyRequest: nonce=491035884
D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1e01600
D/DrmWidevineDash(  184): message_length=1597, signature=0xb479a3c0, signature_length=3029333748
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,I/PeopleSync( 1551): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  184): CdmEngine::CloseSession
D/DrmWidevineDash(  184): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  184): L3 Terminate.
D/DrmWidevineDash(  184): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  184): Service_Uninitialize: starts!
D/QSEECOMAPI: (  184): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  184): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  184): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  735): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3610 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  735): Killing 2606:android.process.acore/u0a4 (adj 15): empty #17
,I/art     (  735): Explicit concurrent mark sweep GC freed 24155(1109KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 873us total 57.964ms
,W/libprocessgroup(  735): failed to open /acct/uid_10004/pid_2606/cgroup.procs: No such file or directory
,W/ResourcesManager( 3610): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/WearableService( 1280): callingUid 10008, callindPid: 1280
,E/MDM     ( 1280): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1551): Restart initialization of location
,D/AuthorizationBluetoothService( 1280): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 3610): Created com.android.providers.calendar.CalendarAlarmManager@27ea1161(com.android.providers.calendar.CalendarProvider2@21fb2486)
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 68076(4MB) AllocSpace objects, 27(455KB) LOS objects, 39% free, 22MB/36MB, paused 934us total 48.807ms
,I/dex2oat ( 3635): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=33 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3635): dex2oat took 42.619ms (threads: 4)
,I/Adreno-EGL( 3545): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Adreno-EGL( 3545): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/GCoreFlp( 1280): No location to return for getLastLocation()
W/FusedLocationProvider( 1280): location=null
,I/dex2oat ( 3646): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-715693045.jar --oat-fd=108 --oat-location=/data/data/com.google.android.gms/cache/ads-715693045.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/WVCdm   (  184): CdmEngine::OpenSession
I/WVCdm   (  184): Level3 Library Sep 25 2014 17:10:03
,W/WVCdm   (  184): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  184): Service_Initialize: starts!
D/QSEECOMAPI: (  184): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  184): App is not loaded in QSEE
,D/QSEECOMAPI: (  184): Loaded image: APP id = 3
,D/DrmWidevineDash(  184): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
E/DrmWidevineDash(  184): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb584b000
,D/DrmWidevineDash(  184): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  184): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  184): OEMCrypto_Initialize Level 1 success. I will use level 1.
,D/DrmWidevineDash(  184): OEMCrypto_OpenSession: starts! SID=0xb3bff940
,I/dex2oat ( 3646): dex2oat took 56.370ms (threads: 4)
,D/DrmWidevineDash(  184): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  184): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_GetRandom: starts! randomData=0xb3019070, dataLength=8
,D/DrmWidevineDash(  184): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb30d4000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  184): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  184): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  184): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,W/WVCdm   (  184): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  184): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: starts! deviceID=0xb1aba480, idLength=0xb4aff710
,D/DrmWidevineDash(  184): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: wv_app_version = 21
,D/DrmWidevineDash(  184): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  184): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  184): hlos api version =  9
D/DrmWidevineDash(  184): tz api version =  9
D/DrmWidevineDash(  184): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  184): PrepareKeyRequest: nonce=506690517
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb1d1c600
D/DrmWidevineDash(  184): message_length=1632, signature=0xb4921280, signature_length=3031430900
,D/DrmWidevineDash(  184): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  184): CdmEngine::CloseSession
D/DrmWidevineDash(  184): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  184): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  184): L3 Terminate.
D/DrmWidevineDash(  184): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  184): Service_Uninitialize: starts!
D/QSEECOMAPI: (  184): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  184): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  184): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  184): OEMCrypto_Terminate: ends! returns 0
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 2759(106KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 827us total 10.668ms
,I/GoogleURLConnFactory( 1551): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 3610): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 3610): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/VacuumService( 1280): Vacuum at: now=1453758161040 tag=VacuumService
,I/PeopleSync( 1551): Sync finished, successful=true, took 1389ms
,I/PeopleContactsSync( 1551): CP2 sync start [5005f081]
,D/Finsky  ( 2409): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2409): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/PeopleContactsSync( 1551): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 1551): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/ActivityManager(  735): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=3672 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/ContactLocale( 3672): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/PeopleContactsSync( 1551): CP2 cleanup done, kept= duration=228 ms
,I/PeopleContactsSync( 1551): ===CP2 sync finished, success=true, time=238,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 1551): ***Sync finished***, duration: 2337 [5005f081]
,I/Adreno-EGL( 3545): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/CheckinRequestBuilder( 1551): Classify the device as Phone.
,I/art     ( 1551): Explicit concurrent mark sweep GC freed 37097(2MB) AllocSpace objects, 15(263KB) LOS objects, 40% free, 23MB/39MB, paused 2.471ms total 76.949ms
,W/SQLiteConnectionPool( 1551): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/CheckinTask( 1551): Sending checkin request (10408 bytes)
,I/CheckinResponseProcessor( 1551): From server: 4 gservices updates and 1 deletes
,W/AbstractGoogleClient( 1984): Application name is not set. Call Builder#setApplicationName.
,I/AnalyticsLogBase( 1984): PlayLogger.onLoggerConnected
,I/CertBlacklister(  735): Certificate blacklist changed, updating...
,I/CertBlacklister(  735): Certificate blacklist updated
,I/GservicesProvider( 1458): main difference update completed
,I/CheckinRequestBuilder( 1551): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1551): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 2297): ApnsOta: OTA version -1
,I/art     (  735): Explicit concurrent mark sweep GC freed 28143(1278KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 933us total 73.072ms
,I/ContactAccountLoggerTas( 1330): canRun() : Opted Out
,I/ActivityManager(  735): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3739 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/Search.GservicesUpdateTask( 1330): Updating Gservices keys
,E/UpdateRequestReceiver( 3739): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 9857(490KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 686us total 17.925ms
,E/UpdateRequestReceiver( 3739): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ContactAccountLoggerTas( 1330): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1330): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1330): canRun() : Opted Out
,E/UpdateRequestReceiver( 3739): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3739): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/CheckinService( 1551): Checkin interval check for package: unspecified last checkin: 1453517974518 min interval config: 0 actual interval: 240188386
,I/SystemUpdateService( 1551): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1551): onCreate
,D/SystemUpdateService( 1551): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1551): active receiver: enabled
,I/SystemUpdateService( 1551): showing system update notification
,I/ValidateNoPeople(  735): skipping global notification
,V/SystemUpdateService( 1551): retry (wakeup: false) in 3599910 ms
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 3579(147KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 640us total 17.512ms
,I/CheckinRequestBuilder( 1551): Classify the device as Phone.
,I/art     ( 1551): Explicit concurrent mark sweep GC freed 19317(1129KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 23MB/39MB, paused 1.036ms total 44.704ms
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 2762(106KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 591us total 10.980ms
,W/BaseAppContext( 1280): Using Auth Proxy for data requests.
,E/BaseAppContext( 1280): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/ActivityManager(  735): Killing 2884:com.android.musicfx/u0a15 (adj 15): empty #17
,D/SystemUpdateService( 1551): onDestroy
,W/libprocessgroup(  735): failed to open /acct/uid_10015/pid_2884/cgroup.procs: No such file or directory
,E/DynamiteModule( 1551): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 1551): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 1551): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 1551): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 1551): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 1551): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 1551): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 1551): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 1551): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 1551): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 1551): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 1551): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
E/DynamiteModule( 1551): 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
E/DynamiteModule( 1551): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
E/DynamiteModule( 1551): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 1551): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 1551): 	at android.app.ActivityThread.main(ActivityThread.java:5221)
E/DynamiteModule( 1551): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 1551): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 1551): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
E/DynamiteModule( 1551): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
E/DynamiteModule( 1551): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 1551): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 1551): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 1551): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 1551): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 1551): 		... 17 more
E/DynamiteModule( 1551): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 1551): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 1551): Selected local version of com.google.android.gms.flags
,I/CheckinTask( 1551): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1551): Checking schedule, now: 1453758163339 next: 1453800330333
I/CheckinService( 1551): active receiver: disabled
,I/CheckinService( 1551): Checking schedule, now: 1453758163386 next: 1453800330333
I/CheckinService( 1551): active receiver: disabled
,D/SystemEventReceiver( 1551): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1551): Updating ocr activity enabled=false
,D/CheckinService( 1551): Recording last checkin time for package unspecified as 1453758163418
,W/ActivityManager(  735): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 1551): Updating downloaded model state (gservices changed)
,I/ContactAccountLoggerTas( 1330): canRun() : Opted Out
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 2818(110KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 493us total 11.051ms
,E/CalendarSyncAdapter( 1984): Unable to get calendar account
E/CalendarSyncAdapter( 1984): java.io.InterruptedIOException
E/CalendarSyncAdapter( 1984): 	at com.android.okio.Deadline.throwIfReached(Deadline.java:56)
E/CalendarSyncAdapter( 1984): 	at com.android.okio.Okio$1.write(Okio.java:67)
E/CalendarSyncAdapter( 1984): 	at com.android.okio.RealBufferedSink.flush(RealBufferedSink.java:154)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.HttpConnection.flush(HttpConnection.java:126)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.HttpTransport.flushRequest(HttpTransport.java:73)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:614)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:379)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:323)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getResponseCode(HttpURLConnectionImpl.java:491)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getResponseCode(DelegatingHttpsURLConnection.java:105)
E/CalendarSyncAdapter( 1984): 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getResponseCode(HttpsURLConnectionImpl.java:25)
E/CalendarSyncAdapter( 1984): 	at com.google.api.client.http.javanet.NetHttpResponse.<init>(NetHttpResponse.java:37)
E/CalendarSyncAdapter( 1984): 	at com.google.api.client.http.javanet.NetHttpRequest.execute(NetHttpRequest.java:94)
E/CalendarSyncAdapter( 1984): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:964)
E/CalendarSyncAdapter( 1984): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 1984): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 1984): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 1984): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2225)
E/CalendarSyncAdapter( 1984): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1747)
E/CalendarSyncAdapter( 1984): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1630)
E/CalendarSyncAdapter( 1984): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:462)
E/CalendarSyncAdapter( 1984): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:366)
E/CalendarSyncAdapter( 1984): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 1984): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 48997(2MB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 22MB/36MB, paused 787us total 37.384ms
D/SyncManager(  735): handleSyncHandlerMessage: dropping since the sync is no longer active: startTime 91264, mTimeoutStartTime 91264, mHistoryRowId 10, syncOperation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 31370, reason: Periodic
,D/GCM     ( 1280): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 1280): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1280): DispatchingService.onCreate()
,E/SQLiteLog( 3610): (284) automatic index on view_events(_id)
,I/GCoreUlr( 1280): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 2606(104KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 1.036ms total 21.435ms
,I/art     (  735): Explicit concurrent mark sweep GC freed 26361(1195KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 1.743ms total 60.519ms
,I/GCoreUlr( 1280): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/CalendarSyncAdapter( 1984): Found no pending settings
,I/GCoreUlr( 1280): Unbound from all location providers
I/GCoreUlr( 1280): Place inference reporting - stopped
,I/ActivityManager(  735): Killing 2915:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10040/pid_2915/cgroup.procs: No such file or directory
,I/GCoreUlr( 1280): DispatchingService.onDestroy()
I/GCoreUlr( 1280): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1280): Unbound from all location providers
I/GCoreUlr( 1280): Place inference reporting - stopped
,W/GeofencerStateMachine( 1280): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1280): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/ctxmgr  ( 1280): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10008, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1280): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 22034(1281KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 22MB/37MB, paused 1.010ms total 40.076ms
,D/GCM     ( 1280): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  735): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=3817 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1280): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1280): DispatchingService.onCreate()
,I/GCoreUlr( 1280): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1280): Unbound from all location providers
I/GCoreUlr( 1280): Place inference reporting - stopped
,I/GCoreUlr( 1280): DispatchingService.onDestroy()
I/GCoreUlr( 1280): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1280): Unbound from all location providers
I/GCoreUlr( 1280): Place inference reporting - stopped
,D/ActivityThread( 3817): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/Gmail   ( 3817): getAccountsCursor
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PhenotypeConfigurator( 1280): Scheduling Phenotype for one-off execution 12248 seconds from now (1453758164611)
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GetConfigurationSnapshotOperation( 1280): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1280): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1280): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  735): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=3854 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 3817): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ValidateNoPeople(  735): mEvictionCount: 0
,W/Gmail   ( 3817): Sync started for account: account:61035162
,I/Gmail   ( 3817): getAccountsCursor
,W/ActivityManager(  735): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 3854): EasService.onCreate
,I/Exchange( 3854): RestartPingTask
,I/Gmail   ( 3817): Observing account changes for notifications
,I/Exchange( 3854): RestartPingsTask did not start any pings.
,I/Exchange( 3854): PSS stopIfIdle
I/Exchange( 3854): PSS has no active accounts; stopping service.
,I/Exchange( 3854): onDestroy
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 3817): (283) recovered 24 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 3817): notifyAccountChanged
E/SQLiteLog( 3672): (284) automatic index on sqlite_sq_A4328B50(STAT_DATA_ID)
,E/SQLiteLog( 3672): (284) automatic index on sqlite_sq_A3C28240(STAT_DATA_ID)
I/Gmail   ( 3817): getAccountsCursor
,I/Gmail   ( 3817): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3817): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3817): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3817): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3817): notifyAccountChanged
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 13529(698KB) AllocSpace objects, 3(71KB) LOS objects, 25% free, 16MB/21MB, paused 958us total 27.356ms
,I/art     (  735): Explicit concurrent mark sweep GC freed 19583(860KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.196ms total 82.423ms
,I/Gmail   ( 3817): getAccountsCursor
,I/Gmail   ( 3817): getStartSyncRequest: handledServerOpId: 15605, upperFetchedConvoId: 1515656576748224512, lowerFetchedConvoId: 0, ackedClientOp: 0
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 3672): (284) automatic index on sqlite_sq_A3C28F60(STAT_DATA_ID)
,E/SQLiteLog( 3672): (284) automatic index on sqlite_sq_A3C28560(STAT_DATA_ID)
,I/ActivityManager(  735): Killing 2777:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/ResourcesManager( 3817): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3817): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  735): failed to open /acct/uid_10005/pid_2777/cgroup.procs: No such file or directory
,V/JNIHelp ( 3817): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3817): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3817): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GHttpClientFactory( 2500): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2500): Using platform SSLCertificateSocketFactory
,I/MusicLifecycle( 2500): Sync started
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicSyncAdapter( 2500): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
I/MusicSyncAdapter( 2500): Periodic update
,W/MusicApiClient( 2500): Activity events list is null or empty. Skip reporting.
,I/MusicLifecycle( 2500): Sync ended
,I/MusicLeanback( 2500): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2500): Stop autocaching.
,I/Gmail   ( 3817): StartSyncInfoProto: Personal inbox enabled: true
,I/ActivityManager(  735): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=3937 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Gmail   ( 3817): StartSyncInfoProto: Personal inbox android config: com.google.c.c.a.a@3aa45718
,D/WearableService( 1280): callingUid 10008, callindPid: 1280
,W/Herrevad( 1280): mobile connection type with no cell id
,E/GmsUtils( 2500): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 2500): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  735): Killing 3074:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  735): Client connection lost with reason: 4
,W/libprocessgroup(  735): failed to open /acct/uid_1000/pid_3074/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 3353:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,I/Gmail   ( 3817): checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^f]), all([^b, userlabel:90242001, userlabel:93982, userlabel:2914615, userlabel:90242029, userlabel:2914456, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, ^f, userlabel:-1492383895, userlabel:94076, userlabel:-1492276994, userlabel:-1492276990, userlabel:3026, userlabel:-1492276991, ^u, ^t, ^s, ^smartlabel_group, userlabel:-812318908, ^smartlabel_personal, ^smartlabel_social, ^p_mtunsub, ^sq_ig_i_personal, ^g, ^punsub, ^r, ^i, ^smartlabel_promo, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, ^p_bs, userlabel:-1711782184, userlabel:93692, userlabel:-244132349, ^sq_ig_i_social, userlabel:3011, userlabel:1123230114, ^p_abs])
,I/art     ( 3817): Explicit concurrent mark sweep GC freed 20345(737KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 327us total 23.571ms
,W/libprocessgroup(  735): failed to open /acct/uid_10061/pid_3353/cgroup.procs: No such file or directory
,I/Gmail   ( 3817): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15605, normalSync: true
,I/Gmail   ( 3817): lowestBackward conversation id 0
,I/GAv4    ( 3937): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3937):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3937):   adb logcat -s GAv4
,W/GAv4    ( 3937): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3937): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3937): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3937): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 4706(194KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 505us total 28.405ms
,I/Gmail   ( 3817): notifyAccountChanged
,I/Gmail   ( 3817): getAccountsCursor
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3817): notifyAccountChanged
,W/Gmail   ( 3817): Sync complete for account: account:61035162
I/Gmail   ( 3817): getAccountsCursor
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3937): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3937): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3937): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 3937): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3937): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 3937): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3937): Installed default security provider GmsCore_OpenSSL
,D/WifiService(  735): acquireWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3fffb7d0}
,I/art     (  735): Explicit concurrent mark sweep GC freed 20878(826KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.262ms total 50.992ms
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Flag    ( 3937): Duration spec must be at least 2 characters long
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 8.114ms
,I/ActivityManager(  735): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=4004 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  735): Killing 3516:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 169us total 7.557ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 168us total 7.357ms
,W/libprocessgroup(  735): failed to open /acct/uid_10076/pid_3516/cgroup.procs: No such file or directory
,I/GAv4    ( 4004): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4004):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4004):   adb logcat -s GAv4
,W/GAv4    ( 4004): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4004): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4004): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 4004): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4004): Time to load native libraries: 1 ms (timestamps 6409-6410)
I/LibraryLoader( 4004): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4004): Binding Chromium to main looper Looper (main, tid 1) {3ed14188}
I/LibraryLoader( 4004): Expected native library version number "",actual native library version number ""
I/chromium( 4004): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4004): Initializing chromium process, singleProcess=true
,W/art     ( 4004): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4004): ApplicationContext is null in ApplicationStatus
,W/chromium( 4004): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4004): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4004): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4004): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/AudioManagerAndroid( 4004): Requires BLUETOOTH permission
,I/NSApplication( 4004): Starting up...
,I/SyncAdapterService( 4004): Ignoring sync request for non-current account
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  735): Killing 3568:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10038/pid_3568/cgroup.procs: No such file or directory
,I/art     ( 1551): Explicit concurrent mark sweep GC freed 18068(1283KB) AllocSpace objects, 21(336KB) LOS objects, 24% free, 23MB/31MB, paused 557us total 40.988ms
,I/Icing   ( 1551): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,I/Gmail   ( 3817): Backfilling search sequence table
,W/Icing   ( 1551): Content incarnation mismatch: Expected [43caf02910957b10] found [1379883abffd1099]
I/Icing   ( 1551): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,E/Icing   ( 1551): Aborting indexing of corpus messages/com.google/thalitester%40gmail.com
I/Icing   ( 1551): Removing corpus key 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 for package com.google.android.gm
,E/DefaultHttpIssuer( 3937): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 3937): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 3937): java.io.IOException
E/DefaultHttpIssuer( 3937): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 3937): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 3937): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 3937): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 3937): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 3937): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 3937): 	at dlr.run(PG:3031)
,D/DelayedSyncController(  942): Delaying sync.
,E/BaseSyncManager( 3937): IOException
E/BaseSyncManager( 3937): java.io.IOException: stream was reset: CANCEL
E/BaseSyncManager( 3937): 	at hzd.b(PG:145)
E/BaseSyncManager( 3937): 	at hya.b(PG:104)
E/BaseSyncManager( 3937): 	at hxn.d(PG:917)
E/BaseSyncManager( 3937): 	at hxn.a(PG:95)
E/BaseSyncManager( 3937): 	at hxn$a.a(PG:902)
E/BaseSyncManager( 3937): 	at hvz.a(PG:50089)
E/BaseSyncManager( 3937): 	at hvz$a.a(PG:230)
E/BaseSyncManager( 3937): 	at hvz.a(PG:3201)
E/BaseSyncManager( 3937): 	at clz.a(PG:127)
E/BaseSyncManager( 3937): 	at cjr.a(PG:47)
E/BaseSyncManager( 3937): 	at cjq.a(PG:22)
E/BaseSyncManager( 3937): 	at cjs.a(PG:68)
E/BaseSyncManager( 3937): 	at cjw.b(PG:92)
E/BaseSyncManager( 3937): 	at cjw.a(PG:80)
E/BaseSyncManager( 3937): 	at cju.b(PG:5140)
E/BaseSyncManager( 3937): 	at cju.a(PG:1096)
E/BaseSyncManager( 3937): 	at dlh.b(PG:14062)
E/BaseSyncManager( 3937): 	at dlh.a(PG:140)
E/BaseSyncManager( 3937): 	at dqo.a(PG:224)
E/BaseSyncManager( 3937): 	at dlt.run(PG:9618)
E/BaseSyncManager( 3937): 	at dlr.run(PG:3031)
,D/WifiService(  735): releaseWifiLockLocked: WifiLock{BaseSyncManager type=1 binder=android.os.BinderProxy@3fffb7d0}
,I/ActivityManager(  735): Killing 2297:com.google.android.talk/u0a54 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10054/pid_2297/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Start proc com.google.android.videos for service com.google.android.videos/.store.SyncService: pid=4087 uid=10077 gids={50077, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,I/Icing   ( 1551): Indexing 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2 from com.google.android.gm
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/ResourcesManager( 4087): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/Icing   ( 1551): Indexing done 009F7E1EAB88E81C4EB4149FAD093AD3E8757DF2
,I/ActivityManager(  735): Start proc com.google.android.apps.cloudprint:sync for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService: pid=4107 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  735): Start proc com.google.android.apps.cloudprint for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService: pid=4129 uid=10035 gids={50035, 9997, 3003, 1028} abi=armeabi-v7a
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4107): Sync request not initiated by GCP app. Dropping
,D/PlayMovies( 4087): PersistentCache.cleanup:103 Cache is below limit, no need to shrink: [size=0, limit=5242880]
,I/ActivityManager(  735): Killing 3313:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/VideoCapabilities( 4087): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4087): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  735): Killing 3109:com.google.android.keep/u0a71 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10080/pid_3313/cgroup.procs: No such file or directory,
,W/libprocessgroup(  735): failed to open /acct/uid_10071/pid_3109/cgroup.procs: No such file or directory
,D/PlayMovies( 4087): TransferService.onCreate:52 creating transfer service
,W/ResourcesManager( 1551): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,E/Auth.Api.Credentials( 1551): [CredentialSyncAdapter] Unknown sync event.
,I/CalendarSyncAdapter( 1984): Found no pending settings
,I/PlayMovies( 4087): SyncService.syncAllPurchasesAndWishlist:151 Starting sync for 515013DC511638B0584069811EF28701C0771BF5
,I/CalendarSyncAdapter( 1984): Found no pending settings
,I/PlayMovies( 4087): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 purchases
,I/PlayMovies( 4087): SyncService.waitForCompletion:177 Sync completed for 515013DC511638B0584069811EF28701C0771BF5 wishlist
,I/ActivityManager(  735): Killing 1440:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10013/pid_1440/cgroup.procs: No such file or directory
,I/GAV2    ( 3817): Thread[GAThread,5,main]: No campaign data found.
,W/PackageSettings(  735): Skipping PackageSetting{2ed72ba com.example.hello/10278} due to missing metadata
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
,W/Launcher( 1255): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b39147 new=com.google.android.velvet.VelvetApplication@2b39147
,I/UpdateIcingCorporaServi( 1330): Updating corpora: APPS=com.google.android.videos, CONTACTS=MAYBE
,D/PackageBroadcastService( 1551): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.videos
,I/UpdateIcingCorporaServi( 1330): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,I/art     (  735): Explicit concurrent mark sweep GC freed 40336(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 27MB/41MB, paused 1.081ms total 58.998ms
,I/ActivityManager(  735): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=4217 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  735): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  735): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  735): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  735): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3324b215
,W/ResourcesManager( 4217): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Launcher( 1255): Deferring update until onResume
,I/GCoreNlp( 1280): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 1255): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Launcher( 1255): Deferring update until onResume
,I/art     ( 1280): Explicit concurrent mark sweep GC freed 111462(6MB) AllocSpace objects, 37(592KB) LOS objects, 39% free, 24MB/40MB, paused 863us total 54.069ms
,I/Launcher( 1255): Deferring update until onResume
,I/Launcher( 1255): Deferring update until onResume
,I/Babel_SMS( 4217): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4217): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4217): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 4217): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4217): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4217): MmsConfig.loadFromResources
E/Babel_SMS( 4217): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4217): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 4217): ApnsOta: OTA version -1
,I/Babel   ( 4217): deleted: false for 0
,W/Settings( 4217): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4217): startup - clean
,I/UpdateIcingCorporaServi( 1330): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1255): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b39147 new=com.google.android.velvet.VelvetApplication@2b39147
,D/PackageBroadcastService( 1551): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1551): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 1551): updateResources: need to parse f{com.google.android.gms}
,W/VideoCapabilities( 4217): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4217): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4217): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4217): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4217): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4217): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4217): onServiceConnected
W/Babel   ( 4217): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4217): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4217): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4217): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4217): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4217): Installed default security provider GmsCore_OpenSSL
,I/UpdateIcingCorporaServi( 1330): UpdateCorporaTask done [took 272 ms] updated apps [took 272 ms] 
,I/Icing   ( 1551): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,D/Icing   ( 1551): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1551): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/Icing   ( 1551): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/Icing   ( 1551): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  735): Killing 3739:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10036/pid_3739/cgroup.procs: No such file or directory
,W/IcingInternalCorpora( 1551): getNumBytesRead when not calculated.
,I/ClearcutLoggerApiImpl( 1551): disconnect managed GoogleApiClient
,I/ClearcutLoggerApiImpl( 1280): disconnect managed GoogleApiClient
,I/ActivityManager(  735): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=4285 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 4285): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4285):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4285):   adb logcat -s GAv4
,W/GAv4    ( 4285): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4285): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4285): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  735): Killing 3854:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10069/pid_3854/cgroup.procs: No such file or directory
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1280): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  735): Killing 2500:com.google.android.music:main/u0a60 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10060/pid_2500/cgroup.procs: No such file or directory
,I/jxcore-log( 2997): --= Surplus to requirements =--
I/jxcore-log( 2997): 
I/jxcore-log( 2997): ****TEST TOOK:  ms ****
I/jxcore-log( 2997): 
I/jxcore-log( 2997): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2997): 
,D/AndroidRuntime( 4347): 
D/AndroidRuntime( 4347): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4347): CheckJNI is OFF
,D/AndroidRuntime( 4347): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  735): Killing 2997:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,D/WifiService(  735): Client connection lost with reason: 4
I/WindowState(  735): WIN DEATH: Window{33b525d3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  735): Skipping PackageSetting{2ed72ba com.example.hello/10278} due to missing metadata
,I/ActivityManager(  735):   Force finishing activity ActivityRecord{291755dc u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  735): Spurious death for ProcessRecord{12fc6ff2 2997:com.test.thalitest/u0a270}, curProc for 2997: null
,I/ActivityManager(  735): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1255): Explicit concurrent mark sweep GC freed 9348(597KB) AllocSpace objects, 3(288KB) LOS objects, 37% free, 26MB/42MB, paused 439us total 25.075ms
,I/art     ( 1330): Explicit concurrent mark sweep GC freed 20019(1291KB) AllocSpace objects, 3(57KB) LOS objects, 24% free, 19MB/25MB, paused 306us total 43.490ms
,I/InputReader(  735): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1072): resetDictionaries() : en_US
W/GeofencerStateMachine( 1280): Ignoring removeGeofence because network location is disabled.
,I/art     (  735): Explicit concurrent mark sweep GC freed 25459(1439KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.191ms total 62.376ms
,I/Keyboard.Facilitator.DecoderInitializer( 1072): run()
,I/art     ( 1551): Explicit concurrent mark sweep GC freed 31247(1892KB) AllocSpace objects, 11(176KB) LOS objects, 25% free, 23MB/31MB, paused 1.063ms total 111.959ms
,I/Decoder ( 1072): createOrResetDecoder
,D/VoicemailCleanupService( 3672): Cleaning up data for package: com.test.thalitest
,D/BackupManagerService(  735): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  735): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  735): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4383 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,D/TaskPersister(  735): removeObsoleteFile: deleting file=216_task.xml
,I/ConfigService( 1280): onCreate
,I/Adreno-EGL(  942): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  942): Initialized EGL, version 1.4
,D/OpenGLRenderer(  942): Enabling debug mode 0
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): run()
,W/InputMethodManagerService(  735): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@d05d862 (uid=10034 pid=942)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1072): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1072): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1072): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1072): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1072): run()
I/StatsUtilsManager( 1072): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1072): shouldRecordStats() = Too Soon
,I/Launcher( 1255): Deferring update until onResume
,I/UpdateIcingCorporaServi( 1330): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/ResourcesManager( 1255): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  735): Explicit concurrent mark sweep GC freed 10317(545KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.484ms total 159.929ms
,W/ResourcesManager( 1255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/Launcher( 1255): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2b39147 new=com.google.android.velvet.VelvetApplication@2b39147
,I/Launcher( 1255): Deferring update until onResume
,I/ActivityManager(  735): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4410 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/AndroidRuntime( 4347): Shutting down VM
,I/UpdateIcingCorporaServi( 1330): UpdateCorporaTask done [took 130 ms] updated apps [took 130 ms] 
,W/ContextImpl( 4410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1551): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1551): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1551): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1551): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1551): Module APK com.google.android.play.games already loaded
,D/AccountUtils( 1551): Clearing selected account for com.test.thalitest
,E/NetworkScheduler.SchedulerReceiver( 1280): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1280): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  735): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4434 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/LocationSettingsChecker( 1551): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  735): Killing 3545:com.google.android.gms.unstable/u0a8 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1551): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1551): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1551): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1551): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1551): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1551): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1551): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1551): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1551): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1551): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1551): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1551): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1551): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/libprocessgroup(  735): failed to open /acct/uid_10008/pid_3545/cgroup.procs: No such file or directory
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,W/BaseAppContext( 1551): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1551): App measurement is starting up, version: 8489
,I/GMPM-SVC( 1551): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/Icing   ( 1551): doRemovePackageData com.test.thalitest
,I/ActivityManager(  735): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4464 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  735): Killing 4004:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10061/pid_4004/cgroup.procs: No such file or directory
,I/ActivityManager(  735): Killing 4129:com.google.android.apps.cloudprint/u0a35 (adj 15): empty #17
,W/libprocessgroup(  735): failed to open /acct/uid_10035/pid_4129/cgroup.procs: No such file or directory

```
