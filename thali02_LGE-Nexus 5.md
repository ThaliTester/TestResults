#### Test 5615109370bee58_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2937): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2937):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2937):   adb logcat -s GAv4
,W/GAv4    ( 2937): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2937): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2937): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2937): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2444): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2937): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2937): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 2984): 
D/AndroidRuntime( 2984): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2984): CheckJNI is OFF
V/JNIHelp ( 2937): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  736): Killing 2212:com.google.android.youtube/u0a80 (adj 15): empty #17
W/System  ( 2937): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2937): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2984): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  736): failed to open /acct/uid_10080/pid_2212/cgroup.procs: No such file or directory
I/ActivityManager(  736): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  736): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3008 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2984): Shutting down VM
V/ActivityManager(  736): Display changed displayId=0
V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WebViewFactory( 3008): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/Icing   ( 1612): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/LibraryLoader( 3008): Time to load native libraries: 2 ms (timestamps 8117-8119)
I/LibraryLoader( 3008): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3008): Binding Chromium to main looper Looper (main, tid 1) {177ea795}
I/LibraryLoader( 3008): Expected native library version number "",actual native library version number ""
I/chromium( 3008): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/NetworkUtils( 1410): OkHttp exception
W/EventLoggerService( 1410): Unable to send logs Error code: 262146
I/BrowserStartupController( 3008): Initializing chromium process, singleProcess=true
W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3008): ApplicationContext is null in ApplicationStatus
W/chromium( 3008): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3008): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3008): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3008): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/Icing   ( 1612): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1612): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ace0420:true
D/BluetoothAdapter( 3008): 978304887: getState() :  mService = null. Returning STATE_OFF
I/Icing   ( 1612): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3008): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3008): CordovaWebView is running on device made by: LGE
W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3008): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3008): Render dirty regions requested: true
D/Atlas   ( 3008): Validating map...
W/chromium( 3008): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3008): Initialized EGL, version 1.4
D/OpenGLRenderer( 3008): Enabling debug mode 0
I/ActivityManager(  736): Displayed com.test.thalitest/.MainActivity: +435ms (total +57s24ms)
W/IInputConnectionWrapper( 3008): showStatusIcon on inactive InputConnection
W/BindingManager( 3008): Cannot call determinedVisibility() - never saw a connection for the pid: 3008
I/ActivityManager(  736): Killing 2364:com.google.android.deskclock/u0a38 (adj 15): empty #17
W/libprocessgroup(  736): failed to open /acct/uid_10038/pid_2364/cgroup.procs: No such file or directory
D/JsMessageQueue( 3008): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3008): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1546717056
D/JX-Cordova( 3008): jxcore cordova android initializing
,W/jxcore-log( 3008): Initializing JXcore engine
W/jxcore-log( 3008): JXcore engine is ready
,W/jxcore-log( 3008): Starting JXcore engine
,W/.test.thalitest( 3008): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6474]" dev="sockfs" ino=6474 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3008): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3008): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6571]" dev="sockfs" ino=6571 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3008): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17643]" dev="sockfs" ino=17643 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3008): Platform android
W/jxcore-log( 3008): 
W/jxcore-log( 3008): Process ARCH arm
W/jxcore-log( 3008): 
,I/jxcore-log( 3008): JXcore Cordova bridge is ready!
I/jxcore-log( 3008): 
W/jxcore-log( 3008): JXcore engine is started
I/Choreographer( 3008): Skipped 121 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3008): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3008): Toggling radios to true
I/jxcore-log( 3008): 
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  736): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  736): Message: 1
D/BluetoothManagerService(  736): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  736): New client listening to asynchronous messages
,D/WifiService(  736): setWifiEnabled: true pid=3008, uid=10270
E/WifiService(  736): Invoking mWifiStateMachine.setWifiEnabled
,I/ActivityManager(  736): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3075 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  180): Softap fwReload - Ok
,I/jxcore-log( 3008): Radios toggled
I/jxcore-log( 3008): 
,I/jxcore-log( 3008): My device name is: LGE-Nexus 5
I/jxcore-log( 3008): 
D/CommandListener(  180): Setting iface cfg
D/CommandListener(  180): Trying to bring down wlan0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,D/WifiMonitor(  736): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  736): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/ActivityManager(  736): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3083 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 3082): Successfully initialized wpa_supplicant
,W/ResourcesManager( 3075): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3082): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3438c767:true
,D/BluetoothAdapter( 3083): 394176405: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  736): Message: 30
D/BluetoothManagerService(  736): Message: 30
D/LocalBluetoothProfileManager( 3083): Adding local MAP profile
D/BluetoothMap( 3083): Create BluetoothMap proxy object
D/BluetoothManagerService(  736): Message: 30
D/BluetoothManagerService(  736): Message: 30
,D/LocalBluetoothProfileManager( 3083): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3083): 394176405: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3083): 394176405: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  736): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3123 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  736): Killing 2413:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10069/pid_2413/cgroup.procs: No such file or directory
,D/AdapterServiceConfig( 3075): Adding HeadsetService
D/AdapterServiceConfig( 3075): Adding A2dpService
D/AdapterServiceConfig( 3075): Adding HidService
D/AdapterServiceConfig( 3075): Adding HealthService
D/AdapterServiceConfig( 3075): Adding PanService
D/AdapterServiceConfig( 3075): Adding GattService
D/AdapterServiceConfig( 3075): Adding BluetoothMapService
,D/BluetoothManagerService(  736): Message: 20
D/BluetoothManagerService(  736): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@127ea82d:true
D/BluetoothAdapterState( 3075): make
,I/bluedroid( 3075): init
I/BluetoothAdapterState( 3075): Entering OffState
,I/bte_conf( 3075): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3075): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3075): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3075): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3075): get_profile_interface socket
I/bluedroid( 3075): get_profile_interface map_client
,I/GKI_LINUX( 3075): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothManagerService(  736): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  736): Message: 40
,D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 3075): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  736): Bluetooth Adapter name changed to Nexus 5
D/BluetoothAdapterProperties( 3075): Name is: Nexus 5
D/BluetoothManagerService(  736): Stored Bluetooth name: Nexus 5
I/bluedroid( 3075): config_hci_snoop_log
D/BluetoothManagerService(  736): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  736): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3075): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3075): Setting state to 11
I/BluetoothAdapterState( 3075): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  736): Message: 60
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  736): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3075): make
,I/BluetoothBondStateMachine( 3075): StableState(): Entering Off State
D/BluetoothHeadset(  736): Proxy object connected
D/BluetoothHeadset( 1184): Proxy object connected
D/BluetoothHeadset( 1184): Proxy object connected
D/BluetoothHeadset( 1228): Proxy object connected
D/HeadsetService( 3075): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3075): classInitNative: succeeds
D/HeadsetStateMachine( 3075): make
,I/BluetoothAdapterState( 3075): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/HeadsetStateMachine( 3075): max_hf_connections = 1
I/bluedroid( 3075): get_profile_interface handsfree
D/HeadsetStateMachine( 3075): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3075): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a3af0aa
,D/A2dpService( 3075): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3075): classInitNative: succeeds
I/bluedroid( 3075): get_profile_interface avrcp
,E/RemoteController( 3075): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3075): classInitNative: succeeds
D/A2dpStateMachine( 3075): make
,I/bluedroid( 3075): get_profile_interface a2dp
I/GKI_LINUX( 3075): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3075): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a3af0aa
I/BluetoothHidServiceJni( 3075): classInitNative: succeeds
,D/A2dpStateMachine( 3075): Enter Disconnected: -2
,D/BluetoothInputDevice( 3083): Proxy object connected
,D/HidProfile( 3083): Bluetooth service connected
I/art     (  736): Explicit concurrent mark sweep GC freed 14059(693KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 938us total 64.321ms
,D/BluetoothA2dp(  736): Proxy object connected
,D/HidService( 3075): Received start request. Starting profile...
I/bluedroid( 3075): get_profile_interface hidhost
D/BluetoothAdapterService( 3075): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a3af0aa
I/BluetoothHealthServiceJni( 3075): classInitNative: succeeds
,D/HealthService( 3075): Received start request. Starting profile...
,I/bluedroid( 3075): get_profile_interface health
,D/BluetoothAdapterService( 3075): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a3af0aa
I/BluetoothPanServiceJni( 3075): classInitNative(L105): succeeds
,D/PanService( 3075): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3075): initializeNative(L110): pan
I/bluedroid( 3075): get_profile_interface pan
D/BluetoothPan( 3083): BluetoothPAN Proxy object connected
D/PanProfile( 3083): Bluetooth service connected
,D/BluetoothAdapterService( 3075): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a3af0aa
,I/BtGatt.JNI( 3075): classInitNative(L863): classInitNative: Success!
D/BtGatt.DebugUtils( 3075): handleDebugAction() action=null
,D/BtGatt.GattService( 3075): Received start request. Starting profile...
D/BtGatt.GattService( 3075): start()
I/bluedroid( 3075): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3075): advertise manager created
,D/BluetoothAdapterService( 3075): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a3af0aa
,V/BluetoothMapService( 3075): BluetoothMapBinder()
,D/BluetoothMap( 3083): Proxy object connected
D/BluetoothMapService( 3075): Received start request. Starting profile...
D/BluetoothMapService( 3075): start()
D/MapProfile( 3083): Bluetooth service connected
D/BluetoothMap( 3083): getConnectedDevices()
,D/BluetoothMap( 3083): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3075): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3075): createReceiver()
,D/BluetoothMapEmailAppObserver( 3075): initObservers()
D/BluetoothMapEmailAppObserver( 3075): getEnabledAccountItems()
,D/BluetoothAdapterService( 3075): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a3af0aa
,D/HeadsetStateMachine( 3075): Proxy object connected
,V/BluetoothMapService( 3075): Handler(): got msg=1
,D/HeadsetStateMachine( 3075): Disconnected process message: 10, size: 0
D/BluetoothAdapterState( 3075): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3075): enable
D/HeadsetPhoneState( 3075): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3075): Disconnected process message: 11, size: 0
I/bt_hci_bdroid( 3075): init
I/GKI_LINUX( 3075): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3075): btu_task pending for preload complete event
I/bt_vendor( 3075): init
I/bt_vnd_conf( 3075): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3075): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3075): userial_init
I/art     ( 1488): Explicit concurrent mark sweep GC freed 1599(55KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/21MB, paused 222us total 10.285ms
,I/bt_userial_vendor( 3075): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3075): device fd = 53 open
D/AuthorizationBluetoothService( 1297): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_userial( 3075): Entering userial_read_thread()
,I/ActivityManager(  736): Killing 1855:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/bt_hwcfg( 3075): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3075): Chipset BCM4335C0
D/bt_hwcfg( 3075): Target name = [BCM4335C0]
I/bt_hwcfg( 3075): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  736): failed to open /acct/uid_10045/pid_1855/cgroup.procs: No such file or directory
,D/Tethering(  736): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3082): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 3082): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/WifiConfigStore(  736): Loading config and enabling all networks 
,D/WifiService(  736): New client listening to asynchronous messages
,I/bt_hwcfg( 3075): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3075): Settlement delay -- 100 ms
I/bt_hwcfg( 3075): Setting fw settlement delay to 100 
,E/WifiConfigStore(  736): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2332): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  736): Setting external_sim to 1
,D/WifiStateMachine(  736): Setting OUI to DA-A1-19
I/WifiNative-HAL(  736): startHal
D/wifi    (  736): setting scan oui 0x9c49f610
D/WifiHAL (  736): Sending mac address OUI
E/WifiHAL (  736): failed to set scanning mac OUI; result = -95
,E/native  (  736): do suspend true
,D/CommandListener(  180): Setting iface cfg
D/CommandListener(  180): Trying to bring up p2p0
,D/WifiMonitor(  736): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  736): p2pGetDeviceAddress
,D/WifiNative-HAL(  736): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,D/WifiScanningService(  736): SCAN_AVAILABLE : 3
D/RttService(  736): SCAN_AVAILABLE : 3
D/WifiScanningService(  736): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  736): startHal
,D/RttService(  736): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  736): getting scan capabilities on interface[1] = 0x9c49f610
D/WifiHAL (  736): Creating message to get scan capablities; iface = 21
,D/WifiHAL (  736): In GetCapabilities::handleResponse
D/WifiHAL (  736): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  736): StartedState
,I/wpa_supplicant( 3082): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3075): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 3075): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3075): vendor lib fwcfg completed
,I/bt-btu  ( 3075): btu_task received preload complete event
,I/        ( 3075): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3075): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3075): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3075): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3075): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3075): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3075): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3075): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3075): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3075): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3075): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3075): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3075): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3075): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3075): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3075): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 3075): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 3075): Calling BTA_HhEnable
E/bt-btif ( 3075): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3075): Address is:34:FC:EF:11:AE:67
D/BluetoothAdapterProperties( 3075): Name is: Nexus 5
D/BluetoothAdapterProperties( 3075): Scan Mode:20
D/BluetoothAdapterProperties( 3075): Discoverable Timeout:120
,W/bt-smp  ( 3075): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3075): Plain text(LSB ~ MSB) = cf 8d 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3075): Encrypted text(LSB ~ MSB) = a6 4c c3 94 fb f2 17 25 1f e0 72 9d a5 94 ae 70 
W/bt-btm  ( 3075): Stopping oneshot timer
,D/BluetoothManagerService(  736): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  736): Stored Bluetooth name: Nexus 5
,D/bte_conf( 3075): Device ID record 1 : primary
D/bte_conf( 3075):   vendorId            = 000f
D/bte_conf( 3075):   vendorIdSource      = 0001
D/bte_conf( 3075):   product             = 1200
D/bte_conf( 3075):   version             = 1436
D/bte_conf( 3075):   clientExecutableURL = 
D/bte_conf( 3075):   serviceDescription  = 
D/bte_conf( 3075):   documentationURL    = 
D/bte_conf( 3075): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3075): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3075): ScanMode =  20
D/BluetoothAdapterProperties( 3075): State =  11
D/BluetoothAdapterProperties( 3075): Setting state to 12
I/BluetoothAdapterState( 3075): Bluetooth adapter state changed: 11-> 12
D/BluetoothManagerService(  736): Message: 60
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  736): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothPanServiceJni( 3075): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothMap( 3083): onBluetoothStateChange: up=true
I/BluetoothAdapterState( 3075): Entering On State
D/BluetoothAdapterProperties( 3075): Scan Mode:21
D/BluetoothAdapterProperties( 3075): Discoverable Timeout:120
D/BluetoothHeadset( 1184): onBluetoothStateChange: up=true
D/BluetoothPbap( 3083): onBluetoothStateChange: up=true
D/BluetoothHeadset(  736): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 3083): onBluetoothStateChange: up=true
D/BluetoothPan( 3083): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1228): onBluetoothStateChange: up=true
D/BluetoothA2dp(  736): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1184): onBluetoothStateChange: up=true
D/BluetoothManagerService(  736): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  736): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  736): Message: 40
D/BluetoothManagerService(  736): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,E/bt_h4   ( 3075): vendor lib postload completed
,I/Telecom ( 1184): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
D/BluetoothMapService( 3075): onReceive
,D/BluetoothMapService( 3075): STATE_ON
V/BluetoothMapService( 3075): Handler(): got msg=1
W/bt-smp  ( 3075): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3075): Plain text(LSB ~ MSB) = 51 93 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3075): Encrypted text(LSB ~ MSB) = c6 67 07 f7 82 f2 75 68 b9 9c 58 ae 26 64 77 84 
W/bt-btm  ( 3075): Stopping oneshot timer
D/BluetoothMapMasInstance( 3075): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3075): MAS initSocket()
D/BluetoothMapMasInstance( 3075):   masId = 00
D/BluetoothMapMasInstance( 3075):   msgTypes = 0e
D/BluetoothMapMasInstance( 3075):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3075):   SDP string = 000eSMS/MMS
,W/bt-smp  ( 3075): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3075): Plain text(LSB ~ MSB) = bb dd 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3075): Encrypted text(LSB ~ MSB) = 7b 0c 14 07 87 07 1a 3f 96 a4 4c 7b 95 c7 81 1c 
W/bt-btm  ( 3075): Stopping oneshot timer
W/bt-smp  ( 3075): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3075): Plain text(LSB ~ MSB) = 0b c1 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3075): Encrypted text(LSB ~ MSB) = 00 fc 29 15 3f ec c3 09 ab 31 38 e8 0f 80 98 6b 
W/bt-btm  ( 3075): Stopping oneshot timer
D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/HeadsetStateMachine( 3075): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3075): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3075): mNumber:  mType: 128
D/HeadsetStateMachine( 3075): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3075): terminateScoUsingVirtualVoiceCall:No present call to terminate
W/BluetoothAdapter( 3075): getBluetoothService() called with no BluetoothManagerCallback
V/BluetoothMapMasInstance( 3075): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3075): Accepting socket connection...
,D/LocalBluetoothProfileManager( 3083): Adding local A2DP profile
D/BluetoothManagerService(  736): Message: 30
D/LocalBluetoothProfileManager( 3083): Adding local HEADSET profile
,D/BluetoothManagerService(  736): Message: 30
W/bt-smp  ( 3075): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3075): Plain text(LSB ~ MSB) = f1 2b 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3075): Encrypted text(LSB ~ MSB) = d5 4e db a8 2d 0c 5b 48 b8 d1 b4 ed 74 99 bf 7e 
W/bt-btm  ( 3075): Stopping oneshot timer
W/ContextImpl( 3083): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3083): Proxy object connected
,D/A2dpProfile( 3083): Bluetooth service connected
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3075): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothHeadset( 3083): Proxy object connected
D/HeadsetProfile( 3083): Bluetooth service connected
,D/DockEventReceiver( 3083): finishStartingService: stopping service
,D/BluetoothPbap( 3083): Proxy object connected
D/PbapServerProfile( 3083): Bluetooth service connected
,D/AuthorizationBluetoothService( 1297): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  736): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3075): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3075): Accept thread started.
,I/jxcore-log( 3008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3008): 
,I/wpa_supplicant( 3082): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  736): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
E/WifiConfigStore(  736): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  736): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  736): will read network variables netId=1
,E/WifiStateMachine(  736): CMD_AUTO_CONNECT did save config ->  nid=1
E/WifiConfigStore(  736): will read network variables netId=1
I/wpa_supplicant( 3082): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  736): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3082): PNO: In assoc process
,I/wpa_supplicant( 3082): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3082): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3082): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  736): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  736): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  180): Setting iface cfg
,E/WifiStateMachine(  736): Start Dhcp Watchdog 1
,E/native  (  736): do suspend false
,E/WifiStateMachine(  736): scanCount==0 - aborting
,I/jxcore-log( 3008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3008): 
,I/jxcore-log( 3008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 3008): 
,I/jxcore-log( 3008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3008): 
,I/jxcore-log( 3008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3008): 
,I/jxcore-log( 3008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3008): 
,I/jxcore-log( 3008): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3008): 
,I/dhcpcd  ( 3255): version 5.5.6 starting
,E/dhcpcd  ( 3255): get_duid: Read-only file system
,I/dhcpcd  ( 3255): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3008): Test app app.js loaded
I/jxcore-log( 3008): 
,I/Choreographer( 3008): Skipped 209 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3008): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 3255): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3255): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  736): do suspend true
,D/ConnectivityService(  736): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  736): Adding iface wlan0 to network 100
,E/WifiStateMachine(  736): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  736): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  736): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  736): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  736): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  736): Setting Dns servers for network 100 to [/192.168.1.1]
,D/Nat464Xlat(  736): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  736): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Connected
D/ConnectivityService(  736): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/CSLegacyTypeTracker(  736): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  736): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.114/24,fe80::5255:27ff:fef0:fd0b/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 14:16:07 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453126567705], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453126567690]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  736): Validated
,D/ConnectivityService(  736): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  736): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  736): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  899): CM callback handler got msg 524290
D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1228): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3008): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3008): BLE advertisement is supported
I/jxcore-log( 3008): 
,D/ConnectivityService(  736): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  736): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  736): Setting time of day to sec=1453126570
,W/AlarmManagerService(  736): Unable to set rtc to 1453126570: Invalid argument
,I/NetworkMonitor( 2526): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2526): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1612): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1612): onCreate
,D/SystemUpdateService( 1612): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1612): active receiver: enabled
,I/SystemUpdateService( 1612): showing system update notification
,I/ValidateNoPeople(  736): skipping global notification
,V/SystemUpdateService( 1612): retry (wakeup: false) in 3599971 ms
,I/iu.SyncManager( 1612): SYNC; picasa accounts
,D/NetworkLogImpl( 1612): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1612): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 1612): num queued entries: 0
,I/iu.UploadsManager( 1612): num updated entries: 0
I/iu.SyncManager( 1612): NEXT; no task
,E/GpsLocationProvider(  736): No APN found to select.
,D/GpsLocationProvider(  736): NTP server returned: 1453126567502 (Mon Jan 18 15:16:07 GMT+01:00 2016) reference: 85660 certainty: 12 system time offset: -3144
,E/LocSvc_eng(  736): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
E/ActivityThread( 1612): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  736): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 31332, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  736): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 120407, reason: UserStart
,D/SystemUpdateService( 1612): onDestroy
,I/ActivityManager(  736): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3362 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 222us total 9.811ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 211us total 9.248ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 213us total 9.668ms
,E/Auth.Api.Credentials( 1612): [CredentialSyncAdapter] Unknown sync event.
,I/Babel   ( 2332): connection state changed from UNKNOWN to CONNECTED
,I/GCM     ( 1297): GCM config loaded
,I/GAv4    ( 3362): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3362):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3362):   adb logcat -s GAv4
,W/GAv4    ( 3362): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3362): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 3362): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService(  736): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  736): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  736): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1612): CM callback handler got msg 524290
,W/DriveInitializer( 1612): Awaiting to be initialized
,W/DriveInitializer( 1612): Background init thread started
,I/WebViewFactory( 3362): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3362): Time to load native libraries: 2 ms (timestamps 9221-9223)
,I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3362): Binding Chromium to main looper Looper (main, tid 1) {2254233f}
,I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
,I/chromium( 3362): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3362): Initializing chromium process, singleProcess=true
W/art     ( 3362): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3362): ApplicationContext is null in ApplicationStatus
,W/chromium( 3362): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3362): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3362): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1612): Background init thread ended
,W/AudioManagerAndroid( 3362): Requires BLUETOOTH permission
,I/NSApplication( 3362): Starting up...
,I/ActivityManager(  736): Killing 2493:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10003/pid_2493/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3454 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,D/TimeService( 3454): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453126571605
,D/        ( 3454): TimeServiceNative: User Time to be set is 1453126571605
D/QC-time-services( 3454): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3454): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3454): Lib:time_genoff_operation: pargs->ts_val = 1453126571605
D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453126571605
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1453126571605, operation = 0
D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/22/70 20:6:38
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 12254798000
D/QC-time-services(  199): Daemon:new time 1453126571605 
D/QC-time-services(  199): Daemon: delta 1440871773605 genoff 1440871773605 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871773605 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3454): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871773605 to memory
,D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1137161771605
E/QC-time-services( 3454): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  736): Killing 2387:com.google.android.gm/u0a70 (adj 15): empty #17
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,W/libprocessgroup(  736): failed to open /acct/uid_10070/pid_2387/cgroup.procs: No such file or directory
,I/art     (  736): Explicit concurrent mark sweep GC freed 50935(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 955us total 57.761ms
,I/CheckinService( 1612): Checkin interval check for package: unspecified last checkin: 1453095904099 min interval config: 0 actual interval: 30667602
,I/ActivityManager(  736): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3473 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3473): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3473):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3473):   adb logcat -s GAv4
,W/GAv4    ( 3473): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3473): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3473): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  736): Killing 1963:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10002/pid_1963/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3495 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  736): Killing 2825:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  736): failed to open /acct/uid_10008/pid_2825/cgroup.procs: No such file or directory
,W/ResourcesManager( 3495): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3495): Created com.android.providers.calendar.CalendarAlarmManager@25f28b4c(com.android.providers.calendar.CalendarProvider2@177ea795)
,I/CalendarProvider2( 3495): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3495): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Finsky  ( 2444): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2444): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,E/SQLiteLog( 3495): (284) automatic index on view_events(_id)
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1297): Vacuum at: now=1453126582732 tag=VacuumService
,E/ActivityThread( 1612): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  736): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 120407, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  736): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 212339, reason: UserStart
,I/ClearcutLoggerApiImpl( 1297): disconnect managed GoogleApiClient
,I/jxcore-log( 3008): --= Surplus to requirements =--
I/jxcore-log( 3008): 
I/jxcore-log( 3008): ****TEST TOOK:  ms ****
I/jxcore-log( 3008): 
I/jxcore-log( 3008): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3008): 
,D/AndroidRuntime( 3553): 
D/AndroidRuntime( 3553): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3553): CheckJNI is OFF
,D/AndroidRuntime( 3553): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  736): Killing 3008:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  736): WIN DEATH: Window{1ffab550 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  736): Client connection lost with reason: 4
,W/PackageSettings(  736): Skipping PackageSetting{766c2d9 com.example.hello/10278} due to missing metadata
,I/ActivityManager(  736):   Force finishing activity ActivityRecord{224f62a2 u0 com.test.thalitest/.MainActivity t216}
,W/ActivityManager(  736): Spurious death for ProcessRecord{3801debb 3008:com.test.thalitest/u0a270}, curProc for 3008: null
,I/ActivityManager(  736): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/art     ( 1612): Explicit concurrent mark sweep GC freed 16112(1131KB) AllocSpace objects, 25(400KB) LOS objects, 24% free, 22MB/30MB, paused 457us total 31.320ms
,I/InputReader(  736): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1297): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1079): resetDictionaries() : en_US
,I/art     ( 1315): Explicit concurrent mark sweep GC freed 3952(294KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 1.116ms total 43.846ms
,I/Keyboard.Facilitator.DecoderInitializer( 1079): run()
,I/Decoder ( 1079): createOrResetDecoder
I/art     (  736): Explicit concurrent mark sweep GC freed 21164(1160KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.101ms total 67.886ms
,I/art     ( 1410): Explicit concurrent mark sweep GC freed 8998(616KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 18MB/25MB, paused 327us total 89.218ms
,D/VoicemailCleanupService( 1384): Cleaning up data for package: com.test.thalitest
,D/NetworkChangeNotifierAutoDetect(  944): Network connectivity changed, type is: 2
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigService( 1297): onCreate
,I/UpdateIcingCorporaServi( 1410): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1315): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a3af0aa new=com.google.android.velvet.VelvetApplication@a3af0aa
,I/LibraryLoader( 1433): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/ActivityManager(  736): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3592 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  736): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  736): Receieved: android.intent.action.PACKAGE_REMOVED
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1297): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/OpenGLRenderer(  944): Initialized EGL, version 1.4
,D/OpenGLRenderer(  944): Enabling debug mode 0
,D/TaskPersister(  736): removeObsoleteFile: deleting file=216_task.xml
,I/LibraryLoader( 1433): Time to load native libraries: 81 ms (timestamps 4070-4151)
I/LibraryLoader( 1433): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1433): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 1433): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 1433): Attempt to remove local handle scope entry from IRT, ignoring
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1079): run()
,W/ContextImpl( 3592): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,I/art     (  736): Explicit concurrent mark sweep GC freed 7649(410KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.665ms total 183.075ms
,W/InputMethodManagerService(  736): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@22a7cc4b (uid=10034 pid=944)
,D/PackageBroadcastService( 1612): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 1612): Clearing selected account for com.test.thalitest
,W/ResourcesManager( 1315): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1612): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1612): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1612): Module APK com.google.android.play.games already loaded
I/ActivityManager(  736): Killing 1472:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1079): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/ResourcesManager( 1315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1079): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1079): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1079): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1079): run()
I/StatsUtilsManager( 1079): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1079): shouldRecordStats() = Too Soon
,I/Launcher( 1315): Deferring update until onResume
,I/Launcher( 1315): Deferring update until onResume
,D/AndroidRuntime( 3553): Shutting down VM
,W/libprocessgroup(  736): failed to open /acct/uid_10013/pid_1472/cgroup.procs: No such file or directory
,E/NetworkScheduler.SchedulerReceiver( 1297): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1297): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1612): Removing dialog suppression flag for package com.test.thalitest
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1612): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/ActivityManager(  736): Delay finish: com.google.android.apps.plus/.service.PhotosAppTransitionMonitor
,I/ActivityManager(  736): Resuming delayed broadcast
I/UpdateIcingCorporaServi( 1410): UpdateCorporaTask done [took 364 ms] updated apps [took 364 ms] 
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1612): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1612): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1612): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1612): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  736): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=3642 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/BaseAppContext( 1612): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1612): App measurement is starting up, version: 8489
I/GMPM-SVC( 1612): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,W/BaseAppContext( 1612): Using Auth Proxy for data requests.
,I/Icing   ( 1612): doRemovePackageData com.test.thalitest
,I/ActivityManager(  736): Killing 2785:com.android.defcontainer/u0a5 (adj 15): empty #17
,I/ActivityManager(  736): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=3668 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,W/libprocessgroup(  736): failed to open /acct/uid_10005/pid_2785/cgroup.procs: No such file or directory
,I/ActivityManager(  736): Killing 3083:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  736): Client connection lost with reason: 4
,W/libprocessgroup(  736): failed to open /acct/uid_1000/pid_3083/cgroup.procs: No such file or directory
,D/ExternalStorage( 3668): After updating volumes, found 1 active roots
,I/PhenotypeConfigurator( 1297): Scheduling Phenotype for one-off execution 4484 seconds from now (1453126796581)

```
