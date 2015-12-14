#### Test 50650278e3ff7c2_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1552): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1552): Module APK com.google.android.play.games already loaded
I/GAv4    ( 2894): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2894):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2894):   adb logcat -s GAv4
W/GAv4    ( 2894): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2894): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2894): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2894): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2376): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
W/ResourcesManager( 2894): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2894): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2297:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 2894): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2894): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2894): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2297/cgroup.procs: No such file or directory
V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1552): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
I/Icing   ( 1552): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1552): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
I/Icing   ( 1552): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,D/AndroidRuntime( 2951): 
D/AndroidRuntime( 2951): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2951): CheckJNI is OFF
D/AndroidRuntime( 2951): Calling main entry com.android.commands.am.Am
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2971 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2951): Shutting down VM
V/ActivityManager(  759): Display changed displayId=0
I/ActivityManager(  759): Killing 2344:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2344/cgroup.procs: No such file or directory
I/WebViewFactory( 2971): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2971): Time to load native libraries: 3 ms (timestamps 7774-7777)
I/LibraryLoader( 2971): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2971): Binding Chromium to main looper Looper (main, tid 1) {1c0c6a92}
I/LibraryLoader( 2971): Expected native library version number "",actual native library version number ""
I/chromium( 2971): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2971): Initializing chromium process, singleProcess=true
W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2971): ApplicationContext is null in ApplicationStatus
W/chromium( 2971): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2971): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2971): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2971): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2971): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@187246b7:true
,D/BluetoothAdapter( 2971): 769811084: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2971): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2971): CordovaWebView is running on device made by: LGE
,W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2971): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2971): Render dirty regions requested: true
,D/Atlas   ( 2971): Validating map...
,W/chromium( 2971): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2971): Initialized EGL, version 1.4
D/OpenGLRenderer( 2971): Enabling debug mode 0
,W/BindingManager( 2971): Cannot call determinedVisibility() - never saw a connection for the pid: 2971
,W/IInputConnectionWrapper( 2971): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +427ms (total +56s224ms)
,D/JsMessageQueue( 2971): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2971): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2971): jxcore cordova android initializing
,W/jxcore-log( 2971): Initializing JXcore engine
W/jxcore-log( 2971): JXcore engine is ready
,W/jxcore-log( 2971): Starting JXcore engine
,W/.test.thalitest( 2971): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7966]" dev="sockfs" ino=7966 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2971): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2971): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9550]" dev="sockfs" ino=9550 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2971): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17314]" dev="sockfs" ino=17314 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2971): Platform android
W/jxcore-log( 2971): 
,W/jxcore-log( 2971): Process ARCH arm
W/jxcore-log( 2971): 
,I/jxcore-log( 2971): JXcore Cordova bridge is ready!
I/jxcore-log( 2971): 
W/jxcore-log( 2971): JXcore engine is started
,I/Choreographer( 2971): Skipped 111 frames!  The application may be doing too much work on its main thread.
,I/chromium( 2971): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2971): Toggling radios to true
I/jxcore-log( 2971): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  759): Message: 1
D/BluetoothManagerService(  759): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  759): New client listening to asynchronous messages
D/WifiService(  759): setWifiEnabled: true pid=2971, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  180): Softap fwReload - Ok
I/jxcore-log( 2971): Radios toggled
I/jxcore-log( 2971): 
,D/CommandListener(  180): Setting iface cfg
,D/CommandListener(  180): Trying to bring down wlan0
,D/CommandListener(  180): Clearing all IP addresses on wlan0
,I/ActivityManager(  759): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3024 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2971): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2971): 
D/WifiMonitor(  759): startMonitoring(wlan0) with mConnected = false
,I/jxcore-log( 2971): Perf Test app loaded loaded
I/jxcore-log( 2971): 
,I/jxcore-log( 2971): check test folder
I/jxcore-log( 2971): 
I/jxcore-log( 2971): found test : ./testFindPeers.js
I/jxcore-log( 2971): 
,I/wpa_supplicant( 3025): Successfully initialized wpa_supplicant
,I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3041 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/jxcore-log( 2971): found test : ./testSendData.js
I/jxcore-log( 2971): 
,I/wpa_supplicant( 3025): rfkill: Cannot open RFKILL control device
,W/ResourcesManager( 3024): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/Choreographer( 2971): Skipped 71 frames!  The application may be doing too much work on its main thread.
I/chromium( 2971): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f5a45b5:true
,D/BluetoothAdapter( 3041): 470575762: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3041): Adding local MAP profile
,D/BluetoothMap( 3041): Create BluetoothMap proxy object
D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3041): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3041): 470575762: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 3041): 470575762: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  759): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3072 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 1756:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/AdapterServiceConfig( 3024): Adding HeadsetService
,D/AdapterServiceConfig( 3024): Adding A2dpService
D/AdapterServiceConfig( 3024): Adding HidService
,D/AdapterServiceConfig( 3024): Adding HealthService
D/AdapterServiceConfig( 3024): Adding PanService
D/AdapterServiceConfig( 3024): Adding GattService
D/AdapterServiceConfig( 3024): Adding BluetoothMapService
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@350bddab:true
,D/BluetoothAdapterState( 3024): make
,I/bluedroid( 3024): init
I/BluetoothAdapterState( 3024): Entering OffState
,I/bte_conf( 3024): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3024): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3024): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3024): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 3024): get_profile_interface socket
I/bluedroid( 3024): get_profile_interface map_client
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_1756/cgroup.procs: No such file or directory
,I/GKI_LINUX( 3024): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  759): Message: 40
,D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/BluetoothAdapterProperties( 3024): Address is:34:FC:EF:11:AE:67
,I/bluedroid( 3024): config_hci_snoop_log
,D/BluetoothAdapterProperties( 3024): Name is: Nexus 5
D/BluetoothManagerService(  759): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceUp() to 9 receivers.
D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterState( 3024): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3024): Setting state to 11
,I/BluetoothAdapterState( 3024): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3024): make
,I/BluetoothBondStateMachine( 3024): StableState(): Entering Off State
,D/BluetoothHeadset( 1170): Proxy object connected
,D/BluetoothHeadset( 1206): Proxy object connected
D/BluetoothHeadset(  759): Proxy object connected
D/HeadsetService( 3024): Received start request. Starting profile...
D/BluetoothHeadset( 1170): Proxy object connected
,I/BluetoothHeadsetServiceJni( 3024): classInitNative: succeeds
,I/BluetoothAdapterState( 3024): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3024): make
,D/HeadsetStateMachine( 3024): max_hf_connections = 1
I/bluedroid( 3024): get_profile_interface handsfree
,D/HeadsetStateMachine( 3024): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3024): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ae0c63
,D/BluetoothA2dp(  759): Proxy object connected
D/A2dpService( 3024): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3024): classInitNative: succeeds
I/bluedroid( 3024): get_profile_interface avrcp
E/RemoteController( 3024): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3024): classInitNative: succeeds
D/A2dpStateMachine( 3024): make
I/bluedroid( 3024): get_profile_interface a2dp
I/GKI_LINUX( 3024): gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/BluetoothAdapterService( 3024): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ae0c63
D/A2dpStateMachine( 3024): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3024): classInitNative: succeeds
,D/HidService( 3024): Received start request. Starting profile...
I/bluedroid( 3024): get_profile_interface hidhost
D/BluetoothAdapterService( 3024): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ae0c63
,I/BluetoothHealthServiceJni( 3024): classInitNative: succeeds
D/BluetoothInputDevice( 3041): Proxy object connected
,D/HidProfile( 3041): Bluetooth service connected
D/HealthService( 3024): Received start request. Starting profile...
I/bluedroid( 3024): get_profile_interface health
D/BluetoothAdapterService( 3024): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ae0c63
I/BluetoothPanServiceJni( 3024): classInitNative(L105): succeeds
,I/art     (  759): Explicit concurrent mark sweep GC freed 14374(701KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.030ms total 49.779ms
,D/PanService( 3024): Received start request. Starting profile...
D/BluetoothPan( 3041): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 3024): initializeNative(L110): pan
I/bluedroid( 3024): get_profile_interface pan
,D/PanProfile( 3041): Bluetooth service connected
,D/BluetoothAdapterService( 3024): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ae0c63
,I/BtGatt.JNI( 3024): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3024): handleDebugAction() action=null
,D/BtGatt.GattService( 3024): Received start request. Starting profile...
D/BtGatt.GattService( 3024): start()
I/bluedroid( 3024): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3024): advertise manager created
,D/BluetoothAdapterService( 3024): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ae0c63
,V/BluetoothMapService( 3024): BluetoothMapBinder()
,D/BluetoothMap( 3041): Proxy object connected
D/BluetoothMapService( 3024): Received start request. Starting profile...
,D/BluetoothMapService( 3024): start()
D/MapProfile( 3041): Bluetooth service connected
D/BluetoothMap( 3041): getConnectedDevices()
,D/BluetoothMap( 3041): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3024): Found 0 applications
D/BluetoothMapEmailAppObserver( 3024): createReceiver()
,D/BluetoothMapEmailAppObserver( 3024): initObservers()
D/BluetoothMapEmailAppObserver( 3024): getEnabledAccountItems()
,D/BluetoothAdapterService( 3024): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38ae0c63
D/HeadsetStateMachine( 3024): Proxy object connected
,D/HeadsetStateMachine( 3024): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3024): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3024): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3024): Handler(): got msg=1
,D/BluetoothAdapterState( 3024): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3024): enable
,I/GKI_LINUX( 3024): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3024): btu_task pending for preload complete event
I/bt_hci_bdroid( 3024): init
,I/bt_vendor( 3024): init
I/bt_vnd_conf( 3024): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3024): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3024): userial_init
,I/bt_userial_vendor( 3024): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3024): device fd = 53 open
D/bt_userial( 3024): Entering userial_read_thread()
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 1564(54KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 413us total 16.353ms
,D/AuthorizationBluetoothService( 1284): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  759): Killing 2444:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/bt_hwcfg( 3024): bt vendor lib: set UART baud 4000000
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2444/cgroup.procs: No such file or directory
,D/bt_hwcfg( 3024): Chipset BCM4335C0
D/bt_hwcfg( 3024): Target name = [BCM4335C0]
,I/bt_hwcfg( 3024): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/Tethering(  759): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3025): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  759): Loading config and enabling all networks 
,E/WifiConfigStore(  759): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  759): Setting external_sim to 1
,D/WifiStateMachine(  759): Setting OUI to DA-A1-19
I/WifiNative-HAL(  759): startHal
D/wifi    (  759): setting scan oui 0x9ba89670
D/WifiHAL (  759): Sending mac address OUI
,E/WifiHAL (  759): failed to set scanning mac OUI; result = -95
,W/Settings( 2261): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiService(  759): New client listening to asynchronous messages
,E/native  (  759): do suspend true
,I/bt_hwcfg( 3024): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3024): Settlement delay -- 100 ms
,I/bt_hwcfg( 3024): Setting fw settlement delay to 100 
,D/WifiScanningService(  759): SCAN_AVAILABLE : 3
D/WifiScanningService(  759): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  759): startHal
D/RttService(  759): SCAN_AVAILABLE : 3
D/RttService(  759): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/wifi    (  759): getting scan capabilities on interface[1] = 0x9ba89670
D/CommandListener(  180): Setting iface cfg
D/WifiHAL (  759): Creating message to get scan capablities; iface = 21
D/CommandListener(  180): Trying to bring up p2p0
D/WifiHAL (  759): In GetCapabilities::handleResponse
D/WifiHAL (  759): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  759): StartedState
D/WifiMonitor(  759): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3025): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  759): p2pGetDeviceAddress
,D/WifiNative-HAL(  759): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/bt_hwcfg( 3024): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3024): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3024): vendor lib fwcfg completed
,I/bt-btu  ( 3024): btu_task received preload complete event
,I/        ( 3024): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3024): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3024): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3024): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 3024): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3024): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3024): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3024): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3024): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3024): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3024): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3024): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3024): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3024): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3024): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3024): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fdf9d5 
E/bt-btm  ( 3024): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fdf9d5 
,E/bt-btif ( 3024): Calling BTA_HhEnable
E/bt-btif ( 3024): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3024): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 3024): Name is: Nexus 5
,W/bt-smp  ( 3024): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3024): Plain text(LSB ~ MSB) = cf 74 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3024): Encrypted text(LSB ~ MSB) = 4f 9c 85 1d 2c 1f 4a fb eb 5e 47 b6 4e af 1a f5 
,W/bt-btm  ( 3024): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3024): Scan Mode:20
D/BluetoothAdapterProperties( 3024): Discoverable Timeout:120
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
,D/bte_conf( 3024): Device ID record 1 : primary
D/bte_conf( 3024):   vendorId            = 000f
D/bte_conf( 3024):   vendorIdSource      = 0001
D/bte_conf( 3024):   product             = 1200
D/bte_conf( 3024):   version             = 1436
D/bte_conf( 3024):   clientExecutableURL = 
D/bte_conf( 3024):   serviceDescription  = 
D/bte_conf( 3024):   documentationURL    = 
D/bte_conf( 3024): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3024): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3024): ScanMode =  20
D/BluetoothAdapterProperties( 3024): State =  11
,D/BluetoothAdapterProperties( 3024): Setting state to 12
I/BluetoothAdapterState( 3024): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothA2dp(  759): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1170): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 3024): Entering On State
,D/BluetoothPanServiceJni( 3024): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 3024): Scan Mode:21
D/BluetoothAdapterProperties( 3024): Discoverable Timeout:120
,D/BluetoothMap( 3041): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3041): onBluetoothStateChange: up=true
,D/BluetoothPbap( 3041): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
,D/BluetoothHeadset( 1206): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1170): onBluetoothStateChange: up=true
,D/BluetoothPan( 3041): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadset(  759): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  759): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  759): Message: 40
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,E/bt_h4   ( 3024): vendor lib postload completed
,D/BluetoothMapService( 3024): onReceive
D/BluetoothMapService( 3024): STATE_ON
,V/BluetoothMapService( 3024): Handler(): got msg=1
,D/BluetoothMapMasInstance( 3024): Map Service startRfcommSocketListener
,I/Telecom ( 1170): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/HeadsetStateMachine( 3024): Disconnected process message: 9, size: 0
,D/HeadsetStateMachine( 3024): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3024): mNumber:  mType: 128
D/HeadsetStateMachine( 3024): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3024): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/BluetoothMapMasInstance( 3024): MAS initSocket()
D/BluetoothMapMasInstance( 3024):   masId = 00
D/BluetoothMapMasInstance( 3024):   msgTypes = 0e
D/BluetoothMapMasInstance( 3024):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3024):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3024): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3024): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3024): Accepting socket connection...
,D/LocalBluetoothProfileManager( 3041): Adding local A2DP profile
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3041): Adding local HEADSET profile
,D/BluetoothManagerService(  759): Message: 30
,W/ContextImpl( 3041): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3041): Proxy object connected
D/A2dpProfile( 3041): Bluetooth service connected
,D/BluetoothHeadset( 3041): Proxy object connected
,D/HeadsetProfile( 3041): Bluetooth service connected
,D/DockEventReceiver( 3041): finishStartingService: stopping service
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3024): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPbap( 3041): Proxy object connected
D/PbapServerProfile( 3041): Bluetooth service connected
,D/AuthorizationBluetoothService( 1284): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3024): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3024): Accept thread started.
,I/jxcore-log( 2971): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2971): 
,D/Finsky  ( 2376): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2376): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ClearcutLoggerApiImpl( 1284): disconnect managed GoogleApiClient
,I/VacuumService( 1284): Vacuum at: now=1450100399095 tag=VacuumService
,D/PerfProfileCollectorService( 1552): User is not opt-in to Usage & Diagnostics.
D/PerfProfileCollectorService( 1552): removeStateFiles() called
,D/PerfProfileCollectorService( 1552): User is not opt-in to Usage & Diagnostics.
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Killing 2321:com.google.android.gm/u0a70 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2321/cgroup.procs: No such file or directory
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Prepared write state in 10ms
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1284): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-13-11-39-27.bin
,TIME-OUT KILL (timeout was 1800000ms)
```
