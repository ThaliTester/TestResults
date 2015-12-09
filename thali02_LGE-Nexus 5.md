#### Test 50650278b28a87a_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 2801): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2801):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2801):   adb logcat -s GAv4
W/GAv4    ( 2801): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2801): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 2801): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 2801): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2365): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
--------- beginning of system
I/ActivityManager(  759): Killing 2093:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
W/ResourcesManager( 2801): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2801): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 2847): 
D/AndroidRuntime( 2847): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2847): CheckJNI is OFF
W/libprocessgroup(  759): failed to open /acct/uid_1000/pid_2093/cgroup.procs: No such file or directory
V/JNIHelp ( 2801): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/AndroidRuntime( 2847): Calling main entry com.android.commands.am.Am
W/System  ( 2801): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ActivityManager(  759): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ProviderInstaller( 2801): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  759): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=2880 uid=10270 gids={50270, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2847): Shutting down VM
V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 1557): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1557): Loaded CLD2 Version V2.0 - 20141016
V/ActivityManager(  759): Display changed displayId=0
I/Icing   ( 1557): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
I/WebViewFactory( 2880): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2880): Time to load native libraries: 1 ms (timestamps 6346-6347)
I/LibraryLoader( 2880): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2880): Binding Chromium to main looper Looper (main, tid 1) {36d1e54e}
I/LibraryLoader( 2880): Expected native library version number "",actual native library version number ""
I/chromium( 2880): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2880): Initializing chromium process, singleProcess=true
W/art     ( 2880): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2880): ApplicationContext is null in ApplicationStatus
,W/chromium( 2880): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2880): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2880): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2880): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2880): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36731cd8:true
,D/BluetoothAdapter( 2880): 37529448: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2880): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2880): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2880): CordovaWebView is running on device made by: LGE
,W/art     ( 2880): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2880): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2880): Render dirty regions requested: true
,D/Atlas   ( 2880): Validating map...
,W/chromium( 2880): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2880): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2880): Enabling debug mode 0
,W/IInputConnectionWrapper( 2880): showStatusIcon on inactive InputConnection
,I/ActivityManager(  759): Displayed com.test.thalitest/.MainActivity: +499ms (total +54s687ms)
,W/BindingManager( 2880): Cannot call determinedVisibility() - never saw a connection for the pid: 2880
,D/JsMessageQueue( 2880): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 2880): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1546221440
D/JX-Cordova( 2880): jxcore cordova android initializing
I/ActivityManager(  759): Killing 2183:com.google.android.youtube/u0a80 (adj 15): empty #17
W/libprocessgroup(  759): failed to open /acct/uid_10080/pid_2183/cgroup.procs: No such file or directory
,W/jxcore-log( 2880): Initializing JXcore engine
,W/jxcore-log( 2880): JXcore engine is ready
W/jxcore-log( 2880): Starting JXcore engine
,W/.test.thalitest( 2880): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9388]" dev="sockfs" ino=9388 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/.test.thalitest( 2880): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/.test.thalitest( 2880): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8522]" dev="sockfs" ino=8522 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/.test.thalitest( 2880): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17037]" dev="sockfs" ino=17037 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2880): Platform android
W/jxcore-log( 2880): 
,W/jxcore-log( 2880): Process ARCH arm
W/jxcore-log( 2880): 
,I/jxcore-log( 2880): JXcore Cordova bridge is ready!
I/jxcore-log( 2880): 
W/jxcore-log( 2880): JXcore engine is started
,I/Choreographer( 2880): Skipped 113 frames!  The application may be doing too much work on its main thread.
I/chromium( 2880): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 2880): Toggling radios to true
I/jxcore-log( 2880): 
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  759): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  759): Message: 1
D/BluetoothManagerService(  759): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  759): setWifiEnabled: true pid=2880, uid=10270
E/WifiService(  759): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  759): New client listening to asynchronous messages
,I/jxcore-log( 2880): Radios toggled
I/jxcore-log( 2880): 
,D/SoftapController(  178): Softap fwReload - Ok
,D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring down wlan0
,D/CommandListener(  178): Clearing all IP addresses on wlan0
,I/ActivityManager(  759): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2948 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 2880): Got Device Bluetooth address: 34:FC:EF:11:AE:67
I/jxcore-log( 2880): 
I/jxcore-log( 2880): Perf Test app loaded loaded
I/jxcore-log( 2880): 
,I/jxcore-log( 2880): check test folder
I/jxcore-log( 2880): 
I/jxcore-log( 2880): found test : ./testFindPeers.js
I/jxcore-log( 2880): 
,D/WifiMonitor(  759): startMonitoring(wlan0) with mConnected = false
,I/ActivityManager(  759): Start proc com.android.settings for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=2957 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/wpa_supplicant( 2947): Successfully initialized wpa_supplicant
,I/jxcore-log( 2880): found test : ./testSendData.js
I/jxcore-log( 2880): 
,I/wpa_supplicant( 2947): rfkill: Cannot open RFKILL control device,
,W/ResourcesManager( 2948): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/chromium( 2880): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  759): Message: 20
,D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2400027f:true
,D/BluetoothAdapter( 2957): 919725390: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 2957): Adding local MAP profile
,D/BluetoothMap( 2957): Create BluetoothMap proxy object
,D/BluetoothManagerService(  759): Message: 30
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 2957): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 2957): 919725390: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 2957): 919725390: getState() :  mService = null. Returning STATE_OFF
,D/AdapterServiceConfig( 2948): Adding HeadsetService
D/AdapterServiceConfig( 2948): Adding A2dpService
D/AdapterServiceConfig( 2948): Adding HidService
D/AdapterServiceConfig( 2948): Adding HealthService
,D/AdapterServiceConfig( 2948): Adding PanService
D/AdapterServiceConfig( 2948): Adding GattService
D/AdapterServiceConfig( 2948): Adding BluetoothMapService
,I/ActivityManager(  759): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2996 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  759): Killing 2278:com.google.android.deskclock/u0a38 (adj 15): empty #17
,D/BluetoothManagerService(  759): Message: 20
D/BluetoothManagerService(  759): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e833b05:true
D/BluetoothAdapterState( 2948): make
,I/bluedroid( 2948): init
,I/BluetoothAdapterState( 2948): Entering OffState
,I/bte_conf( 2948): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2948): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2948): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 2948): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 2948): get_profile_interface socket
I/bluedroid( 2948): get_profile_interface map_client
,I/GKI_LINUX( 2948): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 2948): Address is:34:FC:EF:11:AE:67
,W/libprocessgroup(  759): failed to open /acct/uid_10038/pid_2278/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 2948): Name is: Nexus 5
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  759): Message: 40
,D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 2948): config_hci_snoop_log
,D/BluetoothManagerService(  759): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  759): Broadcasting onBluetoothServiceUp() to 10 receivers.
,D/BluetoothAdapterState( 2948): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2948): Setting state to 11
I/BluetoothAdapterState( 2948): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  759): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 2948): make
,I/BluetoothBondStateMachine( 2948): StableState(): Entering Off State
,D/BluetoothHeadset(  759): Proxy object connected
D/BluetoothHeadset( 1186): Proxy object connected
D/BluetoothHeadset( 1222): Proxy object connected
,D/HeadsetService( 2948): Received start request. Starting profile...
D/BluetoothHeadset( 1186): Proxy object connected
I/BluetoothHeadsetServiceJni( 2948): classInitNative: succeeds
,D/HeadsetStateMachine( 2948): make
,I/BluetoothAdapterState( 2948): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetStateMachine( 2948): max_hf_connections = 1
I/bluedroid( 2948): get_profile_interface handsfree
D/BluetoothAdapterService( 2948): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3390966f
D/HeadsetStateMachine( 2948): Enter Disconnected: -2, size: 0
D/BluetoothA2dp(  759): Proxy object connected
D/A2dpService( 2948): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 2948): classInitNative: succeeds
I/bluedroid( 2948): get_profile_interface avrcp
,E/RemoteController( 2948): Cannot set synchronization mode on an unregistered RemoteController
,I/BluetoothA2dpServiceJni( 2948): classInitNative: succeeds
D/A2dpStateMachine( 2948): make
,I/bluedroid( 2948): get_profile_interface a2dp
,I/GKI_LINUX( 2948): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 2948): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3390966f
D/A2dpStateMachine( 2948): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 2948): classInitNative: succeeds
D/HidService( 2948): Received start request. Starting profile...
D/BluetoothInputDevice( 2957): Proxy object connected
I/bluedroid( 2948): get_profile_interface hidhost
D/BluetoothAdapterService( 2948): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3390966f
I/BluetoothHealthServiceJni( 2948): classInitNative: succeeds
D/HidProfile( 2957): Bluetooth service connected
D/HealthService( 2948): Received start request. Starting profile...
,I/bluedroid( 2948): get_profile_interface health
D/BluetoothAdapterService( 2948): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3390966f
,I/BluetoothPanServiceJni( 2948): classInitNative(L105): succeeds
,D/PanService( 2948): Received start request. Starting profile...
,D/BluetoothPanServiceJni( 2948): initializeNative(L110): pan
I/bluedroid( 2948): get_profile_interface pan
D/BluetoothPan( 2957): BluetoothPAN Proxy object connected
,D/PanProfile( 2957): Bluetooth service connected
,D/BluetoothAdapterService( 2948): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3390966f
I/BtGatt.JNI( 2948): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 2948): handleDebugAction() action=null
,D/BtGatt.GattService( 2948): Received start request. Starting profile...
D/BtGatt.GattService( 2948): start()
I/bluedroid( 2948): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2948): advertise manager created
,D/BluetoothAdapterService( 2948): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3390966f
,V/BluetoothMapService( 2948): BluetoothMapBinder()
,D/BluetoothMap( 2957): Proxy object connected
,D/BluetoothMapService( 2948): Received start request. Starting profile...
,D/BluetoothMapService( 2948): start()
D/MapProfile( 2957): Bluetooth service connected
D/BluetoothMap( 2957): getConnectedDevices()
,D/BluetoothMap( 2957): Bluetooth is Not enabled
D/BluetoothMapEmailSettingsLoader( 2948): Found 0 applications
D/BluetoothMapEmailAppObserver( 2948): createReceiver()
,D/BluetoothMapEmailAppObserver( 2948): initObservers()
D/BluetoothMapEmailAppObserver( 2948): getEnabledAccountItems()
,D/BluetoothAdapterService( 2948): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3390966f
D/HeadsetStateMachine( 2948): Proxy object connected
,D/HeadsetStateMachine( 2948): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 2948): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
V/BluetoothMapService( 2948): Handler(): got msg=1
D/HeadsetStateMachine( 2948): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 2948): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2948): enable
,I/GKI_LINUX( 2948): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2948): btu_task pending for preload complete event
,I/bt_hci_bdroid( 2948): init
,I/bt_vendor( 2948): init
I/bt_vnd_conf( 2948): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 2948): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2948): userial_init
,I/ActivityManager(  759): Killing 2327:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/bt_userial_vendor( 2948): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 2948): device fd = 53 open
,D/bt_userial( 2948): Entering userial_read_thread()
,W/libprocessgroup(  759): failed to open /acct/uid_10069/pid_2327/cgroup.procs: No such file or directory
,I/art     ( 1405): Explicit concurrent mark sweep GC freed 9381(544KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 19MB/32MB, paused 518us total 21.919ms
,I/bt_hwcfg( 2948): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2948): Chipset BCM4335C0
D/bt_hwcfg( 2948): Target name = [BCM4335C0]
I/bt_hwcfg( 2948): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/AuthorizationBluetoothService( 1405): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  759): Killing 1775:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  759): failed to open /acct/uid_10045/pid_1775/cgroup.procs: No such file or directory
,D/Tethering(  759): sendTetherStateChangedBroadcast 1, 0, 0
,I/bt_hwcfg( 2948): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2948): Settlement delay -- 100 ms
I/bt_hwcfg( 2948): Setting fw settlement delay to 100 
,I/wpa_supplicant( 2947): rfkill: Cannot open RFKILL control device
,D/WifiConfigStore(  759): Loading config and enabling all networks 
,D/WifiService(  759): New client listening to asynchronous messages
,E/WifiConfigStore(  759): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  759): Setting external_sim to 1
,D/WifiStateMachine(  759): Setting OUI to DA-A1-19
I/WifiNative-HAL(  759): startHal
D/wifi    (  759): setting scan oui 0x9e6641a8
D/WifiHAL (  759): Sending mac address OUI
E/WifiHAL (  759): failed to set scanning mac OUI; result = -95
,W/Settings( 1793): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  759): do suspend true
,D/WifiScanningService(  759): SCAN_AVAILABLE : 3
D/RttService(  759): SCAN_AVAILABLE : 3
D/WifiScanningService(  759): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  759): startHal
,D/RttService(  759): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  178): Setting iface cfg
D/CommandListener(  178): Trying to bring up p2p0
D/WifiMonitor(  759): startMonitoring(p2p0) with mConnected = true
D/wifi    (  759): getting scan capabilities on interface[1] = 0x9e6641a8
D/WifiHAL (  759): Creating message to get scan capablities; iface = 21
D/WifiHAL (  759): In GetCapabilities::handleResponse
D/WifiHAL (  759): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  759): StartedState
,D/WifiNative-HAL(  759): p2pGetDeviceAddress
,D/WifiNative-HAL(  759): p2pGetDeviceAddress returning 52:55:27:f0:fd:0b
,I/wpa_supplicant( 2947): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/bt_hwcfg( 2948): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2948): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 2948): vendor lib fwcfg completed
I/bt-btu  ( 2948): btu_task received preload complete event
,I/        ( 2948): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 2948): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2948): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2948): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2948): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2948): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2948): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 2948): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2948): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2948): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2948): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2948): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2948): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2948): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2948): BTE_InitTraceLevels -- TRC_BTIF
,E/bt-btm  ( 2948): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3cd99d5 
E/bt-btm  ( 2948): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3cd99d5 
,E/bt-btif ( 2948): Calling BTA_HhEnable
E/bt-btif ( 2948): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 2948): Address is:34:FC:EF:11:AE:67
,D/BluetoothAdapterProperties( 2948): Name is: Nexus 5
,W/bt-smp  ( 2948): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2948): Plain text(LSB ~ MSB) = dc 00 7c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2948): Encrypted text(LSB ~ MSB) = bb 10 84 04 91 95 e9 19 ae 37 23 1a db 70 d3 f4 
,W/bt-btm  ( 2948): Stopping oneshot timer
,D/BluetoothAdapterProperties( 2948): Scan Mode:20
,D/BluetoothAdapterProperties( 2948): Discoverable Timeout:120
,D/bte_conf( 2948): Device ID record 1 : primary
D/bte_conf( 2948):   vendorId            = 000f
D/bte_conf( 2948):   vendorIdSource      = 0001
D/bte_conf( 2948):   product             = 1200
D/bte_conf( 2948):   version             = 1436
D/bte_conf( 2948):   clientExecutableURL = 
D/bte_conf( 2948):   serviceDescription  = 
D/bte_conf( 2948):   documentationURL    = 
D/bte_conf( 2948): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 2948): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2948): ScanMode =  20
D/BluetoothAdapterProperties( 2948): State =  11
D/BluetoothAdapterProperties( 2948): Setting state to 12
,I/BluetoothAdapterState( 2948): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  759): Message: 60
D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,I/BluetoothAdapterState( 2948): Entering On State
,E/bt_h4   ( 2948): vendor lib postload completed
,D/BluetoothPanServiceJni( 2948): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothManagerService(  759): Broadcasting onBluetoothStateChange(true) to 9 receivers.
,D/BluetoothPan( 2957): onBluetoothStateChange(on) call bindService
,D/BluetoothManagerService(  759): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  759): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 2948): Scan Mode:21
,D/BluetoothAdapterProperties( 2948): Discoverable Timeout:120
,D/BluetoothInputDevice( 2957): onBluetoothStateChange: up=true
,D/BluetoothPbap( 2957): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  759): onBluetoothStateChange: up=true
,D/BluetoothMap( 2957): onBluetoothStateChange: up=true
D/BluetoothA2dp(  759): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1222): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1186): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  759): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  759): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  759): Message: 40
,D/BluetoothManagerService(  759): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,I/Telecom ( 1186): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BluetoothMapService( 2948): onReceive
D/BluetoothMapService( 2948): STATE_ON
V/BluetoothMapService( 2948): Handler(): got msg=1
,D/BluetoothMapMasInstance( 2948): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 2948): MAS initSocket()
D/BluetoothMapMasInstance( 2948):   masId = 00
D/BluetoothMapMasInstance( 2948):   msgTypes = 0e
D/BluetoothMapMasInstance( 2948):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2948):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/HeadsetStateMachine( 2948): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2948): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2948): mNumber:  mType: 128
D/HeadsetStateMachine( 2948): terminateScoUsingVirtualVoiceCall: Received
E/HeadsetStateMachine( 2948): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,V/BluetoothMapMasInstance( 2948): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2948): Accepting socket connection...
,D/LocalBluetoothProfileManager( 2957): Adding local A2DP profile
,D/BluetoothManagerService(  759): Message: 30
,D/LocalBluetoothProfileManager( 2957): Adding local HEADSET profile
,D/BluetoothManagerService(  759): Message: 30
,I/art     (  759): Explicit concurrent mark sweep GC freed 22468(1158KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 1.096ms total 66.899ms
,W/ContextImpl( 2957): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothA2dp( 2957): Proxy object connected
,D/A2dpProfile( 2957): Bluetooth service connected
,D/BluetoothHeadset( 2957): Proxy object connected
,D/HeadsetProfile( 2957): Bluetooth service connected
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,D/DockEventReceiver( 2957): finishStartingService: stopping service
,D/BluetoothPbap( 2957): Proxy object connected
,D/PbapServerProfile( 2957): Bluetooth service connected
,D/AuthorizationBluetoothService( 1405): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  759): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2948): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 2948): Accept thread started.
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1349): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Search.LoginHelper( 1349): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/NetworkUtils( 1349): OkHttp exception
W/EventLoggerService( 1349): Unable to send logs Error code: 262146
,I/jxcore-log( 2880): BLE advertisement not supported: MultipleAdvertisement not supported
I/jxcore-log( 2880): 
,D/Finsky  ( 2365): [230] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 2365): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ClearcutLoggerApiImpl( 1405): disconnect managed GoogleApiClient
,I/ClearcutLoggerApiImpl( 1297): disconnect managed GoogleApiClient
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-smp  ( 2948): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2948): Plain text(LSB ~ MSB) = 62 d1 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2948): Encrypted text(LSB ~ MSB) = 15 55 a3 58 a0 dc e1 76 a9 c4 db 61 70 39 33 ab 
,W/bt-btm  ( 2948): Stopping oneshot timer
,I/UsageStatsService(  759): User[0] Flushing usage stats to disk
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  759): Killing 2428:com.android.cellbroadcastreceiver/u0a3 (adj 15): empty for 1800s
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Prepared write state in 4ms
,W/libprocessgroup(  759): failed to open /acct/uid_10003/pid_2428/cgroup.procs: No such file or directory
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1405): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  759): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-42-42.bin
,I/ActivityManager(  759): Killing 1460:com.google.android.partnersetup/u0a13 (adj 13): empty for 1805s
,W/bt-smp  ( 2948): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2948): Plain text(LSB ~ MSB) = 20 1b 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2948): Encrypted text(LSB ~ MSB) = 7c c4 2b bc 4c 43 87 20 6c fc 14 d2 d6 7d 0f 2f 
,W/bt-btm  ( 2948): Stopping oneshot timer
,I/ActivityManager(  759): Killing 1928:com.android.providers.calendar/u0a2 (adj 13): empty for 1808s
,I/ActivityManager(  759): Killing 1793:com.google.android.talk/u0a54 (adj 13): empty for 1832s
,I/ActivityManager(  759): Killing 2448:com.google.android.music:main/u0a60 (adj 13): empty for 1834s
,I/ActivityManager(  759): Killing 2004:com.google.android.calendar/u0a31 (adj 15): empty for 1839s
,I/ActivityManager(  759): Killing 2301:com.google.android.gm/u0a70 (adj 15): empty for 1839s
,W/libprocessgroup(  759): failed to open /acct/uid_10013/pid_1460/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10002/pid_1928/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10054/pid_1793/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10060/pid_2448/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10031/pid_2004/cgroup.procs: No such file or directory
,W/libprocessgroup(  759): failed to open /acct/uid_10070/pid_2301/cgroup.procs: No such file or directory
,TIME-OUT KILL (timeout was 1800000ms)
```
