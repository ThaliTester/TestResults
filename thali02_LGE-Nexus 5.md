#### Test 5319156460e1811_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1616): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2952): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2952):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2952):   adb logcat -s GAv4
W/GAv4    ( 2952): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2952): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2952): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2952): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
D/Finsky  ( 2430): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/AndroidRuntime( 2994): 
D/AndroidRuntime( 2994): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2994): CheckJNI is OFF
--------- beginning of system
W/ResourcesManager( 2952): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2952): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  759): Killing 2343:com.google.android.deskclock/u0a38 (adj 15): empty #17
V/JNIHelp ( 2952): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 2994): Calling main entry com.android.commands.am.Am
W/System  ( 2952): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2952): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2343/cgroup.procs: No such file or directory
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3031 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2994): Shutting down VM
V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/ActivityManager(  759): Display changed displayId=0
I/WebViewFactory( 3031): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3031): Time to load native libraries: 5 ms (timestamps 7811-7816)
I/LibraryLoader( 3031): Expected native library version number "",actual native library version number ""
I/Icing   ( 1616): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
V/WebViewChromiumFactoryProvider( 3031): Binding Chromium to main looper Looper (main, tid 1) {f37ae2c}
I/LibraryLoader( 3031): Expected native library version number "",actual native library version number ""
I/chromium( 3031): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3031): Initializing chromium process, singleProcess=true
W/art     ( 3031): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3031): ApplicationContext is null in ApplicationStatus
W/chromium( 3031): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3031): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3031): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3031): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3031): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/Icing   ( 1616): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6b731ef:true
D/BluetoothAdapter( 3031): 77035377: getState() :  mService = null. Returning STATE_OFF
I/Icing   ( 1616): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/Icing   ( 1616): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/art     ( 3031): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3031): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3031): CordovaWebView is running on device made by: LGE
W/art     ( 3031): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3031): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3031): Render dirty regions requested: true
D/Atlas   ( 3031): Validating map...
W/chromium( 3031): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 3031): Initialized EGL, version 1.4
D/OpenGLRenderer( 3031): Enabling debug mode 0
I/Keyboard.Facilitator( 1067): onFinishInput()
W/IInputConnectionWrapper( 3031): showStatusIcon on inactive InputConnection
I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +471ms (total +56s463ms)
W/BindingManager( 3031): Cannot call determinedVisibility() - never saw a connection for the pid: 3031
D/JsMessageQueue( 3031): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3031): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 3031): jxcore cordova android initializing
,I/ActivityManager(  759): Killing 2402:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2402/cgroup.procs: No such file or directory
,W/jxcore-log( 3031): Initializing JXcore engine
W/jxcore-log( 3031): JXcore engine is ready
,W/jxcore-log( 3031): Starting JXcore engine
,W/.test.thalitest( 3031): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7968]" dev="sockfs" ino=7968 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3031): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 3031): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8519]" dev="sockfs" ino=8519 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 3031): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18333]" dev="sockfs" ino=18333 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 3031): Platform android
W/jxcore-log( 3031): 
W/jxcore-log( 3031): Process ARCH arm
W/jxcore-log( 3031): 
,I/jxcore-log( 3031): JXcore Cordova bridge is ready!
I/jxcore-log( 3031): 
W/jxcore-log( 3031): JXcore engine is started
I/Choreographer( 3031): Skipped 111 frames!  The application may be doing too much work on its main thread.
I/chromium( 3031): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3031): Toggling radios to true
I/jxcore-log( 3031): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  759): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  759): Message: 1
D/BluetoothManagerService(  759): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  759): setWifiEnabled: true pid=3031, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  759): New client listening to asynchronous messages
,I/ActivityManager(  759): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3097 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SoftapController(  178): Softap fwReload - Ok
I/jxcore-log( 3031): Radios toggled
I/jxcore-log( 3031): 
D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring down wlan0
D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/WifiMonitor(  759): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=3115 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/ResourcesManager( 3097): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3112): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 3112): rfkill: Cannot open RFKILL control device
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23e043e2:true
,D/AdapterServiceConfig( 3097): Adding HeadsetService
D/AdapterServiceConfig( 3097): Adding A2dpService
D/AdapterServiceConfig( 3097): Adding HidService
D/AdapterServiceConfig( 3097): Adding HealthService
D/AdapterServiceConfig( 3097): Adding PanService
D/AdapterServiceConfig( 3097): Adding GattService
D/AdapterServiceConfig( 3097): Adding BluetoothMapService
D/BluetoothAdapter( 3115): 255307308: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3115): Adding local MAP profile
,D/BluetoothMap( 3115): Create BluetoothMap proxy object
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 3115): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3115): 255307308: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3115): 255307308: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20da3760:true
,D/BluetoothAdapterState( 3097): make
,I/bluedroid( 3097): init
,I/BluetoothAdapterState( 3097): Entering OffState
,I/bte_conf( 3097): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3097): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3097): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3097): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 3097): get_profile_interface socket
I/bluedroid( 3097): get_profile_interface map_client
,I/GKI_LINUX( 3097): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 3097): Address is:34:FC:EF:11:AE:67
,I/ActivityManager(  759): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3150 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
,I/ActivityManager(  759): Killing 1812:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,D/BluetoothAdapterProperties( 3097): Name is: Nexus 5
,I/art     (  193): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 294us total 11.185ms
,I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 175us total 7.892ms
,I/art     (  193): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 176us total 7.794ms
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_1812/cgroup.procs: No such file or directory
D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  759): Message: 40
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3097): config_hci_snoop_log
D/BluetoothManagerService(  759): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 3097): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3097): Setting state to 11
I/BluetoothAdapterState( 3097): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3097): make
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,D/BluetoothHeadset( 1147): Proxy object connected
,D/BluetoothHeadset( 1147): Proxy object connected
D/HeadsetService( 3097): Received start request. Starting profile...
D/BluetoothHeadset( 1176): Proxy object connected
,D/BluetoothHeadset(  759): Proxy object connected
,I/BluetoothHeadsetServiceJni( 3097): classInitNative: succeeds
,I/BluetoothAdapterState( 3097): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 3097): make
,D/HeadsetStateMachine( 3097): max_hf_connections = 1
I/bluedroid( 3097): get_profile_interface handsfree
,D/HeadsetStateMachine( 3097): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,D/BluetoothA2dp(  759): Proxy object connected
,D/A2dpService( 3097): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3097): classInitNative: succeeds
I/bluedroid( 3097): get_profile_interface avrcp
,E/RemoteController( 3097): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 3097): classInitNative: succeeds
D/A2dpStateMachine( 3097): make
I/bluedroid( 3097): get_profile_interface a2dp
I/GKI_LINUX( 3097): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
D/A2dpStateMachine( 3097): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3097): classInitNative: succeeds
,D/BluetoothInputDevice( 3115): Proxy object connected
D/HidService( 3097): Received start request. Starting profile...
I/bluedroid( 3097): get_profile_interface hidhost
D/HidProfile( 3115): Bluetooth service connected
D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
I/BluetoothHealthServiceJni( 3097): classInitNative: succeeds
D/HealthService( 3097): Received start request. Starting profile...
I/bluedroid( 3097): get_profile_interface health
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
I/BluetoothPanServiceJni( 3097): classInitNative(L105): succeeds
,D/BluetoothPan( 3115): BluetoothPAN Proxy object connected
D/PanService( 3097): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3097): initializeNative(L110): pan
I/bluedroid( 3097): get_profile_interface pan
D/PanProfile( 3115): Bluetooth service connected
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
I/BtGatt.JNI( 3097): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 3097): handleDebugAction() action=null
,D/BtGatt.GattService( 3097): Received start request. Starting profile...
D/BtGatt.GattService( 3097): start()
I/bluedroid( 3097): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 3097): advertise manager created
,I/art     (  759): Explicit concurrent mark sweep GC freed 14104(713KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.034ms total 60.819ms
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,V/BluetoothMapService( 3097): BluetoothMapBinder()
,D/BluetoothMapService( 3097): Received start request. Starting profile...
,D/BluetoothMapService( 3097): start()
,D/BluetoothMap( 3115): Proxy object connected
D/MapProfile( 3115): Bluetooth service connected
D/BluetoothMap( 3115): getConnectedDevices()
D/BluetoothMap( 3115): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 3097): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3097): createReceiver()
,D/BluetoothMapEmailAppObserver( 3097): initObservers()
,D/BluetoothMapEmailAppObserver( 3097): getEnabledAccountItems()
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
D/HeadsetStateMachine( 3097): Proxy object connected
,D/HeadsetStateMachine( 3097): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3097): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3097): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 3097): Handler(): got msg=1
,D/BluetoothAdapterState( 3097): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3097): enable
,I/GKI_LINUX( 3097): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3097): btu_task pending for preload complete event
I/bt_hci_bdroid( 3097): init
,I/bt_vendor( 3097): init
I/bt_vnd_conf( 3097): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3097): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3097): userial_init
,I/bt_userial_vendor( 3097): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 3097): device fd = 53 open
D/bt_userial( 3097): Entering userial_read_thread()
,D/AuthorizationBluetoothService( 1305): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  759): Killing 2489:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty #17
,I/bt_hwcfg( 3097): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 3097): Chipset BCM4335C0
D/bt_hwcfg( 3097): Target name = [BCM4335C0]
,I/bt_hwcfg( 3097): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2489/cgroup.procs: No such file or directory
,D/Tethering(  759): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3112): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  759): Loading config and enabling all networks 
,E/WifiConfigStore(  759): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  759): Setting external_sim to 1
,W/Settings( 2309): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  759): Setting OUI to DA-A1-19
I/WifiNative-HAL(  759): startHal
,D/wifi    (  759): setting scan oui 0x9283d5b0
D/WifiHAL (  759): Sending mac address OUI
E/WifiHAL (  759): failed to set scanning mac OUI; result = -95
,I/wpa_supplicant( 3112): wlan0: CTRL-EVENT-SCAN-STARTED 
,E/native  (  759): do suspend true
,D/WifiScanningService(  759): SCAN_AVAILABLE : 3
D/RttService(  759): SCAN_AVAILABLE : 3
D/WifiScanningService(  759): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  759): startHal
,D/RttService(  759): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiService(  759): New client listening to asynchronous messages
,D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring up p2p0
,D/wifi    (  759): getting scan capabilities on interface[1] = 0x9283d5b0
D/WifiHAL (  759): Creating message to get scan capablities; iface = 21
D/WifiHAL (  759): In GetCapabilities::handleResponse
D/WifiHAL (  759): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiMonitor(  759): startMonitoring(p2p0) with mConnected = true
D/WifiScanningService(  759): StartedState
,D/WifiNative-HAL(  759): p2pGetDeviceAddress
,D/WifiNative-HAL(  759): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 3112): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 3097): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3097): Settlement delay -- 100 ms
,I/bt_hwcfg( 3097): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3097): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 3097): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 3097): vendor lib fwcfg completed
I/bt-btu  ( 3097): btu_task received preload complete event
,I/        ( 3097): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3097): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3097): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3097): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3097): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3097): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3097): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3097): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3097): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3097): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3097): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3097): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3097): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3097): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3097): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 3097): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ed99d5 
E/bt-btm  ( 3097): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ed99d5 
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkUtils( 1360): OkHttp exception
W/EventLoggerService( 1360): Unable to send logs Error code: 262146
,E/bt-btif ( 3097): Calling BTA_HhEnable
E/bt-btif ( 3097): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3097): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 3097): Name is: Nexus 5
,D/BluetoothAdapterProperties( 3097): Scan Mode:20
D/BluetoothAdapterProperties( 3097): Discoverable Timeout:120
,D/bte_conf( 3097): Device ID record 1 : primary
D/bte_conf( 3097):   vendorId            = 000f
D/bte_conf( 3097):   vendorIdSource      = 0001
D/bte_conf( 3097):   product             = 1200
D/bte_conf( 3097):   version             = 1436
D/bte_conf( 3097):   clientExecutableURL = 
D/bte_conf( 3097):   serviceDescription  = 
D/bte_conf( 3097):   documentationURL    = 
D/bte_conf( 3097): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 3097): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 3097): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3097): ScanMode =  20
D/BluetoothAdapterProperties( 3097): State =  11
D/BluetoothAdapterProperties( 3097): Setting state to 12
I/BluetoothAdapterState( 3097): Bluetooth adapter state changed: 11-> 12
W/bt-smp  ( 3097): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3097): Plain text(LSB ~ MSB) = f9 9e 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3097): Encrypted text(LSB ~ MSB) = 79 c1 a7 1f 88 99 2b 41 76 ae ed 76 6b bc 5a f9 
W/bt-btm  ( 3097): Stopping oneshot timer
,D/BluetoothManagerService(  759): Message: 60
,D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(true) to 9 receivers.
D/BluetoothAdapterProperties( 3097): Scan Mode:21
D/BluetoothAdapterProperties( 3097): Discoverable Timeout:120
I/BluetoothAdapterState( 3097): Entering On State
D/BluetoothHeadset( 1147): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1147): onBluetoothStateChange: up=true
D/BluetoothA2dp(  759): onBluetoothStateChange: up=true
D/BluetoothMap( 3115): onBluetoothStateChange: up=true
D/BluetoothPan( 3115): onBluetoothStateChange(on) call bindService
D/BluetoothPbap( 3115): onBluetoothStateChange: up=true
,D/BluetoothInputDevice( 3115): onBluetoothStateChange: up=true
D/BluetoothHeadset(  759): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1176): onBluetoothStateChange: up=true
D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothMapService( 3097): onReceive
D/BluetoothMapService( 3097): STATE_ON
V/BluetoothMapService( 3097): Handler(): got msg=1
D/BluetoothMapMasInstance( 3097): Map Service startRfcommSocketListener
,E/bt_h4   ( 3097): vendor lib postload completed
,D/BluetoothManagerService(  759): Message: 40
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/bt-smp  ( 3097): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3097): Plain text(LSB ~ MSB) = 2a d5 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3097): Encrypted text(LSB ~ MSB) = df ff d2 47 33 72 9b 74 85 de 02 80 71 02 bc 3b 
W/bt-btm  ( 3097): Stopping oneshot timer
D/BluetoothMapMasInstance( 3097): MAS initSocket()
D/BluetoothMapMasInstance( 3097):   masId = 00
D/BluetoothMapMasInstance( 3097):   msgTypes = 0e
D/BluetoothMapMasInstance( 3097):   masName = SMS/MMS
D/BluetoothMapMasInstance( 3097):   SDP string = 000eSMS/MMS
W/bt-smp  ( 3097): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3097): Plain text(LSB ~ MSB) = 3f 7a 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3097): Encrypted text(LSB ~ MSB) = a2 95 0e 22 39 6d 88 22 32 be cc 19 e1 52 08 f3 
W/bt-btm  ( 3097): Stopping oneshot timer
I/Telecom ( 1147): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
W/bt-smp  ( 3097): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3097): Plain text(LSB ~ MSB) = ab ce 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3097): Encrypted text(LSB ~ MSB) = ea ce b0 45 49 4a 9d 34 16 77 eb b0 fa 60 a1 50 
W/bt-btm  ( 3097): Stopping oneshot timer
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 3097): Succeed to create listening socket 
D/BluetoothMapMasInstance( 3097): Accepting socket connection...
W/bt-smp  ( 3097): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3097): Plain text(LSB ~ MSB) = 21 14 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3097): Encrypted text(LSB ~ MSB) = e4 d5 9a b7 b2 b1 bb f8 71 31 94 2d 50 62 4a e8 
W/bt-btm  ( 3097): Stopping oneshot timer
D/HeadsetStateMachine( 3097): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 3097): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 3097): mNumber:  mType: 128
D/HeadsetStateMachine( 3097): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 3097): terminateScoUsingVirtualVoiceCall:No present call to terminate
D/LocalBluetoothProfileManager( 3115): Adding local A2DP profile
D/BluetoothManagerService(  759): Message: 30
D/LocalBluetoothProfileManager( 3115): Adding local HEADSET profile
,D/BluetoothManagerService(  759): Message: 30
,W/ContextImpl( 3115): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 3115): Proxy object connected
D/A2dpProfile( 3115): Bluetooth service connected
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothHeadset( 3115): Proxy object connected
D/HeadsetProfile( 3115): Bluetooth service connected
,D/DockEventReceiver( 3115): finishStartingService: stopping service
,D/BluetoothPbap( 3115): Proxy object connected
D/PbapServerProfile( 3115): Bluetooth service connected
,D/AuthorizationBluetoothService( 1305): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3097): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3097): Accept thread started.
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 3031): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 3031): 
I/jxcore-log( 3031): my name is : LGE-Nexus 5_PT4768
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): attempting to connect to test coordinator
I/jxcore-log( 3031): 
I/jxcore-log( 3031): check test folder
I/jxcore-log( 3031): 
I/jxcore-log( 3031): found test : ./testFindPeers.js
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): found test : ./testReConnect.js
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): found test : ./testSendData.js
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): Test app app.js loaded
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/chromium( 3031): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  759): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiStateMachine(  759): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  759): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=1
,E/WifiConfigStore(  759): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  759): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  759): will read network variables netId=1
,E/WifiStateMachine(  759): CMD_AUTO_CONNECT did save config ->  nid=1
,E/WifiConfigStore(  759): will read network variables netId=1
,I/wpa_supplicant( 3112): wlan0: Trying to associate with c0:ff:d4:d3:aa:4a (SSID='NG7005g' freq=5220 MHz)
,E/WifiConfigStore(  759): setLastSelectedConfiguration -1
,E/wpa_supplicant( 3112): PNO: In assoc process
,I/wpa_supplicant( 3112): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3112): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3112): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=1 id_str=]
,D/ConnectivityService(  759): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  178): Setting iface cfg
E/WifiStateMachine(  759): Start Dhcp Watchdog 1
,E/native  (  759): do suspend false
,E/WifiStateMachine(  759): scanCount==0 - aborting
,I/dhcpcd  ( 3277): version 5.5.6 starting
,E/dhcpcd  ( 3277): get_duid: Read-only file system
,I/dhcpcd  ( 3277): wlan0: rebinding lease of 192.168.1.114
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/dhcpcd  ( 3277): wlan0: acknowledged 192.168.1.114 from 192.168.1.1
,I/dhcpcd  ( 3277): wlan0: leased 192.168.1.114 for 86400 seconds
,E/native  (  759): do suspend true
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  759): Adding iface wlan0 to network 100
,E/WifiStateMachine(  759): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  759): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  759): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  759): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  759): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  759): Setting Dns servers for network 100 to [/192.168.1.1]
D/Nat464Xlat(  759): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  759): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759):    accepting network in place of null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on "NG7005g"
D/ConnectivityService(  759): Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
D/CSLegacyTypeTracker(  759): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  759): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::5255:27ff:fef0:fd0b/64,192.168.1.114/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 09 Dec 2015 23:13:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449702826548], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449702826529]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Validated
D/ConnectivityService(  759): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  759): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  759): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524290
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/TelephonyNetworkFactory( 1176): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/jxcore-log( 3031): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  759): MasterInitialState.processMessage what=3
,D/AlarmManagerService(  759): Setting time of day to sec=1449702829
,W/AlarmManagerService(  759): Unable to set rtc to 1449702829: Invalid argument
,I/NetworkMonitor( 2510): type=WIFI subType= reason=null isConnected=true
,V/MusicLeanback( 2510): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SystemUpdateService( 1616): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1616): onCreate
,D/SystemUpdateService( 1616): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1616): active receiver: enabled
,I/SystemUpdateService( 1616): showing system update notification
,I/ValidateNoPeople(  759): skipping global notification
,I/GoogleURLConnFactory( 1305): Using platform SSLCertificateSocketFactory
,V/SystemUpdateService( 1616): retry (wakeup: false) in 3599976 ms
,I/PhenotypeConfigurator( 1305): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,I/iu.SyncManager( 1616): SYNC; picasa accounts
,D/NetworkLogImpl( 1616): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1616): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1616): num queued entries: 0
,I/iu.UploadsManager( 1616): num updated entries: 0
,D/SystemUpdateService( 1616): onDestroy
,I/iu.SyncManager( 1616): NEXT; no task
,E/GpsLocationProvider(  759): No APN found to select.
,I/ActivityManager(  759): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3378 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GpsLocationProvider(  759): NTP server returned: 1449702826691 (Thu Dec 10 00:13:46 GMT+01:00 2015) reference: 86423 certainty: 7 system time offset: -3156
E/LocSvc_eng(  759): E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,E/ActivityThread( 1616): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  759): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 25408, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  759): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 120287, reason: UserStart
,I/Babel   ( 2309): connection state changed from UNKNOWN to CONNECTED
,E/Auth.Api.Credentials( 1616): [CredentialSyncAdapter] Unknown sync event.
,I/GAv4    ( 3378): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3378):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3378):   adb logcat -s GAv4
,D/ConnectivityService(  759): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  759): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  759): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 1616): CM callback handler got msg 524290
,W/GAv4    ( 3378): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GCM     ( 1305): GCM config loaded
,W/GAv4    ( 3378): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3378): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1616): Explicit concurrent mark sweep GC freed 30462(2MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 22MB/37MB, paused 1.084ms total 45.808ms
,W/DriveInitializer( 1616): Awaiting to be initialized
,W/DriveInitializer( 1616): Background init thread started
,I/art     (  759): Explicit concurrent mark sweep GC freed 53859(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 27MB/41MB, paused 897us total 63.241ms
,I/WebViewFactory( 3378): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3378): Time to load native libraries: 2 ms (timestamps 9-11)
I/LibraryLoader( 3378): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3378): Binding Chromium to main looper Looper (main, tid 1) {3655333e}
I/LibraryLoader( 3378): Expected native library version number "",actual native library version number ""
I/chromium( 3378): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3378): Initializing chromium process, singleProcess=true
W/art     ( 3378): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3378): ApplicationContext is null in ApplicationStatus
,W/chromium( 3378): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 3378): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,W/DriveInitializer( 1616): Background init thread ended
,W/AudioManagerAndroid( 3378): Requires BLUETOOTH permission
,I/NSApplication( 3378): Starting up...
,W/art     ( 2644): Suspending all threads took: 7.120ms
,I/ActivityManager(  759): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3481 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimeService( 3481): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449702830473
D/        ( 3481): TimeServiceNative: User Time to be set is 1449702830473
D/QC-time-services( 3481): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3481): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3481): Lib:time_genoff_operation: pargs->ts_val = 1449702830473
,D/QC-time-services(  196): Daemon: Connection accepted:time_genoff
D/QC-time-services( 3481): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  196): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449702830473
D/QC-time-services(  196): Daemon:genoff_opr: Base = 2, val = 1449702830473, operation = 0
D/QC-time-services(  196): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/13/70 5:4:34
D/QC-time-services(  196): Daemon:Value read from RTC seconds = 8831074000
D/QC-time-services(  196): Daemon:new time 1449702830473 
D/QC-time-services(  196): Daemon: delta 1440871756473 genoff 1440871756473 
D/QC-time-services(  196): Daemon:genoff_persistent_update: Writing genoff = 1440871756473 to memory
D/QC-time-services(  196): Daemon:Opening File: /data/system/time/ats_2
,D/QC-time-services(  196): Daemon:time_persistent_memory_opr:Genoff write operation 
V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QC-time-services(  196): Updating the TOD offset
D/QC-time-services(  196): Daemon:genoff_persistent_update: Writing genoff = 1440871756473 to memory
,D/QC-time-services(  196): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  196): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  196): Daemon:Update to modem bit set
E/QC-time-services( 3481): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  196): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  196): Daemon: Base = 2, Value being sent to MODEM = 1133738030473
I/ActivityManager(  759): Killing 2366:com.google.android.gm/u0a70 (adj 15): empty #17
,D/QC-time-services(  196): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  196): Daemon: Time-services: Waiting to acceptconnection
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2366/cgroup.procs: No such file or directory
,I/CheckinService( 1616): Checkin interval check for package: unspecified last checkin: 1449673064750 min interval config: 0 actual interval: 29765772
,W/art     ( 2644): Attempt to remove local handle scope entry from IRT, ignoring
,W/PhenotypeConfigurator( 1305): Server returned 404
,I/art     ( 1475): Explicit concurrent mark sweep GC freed 2611(105KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 1.799ms total 13.334ms
,I/ActivityManager(  759): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=3511 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 3511): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3511):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3511):   adb logcat -s GAv4
,W/GAv4    ( 3511): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3511): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3511): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  759): Killing 1935:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_1935/cgroup.procs: No such file or directory
,I/ActivityManager(  759): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3540 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/VacuumService( 1305): Vacuum at: now=1449702831066 tag=VacuumService
,W/ResourcesManager( 3540): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/ActivityManager(  759): Killing 2806:com.google.android.gms:car/u0a8 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10008/pid_2806/cgroup.procs: No such file or directory
,I/CalendarProvider2( 3540): Created com.android.providers.calendar.CalendarAlarmManager@201dc1df(com.android.providers.calendar.CalendarProvider2@f37ae2c)
,I/PhenotypeConfigurator( 1305): Scheduling Phenotype for one-off execution 125 seconds from now (1449702831413)
,D/GetConfigurationSnapshotOperation( 1305): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1305): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1305): Using platform SSLCertificateSocketFactory
,I/art     ( 1305): Explicit concurrent mark sweep GC freed 63908(3MB) AllocSpace objects, 34(567KB) LOS objects, 39% free, 22MB/36MB, paused 694us total 48.902ms
,I/CalendarProvider2( 3540): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3540): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Finsky  ( 2430): [235] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2430): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,E/SQLiteLog( 3540): (284) automatic index on view_events(_id)
,I/art     (  759): Explicit concurrent mark sweep GC freed 29426(1262KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 1.166ms total 81.192ms
,I/ActivityManager(  759): Killing 2608:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10004/pid_2608/cgroup.procs: No such file or directory
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,W/SQLiteConnectionPool( 1616): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1067): run()
I/Keyboard.Facilitator( 1067): flushDynamicLanguageModels()
,I/ConfigService( 1305): onCreate
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/ConfigService( 1305): onDestroy
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,E/ActivityThread( 1616): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager(  759): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 120287, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  759): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 211201, reason: UserStart
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/ClearcutLoggerApiImpl( 1305): disconnect managed GoogleApiClient
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Coordinator is now connected to the server!
I/jxcore-log( 3031): 
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1305): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Killing 1461:com.google.android.partnersetup/u0a13 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1461/cgroup.procs: No such file or directory
,I/jxcore-log( 3031): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector command called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":22,"addressList":[{"address":"90:E7:C4:F6:69:77","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"F8:CF:C5:D9:E5:61","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"80:01:84:8A:B3
I/jxcore-log( 3031): Start now : testSendData.js
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 22
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): check server
I/jxcore-log( 3031): 
I/jxcore-log( 3031): serverPort is 37057
I/jxcore-log( 3031): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): stop: Stopping Bluetooth and peer discovery...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): initialize: 34:FC:EF:11:AE:67 LGE-Nexus 5_PT4768
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3031): initialize: My bluetooth address is 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): setState: INITIALIZED
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): verifyIdentityString: Identity string created: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): startWifiPeerDiscovery: Started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3031): start: OK
I/jxcore-log( 3031): StartBroadcasting started ok
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:36.139Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:36.139Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:36.139Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 00:F4:6F:30:E0:6C
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 00:F4:6F:30:E0:6C)
I/jxcore-log( 3031): 2015-12-09T23:19:36.151Z SendDataTCPServer.js: TCP/IP server is bound to port: 37057
I/jxcore-log( 3031): 
I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): startWifiPeerDiscovery: Already started
I/io.jxcore.node.ConnectionHelper( 3031): onConnectionManagerStateChanged: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3031): onConnectionManagerStateChanged: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 00:F4:6F:30:E0:6C (thread ID: 282)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 7C:F9:0E:51:18:22 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 7C:F9:0E:51:18:22, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 283)
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 283)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 283
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 283)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 283)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT7365, Bluetooth address: 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:51:18:22, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 284)
,I/jxcore-log( 3031): 2015-12-09T23:19:37.856Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 284)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 286, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 285, name: Sender)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,I/jxcore-log( 3031): 2015-12-09T23:19:38.782Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:38.789Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:38.874Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:38.955Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:38.964Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.009Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.058Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.156Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.175Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3031): 
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,I/jxcore-log( 3031): 2015-12-09T23:19:39.251Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3031): 
,E/BluetoothEventManager( 3115): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/jxcore-log( 3031): 2015-12-09T23:19:39.329Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/jxcore-log( 3031): 2015-12-09T23:19:39.362Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.401Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.468Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.474Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.518Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3031): 
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 00:F4:6F:30:E0:6C
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 00:F4:6F:30:E0:6C not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 00:F4:6F:30:E0:6C, but we have no record of that device.
,I/jxcore-log( 3031): 2015-12-09T23:19:39.618Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.728Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:39.745Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.204Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.367Z SendDataTCPServer.js: TCP/IP server has received 41580 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.386Z SendDataTCPServer.js: TCP/IP server has received 43560 bytes of data
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9988, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3031): 2015-12-09T23:19:40.578Z SendDataTCPServer.js: TCP/IP server has received 45540 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.586Z SendDataTCPServer.js: TCP/IP server has received 47520 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.621Z SendDataTCPServer.js: TCP/IP server has received 49500 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.695Z SendDataTCPServer.js: TCP/IP server has received 51480 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.735Z SendDataTCPServer.js: TCP/IP server has received 53460 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:40.974Z SendDataTCPServer.js: TCP/IP server has received 55440 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.025Z SendDataTCPServer.js: TCP/IP server has received 57420 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.032Z SendDataTCPServer.js: TCP/IP server has received 59400 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.062Z SendDataTCPServer.js: TCP/IP server has received 61380 bytes of data
I/jxcore-log( 3031): 
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 282)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 287)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 287)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 282)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 287)
,I/jxcore-log( 3031): 2015-12-09T23:19:41.233Z SendDataTCPServer.js: TCP/IP server has received 63360 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.268Z SendDataTCPServer.js: TCP/IP server has received 65340 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.426Z SendDataTCPServer.js: TCP/IP server has received 67320 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.438Z SendDataTCPServer.js: TCP/IP server has received 69300 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.558Z SendDataTCPServer.js: TCP/IP server has received 71280 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.686Z SendDataTCPServer.js: TCP/IP server has received 73260 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.943Z SendDataTCPServer.js: TCP/IP server has received 75240 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.961Z SendDataTCPServer.js: TCP/IP server has received 77220 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:41.987Z SendDataTCPServer.js: TCP/IP server has received 79200 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.021Z SendDataTCPServer.js: TCP/IP server has received 81180 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.144Z SendDataTCPServer.js: TCP/IP server has received 83160 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.185Z SendDataTCPServer.js: TCP/IP server has received 85140 bytes of data
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3031): 2015-12-09T23:19:42.353Z SendDataTCPServer.js: TCP/IP server has received 87120 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.361Z SendDataTCPServer.js: TCP/IP server has received 89100 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.397Z SendDataTCPServer.js: TCP/IP server has received 91080 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.426Z SendDataTCPServer.js: TCP/IP server has received 93060 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.505Z SendDataTCPServer.js: TCP/IP server has received 95040 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.548Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3031): 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3031): 2015-12-09T23:19:42.818Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:42.824Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 82 bytes successfully (thread ID: 287)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 287)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT9988, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
,I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 2
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 288)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 53267
,I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 53267 (peer ID: 00:F4:6F:30:E0:6C)
,I/jxcore-log( 3031): 2015-12-09T23:19:43.269Z SendDataConnector.js: CLIENT connected to 53267, error: null
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:43.276Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 53267
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 288)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 290, name: Receiver)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 286, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 284
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 286
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 285
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 285, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:51:18:22 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 285, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 286, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 289, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:19:43.360Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:43.360Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x42
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:3100
,I/jxcore-log( 3031): 2015-12-09T23:19:47.017Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/jxcore-log( 3031): 2015-12-09T23:19:48.103Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3031): 
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@113dab90:true
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/jxcore-log( 3031): 2015-12-09T23:19:48.530Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:48.905Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3031): 2015-12-09T23:19:49.258Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:49.552Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:50.006Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:50.371Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:50.552Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:50.762Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:50.767Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:19:50.789Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:50.790Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 290
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 289
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 289, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 290, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:F4:6F:30:E0:6C
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 289, name: Sender)
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:F4:6F:30:E0:6C
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 290, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:19:50.837Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:50.838Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:50.838Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:19:50.839Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 291)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: S5mini-1
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 7C:F9:0E:37:96:AB not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 7C:F9:0E:37:96:AB, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 292)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 292)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 292)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 292)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 292
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 292)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 292)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [00:f4:6f:30:e0:6c]: 0, 0, 0
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): invalid rfc slot id: 6
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 293)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 82 bytes successfully (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 293)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 293
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 293)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 293)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): invalid rfc slot id: 7
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,W/bt-btif ( 3097): invalid rfc slot id: 8
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 294)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 294)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 294)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 294)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 294
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 294)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 294)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3097): invalid rfc slot id: 9
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 295)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 295)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 82 bytes successfully (thread ID: 295)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 295)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 295
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 295)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 295)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
,W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): invalid rfc slot id: 11
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
,W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x40
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f8:cf:c5:d9:e5:61]: 7, f, 230f
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F8:CF:C5:D9:E5:61 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: F8:CF:C5:D9:E5:61
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F8:CF:C5:D9:E5:61 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F8:CF:C5:D9:E5:61 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F8:CF:C5:D9:E5:61, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 296)
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: S5mini-1
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [7c:f9:0e:37:96:ab]: 6, f, 410d
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 81 bytes successfully (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT149 F8:CF:C5:D9:E5:61]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 296)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 296
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 296)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT149 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 296)
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 297)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 297)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 297)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 297)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 297
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 297)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 297)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [00:f4:6f:30:e0:6c]: 0, 0, 0
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: S5mini-1
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 298)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 298)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 82 bytes successfully (thread ID: 298)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 298)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 298
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 298)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 298)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): invalid rfc slot id: 12
,W/bt-btif ( 3097): invalid rfc slot id: 13
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x42 current:0x0
,W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x42
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x43
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 291),
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 291)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,W/bt-btif ( 3097): invalid rfc slot id: 10
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT149 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT1003, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT9988, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 2
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT1003, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3031): onConnected: Already connected with peer (ID: 7C:F9:0E:37:96:AB), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 3
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT9988, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: We have an incoming connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3031): onConnected: Already connected with peer (ID: 00:F4:6F:30:E0:6C), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 4
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT149, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
,I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 5
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT1003, Bluetooth address: 7C:F9:0E:37:96:AB
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: We have an incoming connection with peer with ID 7C:F9:0E:37:96:AB
W/io.jxcore.node.ConnectionHelper( 3031): onConnected: Already connected with peer (ID: 7C:F9:0E:37:96:AB), continuing anyway...
,I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 7C:F9:0E:37:96:AB, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 6
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT9988, Bluetooth address: 00:F4:6F:30:E0:6C
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: We have an incoming connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3031): onConnected: Already connected with peer (ID: 00:F4:6F:30:E0:6C), continuing anyway...
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 00:F4:6F:30:E0:6C, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 7
,I/jxcore-log( 3031): 2015-12-09T23:21:55.947Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:55.947Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 302)
,I/jxcore-log( 3031): 2015-12-09T23:21:55.950Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 301)
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 303)
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 304)
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 300)
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 305)
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 299)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 302)
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 300)
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
,D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
,D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
,D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 303)
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 304)
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3031): 2015-12-09T23:21:55.975Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:55.979Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 306, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 308, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 307, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 307, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 302
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 307
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 306
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 6 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 307, name: Receiver)
,I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 301)
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 305)
,I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 299)
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 306, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 6 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 306, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 310, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 311, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 309, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 309, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 300
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 309
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 308
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 314, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 312, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 313, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 316, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 315, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 318, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 319, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 317, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:21:56.000Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 308, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 312, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 314, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 319, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 5 incoming connection(s) left
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 5 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 308, name: Sender)
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 304
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 312
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 311
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 4 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 312, name: Receiver)
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 309, name: Receiver)
I/jxcore-log( 3031): 2015-12-09T23:21:56.015Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.015Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 303
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 314
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 310
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 3 incoming connection(s) left
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 311, thread name: Sender): Socket closed
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 299
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 319
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 316
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 314, name: Receiver)
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 317, thread name: Receiver): bt socket closed, read return: -1
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 2 incoming connection(s) left
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 310, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/jxcore-log( 3031): 2015-12-09T23:21:56.034Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.035Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 316, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 319, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 2 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 310, name: Sender)
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 301
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 317
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 313
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 317, name: Receiver)
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 311, name: Sender)
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 316, name: Sender)
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 313, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 7C:F9:0E:37:96:AB disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 313, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:21:56.046Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.050Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.052Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.054Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.055Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.058Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.062Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.065Z SendDataTCPServer.js: TCP/IP server got error : Error: write EPIPE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.066Z SendDataTCPServer.js: TCP/IP server got error : Error: write EPIPE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.066Z SendDataTCPServer.js: TCP/IP server got error : Error: write EPIPE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.067Z SendDataTCPServer.js: TCP/IP server got error : Error: write EPIPE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.068Z SendDataTCPServer.js: TCP/IP server got error : Error: write EPIPE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:21:56.069Z SendDataTCPServer.js: TCP/IP server got error : Error: write EPIPE
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 291)
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Thali Test's G2 36:fc:ef:de:0a:e2
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): invalid rfc slot id: 14
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 318, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 305
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 318
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 315
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 315, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 00:F4:6F:30:E0:6C disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 315, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 318, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:21:58.598Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3031): 2015-12-09T23:22:00.951Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:00.953Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4050ebc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test's G2 36:fc:ef:de:0a:e2
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: S5mini-1
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: F4:F1:E1:5C:3B:E2
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F4:F1:E1:5C:3B:E2 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F4:F1:E1:5C:3B:E2, but we have no record of that device.
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8773"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8773 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8773"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT8773, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: , Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 320)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 81 bytes successfully (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 320)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 320
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 320)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 320)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT1888, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 321)
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3031): 2015-12-09T23:22:04.835Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 321)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 322, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 323, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:22:05.832Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:05.842Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:05.912Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:22:05.964Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:05.965Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:05.965Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:05.966Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
I/jxcore-log( 3031): 2015-12-09T23:22:05.987Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 324)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8773"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8773"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/jxcore-log( 3031): 2015-12-09T23:22:06.547Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:06.717Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:06.879Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:06.911Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.082Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.089Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.247Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.537Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.573Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.625Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.634Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.707Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:07.804Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3031): 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3031): 2015-12-09T23:22:08.267Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:08.415Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:08.421Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:08.688Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:08.698Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:08.712Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:08.783Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:08.963Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.127Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data,
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.212Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.391Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.423Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.583Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.653Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.852Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.863Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:09.932Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.013Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.084Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.093Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.178Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.263Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.422Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.503Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.667Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.685Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.717Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.756Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.775Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.919Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:10.932Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:11.002Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:11.201Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:11.217Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:11.384Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,W/bt-btif ( 3097): invalid rfc slot id: 15
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 323, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 321
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 323
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 322
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 322, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 322, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 323, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:22:12.652Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9988, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-btm  ( 3097): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=2
E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f8:cf:c5:d9:e5:61]: 6, 1d, 7d3
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 325)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 325)
,W/bt-btif ( 3097): invalid rfc slot id: 16
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 325
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake failed (thread ID: 325)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 325)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x4f
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051084 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
I/jxcore-log( 3031): 2015-12-09T23:22:29.527Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:29.528Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:29.528Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 324)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 324)
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:22:34.531Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:34.532Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f8:cf:c5:d9:e5:61]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 326)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 81 bytes successfully (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT149 F8:CF:C5:D9:E5:61]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 326)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 326
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 326)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT149 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 326)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT149 F8:CF:C5:D9:E5:61]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: F8:CF:C5:D9:E5:61, name: motorola-Nexus 6_PT149, Bluetooth address: F8:CF:C5:D9:E5:61
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F8:CF:C5:D9:E5:61
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID F8:CF:C5:D9:E5:61, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 327)
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 327)
,I/jxcore-log( 3031): 2015-12-09T23:22:39.249Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 329, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 328, name: Sender)
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:22:39.535Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:39.536Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:39.536Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:22:39.536Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 330)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3031): 2015-12-09T23:22:39.995Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3031): 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:22:43.142Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:22:43.169Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:43.257Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:43.273Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:43.342Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3031): 2015-12-09T23:22:43.435Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:43.570Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:43.581Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3031): 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 20
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3031): 2015-12-09T23:22:45.903Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:46.038Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:46.181Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:46.319Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:46.387Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:46.531Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:46.733Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:46.937Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.072Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.170Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.205Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.211Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.220Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.255Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.269Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.303Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.310Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.319Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.446Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.582Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.717Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.852Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:47.993Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:48.134Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:48.268Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:48.400Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:48.535Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:48.744Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:48.822Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:48.955Z SendDataTCPServer.js: TCP/IP server has received 96128 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:49.089Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:22:49.224Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): invalid rfc slot id: 18
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 329, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 327
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 329
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 328
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 328, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:CF:C5:D9:E5:61 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 328, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 329, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:22:49.838Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 21
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 330)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x44
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051414 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:CF:C5:D9:E5:61, alias=null, name=Nexus 6, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 6
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 22
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 23
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 330)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 330)
,I/jxcore-log( 3031): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): The Coordinator has disconnected!
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
I/jxcore-log( 3031): 2015-12-09T23:23:00.915Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:00.916Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:00.916Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 330)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Coordinator is now connected to the server!
I/jxcore-log( 3031): 
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3031): 2015-12-09T23:23:05.916Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:05.917Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:23:10.926Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:10.926Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:10.927Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:10.927Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 24
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 25
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 331)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 331)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:26, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 26
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
,E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): invalid rfc slot id: 27
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 331)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 331)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
,I/jxcore-log( 3031): 2015-12-09T23:23:31.895Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:31.896Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:31.896Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 331)
,I/jxcore-log( 3031): 2015-12-09T23:23:36.896Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:36.897Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [7c:f9:0e:37:96:ab]: 7, f, 230f
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 332)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 332)
,W/bt-btif ( 3097): invalid rfc slot id: 19
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 332
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake failed (thread ID: 332)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 332)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x47
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT7825"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:9D:93:0B LGE-LG-D802_PT7825 34:FC:EF:9D:93:0B]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 34:FC:EF:9D:93:0B, peer name: LGE-LG-D802_PT7825, peer ID: 34:FC:EF:9D:93:0B, Wi-Fi Direct device name: Thali Test's G2, Wi-Fi Direct address: 36:fc:ef:de:0a:e2
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:9D:93:0B
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:23:41.903Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:41.904Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:41.905Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:23:41.905Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 7C:F9:0E:51:18:22)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 7C:F9:0E:51:18:22 (thread ID: 333)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9988, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,W/bt-btm  ( 3097): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa405124c rs_disc_pending=2
E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A5-1
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:29, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 29
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:30, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 30
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 333)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 333)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:31, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 31
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:32, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 32
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 333)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 333)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
,I/jxcore-log( 3031): 2015-12-09T23:24:04.102Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:04.103Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:04.117Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 7C:F9:0E:51:18:22
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 7C:F9:0E:51:18:22
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 7C:F9:0E:51:18:22), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:24:04.118Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- gotta redo : 7C:F9:0E:51:18:22, try count now: 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:04.119Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:04.119Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:04.119Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 80:01:84:8A:B3:68
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 80:01:84:8A:B3:68)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 80:01:84:8A:B3:68 (thread ID: 334)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: Connection to peer with ID 7C:F9:0E:51:18:22 failed", source: file:///android_asset/www/js/thali_main.js (63)
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 333)
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0xd  CID 0x40
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:33, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 33
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 80:01:84:8A:B3:68 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 80:01:84:8A:B3:68, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 334)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 335)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 334)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 335)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 335)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 335)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT936, Bluetooth address: 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID 80:01:84:8A:B3:68, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 336)
D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 48558
I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 48558 (peer ID: 80:01:84:8A:B3:68)
I/jxcore-log( 3031): 2015-12-09T23:24:08.679Z SendDataConnector.js: CLIENT connected to 48558, error: null
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:08.679Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:08.695Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 48558
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 336)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 338, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 337, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:24:09.318Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.377Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.475Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.508Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.594Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.676Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.730Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.753Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.845Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.925Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:09.926Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:24:09.944Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:09.944Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 80:01:84:8A:B3:68
I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 338
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 337
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 337, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 338, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Successfully disconnected (peer ID: 80:01:84:8A:B3:68
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 338, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 337, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:24:09.986Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:09.987Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:09.987Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:09.988Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa40517a4 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x43
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 35
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x10  CID 0x4d
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:36, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 36
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 339)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:37, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 37
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:38, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 38
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 339)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/jxcore-log( 3031): 2015-12-09T23:24:34.928Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:34.928Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:34.928Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 339)
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/jxcore-log( 3031): 2015-12-09T23:24:39.942Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:39.942Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:2A:F7:ED:96:BE), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:24:44.947Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:44.948Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:44.949Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:24:44.949Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:39, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 39
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 40
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 340)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 41
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 42
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 340)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 340)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE],
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/jxcore-log( 3031): 2015-12-09T23:25:05.900Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:05.900Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:05.900Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 340)
,I/jxcore-log( 3031): 2015-12-09T23:25:10.901Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:10.901Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1003","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT1003, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT936"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT936, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: , Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:2A:F7:ED:96:BE), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:25:15.905Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:25:15.912Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:15.913Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:15.913Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 341)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 43
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 44
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 341)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 341)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 45
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x10  CID 0x40
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:46, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 46
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 341)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1024","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
,I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT1024, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: , Wi-Fi Direct address: a2:39:f7:70:12:80
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
I/jxcore-log( 3031): 2015-12-09T23:25:41.677Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:41.678Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:41.679Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:25:46.681Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:46.682Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT149","ra":"F8:CF:C5:D9:E5:61"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT149 F8:CF:C5:D9:E5:61]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: F8:CF:C5:D9:E5:61, peer name: motorola-Nexus 6_PT149, peer ID: F8:CF:C5:D9:E5:61, Wi-Fi Direct device name: , Wi-Fi Direct address: fa:cf:c5:d9:e5:62
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:CF:C5:D9:E5:61 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:2A:F7:ED:96:BE), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:25:51.687Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:51.688Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:51.688Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:25:51.689Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 47
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x10  CID 0x44
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 48
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 342)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 49
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x10  CID 0x46
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 50
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 342)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 342)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/jxcore-log( 3031): 2015-12-09T23:26:23.764Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:23.765Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:23.765Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 342)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_2dc2 52:55:27:f0:ff:f0
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3031): 2015-12-09T23:26:28.765Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:28.766Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9777 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT9777, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:2A:F7:ED:96:BE), either no such connection or failed to close the connection
,I/jxcore-log( 3031): 2015-12-09T23:26:33.776Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:33.777Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:26:33.779Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:26:33.783Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 58:2A:F7:ED:96:BE
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 58:2A:F7:ED:96:BE
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 58:2A:F7:ED:96:BE)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 58:2A:F7:ED:96:BE (thread ID: 343)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9777 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT9777, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x10  CID 0x43
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:51, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 51
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x10  CID 0x4d
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:52, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 52
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 343)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
,I/jxcore-log( 3031): 2015-12-09T23:26:48.817Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:48.818Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:26:48.855Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 58:2A:F7:ED:96:BE
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 58:2A:F7:ED:96:BE
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 58:2A:F7:ED:96:BE), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:26:48.858Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 343)
,I/jxcore-log( 3031): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:48.878Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:48.878Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:26:48.879Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to peer with ID 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 344)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f4:f1:e1:5c:3b:e2]: 7, f, 230f
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 344)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 345)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 344)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 345)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 81 bytes successfully (thread ID: 345)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 345)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2],
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT1888, Bluetooth address: F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F4:F1:E1:5C:3B:E2 already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID F4:F1:E1:5C:3B:E2, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 346)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 60189
I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 60189 (peer ID: F4:F1:E1:5C:3B:E2)
I/jxcore-log( 3031): 2015-12-09T23:26:52.401Z SendDataConnector.js: CLIENT connected to 60189, error: null
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:26:52.402Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 60189
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 346)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 348, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 347, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:26:52.444Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10444,tx.queue.count:11,available:23716
,I/jxcore-log( 3031): 2015-12-09T23:26:54.001Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:26:54.217Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3031): 
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3031): 2015-12-09T23:26:54.519Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:26:54.901Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3031): 
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3916
,I/jxcore-log( 3031): 2015-12-09T23:26:55.253Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:26:55.558Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3031): 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5605","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5605 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT5605","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: E0:DB:10:14:E2:C0, peer name: samsung-SM-N910C_PT5605, peer ID: E0:DB:10:14:E2:C0, Wi-Fi Direct device name: Note4-1, Wi-Fi Direct address: 92:b6:86:43:73:1c
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:14:E2:C0
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9988, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): dm_pm_timer expires
W/bt-btif ( 3097): dm_pm_timer expires 0
W/bt-btif ( 3097): proc dm_pm_timer expires
,I/jxcore-log( 3031): 2015-12-09T23:27:02.835Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1110 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT1110, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: , Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 90:E7:C4:F6:69:77
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3549"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3549 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3549"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3549, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6685","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT6685 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6685","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT6685, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3097): invalid rfc slot id: 53
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 348, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 348
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 347
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 347, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID F4:F1:E1:5C:3B:E2 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 347, name: Sender)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 348, name: Receiver)
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/jxcore-log( 3031): 2015-12-09T23:27:12.836Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:12.837Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:27:12.843Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:12.844Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:12.845Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:27:17.846Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:17.846Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:17.847Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:9a:02:7b:60:ac p2p_dev_addr=02:9a:02:7b:60:ac pri_dev_type=10-0050F204-5 name='G3-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT9583","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT9583 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT9583","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT9583, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: G3-1, Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT936"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 8 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT936"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 80:01:84:8A:B3:68, peer name: HTC-HTC Desire 820_PT936, peer ID: 80:01:84:8A:B3:68, Wi-Fi Direct device name: Android_63cc, Wi-Fi Direct address: 82:01:84:6b:e8:5d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 8 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
,I/jxcore-log( 3031): 2015-12-09T23:27:22.863Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:22.865Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:22.865Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:22.866Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 349)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:9a:02:7b:60:ac
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,W/bt-l2cap( 3097): L2CAP - con rsp - bad ID. Exp: 5 Got: 4
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 349)
W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 349)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 3031): 2015-12-09T23:27:39.257Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:39.258Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:39.258Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:39.258Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"38:94:96:B5:06:DC","pi":"38:94:96:B5:06:DC","pn":"samsung-SM-G800H_PT3549"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [38:94:96:B5:06:DC samsung-SM-G800H_PT3549 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 38:94:96:B5:06:DC, peer name: samsung-SM-G800H_PT3549, peer ID: 38:94:96:B5:06:DC, Wi-Fi Direct device name: , Wi-Fi Direct address: 3a:94:96:b5:06:dd
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 38:94:96:B5:06:DC already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
,I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9988, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/jxcore-log( 3031): 2015-12-09T23:27:44.258Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:44.259Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:27:44.259Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:27:49.268Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:27:49.269Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:27:49.274Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:27:49.277Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 350)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 55
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT9583","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT9583 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT9583, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [08:ec:a9:50:75:41]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 08:EC:A9:50:75:41 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 08:EC:A9:50:75:41, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 351)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): info:x10
D/        ( 3097): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 352)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 352)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 77 bytes successfully (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 352)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 352
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 352)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 352)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): invalid rfc slot id: 57
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,W/bt-rfcomm( 3097): PORT_StartCnf failed result:13
,W/bt-btif ( 3097): invalid rfc slot id: 56
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 350)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT1024, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
I/jxcore-log( 3031): 2015-12-09T23:28:47.771Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:28:47.772Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:28:47.772Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:28:47.772Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 353)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 353)
,I/jxcore-log( 3031): 2015-12-09T23:28:47.794Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 355, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:28:47.796Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 354, name: Sender)
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 354, thread name: Sender): Broken pipe
E/io.jxcore.node.IncomingSocketThread( 3031): The sending thread failed with error: Either failed to read from the output stream or write to the input stream: Broken pipe
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Broken pipe
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 355, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/jxcore-log( 3031): 2015-12-09T23:28:47.804Z SendDataTCPServer.js: TCP/IP server has received 81920 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 353
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 355
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 354
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 354, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:28:47.807Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:47.808Z SendDataTCPServer.js: TCP/IP server got error : Error: write ECONNRESET
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 355, name: Receiver)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f8:95:c7:87:85:54]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,I/jxcore-log( 3031): 2015-12-09T23:28:52.772Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:28:52.773Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:28:52.773Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device F8:95:C7:87:85:54 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for F8:95:C7:87:85:54, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 356)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 356)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 77 bytes successfully (thread ID: 356)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 356)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 356
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 356)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 356)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT1024, Bluetooth address: F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID F8:95:C7:87:85:54, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 357)
,I/jxcore-log( 3031): 2015-12-09T23:28:54.599Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 357)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 359, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 358, name: Sender)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3031): 2015-12-09T23:28:55.559Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.570Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.577Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.586Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.620Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.623Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.628Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.660Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.663Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.700Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.811Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.854Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.859Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:55.947Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT6011"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 34:FC:EF:11:B1:66, peer name: LGE-Nexus 5_PT6011, peer ID: 34:FC:EF:11:B1:66, Wi-Fi Direct device name: , Wi-Fi Direct address: 52:55:27:f0:ff:f0
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3031): 2015-12-09T23:28:56.028Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT9583","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT9583 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 58:3F:54:73:64:C0, peer name: LGE-LG-D855_PT9583, peer ID: 58:3F:54:73:64:C0, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:9a:02:7b:60:ac
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 58:3F:54:73:64:C0 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,I/jxcore-log( 3031): 2015-12-09T23:28:56.065Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.090Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.098Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.130Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.133Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.195Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.230Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.232Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.235Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.239Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.271Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:56.281Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3097): invalid rfc slot id: 58
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 359, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 357
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 359
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 358
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 358, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID F8:95:C7:87:85:54 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 358, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 359, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:28:56.928Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051cfc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:28:57.779Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:28:57.779Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:28:57.787Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:28:57.788Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
,D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x48
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: G3s-1
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3097): invalid rfc slot id: 28
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Disconnected: bt socket closed, read return: -1
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 351
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake failed (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 351)
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 60
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4e
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 61
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 360)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 360)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 62
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,I/jxcore-log( 3031): 2015-12-09T23:29:36.212Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:29:36.212Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:29:36.213Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:29:36.213Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using system decided port, total number of attempts: 2 (thread ID: 360)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 360)
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/jxcore-log( 3031): 2015-12-09T23:29:41.213Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:29:41.214Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:29:41.215Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:29:46.219Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:29:46.219Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:29:46.226Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:29:46.229Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: F4:F1:E1:5C:3B:E2)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address F4:F1:E1:5C:3B:E2 (thread ID: 361)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_2dc2 52:55:27:f0:ff:f0
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/EventLogService( 1616): Aggregate from 1449702000137 (log), 1449702000137 (data)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3097): invalid rfc slot id: 64
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapService( 3097): onReceive
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 361)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 361)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT1888 F4:F1:E1:5C:3B:E2]
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 14 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Note4-1 92:b6:86:43:73:1c
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: Android_1950 b6:ce:f6:ad:a4:6b
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 6: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 7: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 8: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 9: XT1072_23d5 44:80:eb:7b:5a:07
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 11: A5-1 7e:f9:0e:37:96:ac
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 12: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 13: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 14: Android_50a5 fa:cf:c5:d9:e5:62
,I/jxcore-log( 3031): 2015-12-09T23:30:31.097Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:31.098Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:31.098Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:31.101Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:31.101Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:31.101Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID F4:F1:E1:5C:3B:E2
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F4:F1:E1:5C:3B:E2
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: F4:F1:E1:5C:3B:E2), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:30:31.102Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: 90:E7:C4:F6:69:77
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:31.102Z SendDataConnector.js: Start called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:31.102Z SendDataConnector.js: doConnect called with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:31.102Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address 90:E7:C4:F6:69:77
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null 90:E7:C4:F6:69:77
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 90:E7:C4:F6:69:77)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: Connection to peer with ID F4:F1:E1:5C:3B:E2 failed", source: file:///android_asset/www/js/thali_main.js (63)
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 90:E7:C4:F6:69:77 (thread ID: 362)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got a list of peers, but since we are currently discovering services (not peers), the new list is ignored
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Failed to start the service discovery, got error code: 3
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa40515dc rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1039
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:66, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 66
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 1
,E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 90:E7:C4:F6:69:77 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 90:E7:C4:F6:69:77
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:90:E7:C4:F6:69:77 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 90:E7:C4:F6:69:77 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 90:E7:C4:F6:69:77, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1110 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 362)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 363)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 362)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 363)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 81 bytes successfully (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1110 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1110 90:E7:C4:F6:69:77]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1110 90:E7:C4:F6:69:77]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: 90:E7:C4:F6:69:77, name: HTC-HTC One M8s_PT1110, Bluetooth address: 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID 90:E7:C4:F6:69:77, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 364)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 48705
I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 48705 (peer ID: 90:E7:C4:F6:69:77)
I/jxcore-log( 3031): 2015-12-09T23:30:38.878Z SendDataConnector.js: CLIENT connected to 48705, error: null
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:38.879Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 48705
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 364)
,I/jxcore-log( 3031): 2015-12-09T23:30:38.910Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 366, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 365, name: Sender)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,I/jxcore-log( 3031): 2015-12-09T23:30:39.699Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:30:39.797Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3031): 
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13816
,I/jxcore-log( 3031): 2015-12-09T23:30:39.854Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8866
,I/jxcore-log( 3031): 2015-12-09T23:30:39.939Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.072Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.161Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9988, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: S5mini-1, Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3031): 2015-12-09T23:30:40.435Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.684Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.916Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.959Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:40.959Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.961Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:40.961Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 90:E7:C4:F6:69:77
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 90:E7:C4:F6:69:77
I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 366
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 365
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 365, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 366, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 90:E7:C4:F6:69:77 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Successfully disconnected (peer ID: 90:E7:C4:F6:69:77
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 365, name: Sender)
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 90:E7:C4:F6:69:77
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 366, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:30:40.969Z SendDataConnector.js: Mobile.Disconnect() callback with peer 90:E7:C4:F6:69:77
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: E0:DB:10:14:E2:C0
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.969Z SendDataConnector.js: Start called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:40.970Z SendDataConnector.js: doConnect called with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:40.971Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: Note4-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to null in address E0:DB:10:14:E2:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: null E0:DB:10:14:E2:C0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to null in address E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: E0:DB:10:14:E2:C0)
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 90:E7:C4:F6:69:77 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address E0:DB:10:14:E2:C0 (thread ID: 367)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa405208c rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC One M8s
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: E0:DB:10:14:E2:C0 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: E0:DB:10:14:E2:C0
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device E0:DB:10:14:E2:C0 not found, calling readPairedDevices().
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:E0:DB:10:14:E2:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,E/BluetoothEventManager( 3115): Got bonding state changed for E0:DB:10:14:E2:C0, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5605 E0:DB:10:14:E2:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 367)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 367)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 368)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 82 bytes successfully (thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5605 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5605 E0:DB:10:14:E2:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 368)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT5605 E0:DB:10:14:E2:C0]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: E0:DB:10:14:E2:C0, name: samsung-SM-N910C_PT5605, Bluetooth address: E0:DB:10:14:E2:C0
,D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID E0:DB:10:14:E2:C0
,I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID E0:DB:10:14:E2:C0 already in the list
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID E0:DB:10:14:E2:C0, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 369)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 37037
I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa405208c rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 37037 (peer ID: E0:DB:10:14:E2:C0)
I/jxcore-log( 3031): 2015-12-09T23:30:47.462Z SendDataConnector.js: CLIENT connected to 37037, error: null
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:47.463Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 37037
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 369)
,I/jxcore-log( 3031): 2015-12-09T23:30:47.486Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 370, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 371, name: Receiver)
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1392
,I/jxcore-log( 3031): 2015-12-09T23:30:48.299Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:48.875Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:49.654Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3031): 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3031): 2015-12-09T23:30:51.042Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:51.967Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:52.380Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:52.464Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:52.565Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:53.338Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:53.833Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:53.833Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:30:53.849Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:53.850Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID E0:DB:10:14:E2:C0
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: E0:DB:10:14:E2:C0
I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 371
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 370
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 370, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 371, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID E0:DB:10:14:E2:C0 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Successfully disconnected (peer ID: E0:DB:10:14:E2:C0
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID E0:DB:10:14:E2:C0
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 371, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 370, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:30:53.900Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:14:E2:C0
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/jxcore-log( 3031): 2015-12-09T23:30:53.914Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:53.914Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:30:53.914Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3031): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:14:E2:C0 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 372)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa405208c rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa405208c rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Note4-1
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:69, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 69
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 08:EC:A9:50:75:41 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using system decided port, total number of attempts: 1 (thread ID: 372)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 373)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 373)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 373)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 373)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 373)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT1682, Bluetooth address: 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 374)
D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 43176
,I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 43176 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3031): 2015-12-09T23:31:05.648Z SendDataConnector.js: CLIENT connected to 43176, error: null
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:05.649Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 43176
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 374)
,I/jxcore-log( 3031): 2015-12-09T23:31:05.674Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 375, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 376, name: Receiver)
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:946
,W/bt-btif ( 3097): dm_pm_timer expires
W/bt-btif ( 3097): dm_pm_timer expires 0
W/bt-btif ( 3097): proc dm_pm_timer expires
,I/jxcore-log( 3031): 2015-12-09T23:31:16.146Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:16.147Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:16.157Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:16.158Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:16.159Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3031): 
,E/io.jxcore.node.StreamCopyingThread( 3031): Input stream got -1 on read (thread ID: 375, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3031): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 376
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 375
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 376, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 376, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 375, name: Sender)
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,I/jxcore-log( 3031): 2015-12-09T23:31:21.160Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:21.161Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:31:26.164Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:26.165Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:26.166Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:26.166Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 377)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 377)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 378)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 377)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 378)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 378)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT1682, Bluetooth address: 08:EC:A9:50:75:41
,D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 378)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 379)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 38639
,I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 38639 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3031): 2015-12-09T23:31:30.898Z SendDataConnector.js: CLIENT connected to 38639, error: null
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:30.899Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 38639
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 379)
,I/jxcore-log( 3031): 2015-12-09T23:31:30.923Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 381, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 380, name: Sender)
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10172,tx.queue.count:11,available:24706
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12826
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:946
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): dm_pm_timer expires
W/bt-btif ( 3097): dm_pm_timer expires 0
W/bt-btif ( 3097): proc dm_pm_timer expires
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3031): 2015-12-09T23:31:41.363Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:41.364Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:41.365Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:41.366Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:41.367Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3031): 
,E/io.jxcore.node.StreamCopyingThread( 3031): Input stream got -1 on read (thread ID: 380, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3031): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
,I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 381
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 380
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 381, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 381, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 380, name: Sender)
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4052254 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:B1:66 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 34:FC:EF:11:B1:66
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:34:FC:EF:11:B1:66 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 34:FC:EF:11:B1:66 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 34:FC:EF:11:B1:66, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 382)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 77 bytes successfully (thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 382)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 382
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 382)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 382)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 34:FC:EF:11:B1:66, name: LGE-Nexus 5_PT6011, Bluetooth address: 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 34:FC:EF:11:B1:66 already in the list
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 34:FC:EF:11:B1:66, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 383)
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3031): 2015-12-09T23:31:46.107Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 383)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 385, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 384, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:31:46.369Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:46.372Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9777 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT9777, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/jxcore-log( 3031): 2015-12-09T23:31:46.949Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:46.958Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:46.973Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.007Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.045Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.075Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.113Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.120Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.130Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.145Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.168Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.202Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.489Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.498Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.537Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.540Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.570Z SendDataTCPServer.js: TCP/IP server has received 34748 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.575Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.622Z SendDataTCPServer.js: TCP/IP server has received 38708 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.630Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.638Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.670Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.672Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.686Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.724Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.816Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.828Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.837Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.857Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.869Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:47.996Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.142Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.233Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.249Z SendDataTCPServer.js: TCP/IP server has received 74348 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.281Z SendDataTCPServer.js: TCP/IP server has received 76328 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.292Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.299Z SendDataTCPServer.js: TCP/IP server has received 80288 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.316Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.351Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.362Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.369Z SendDataTCPServer.js: TCP/IP server has received 88208 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.379Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.396Z SendDataTCPServer.js: TCP/IP server has received 94148 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:48.432Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,W/bt-btif ( 3097): invalid rfc slot id: 59
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 385, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 383
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 385
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 384
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 384, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 34:FC:EF:11:B1:66 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 384, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 385, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:31:48.518Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x4f
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:31:51.379Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:51.379Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:31:51.386Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:51.388Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 386)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5447","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT5447 7C:F9:0E:34:8A:A0]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5447","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 7C:F9:0E:34:8A:A0, peer name: samsung-SM-G900F_PT5447, peer ID: 7C:F9:0E:34:8A:A0, Wi-Fi Direct device name: S5-1, Wi-Fi Direct address: ee:1f:72:63:11:86
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:34:8A:A0
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4052254 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:B1:66, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 386)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 387)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 386)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 387)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 387)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT1682, Bluetooth address: 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 387)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 388)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 35675
I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT768","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT768 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 3 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 35675 (peer ID: 08:EC:A9:50:75:41)
I/jxcore-log( 3031): 2015-12-09T23:31:54.108Z SendDataConnector.js: CLIENT connected to 35675, error: null
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:31:54.108Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 35675
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 388)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT768","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 389, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:31:54.139Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 390, name: Receiver)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:76:27, peer name: samsung-SM-A300FU_PT768, peer ID: 08:EC:A9:50:76:27, Wi-Fi Direct device name: Thali Test (Galaxy A3), Wi-Fi Direct address: 0a:ec:a9:50:76:28
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29210
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 3 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17330
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5450
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6685","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT6685 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 4 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT6685","ra":"E0:DB:10:1F:C9:5E"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: E0:DB:10:1F:C9:5E, peer name: samsung-SM-N9005_PT6685, peer ID: E0:DB:10:1F:C9:5E, Wi-Fi Direct device name: Note3-1, Wi-Fi Direct address: ea:50:8b:de:28:a3
,I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID E0:DB:10:1F:C9:5E already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 4 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT9988 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 5 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT9988"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 00:F4:6F:30:E0:6C, peer name: samsung-SM-G800F_PT9988, peer ID: 00:F4:6F:30:E0:6C, Wi-Fi Direct device name: , Wi-Fi Direct address: 02:f4:6f:30:e0:6d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 00:F4:6F:30:E0:6C already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 5 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,W/bt-btif ( 3097): dm_pm_timer expires
W/bt-btif ( 3097): dm_pm_timer expires 0
,W/bt-btif ( 3097): proc dm_pm_timer expires
,I/jxcore-log( 3031): 2015-12-09T23:32:04.589Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:04.590Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:04.591Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:04.592Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:04.593Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3031): 
,E/io.jxcore.node.StreamCopyingThread( 3031): Input stream got -1 on read (thread ID: 389, thread name: Sender)
E/io.jxcore.node.OutgoingSocketThread( 3031): The sending thread failed with error: Input stream got -1 on read
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Input stream got -1 on read
,I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3031): close
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 390
I/io.jxcore.node.OutgoingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 389
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 3031): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 390, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.OutgoingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 390, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 389, name: Sender)
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:09.593Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:09.594Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7365","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT7365 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 6 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT7365","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 7C:F9:0E:51:18:22, peer name: samsung-SM-A500FU_PT7365, peer ID: 7C:F9:0E:51:18:22, Wi-Fi Direct device name: , Wi-Fi Direct address: 7e:f9:0e:51:18:23
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:51:18:22 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 6 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:32:14.597Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:14.598Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:14.599Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:14.599Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 391)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,W/bt-sdp  ( 3097): process_service_search_attr_rsp
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onSocketConnected: Authenticating next: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Socket connection succeeded using port (1), total number of attempts: 1 (thread ID: 391)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 392)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Outgoing connection initialized (*handshake* thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 391)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 392)
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 392)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onAuthenticated: Fully connected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 392)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT1682, Bluetooth address: 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Outgoing socket thread, for peer with ID 08:EC:A9:50:75:41, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 3031): Entering thread (ID: 393)
,D/io.jxcore.node.OutgoingSocketThread( 3031): Server socket local port: 59408
I/io.jxcore.node.OutgoingSocketThread( 3031): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 3031): onListeningForIncomingConnections: Outgoing connection is using port 59408 (peer ID: 08:EC:A9:50:75:41)
,I/jxcore-log( 3031): 2015-12-09T23:32:18.643Z SendDataConnector.js: CLIENT connected to 59408, error: null
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:18.644Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3031): 
,I/io.jxcore.node.OutgoingSocketThread( 3031): Incoming data from address: /127.0.0.1, port: 59408
D/io.jxcore.node.OutgoingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 3031): startStreamCopyingThreads: OK
,D/io.jxcore.node.OutgoingSocketThread( 3031): Exiting thread (ID: 393)
,I/jxcore-log( 3031): 2015-12-09T23:32:18.676Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 395, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 394, name: Sender)
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:29210
,I/jxcore-log( 3031): 2015-12-09T23:32:19.692Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3031): 
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3097): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18320
,I/jxcore-log( 3031): 2015-12-09T23:32:20.241Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3031): 
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3097): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3097): Entering PendingCommandState State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,I/BluetoothBondStateMachine( 3097): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3097): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3097): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3097): StableState(): Entering Off State
,W/BluetoothEventManager( 3115): CachedBluetoothDevice for device 44:80:EB:7B:5A:05 not found, calling readPairedDevices().
,E/BluetoothEventManager( 3115): Got bonding state changed for 44:80:EB:7B:5A:05, but we have no record of that device.
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 396)
,I/jxcore-log( 3031): 2015-12-09T23:32:21.542Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3031): 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa405241c rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 81 bytes successfully (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT2151 44:80:EB:7B:5A:05]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 396)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 396
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 396)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT2151 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 396)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT2151 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT2151, Bluetooth address: 44:80:EB:7B:5A:05
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05
,I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 44:80:EB:7B:5A:05, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 2
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 397)
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
,I/jxcore-log( 3031): 2015-12-09T23:32:21.812Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 397)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 399, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 398, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:32:22.711Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.747Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.752Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.822Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.831Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.860Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.871Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.904Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:22.906Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:22.949Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.024Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.034Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.126Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.133Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.167Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.176Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.214Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.301Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.319Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.345Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.348Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.407Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.440Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.448Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.485Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.499Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.549Z SendDataTCPServer.js: TCP/IP server has received 52024 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.581Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.652Z SendDataTCPServer.js: TCP/IP server has received 55984 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.662Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.750Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.757Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.796Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:23.831Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.126Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.211Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.252Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.470Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.541Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.768Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.775Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.784Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:24.867Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.173Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.219Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.229Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.331Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.366Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.622Z SendDataTCPServer.js: TCP/IP server has received 95584 bytes of data
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.673Z SendDataTCPServer.js: TCP/IP server has received 97564 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:25.681Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3097): invalid rfc slot id: 72
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 399, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 397
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 399
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 398
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 398, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 44:80:EB:7B:5A:05 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 399, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 398, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:32:25.957Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-btif ( 3097): dm_pm_timer expires
W/bt-btif ( 3097): dm_pm_timer expires 0
W/bt-btif ( 3097): proc dm_pm_timer expires
,D/        ( 3097): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8420
,I/jxcore-log( 3031): 2015-12-09T23:32:26.583Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa405241c rs_disc_pending=1
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: XT1072
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:32.924Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3031): 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:34.354Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3031): 
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1003","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1003 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 7 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT1003","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 7C:F9:0E:37:96:AB, peer name: samsung-SM-A500FU_PT1003, peer ID: 7C:F9:0E:37:96:AB, Wi-Fi Direct device name: A5-1, Wi-Fi Direct address: 7e:f9:0e:37:96:ac
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 7C:F9:0E:37:96:AB already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 7 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/jxcore-log( 3031): 2015-12-09T23:32:44.355Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:44.356Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:44.357Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:44.358Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:44.359Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3031): 
,E/io.jxcore.node.StreamCopyingThread( 3031): Input stream got -1 on read (thread ID: 394, thread name: Sender)
E/io.jxcore.node.IncomingSocketThread( 3031): The sending thread failed with error: Input stream got -1 on read
,W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Input stream got -1 on read
I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.IncomingSocketThread( 3031): close
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 395
,I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 394
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 395, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Outgoing connection, peer with ID 08:EC:A9:50:75:41 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 395, name: Receiver)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 394, name: Sender)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,E/bt-btm  ( 3097): tBTM_SEC_DEV:0xa4051b34 rs_disc_pending=0
W/bt-btif ( 3097): bta_dm_check_av:0
,W/bt-btif ( 3097): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:b6:86:43:73:1c
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,W/bt-btif ( 3097): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,I/jxcore-log( 3031): 2015-12-09T23:32:49.359Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:49.363Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-9ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 7e:f9:0e:51:18:23 p2p_dev_addr=7e:f9:0e:51:18:23 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-10ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,D/WifiP2pManager( 3031): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:32:54.368Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:54.369Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:32:54.369Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:32:54.374Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: A3-1 08:EC:A9:50:75:41
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 08:EC:A9:50:75:41)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 08:EC:A9:50:75:41 (thread ID: 400)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:76, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3097): invalid rfc slot id: 76
,D/BluetoothMapService( 3097): onReceive
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: A3-1
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:77, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 77
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 400)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 400)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:78, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 78
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:79, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3097): invalid rfc slot id: 79
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 400)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
,I/jxcore-log( 3031): 2015-12-09T23:33:10.336Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:33:10.336Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:33:10.356Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:33:10.357Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:75:41
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:75:41
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 08:EC:A9:50:75:41), either no such connection or failed to close the connection
,I/jxcore-log( 3031): 2015-12-09T23:33:10.365Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): ---- round done--------
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): do fake peer & start
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:33:10.373Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:33:10.373Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:33:10.374Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to peer with ID 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 401)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:51:18:23
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x22  CID 0x4e
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:80, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 80
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): No ag scb for peer addr
,E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:81, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 81
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 401)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 401)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/jxcore-log( 3031): 2015-12-09T23:34:41.531Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:34:41.531Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:34:41.531Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 401)
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 1 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3031): 2015-12-09T23:34:46.531Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:34:46.532Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5-1 ee:1f:72:63:11:86
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1024","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT1024 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT1024","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: F8:95:C7:87:85:54, peer name: LGE-LG-D722_PT1024, peer ID: F8:95:C7:87:85:54, Wi-Fi Direct device name: G3s-1, Wi-Fi Direct address: a2:39:f7:70:12:80
,I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:85:54 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:34:51.535Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:34:51.536Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:34:51.536Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:34:51.537Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 402)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x4c
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:82, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 82
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x41
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:83, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 83
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 402)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 402)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x40
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:84, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 84
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x4f
,E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:85, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 85
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 402)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 402)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x45
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:86, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 86
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x44
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:87, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 87
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 402)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 402)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x42
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:88, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 88
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x43
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:89, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 89
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 402)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 402)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x47
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:90, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 90
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x46
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:91, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 91
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 402)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Maximum number of retries (5) reached, giving up... (thread ID: 402)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
I/jxcore-log( 3031): 2015-12-09T23:35:09.646Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:35:09.647Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:35:09.647Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 402)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Failed to connect (tried 5 time(s)): read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
,I/jxcore-log( 3031): 2015-12-09T23:35:14.648Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:35:14.649Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:35:19.658Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:35:19.659Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:35:19.659Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:35:19.666Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 403)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x4d
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:92, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 92
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x48
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:93, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 93
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 403)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 403)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x4b
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:94, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 94
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-btif ( 3097): info:x10
,D/        ( 3097): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC Desire 820
,W/bt-btif ( 3097): new conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3097): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Incoming connection initialized (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Entering thread (ID: 404)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesRead: Read 83 bytes successfully (thread ID: 404)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Got valid identity from [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): onBytesWritten: 77 bytes successfully written (thread ID: 404)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): removeThreadFromList: Removing thread with ID 404
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Handshake thread disposed (thread ID: 404)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3031): Exiting thread (ID: 404)
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x22  CID 0x4a
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:95, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 95
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 403)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 403)
,I/jxcore-log( 3031): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): The Coordinator has disconnected!
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnected: [80:01:84:8A:B3:68 HTC-HTC Desire 820_PT936 80:01:84:8A:B3:68]
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming connection, peer ID: 80:01:84:8A:B3:68, name: HTC-HTC Desire 820_PT936, Bluetooth address: 80:01:84:8A:B3:68
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 80:01:84:8A:B3:68 already in the list
I/io.jxcore.node.ConnectionHelper( 3031): onConnected: Incoming socket thread, for peer with ID 80:01:84:8A:B3:68, created successfully
D/io.jxcore.node.ConnectionHelper( 3031): onConnected: The total number of connections is now 1
I/jxcore-log( 3031): 2015-12-09T23:35:54.115Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:35:54.115Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:35:54.115Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,D/io.jxcore.node.IncomingSocketThread( 3031): Entering thread (ID: 405)
,I/io.jxcore.node.IncomingSocketThread( 3031): Local host address: localhost/127.0.0.1, port: 37057
D/io.jxcore.node.IncomingSocketThread( 3031): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
,I/jxcore-log( 3031): 2015-12-09T23:35:54.123Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 3031): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 3031): Exiting thread (ID: 405)
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 407, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:35:54.126Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:35:54.128Z SendDataTCPServer.js: TCP/IP server has received 81920 bytes of data
I/jxcore-log( 3031): 
,I/io.jxcore.node.StreamCopyingThread( 3031): Entering thread (ID: 406, name: Sender)
,I/jxcore-log( 3031): 2015-12-09T23:35:54.131Z SendDataTCPServer.js: TCP/IP server has received 97020 bytes of data
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:35:54.171Z SendDataTCPServer.js: TCP/IP server has received 99000 bytes of data
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 403)
,I/jxcore-log( 3031): 2015-12-09T23:35:54.348Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3031): 
,W/bt-btif ( 3097): invalid rfc slot id: 75
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 407, thread name: Receiver): bt socket closed, read return: -1
,E/io.jxcore.node.IncomingSocketThread( 3031): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 405
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 407
I/io.jxcore.node.IncomingSocketThread( 3031): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 3031): doStop: Thread ID: 406
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local input stream...
,W/io.jxcore.node.StreamCopyingThread( 3031): Either failed to read from the output stream or write to the input stream (thread ID: 406, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 3031): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 3031): onDisconnected: Incoming connection, peer with ID 80:01:84:8A:B3:68 disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
,I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the local output stream...
I/io.jxcore.node.IncomingSocketThread( 3031): closeLocalSocketAndStreams: Closing the localhost socket...
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.IncomingSocketThread( 3031): closeBluetoothSocketAndStreams
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 406, name: Sender)
,I/io.jxcore.node.StreamCopyingThread( 3031): Exiting thread (ID: 407, name: Receiver)
,I/jxcore-log( 3031): 2015-12-09T23:35:54.908Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Coordinator is now connected to the server!
I/jxcore-log( 3031): 
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-rfcomm( 3097): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
W/bt-rfcomm( 3097): RFCOMM_DisconnectInd LCID:0x49
,E/bt-btm  ( 3097): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3097): onReceive
,I/BTConnectionReceiver( 1360): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1360): Bluetooth Device Name: HTC Desire 820
,I/jxcore-log( 3031): 2015-12-09T23:35:59.116Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:35:59.116Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 3a:94:96:b5:06:dd p2p_dev_addr=3a:94:96:b5:06:dd pri_dev_type=10-0050F204-5 name='Galaxy S5-2' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 6 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Galaxy S5-2 3a:94:96:b5:06:dd
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Note3-1 ea:50:8b:de:28:a3
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 6: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
,I/jxcore-log( 3031): 2015-12-09T23:36:04.124Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:04.125Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:04.125Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:04.126Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 408)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x4c
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:97, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 97
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:98, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 98
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 408)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 408)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3031): timeout now
I/jxcore-log( 3031): 
I/jxcore-log( 3031): dun
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): weAreDoneNow , resultArray.length: 4
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): done, now sending data to server
I/jxcore-log( 3031): 
I/jxcore-log( 3031): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): -- RESULT DATA {"name:":"LGE-Nexus 5_PT4768","time":1000080,"result":"TIMEOUT","sendList":[{"name":"00:F4:6F:30:E0:6C","time":14635,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"80:01:84:8A:B3:68","time":5808,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":9857,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":12864,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:1F:C9:5E","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0
,I/jxcore-log( 3031): sendList : 100% : 14635 ms, 99% : 14635 ms, 95 : 14635 ms, 90% : 14635 ms.
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Result count 4, range 5808 ms to  14635 ms.
I/jxcore-log( 3031): 
I/jxcore-log( 3031): sendList failed peers count : 5 [55.55555555555556 %]
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 7C:F9:0E:51:18:22, Tried : 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3031): 
I/jxcore-log( 3031): sendList never tried peers count : 13 [59.09090909090909 %]
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : E0:DB:10:1F:C9:5E
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : B0:C5:59:3F:75:69
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 7C:F9:0E:37:96:AB
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : F8:95:C7:87:3C:51
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): - Peer ID : 58:3F:54:73:64:C0
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 08:EC:A9:50:76:27
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : 38:94:96:B5:06:DC
I/jxcore-log( 3031): 
I/jxcore-log( 3031): - Peer ID : F8:CF:C5:D9:E5:61
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:16.243Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:36:16.243Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,W/bt-smp  ( 3097): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 3097): Plain text(LSB ~ MSB) = 53 38 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 3097): Encrypted text(LSB ~ MSB) = 15 74 2e bc ce 28 27 e1 d1 b2 5a d8 35 74 b5 a0 
W/bt-btm  ( 3097): Stopping oneshot timer
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x22  CID 0x40
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:99, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 99
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x4f
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:100, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 100
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 408)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Got discovery timeout, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=3a:94:96:b5:06:dd
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/jxcore-log( 3031): 2015-12-09T23:36:47.469Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:47.471Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:47.471Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3031): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/jxcore-log( 3031): 2015-12-09T23:36:52.471Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:52.472Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND fa:cf:c5:d9:e5:62 p2p_dev_addr=fa:cf:c5:d9:e5:62 pri_dev_type=10-0050F204-5 name='Android_50a5' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 2 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_50a5 fa:cf:c5:d9:e5:62
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 LGE-LG-H815_PT9777 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT9777","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: F8:95:C7:87:3C:51, peer name: LGE-LG-H815_PT9777, peer ID: F8:95:C7:87:3C:51, Wi-Fi Direct device name: G4-1, Wi-Fi Direct address: a2:39:f7:6f:c9:5d
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID F8:95:C7:87:3C:51 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:36:57.477Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:57.478Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:57.478Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:36:57.479Z SendDataConnector.js: do connect now
I/jxcore-log( 3031): 
,I/io.jxcore.node.ConnectionHelper( 3031): connect: Trying to connect to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnecting: Nexus 5 34:FC:EF:11:B1:66
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:B1:66
I/io.jxcore.node.ConnectionHelper( 3031): connect: Connection process successfully started (peer ID: 34:FC:EF:11:B1:66)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect to peer with address 34:FC:EF:11:B1:66 (thread ID: 409)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x45
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:101, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 101
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x44
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:102, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 102
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 1 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 409)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 409)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x42
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:103, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 103
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x43
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:104, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 104
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 2 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 409)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1682","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT1682 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 2 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1682","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT1682","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT1682, peer ID: 08:EC:A9:50:75:41, Wi-Fi Direct device name: A3-1, Wi-Fi Direct address: 0a:ec:a9:50:75:42
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 08:EC:A9:50:75:41 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 2 peer(s), but doing nothing with that list
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x47
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:105, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 105
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x9  CID 0x46
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:106, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 106
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 3 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 409)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 409)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils( 3031): createBluetoothSocketToServiceRecord: Socket created with channel/port 1
W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3097): No ag scb for peer addr
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Connection timeout
,E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:107, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 107
,W/BluetoothAdapter( 3031): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3097): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=fa:cf:c5:d9:e5:62
,W/bt-sdp  ( 3097): SDP - Rcvd conn cnf with error: 0x22  CID 0x48
E/bt-btif ( 3097): DISCOVERY_COMP_EVT slot id:108, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3097): invalid rfc slot id: 108
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): cancel: Connection timeout
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onConnectionFailed: Cancelled: Connection timeout
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Failed to connect (tried 4 time(s)): read failed, socket might closed or timeout, read ret: -1 (thread ID: 409)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Trying to connect again in 300 ms... (thread ID: 409)
,I/jxcore-log( 3031): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): The Coordinator has disconnected!
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Cancelled: Connection timeout [34:FC:EF:11:B1:66 LGE-Nexus 5_PT6011 34:FC:EF:11:B1:66]
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/jxcore-log( 3031): 2015-12-09T23:38:35.898Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:38:35.898Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3031): 
I/jxcore-log( 3031): 2015-12-09T23:38:35.899Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3031): 
,D/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:B1:66
E/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:B1:66
D/io.jxcore.node.ConnectionHelper( 3031): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.ConnectionHelper( 3031): disconnectOutgoingConnection: Failed to disconnect (peer ID: 34:FC:EF:11:B1:66), either no such connection or failed to close the connection
I/jxcore-log( 3031): 2015-12-09T23:38:35.900Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3031): 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3031): Exiting thread (thread ID: 409)
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 3 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/jxcore-log( 3031): DBG, CoordinatorConnector connect called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Coordinator is now connected to the server!
I/jxcore-log( 3031): 
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
,D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 8 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 7: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3031): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 9 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_2dc2 52:55:27:f0:ff:f0
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: Android_63cc 82:01:84:6b:e8:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 6: G4-1 a2:39:f7:6f:c9:5d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 8: S5mini-1 02:f4:6f:30:e0:6d
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3031): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT1110 90:E7:C4:F6:69:77]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT1110","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: 90:E7:C4:F6:69:77, peer name: HTC-HTC One M8s_PT1110, peer ID: 90:E7:C4:F6:69:77, Wi-Fi Direct device name: Android_608e, Wi-Fi Direct address: 92:e7:c4:e6:4c:f8
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID 90:E7:C4:F6:69:77 already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:18:8b:78
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): start: {"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): start: Identity string: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4768","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp"
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): initialize: Success
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: true
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local service added successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Got empty list
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list of peers, which is null
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): restart: Restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 92:e7:c4:e6:4c:f8 p2p_dev_addr=92:e7:c4:e6:4c:f8 pri_dev_type=10-0050F204-5 name='Android_608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 4 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: G4-1 a2:39:f7:6f:c9:5d
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): startServiceDiscovery: Invalid state, try calling restart()
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Start timer timeout, starting now...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): start: Starting peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery started successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P discovery started
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: 5 P2P devices discovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 1: Android_608e 92:e7:c4:e6:4c:f8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 2: XT1039_8c05 f4:f1:e1:5c:43:c8
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 3: G3s-1 a2:39:f7:70:12:80
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 4: A3-1 0a:ec:a9:50:75:42
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onP2pDeviceListChanged: Peer 5: G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3031): Ignored { when=-11ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
D/WifiP2pManager( 3031): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service request added successfully
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/wpa_supplicant( 3112): p2p0: P2P: Reject scan trigger since one is already pending
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3112): P2P-DEVICE-FOUND b6:ce:f6:ad:a4:6b p2p_dev_addr=b6:ce:f6:ad:a4:6b pri_dev_type=10-0050F204-5 name='Android_1950' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service discovery started successfully
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: Got empty list
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-SCAN-STARTED 
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8773"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Resolved peer properties: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT8773 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceDiscovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerDiscovered
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): onServiceListChanged: 1 services discovered
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onPeerListChanged
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Identity: "{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT8773"}", service type: "Cordovap2p._tcp.local."
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): onDnsSdServiceAvailable: Peer already exists in the list of peers
I/io.jxcore.node.ConnectionHelper( 3031): onPeerDiscovered: Bluetooth address: B4:CE:F6:AB:A4:6A, peer name: HTC-HTC Desire 820_PT8773, peer ID: B4:CE:F6:AB:A4:6A, Wi-Fi Direct device name: Android_1950, Wi-Fi Direct address: b6:ce:f6:ad:a4:6b
I/io.jxcore.node.ConnectionHelper( 3031): addNewPeerToListAndNotify: Peer with ID B4:CE:F6:AB:A4:6A already in the list
W/io.jxcore.node.ConnectionHelper( 3031): onPeerListChanged: Got a list containing 1 peer(s), but doing nothing with that list
,I/wpa_supplicant( 3112): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3031): DBG, CoordinatorConnector command called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]}
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): stop tests now !
I/jxcore-log( 3031): 
I/jxcore-log( 3031): stop current!
I/jxcore-log( 3031): 
I/jxcore-log( 3031): testSendData stopped
I/jxcore-log( 3031): 
I/io.jxcore.node.ConnectionHelper( 3031): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): Shutting down...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:89)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onIncomingConnectionFailed: Socket is null
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3031): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3031): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 3031): stop: Stopping services
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): stopServiceDiscovery
,I/wpa_supplicant( 3112): P2P-FIND-STOPPED 
,I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=b6:ce:f6:ad:a4:6b
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=f4:f1:e1:5c:43:c8
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=92:e7:c4:e6:4c:f8
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:75:42
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
I/wpa_supplicant( 3112): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onIsDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): setState: NOT_INITIALIZED
,I/jxcore-log( 3031): StopBroadcasting went ok
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): 2015-12-09T23:40:36.439Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 3031): 
I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3031): onConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 3031): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 3031): Peer discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 3031): onConnectionManagerStateChanged: INITIALIZED
I/io.jxcore.node.ConnectionHelper( 3031): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3031): DBG, CoordinatorConnector command called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[{\"name\":\"80:01:84:8A:B3:68\",\"time\":5808,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"90:E7:C4:F6:69:77\",\"time\":9857,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"E0:DB:10:14:E2:C0\",\"time\":12864,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000},{\"name\":\"00:F4:6F:30:E0:6C\",\"time\":14635,\"result\":\"OK\",\"connections\":1,\"tryCount\":1,\"doneRounds\":1,\"dataAmount\":100000,\"dataReceived\":100000}],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:51:18:22\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\"Fail\"},{\"
I/jxcore-log( 3031): ****TEST TOOK:  ms ****
I/jxcore-log( 3031): 
I/jxcore-log( 3031): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3031): 
I/jxcore-log( 3031): stop tests now !
I/jxcore-log( 3031): 
I/jxcore-log( 3031): end, event received
I/jxcore-log( 3031): 
I/jxcore-log( 3031): CoordinatorConnector close called
I/jxcore-log( 3031): 
,I/jxcore-log( 3031): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3031): 
I/jxcore-log( 3031): The Coordinator has disconnected!
I/jxcore-log( 3031): 
I/jxcore-log( 3031): The Coordinator has closed!
I/jxcore-log( 3031): 
I/jxcore-log( 3031): stop tests now !
I/jxcore-log( 3031): 
I/jxcore-log( 3031): turning Radios off
I/jxcore-log( 3031): 
I/jxcore-log( 3031): Toggling radios to false
I/jxcore-log( 3031): 
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@388953b4 mBinding = false
,D/BluetoothManagerService(  759): Message: 2
D/BluetoothManagerService(  759): Sending off request.
,D/BluetoothAdapterState( 3097): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3097): Setting state to 13
I/BluetoothAdapterState( 3097): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 3097): onBluetoothDisable()
I/BluetoothAdapterState( 3097): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 3097): Scan Mode:20
,D/BluetoothAdapterState( 3097): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/btif_config_util( 3097): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/BluetoothMapMasInstance( 3097): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3097): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3097): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3097): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3097): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3097): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3097): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3097): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3097): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,W/bt-btif ( 3097): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,W/bt-l2cap( 3097): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3097): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 12 -> 13
,D/WifiService(  759): setWifiEnabled: false pid=3031, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,D/BluetoothMapService( 3097): onReceive
D/BluetoothMapService( 3097): STATE_TURNING_OFF
V/BluetoothMapService( 3097): Handler(): got msg=4
D/BluetoothMapService( 3097): MAP Service closeService in
D/BluetoothMapMasInstance( 3097): MAP Service shutdown
V/BluetoothMapService( 3097): MAP Service closeService out
,E/WifiStateMachine(  759): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/native  (  759): do suspend true
,I/BtOppRfcommListener( 3097): stopping Accept Thread
,I/BtOppRfcommListener( 3097): BluetoothSocket listen thread finished
,I/jxcore-log( 3031): Radios toggled
I/jxcore-log( 3031): 
,I/chromium( 3031): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,W/ContextImpl( 3115): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,D/DockEventReceiver( 3115): finishStartingService: stopping service
,D/AuthorizationBluetoothService( 1305): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 3115): Proxy object disconnected
D/PbapServerProfile( 3115): Bluetooth service disconnected
,W/bt-btif ( 3097): ag scb idx 1 not allocated
E/bt-btif ( 3097): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3097): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3097): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3097): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3097): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3097): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3097): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 3097): RX termination
W/bt_userial( 3097): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3097): Leaving userial_read_thread()
,D/bt_userial( 3097): userial_close_reader Joined userial reader thread: 0
,D/bt_hwcfg( 3097): hw_epilog_process
,I/bt_userial_vendor( 3097): device fd = 53 close
,I/GKI_LINUX( 3097): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 3097): GKI_exit_task 0 done
I/GKI_LINUX( 3097): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 3097): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 3097): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,D/HeadsetStateMachine( 3097): Exit Disconnected: -1
,D/BluetoothAdapterState( 3097): Stopping profile services that were post enabled
,D/BluetoothHeadset( 1147): Proxy object disconnected
D/BluetoothHeadset( 1147): Proxy object disconnected
,D/BluetoothHeadset( 1176): Proxy object disconnected
,V/NativeCrypto( 1305): Read error: ssl=0x9e178200: I/O error during system call, Connection timed out
,D/BluetoothHeadset(  759): Proxy object disconnected
,D/A2dpService( 3097): Received stop request...Stopping profile...
,E/WifiConfigStore(  759): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,V/NativeCrypto( 1305): SSL shutdown failed: ssl=0x9e178200: I/O error during system call, Broken pipe
,D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/A2dpStateMachine( 3097): Exit Disconnected: -1
D/ConnectivityService(  759): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/ConnectivityService(  759): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Checking http://clients3.google.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  759): scanCount==0 - aborting
,D/BluetoothA2dp(  759): Proxy object disconnected
,D/HidService( 3097): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,D/HealthService( 3097): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,D/PanService( 3097): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,D/BtGatt.DebugUtils( 3097): handleDebugAction() action=null
,D/BtGatt.GattService( 3097): Received stop request...Stopping profile...
D/BtGatt.GattService( 3097): stop()
D/BtGatt.AdvertiseManager( 3097): advertise clients cleared
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,D/BluetoothMapService( 3097): Received stop request...Stopping profile...
D/BluetoothMapService( 3097): stop()
,D/BluetoothMapEmailAppObserver( 3097): deinitObservers()
D/BluetoothMapEmailAppObserver( 3097): removeReceiver()
,D/BluetoothAdapterService( 3097): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13cec0f5
,D/HeadsetStateMachine( 3097): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3097): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3097): Cleaning up Bluetooth Handsfree callback object
I/GKI_LINUX( 3097): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 3097): GKI_exit_task 2 done
I/GKI_LINUX( 3097): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3097): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3097): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3097): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3097): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3097): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 3097): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3097): Cleaning up Bluetooth PAN callback object
,D/WifiScanningService(  759): SCAN_AVAILABLE : 1
,D/RttService(  759): SCAN_AVAILABLE : 1
D/WifiScanningService(  759): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  759): DefaultState
,D/WifiNetworkAgent(  759): NetworkAgent: NetworkAgent channel lost
,D/RttService(  759): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/native  (  759): do suspend true
,V/BluetoothMapService( 3097): Handler(): got msg=4
D/BluetoothMapService( 3097): MAP Service closeService in
V/BluetoothMapService( 3097): MAP Service closeService out
,D/BluetoothAdapterState( 3097): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,D/BluetoothMapService( 3097): cleanup()
D/BluetoothMapService( 3097): MAP Service closeService in
,D/BluetoothAdapterProperties( 3097): Setting state to 10
V/BluetoothMapService( 3097): MAP Service closeService out
I/BluetoothAdapterState( 3097): Bluetooth adapter state changed: 13-> 10
,I/BluetoothAdapterState( 3097): Entering OffState
D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(false) to 11 receivers.
,D/BluetoothHeadset( 1147): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1147): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  759): onBluetoothStateChange: up=false
,D/BluetoothMap( 3115): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3115): Proxy object disconnected
D/HeadsetProfile( 3115): Bluetooth service disconnected
,D/BluetoothPbap( 3115): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3115): Proxy object disconnected
,D/BluetoothInputDevice( 3115): onBluetoothStateChange: up=false
,D/A2dpProfile( 3115): Bluetooth service disconnected
D/BluetoothA2dp( 3115): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 3115): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  759): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1176): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  759): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothManagerService(  759): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@388953b4 mBinding = false
,D/BluetoothManagerService(  759): Sending unbind request.
,D/AndroidRuntime( 3936): 
D/AndroidRuntime( 3936): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/BluetoothManagerService(  759): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapter(  896): 285412046: getState() :  mService = null. Returning STATE_OFF
D/ConnectivityService(  759): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/AndroidRuntime( 3936): CheckJNI is OFF
D/ConnectivityManager.CallbackHandler(  896): CM callback handler got msg 524292
D/Nat464Xlat(  759): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/BluetoothAdapter(  896): 285412046: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  896): 285412046: getState() :  mService = null. Returning STATE_OFF
D/CSLegacyTypeTracker(  759): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1616): CM callback handler got msg 524292
D/CommandListener(  178): Clearing all IP addresses on wlan0
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
D/ConnectivityService(  759): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  759): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  759): Disconnected - quitting
D/TelephonyNetworkFactory( 1176): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/BluetoothAdapter( 1305): 802625475: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1305): 802625475: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1305): 802625475: getState() :  mService = null. Returning STATE_OFF
E/BluetoothDevice( 1305): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1305): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1305): BT not enabled. Cannot get Remote Device Alias
E/BluetoothDevice( 1305): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1305): BT not enabled. Cannot get Bluetooth Class
E/BluetoothDevice( 1305): BT not enabled. Cannot get Remote Device name
E/BluetoothDevice( 1305): BT not enabled. Cannot get Remote Device Alias
I/GKI_LINUX( 3097): gki_task task_id=1 [BTIF] terminating
W/ContextImpl( 3115): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
I/GKI_LINUX( 3097): GKI_exit_task 1 done
I/GKI_LINUX( 3097): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3097): cleanupNative: return from cleanup
,I/art     ( 3097): System.exit called, status: 0
I/AndroidRuntime( 3097): VM exiting with result code 0, cleanup skipped.
D/DockEventReceiver( 3115): finishStartingService: stopping service
,D/AndroidRuntime( 3936): Calling main entry com.android.commands.pm.Pm
,I/art     (  759): Explicit concurrent mark sweep GC freed 108625(5MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 28MB/43MB, paused 1.026ms total 74.925ms
,I/ActivityManager(  759): Process com.android.bluetooth (pid 3097) has died
,I/wpa_supplicant( 3112): p2p0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3112): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  759): Skipping PackageSetting{20056e00 com.example.hello/10277} due to missing metadata
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=-1: uninstall pkg
I/ActivityManager(  759): Killing 3031:com.test.thalitest/u0a270 (adj 0): stop com.test.thalitest
,I/WindowState(  759): WIN DEATH: Window{323e74df u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/WifiService(  759): Client connection lost with reason: 4
,D/Tethering(  759): InitialState.processMessage what=4
I/wpa_supplicant( 3112): wlan0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{1a477f15 u0 com.test.thalitest/.MainActivity t214}
,I/ActivityManager(  759): Force stopping com.test.thalitest appid=10270 user=0: pkg removed
,I/ActivityManager(  759):   Force finishing activity ActivityRecord{1a477f15 u0 com.test.thalitest/.MainActivity t214 f}
W/ActivityManager(  759): Duplicate finish request for ActivityRecord{1a477f15 u0 com.test.thalitest/.MainActivity t214 f}
,W/ActivityManager(  759): Spurious death for ProcessRecord{35d3b29e 3031:com.test.thalitest/u0a270}, curProc for 3031: null
D/Tethering(  759): sendTetherStateChangedBroadcast 0, 0, 0
W/GeofencerStateMachine( 1305): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1067): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1067): run()
I/Decoder ( 1067): createOrResetDecoder
I/InputReader(  759): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1360): Explicit concurrent mark sweep GC freed 65741(3MB) AllocSpace objects, 13(208KB) LOS objects, 24% free, 19MB/25MB, paused 319us total 40.979ms
,W/Settings( 2309): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1305): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 1239): Explicit concurrent mark sweep GC freed 3975(295KB) AllocSpace objects, 1(126KB) LOS objects, 38% free, 25MB/41MB, paused 2.438ms total 39.052ms
,I/ConfigService( 1305): onCreate
,I/LibraryLoader( 1430): Loading chrome directly from within /data/app/com.android.chrome-1/base.apk
I/art     ( 1616): Explicit concurrent mark sweep GC freed 4138(234KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 22MB/30MB, paused 517us total 72.842ms
,D/BluetoothAdapter( 3115): 255307308: getState() :  mService = null. Returning STATE_OFF
,I/OpenGLRenderer(  948): Initialized EGL, version 1.4
,D/OpenGLRenderer(  948): Enabling debug mode 0
I/LibraryLoader( 1430): Time to load native libraries: 61 ms (timestamps 7030-7091)
I/LibraryLoader( 1430): Expected native library version number "44.0.2403.133",actual native library version number "44.0.2403.133"
I/chromium( 1430): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/art     ( 1430): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 1430): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  759): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=3990 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/BackupManagerService(  759): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  759): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  759): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): run()
,W/art     (  948): Attempt to remove local handle scope entry from IRT, ignoring
,W/InputMethodManagerService(  759): Focus gain on non-focused client com.android.internal.view.IInputMethodClient$Stub$Proxy@256a2ef8 (uid=10034 pid=948)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1067): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/ResourcesManager( 3990): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/art     (  759): Explicit concurrent mark sweep GC freed 30573(1766KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 6.362ms total 137.146ms
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1067): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1067): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1067): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1067): run()
I/StatsUtilsManager( 1067): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1067): shouldRecordStats() = Too Soon
,D/AdapterServiceConfig( 3990): Adding HeadsetService
D/AdapterServiceConfig( 3990): Adding A2dpService
,D/AdapterServiceConfig( 3990): Adding HidService
,D/AdapterServiceConfig( 3990): Adding HealthService
D/AdapterServiceConfig( 3990): Adding PanService
D/AdapterServiceConfig( 3990): Adding GattService
D/AdapterServiceConfig( 3990): Adding BluetoothMapService
,I/ActivityManager(  759): Killing 2921:com.android.musicfx/u0a15 (adj 15): empty #17
,W/InputMethodManagerService(  759): Got RemoteException sending setActive(false) notification to pid 3031 uid 10270
,I/Keyboard.Facilitator( 1067): onFinishInput()
,D/AuthorizationBluetoothService( 1305): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup(  759): failed to open /acct/uid_10015/pid_2921/cgroup.procs: No such file or directory
,I/Launcher( 1239): Deferring update until onResume
,D/BluetoothAdapter( 3115): 255307308: getState() :  mService = null. Returning STATE_OFF
,W/ResourcesManager( 1239): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 3936): Shutting down VM
,W/ResourcesManager( 1239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  759): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=4018 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/Launcher( 1239): Deferring update until onResume
,D/VoicemailCleanupService( 4018): Cleaning up data for package: com.test.thalitest
,I/ActivityManager(  759): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=4040 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ContactLocale( 4018): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  759): Killing 2952:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10040/pid_2952/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1360): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,W/Launcher( 1239): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@13cec0f5 new=com.google.android.velvet.VelvetApplication@13cec0f5
,I/ActivityManager(  759): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4065 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  759): Killing 2870:com.android.defcontainer/u0a5 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10005/pid_2870/cgroup.procs: No such file or directory
,W/ContextImpl( 4065): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1616): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1616): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1616): Clearing selected account for com.test.thalitest
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1616): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1305): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1305): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,W/FileUtils( 4065): Failed to chmod(/data/data/com.android.keychain/databases/grants.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/ActivityManager(  759): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4088 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,E/SQLiteLog( 4065): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
E/AndroidRuntime( 4065): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4065): Process: com.android.keychain, PID: 4065
E/AndroidRuntime( 4065): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4065): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4065): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4065): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4065): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4065): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4065): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4065): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:404)
E/AndroidRuntime( 4065): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 4065): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4065): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4065): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4065): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  759): Can't write: system_app_crash
E/DropBoxManagerService(  759): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  759): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  759): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  759): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  759): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  759): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  759): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  759): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  759): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  759): 	... 5 more
,I/LocationSettingsChecker( 1616): Removing dialog suppression flag for package com.test.thalitest
,I/Process ( 4065): Sending signal. PID: 4065 SIG: 9
,E/SQLiteDatabase( 1616): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1616): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1616): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1616): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1616): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1616): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 1616): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 1616): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/PhenotypeInitializer( 1616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1616): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1616): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1616): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1616): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1360): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1616): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 1616): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1616): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1616): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1616): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1616): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1616): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1616): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1616): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1616): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 1616): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1616): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteOpenHelper( 1616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1616): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1616): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1616): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1616): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1616): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1616): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1616): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1616): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DriveAsyncService( 1616): disk I/O error (code 3850)
E/DriveAsyncService( 1616): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1616): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1616): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1616): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1616): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1616): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 1616): Opened metrics.db in read-only mode

```
