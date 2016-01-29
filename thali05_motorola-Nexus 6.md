#### Test 57531243c766d4e_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
D/Finsky  ( 2684): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 2684): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/AndroidRuntime( 3085): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3085): CheckJNI is OFF
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  821): Explicit concurrent mark sweep GC freed 18218(870KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.826ms total 74.662ms
W/Finsky  ( 2684): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/AndroidRuntime( 3085): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  821): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  821): addAppToken: AppWindowToken{3d9e56ff token=Token{16130e1e ActivityRecord{79fc259 u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3085): Shutting down VM
V/WindowManager(  821): Adding window Window{103c09b8 u0 Starting com.test.thalitest} at 2 of 7 (after Window{3165ae98 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/HotwordDetector( 1516): Closing mic
I/MicrophoneInputStream( 1516): mic_close com.google.android.apps.gsa.speech.audio.u@11a629b7
I/ActivityManager(  821): Start proc 3101:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1516): Stopping hotword detection.
I/HotwordRecognitionRnr( 1516): Hotword detection finished
I/ActivityManager(  821): Killing 2643:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/art     ( 1705): Explicit concurrent mark sweep GC freed 13235(763KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.337ms total 39.092ms
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3101): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/Finsky  ( 2684): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 2684): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 2684): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 2684): [1] DailyHygiene.reschedule: Scheduling new run in 289 minutes (failures=4)
,I/LibraryLoader( 3101): Time to load native libraries: 1 ms (timestamps 478-479)
I/LibraryLoader( 3101): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  821): Killing 2808:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/DeviceConnectionService( 1705): client connected with version: 7571000
,V/WebViewChromiumFactoryProvider( 3101): Binding Chromium to main looper Looper (main, tid 1) {12dc05ae}
,I/LibraryLoader( 3101): Expected native library version number "",actual native library version number ""
I/chromium( 3101): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660626195
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/BrowserStartupController( 3101): Initializing chromium process, singleProcess=true
,W/art     ( 3101): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3101): ApplicationContext is null in ApplicationStatus
,W/chromium( 3101): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3101): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3101): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3101): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3101): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20e5a632:true
D/BluetoothAdapter( 3101): 381023205: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3101): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3101): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3101): CordovaWebView is running on device made by: motorola
,W/art     ( 3101): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 3101): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3101): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3101): Validating map...,
,V/WindowManager(  821): Adding window Window{29da865 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{103c09b8 u0 Starting com.test.thalitest})
W/chromium( 3101): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3101): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3101): Enabling debug mode 0
,I/ActivityManager(  821): Displayed com.test.thalitest/.MainActivity: +672ms
,I/Keyboard.Facilitator( 1214): onFinishInput()
,W/BindingManager( 3101): Cannot call determinedVisibility() - never saw a connection for the pid: 3101
,D/JsMessageQueue( 3101): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3101): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576316032
,I/chromium( 3101): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 24706(1662KB) AllocSpace objects, 11(176KB) LOS objects, 22% free, 27MB/35MB, paused 705us total 48.728ms
,W/jxcore-log( 3101): Initializing JXcore engine
,W/jxcore-log( 3101): JXcore engine is ready
,W/Thread-323( 3159): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12415]" dev="sockfs" ino=12415 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-323( 3159): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-323( 3159): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11739]" dev="sockfs" ino=11739 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-323( 3159): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19290]" dev="sockfs" ino=19290 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3101): Starting JXcore engine,
,W/jxcore-log( 3101): Platform android,
W/jxcore-log( 3101): 
W/jxcore-log( 3101): Process ARCH arm
,W/jxcore-log( 3101): 
,I/jxcore-log( 3101): JXcore Cordova bridge is ready!
I/jxcore-log( 3101): 
W/jxcore-log( 3101): JXcore engine is started
,I/jxcore-log( 3101): Toggling radios to true
I/jxcore-log( 3101): 
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  821): Message: 1
D/BluetoothManagerService(  821): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  821): setWifiEnabled: true pid=3101, uid=10265
,D/WifiService(  821): New client listening to asynchronous messages
E/WifiService(  821): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3101): Radios toggled
I/jxcore-log( 3101): 
D/SoftapController(  352): Softap fwReload - Ok
,I/jxcore-log( 3101): My device name is: motorola-Nexus 6
I/jxcore-log( 3101): 
,I/ActivityManager(  821): Start proc 3167:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/CommandListener(  352): Setting iface cfg
,D/CommandListener(  352): Trying to bring down wlan0
,D/CommandListener(  352): Clearing all IP addresses on wlan0
,E/WifiMonitor(  821): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  821): startMonitoring(wlan0) with mConnected = false
E/WifiHW  (  821): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/wpa_supplicant( 3177): Successfully initialized wpa_supplicant
,I/ActivityManager(  821): Start proc 3185:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3167): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3177): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  821): Start proc 3211:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  821): Killing 2927:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/AdapterServiceConfig( 3167): Adding HeadsetService
,D/AdapterServiceConfig( 3167): Adding A2dpService,
,D/AdapterServiceConfig( 3167): Adding HidService
,D/AdapterServiceConfig( 3167): Adding HealthService
,D/AdapterServiceConfig( 3167): Adding PanService
D/AdapterServiceConfig( 3167): Adding GattService
,D/AdapterServiceConfig( 3167): Adding BluetoothMapService,
,D/BluetoothManagerService(  821): Message: 20,
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1693ba24:true,
,D/BluetoothAdapterState( 3167): make,
,I/bluedroid( 3167): init,
,I/BluetoothAdapterState( 3167): Entering OffState
,I/bte_conf( 3167): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3167): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3167): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3167): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 3167): get_profile_interface socket
I/bluedroid( 3167): get_profile_interface map_client
,I/GKI_LINUX( 3167): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3167): Address is:F8:CF:C5:D9:E5:61,
D/BluetoothAdapterProperties( 3167): Name is: Nexus 6
D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  821): Message: 40
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3167): config_hci_snoop_log
,D/BluetoothManagerService(  821): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  821): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3167): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3167): Setting state to 11
I/BluetoothAdapterState( 3167): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  821): Message: 60
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  821): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3167): make
I/BluetoothBondStateMachine( 3167): StableState(): Entering Off State
,I/BluetoothAdapterState( 3167): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
D/HeadsetService( 3167): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3167): classInitNative: succeeds
D/HeadsetStateMachine( 3167): make
,D/HeadsetStateMachine( 3167): max_hf_connections = 1
I/bluedroid( 3167): get_profile_interface handsfree
D/HeadsetStateMachine( 3167): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
,D/BluetoothA2dp(  821): Proxy object connected
D/A2dpService( 3167): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3167): classInitNative: succeeds
,I/bluedroid( 3167): get_profile_interface avrcp
D/BluetoothA2dp( 1066): Proxy object connected
E/RemoteController( 3167): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3167): classInitNative: succeeds
D/A2dpStateMachine( 3167): make
I/bluedroid( 3167): get_profile_interface a2dp
I/GKI_LINUX( 3167): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3167): Enter Disconnected: -2
I/BluetoothHidServiceJni( 3167): classInitNative: succeeds
,D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
D/HidService( 3167): Received start request. Starting profile...
,I/bluedroid( 3167): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3167): classInitNative: succeeds
D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
,D/HealthService( 3167): Received start request. Starting profile...
I/bluedroid( 3167): get_profile_interface health
,I/BluetoothPanServiceJni( 3167): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
D/BluetoothInputDevice( 1066): Proxy object connected
D/BluetoothPan( 1066): BluetoothPAN Proxy object connected
D/PanService( 3167): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3167): initializeNative(L110): pan
I/bluedroid( 3167): get_profile_interface pan
I/BtGatt.JNI( 3167): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
D/BtGatt.DebugUtils( 3167): handleDebugAction() action=null
D/BtGatt.GattService( 3167): Received start request. Starting profile...
D/BtGatt.GattService( 3167): start()
I/bluedroid( 3167): get_profile_interface gatt
D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
D/BtGatt.AdvertiseManager( 3167): advertise manager created
,D/BluetoothAdapterService( 3167): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23fd9f4f
,D/BluetoothMap( 1066): Proxy object connected
D/BluetoothMapService( 3167): Received start request. Starting profile...
D/BluetoothMapService( 3167): start()
,D/BluetoothMapEmailSettingsLoader( 3167): Found 0 applications
D/BluetoothMapEmailAppObserver( 3167): createReceiver()
D/BluetoothMapEmailAppObserver( 3167): initObservers()
D/BluetoothMapEmailAppObserver( 3167): getEnabledAccountItems()
,D/HeadsetStateMachine( 3167): Proxy object connected
D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3167): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3167): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3167): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3167): enable
I/bt_hci_bdroid( 3167): init
,I/GKI_LINUX( 3167): gki_task_entry task_id=0 [BTU] starting
,I/bt-btu  ( 3167): btu_task pending for preload complete event
,I/bt_vendor( 3167): init
I/bt_vnd_conf( 3167): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3167): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3167): userial_init
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 17235(934KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 798us total 20.388ms
,I/bt_userial_vendor( 3167): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3167): device fd = 53 open
D/bt_userial( 3167): Entering userial_read_thread()
,I/bt_hwcfg( 3167): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  821): Start proc 3255:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,D/Tethering(  821): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  821): Killing 2947:com.android.musicfx/u0a18 (adj 15): empty #17
,D/bt_hwcfg( 3167): Chipset BCM4354A2
D/bt_hwcfg( 3167): Target name = [BCM4354A2]
I/bt_hwcfg( 3167): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/wpa_supplicant( 3177): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3177): Could not read interface p2p-dev-wlan0 flags: No such device
,I/ActivityManager(  821): Killing 2105:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/bt_hwcfg( 3167): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3167): Settlement delay -- 100 ms
I/bt_hwcfg( 3167): Setting fw settlement delay to 100 
,D/WifiConfigStore(  821): Loading config and enabling all networks 
,E/WifiConfigStore(  821): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@6ad361c}
,I/bt_hwcfg( 3167): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3167): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/ActivityManager(  821): Start proc 3273:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  821): Setting external_sim to 1
,W/Settings( 2613): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  821): Setting OUI to 92-68-C3
,I/WifiNative-HAL(  821): startHal
D/wifi    (  821): setting scan oui 0xaec7e3b8
D/WifiHAL (  821): Sending mac address OUI
,I/bt_hwcfg( 3167): vendor lib fwcfg completed
,I/bt-btu  ( 3167): btu_task received preload complete event
E/WifiStateMachine(  821): cancelDelayedScan -> 1
,I/        ( 3167): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3167): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3167): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3167): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3167): BTE_InitTraceLevels -- TRC_AVRC
,I/        ( 3167): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3167): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3167): BTE_InitTraceLevels -- TRC_BTM,
I/        ( 3167): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3167): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3167): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 3167): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3167): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3167): BTE_InitTraceLevels -- TRC_BTAPP
,I/        ( 3167): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiScanningService(  821): SCAN_AVAILABLE : 3,
D/RttService(  821): SCAN_AVAILABLE : 3,
D/RttService(  821): DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  821): DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  821): startHal
,I/wpa_supplicant( 3177): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,W/CommandListener(  352): Failed to retrieve HW addr for p2p0 (No such device)
D/CommandListener(  352): Setting iface cfg
E/WifiP2pService(  821): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  821): startMonitoring(p2p0) with mConnected = true
,D/wifi    (  821): getting scan capabilities on interface[0] = 0xaec7e3b8
D/WifiHAL (  821): Creating message to get scan capablities; iface = 5
D/WifiHAL (  821): In GetCapabilities::handleResponse
,D/WifiHAL (  821): Id = 0, subcmd = 0, len = 28, expected len = 32
E/native  (  821): do suspend false
D/WifiScanningService(  821): StartedState
,D/WifiNative-HAL(  821): p2pGetDeviceAddress
,D/WifiNative-HAL(  821): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/bt-btm  ( 3167): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2dc8085 
,E/bt-btm  ( 3167): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2dc8085 ,
,D/BluetoothAdapterProperties( 3167): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3167): Calling BTA_HhEnable
E/bt-btif ( 3167): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 3167): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3167): Name is: Nexus 6
D/BluetoothAdapterProperties( 3167): Scan Mode:20
D/BluetoothAdapterProperties( 3167): Discoverable Timeout:120
,D/BluetoothManagerService(  821): Bluetooth Adapter name changed to Nexus 6,
D/BluetoothManagerService(  821): Stored Bluetooth name: Nexus 6
,D/bte_conf( 3167): Device ID record 1 : primary
D/bte_conf( 3167):   vendorId            = 000f
D/bte_conf( 3167):   vendorIdSource      = 0001
D/bte_conf( 3167):   product             = 1200
,D/bte_conf( 3167):   version             = 1436,
D/bte_conf( 3167):   clientExecutableURL = 
D/bte_conf( 3167):   serviceDescription  = 
D/bte_conf( 3167):   documentationURL    = 
D/bte_conf( 3167): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3167): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3167): ScanMode =  20
D/BluetoothAdapterProperties( 3167): State =  11
D/BluetoothAdapterProperties( 3167): Setting state to 12
I/BluetoothAdapterState( 3167): Bluetooth adapter state changed: 11-> 12,
D/BluetoothPanServiceJni( 3167): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  821): Message: 60,
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  821): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3167): Entering On State
D/BluetoothHeadset( 1066): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3167): Scan Mode:21
D/BluetoothAdapterProperties( 3167): Discoverable Timeout:120
D/BluetoothManagerService(  821): Creating new ProfileServiceConnections object for profile: 1
D/BluetoothA2dp(  821): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1066): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1066): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothInputDevice( 1066): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1066): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1066): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink },
D/BluetoothA2dp( 1066): onBluetoothStateChange: up=true
,D/BluetoothPan( 1066): onBluetoothStateChange(on) call bindService
,D/BluetoothHeadsetClient( 1066): onBluetoothStateChange: up=true,
E/BluetoothHeadsetClient( 1066): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1273): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
D/BluetoothMap( 1066): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  821): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  821): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  821): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  821): Message: 40,
D/BluetoothManagerService(  821): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
W/bt-btm  ( 3167): Stopping oneshot timer
E/bt_h4   ( 3167): vendor lib postload completed
,D/BluetoothMapService( 3167): onReceive
D/BluetoothMapService( 3167): STATE_ON
,D/BluetoothMapMasInstance( 3167): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3167): MAS initSocket()
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3167): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3167): Accepting socket connection...
,W/bt-btm  ( 3167): Stopping oneshot timer
,W/bt-btm  ( 3167): Stopping oneshot timer
,W/bt-btm  ( 3167): Stopping oneshot timer
,D/StrictMode( 3273): StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3273): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3273): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3273): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3273): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3273): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3273): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3273): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3273): StrictMode policy violation; ~duration=206 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3273): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3273): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3273): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3273): StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
,D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3273): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3273): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3273): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3273): 	at java.lang.Runtime.loadLibrary(Runtime.java:360),
D/StrictMode( 3273): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3273): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3273): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit,.main(ZygoteInit.java:698)
D/StrictMode( 3273): StrictMode policy violation; ~duration=200 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3273): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3273): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3273): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
,D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698),
D/StrictMode( 3273): StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3273): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3273): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3273): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3273): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3273): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
,D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3273): StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3273): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3273): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3273): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62),
D/StrictMode( 3273): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3273): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3273): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3273): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3273): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3273): # via Binder call with stack:
,D/StrictMode( 3273): android.os.StrictMode$LogStackTrace
D/StrictMode( 3273): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3273): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3273): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3273): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3273): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3273): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3273): 	at com.google.android.c.c.a(PG:87)
,D/StrictMode( 3273): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3273): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3273): StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3273): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3273): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3273): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3273): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3273): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3273): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3273): ,	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
,D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3273): StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3273): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3273): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3273): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3273): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3273): 	,at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): ,	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3273): StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3273): 	,at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3273): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3273): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3273): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012),
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	,at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3273): StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3273): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3273): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3273): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3273): 	at java.io.FileInputStream.read(FileInputStream.java:177)
,D/StrictMode( 3273): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3273): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3273): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3273): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3273): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3273): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3273): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3273): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3273): 	,at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3273): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3273): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3273): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3273): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3273): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3273): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3273): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3273): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3273): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3273): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/bt-btm  ( 3167): Stopping oneshot timer
W/bt-btm  ( 3167): Stopping oneshot timer
W/bt-btm  ( 3167): Stopping oneshot timer
W/com.google.a.a.a.b.a( 3273): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  821): Message: 20
,D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@323bddd9:true
,I/ActivityManager(  821): Killing 2976:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 1066): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset(  821): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset( 1273): Proxy object connected
,D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
D/BluetoothManagerService(  821): Message: 400
D/BluetoothHeadset(  821): Proxy object connected
,D/AuthorizationBluetoothService( 1489): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/art     (  821): Explicit concurrent mark sweep GC freed 26069(1279KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.383ms total 78.297ms
,W/ContextImpl( 3255): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  821): Message: 20
D/BluetoothManagerService(  821): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32ffeb13:true
,D/LocalBluetoothProfileManager( 3255): Adding local A2DP profile
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  821): Message: 30
W/BluetoothAdapter( 3167): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1489): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3255): Adding local HEADSET profile
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3167): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3167): Accept thread started.
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3255): Adding local MAP profile
,D/BluetoothMap( 3255): Create BluetoothMap proxy object
,D/BluetoothManagerService(  821): Message: 30
,D/BluetoothManagerService(  821): Message: 30
,D/LocalBluetoothProfileManager( 3255): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3255): finishStartingService: stopping service
,D/BluetoothA2dp( 3255): Proxy object connected
D/A2dpProfile( 3255): Bluetooth service connected
,D/BluetoothInputDevice( 3255): Proxy object connected
D/HidProfile( 3255): Bluetooth service connected
,D/BluetoothPan( 3255): BluetoothPAN Proxy object connected
,D/PanProfile( 3255): Bluetooth service connected
,D/BluetoothMap( 3255): Proxy object connected
D/MapProfile( 3255): Bluetooth service connected
D/BluetoothMap( 3255): getConnectedDevices()
,D/BluetoothPbap( 3255): Proxy object connected
D/PbapServerProfile( 3255): Bluetooth service connected
,D/BluetoothManagerService(  821): Message: 400
,D/BluetoothHeadset( 3255): Proxy object connected
D/HeadsetProfile( 3255): Bluetooth service connected
,I/wpa_supplicant( 3177): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  821): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000,
E/WifiConfigStore(  821):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  821):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3,
E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  821): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  821): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  821): will read network variables netId=0
,E/WifiStateMachine(  821): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  821): will read network variables netId=0
,I/wpa_supplicant( 3177): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3177): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3177): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3177): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  821): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  821): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  352): Setting iface cfg
,E/WifiStateMachine(  821): Start Dhcp Watchdog 1
,E/WifiStateMachine(  821):  WifiLinkLayerStats: 
E/WifiStateMachine(  821):  my bss beacon rx: 1
E/WifiStateMachine(  821):  RSSI mgmt: -49
E/WifiStateMachine(  821):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  821):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  821):  on_time : 0 tx_time=59 rx_time=262 scan_time=0
,D/ConnectivityService(  821): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  821): do suspend false
,E/WifiStateMachine(  821): scanCount==0 - aborting
,I/dhcpcd  ( 3314): version 5.5.6 starting
,I/dhcpcd  ( 3314): wlan0: rebinding lease of 192.168.1.122
,I/jxcore-log( 3101): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3101): 
,I/dhcpcd  ( 3314): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/dhcpcd  ( 3314): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  821): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  821): Adding iface wlan0 to network 100
,E/WifiStateMachine(  821): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/jxcore-log( 3101): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3101): 
,E/ConnectivityService(  821): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  821): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  821): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  821): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  821): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821):    accepting network in place of null
,D/ConnectivityService(  821): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} },
,D/ConnectivityService(  821): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576,
,D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
D/CSLegacyTypeTracker(  821): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  821): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1273): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  821): getDataEnabled: retVal=false
V/BackupManagerService(  821): Scheduling immediate backup pass
,V/BackupManagerService(  821): Running a backup pass
,V/BackupManagerService(  821): clearing pending backups
,I/NetworkMonitor( 2847): type=WIFI subType= reason=null isConnected=true
,V/PerformBackupTask(  821): Beginning backup of 14 targets
,V/MusicLeanback( 2847): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/PerformBackupTask(  821): invokeAgentForBackup on @pm@
,E/GpsLocationProvider(  821): No APN found to select.
,V/BackupServiceBinder(  821): doBackup() invoked
,I/PMBA    (  821): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/AlarmManagerService(  821): Setting time of day to sec=1454090202
,W/AlarmManagerService(  821): Unable to set rtc to 1454090202: Invalid argument
,I/BackupRestoreController(  821): Getting widget state for user: 0
,I/ActivityManager(  821): Start proc 3350:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/jxcore-log( 3101): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3101): 
,I/art     (  367): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 768us total 18.718ms
,I/jxcore-log( 3101): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3101): 
,I/jxcore-log( 3101): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3101): 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 17:56:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454090202291], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454090202278]}
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 234us total 20.842ms
,D/SprintDMReceiver( 3350): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3350): simOperator:  IMSI: null
D/SprintDMReceiver( 3350): Not Sprint UICC, don't do anything.
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  821): Validated
D/ConnectivityService(  821): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  821): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  821): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  821): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  821): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1066): CM callback handler got msg 524290
,I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 231us total 10.475ms
,I/SystemUpdateService( 1734): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/GpsLocationProvider(  821): NTP server returned: 1454090202240 (Fri Jan 29 18:56:42 GMT+01:00 2016) reference: 88444 certainty: 9 system time offset: -88
,V/GoogleAuthProtoRequest( 3185): [321] a.<init>: mAccountName set to: thalitester@gmail.com
,W/GmsBackupTransport( 1705): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1705): starting performBackup for @pm@
,V/GmsBackupTransport( 1705): performBackup done for @pm@
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSActivity( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1489): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1489): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1489): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1705): Error sending final backup to server: 
W/GmsBackupTransport( 1705): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1705): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1705): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1705): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1705): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1705): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1705): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1705): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1705): 	... 1 more
,D/BackupManagerService(  821): Now staging backup of com.google.android.talk
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3185): [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3185): [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,E/Auth.Api.Credentials( 1734): [CredentialSyncAdapter] Unknown sync event.
,D/BackupManagerService(  821): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  821): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  821): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  821): Now staging backup of com.google.android.gm
,D/BackupManagerService(  821): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  821): Now staging backup of com.android.nfc
,D/BackupManagerService(  821): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  821): Now staging backup of com.google.android.marvin.talkback
D/BackupManagerService(  821): Now staging backup of com.google.android.inputmethod.latin
D/BackupManagerService(  821): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  821): Now staging backup of com.android.vending
,D/BackupManagerService(  821): Now staging backup of android
,D/BackupManagerService(  821): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1705): Next backup will happen in 43199910 millis.
,I/BackupManagerService(  821): Backup pass finished.
,V/GoogleAuthProtoRequest( 3185): [322] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/DriveInitializer( 1734): Background init thread started
D/SystemUpdateService( 1734): onCreate
,D/SystemUpdateService( 1734): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1734): active receiver: enabled
,I/SystemUpdateService( 1734): showing system update notification
,W/ExperimentUpdateService( 3185): [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,I/ValidateNoPeople(  821): skipping global notification
,V/SystemUpdateService( 1734): retry (wakeup: false) in 3599961 ms
,W/DriveInitializer( 1734): Awaiting to be initialized
,D/SystemUpdateService( 1734): onDestroy
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 15872(845KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 815us total 20.728ms
,I/iu.SyncManager( 1734): SYNC; picasa accounts
,D/NetworkLogImpl( 1734): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1734): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1734): num queued entries: 0
I/iu.UploadsManager( 1734): num updated entries: 0
,I/iu.SyncManager( 1734): NEXT; no task
,W/DriveInitializer( 1734): Background init thread ended
,I/VacuumService( 1489): Vacuum at: now=1454090202761 tag=VacuumService
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  821): Start proc 3405:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1489): Connected
,I/ActivityManager(  821): Start proc 3428:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/GCM     ( 1489): Message class com.google.f.a.a.p
,D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): 	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
,I/Babel   ( 2613): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  821): Explicit concurrent mark sweep GC freed 48736(2MB) AllocSpace objects, 7(151KB) LOS objects, 32% free, 33MB/49MB, paused 1.920ms total 74.867ms
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1734): [AccountUtils] Account not ready
W/Kids    ( 1734): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1734): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1734): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1734): 	at java.lang.Thread.run(Thread.java:818)
,I/GAv4    ( 3428): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3428):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3428):   adb logcat -s GAv4
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36787, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,W/GAv4    ( 3428): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3428): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3428): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/KeepSync( 3211): Connecting to GoogleApiClient
,W/BaseAppContext( 1734): Using Auth Proxy for data requests.
,W/BaseAppContext( 1734): Using Auth Proxy for data requests.
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WebViewFactory( 3428): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/GAV2    ( 3405): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
,V/KeepSync( 3211): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,I/BooksApp( 3405): Created application version: 3.6.8 (30608)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,I/LibraryLoader( 3428): Time to load native libraries: 1 ms (timestamps 9527-9528)
I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3428): Binding Chromium to main looper Looper (main, tid 1) {13cadeb3}
,I/LibraryLoader( 3428): Expected native library version number "",actual native library version number ""
I/chromium( 3428): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3428): Initializing chromium process, singleProcess=true
W/art     ( 3428): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3428): ApplicationContext is null in ApplicationStatus
,W/chromium( 3428): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3428): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3428): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3428): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/BooksSync( 3405): Starting books sync for 61035162, extras: ade
,I/NSApplication( 3428): Starting up...
,W/AudioManagerAndroid( 3428): Requires BLUETOOTH permission
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  821): Start proc 3500:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3211): IOException
E/KeepSync( 3211): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3211): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3211): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3211): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3211): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3211): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3211): 	... 10 more
W/KeepSync( 3211): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36791, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  821): Killing 2721:com.google.android.gms:car/u0a11 (adj 15): empty #17
,I/BooksConfig( 3405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): Soft error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3405): Sync error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3405): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36791, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  821): Killing 2742:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  821): Killing 2340:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 24939(1501KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 1.032ms total 25.315ms
,I/ActivityManager(  821): Start proc 3532:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver,
,I/ActivityManager(  821): Killing 1378:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  821): Killing 1771:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3549:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,E/SQLiteLog( 3549): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  821): Start proc 3574:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3549): PlayLogger.onLoggerConnected
,I/art     (  821): Explicit concurrent mark sweep GC freed 24846(1087KB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.236ms total 66.159ms
,D/TimeService( 3574): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1454090205430
D/        ( 3574): TimeServiceNative: User Time to be set is 1454090205430
D/QC-time-services( 3574): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3574): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3574): Lib:time_genoff_operation: pargs->ts_val = 1454090205430
D/QC-time-services( 3574): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  371): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  371): Daemon:Received base = 2, unit = 1, operation = 0,value = 1454090205430
D/QC-time-services(  371): Daemon:genoff_opr: Base = 2, val = 1454090205430, operation = 0
D/QC-time-services(  371): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/16/70 14:9:10
D/QC-time-services(  371): Daemon:Value read from RTC seconds = 14393350000
D/QC-time-services(  371): Daemon:new time 1454090205430 
D/QC-time-services(  371): Daemon: delta 1439696855430 genoff 1439696855430 
D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1439696855430 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  371): Updating the TOD offset
,D/QC-time-services(  371): Daemon:genoff_persistent_update: Writing genoff = 1439696855430 to memory
D/QC-time-services(  371): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  371): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  371): Daemon:Update to modem bit set
E/QC-time-services( 3574): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  371): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  371): Daemon: Base = 2, Value being sent to MODEM = 1138125405430
,I/ActivityManager(  821): Killing 2684:com.android.vending/u0a19 (adj 15): empty #17
,E/QC-time-services(  371): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  371): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40,
,I/ActivityManager(  821): Start proc 3595:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  821): Killing 3255:com.android.settings/1000 (adj 15): empty #17
,I/GAv4    ( 3595): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3595):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3595):   adb logcat -s GAv4
,W/GAv4    ( 3595): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3595): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3595): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@6ad361c}
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 15741(1238KB) AllocSpace objects, 19(304KB) LOS objects, 35% free, 28MB/44MB, paused 1.445ms total 31.764ms
,V/Herrevad( 1734): NQAS connected
,D/WifiService(  821): New client listening to asynchronous messages
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2613): UserRecoverableAuthException.
,E/Babel   ( 2613): eei: BadAuthentication
E/Babel   ( 2613): 	at eeg.a(Unknown Source)
E/Babel   ( 2613): 	at eeg.a(Unknown Source)
E/Babel   ( 2613): 	at eeg.a(Unknown Source)
E/Babel   ( 2613): 	at g.a(Unknown Source)
E/Babel   ( 2613): 	at cae.a(SourceFile:3089)
E/Babel   ( 2613): 	at cae.a(SourceFile:1131)
E/Babel   ( 2613): 	at cws.a(SourceFile:4333)
E/Babel   ( 2613): 	at cws.a(SourceFile:1419)
E/Babel   ( 2613): 	at crl.a(SourceFile:492)
E/Babel   ( 2613): 	at crl.a(SourceFile:1468)
E/Babel   ( 2613): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2613): 	at cas.b(SourceFile:106)
E/Babel   ( 2613): 	at cap.d(SourceFile:335)
E/Babel   ( 2613): 	at caq.run(SourceFile:81)
,E/Babel   ( 2613): Error getting auth token
E/Babel   ( 2613): dvm
E/Babel   ( 2613): 	at g.a(Unknown Source)
E/Babel   ( 2613): 	at cae.a(SourceFile:3089)
E/Babel   ( 2613): 	at cae.a(SourceFile:1131)
E/Babel   ( 2613): 	at cws.a(SourceFile:4333)
E/Babel   ( 2613): 	at cws.a(SourceFile:1419)
E/Babel   ( 2613): 	at crl.a(SourceFile:492)
E/Babel   ( 2613): 	at crl.a(SourceFile:1468)
E/Babel   ( 2613): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2613): 	at cas.b(SourceFile:106)
E/Babel   ( 2613): 	at cap.d(SourceFile:335)
E/Babel   ( 2613): 	at caq.run(SourceFile:81)
,E/Babel   ( 2613): Account registration failed 1-Redacted-21,
E/Babel   ( 2613): cyp: null -- null
E/Babel   ( 2613): 	at cae.a(SourceFile:3121)
E/Babel   ( 2613): 	at cae.a(SourceFile:1131)
E/Babel   ( 2613): 	at cws.a(SourceFile:4333)
E/Babel   ( 2613): 	at cws.a(SourceFile:1419)
E/Babel   ( 2613): 	at crl.a(SourceFile:492)
E/Babel   ( 2613): 	at crl.a(SourceFile:1468)
E/Babel   ( 2613): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2613): 	at cas.b(SourceFile:106)
,E/Babel   ( 2613): 	at cap.d(SourceFile:335)
E/Babel   ( 2613): 	at caq.run(SourceFile:81)
,I/art     ( 2613): Note: end time exceeds epoch: 
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1489): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2613): Unexpected exception while authenticating.
,E/Babel   ( 2613): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2613): 	at eeg.b(Unknown Source)
E/Babel   ( 2613): 	at eeg.b(Unknown Source)
E/Babel   ( 2613): 	at g.a(Unknown Source)
E/Babel   ( 2613): 	at cae.b(SourceFile:1146)
E/Babel   ( 2613): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2613): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2613): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2613): 	at java.lang.Thread.run(Thread.java:818)
,I/jxcore-log( 3101): Test app app.js loaded
I/jxcore-log( 3101): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3101): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3101): BLE advertisement is supported
I/jxcore-log( 3101): 
,I/chromium( 3101): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/GAV2    ( 3405): Thread[GAThread,5,main]: No campaign data found.
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=19.66 rxSuccessRate=20.31 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=19.66 rxSuccessRate=20.31 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GAV2    ( 3549): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  821): Killing 3273:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  821): Start proc 3643:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,D/Finsky  ( 3643): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3643): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  821): Start proc 3679:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3643): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3643): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 3679): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3679): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 3643): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3643): [370] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,D/Finsky  ( 3643): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3643): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 3679): VM with version 2.1.0 has multidex support
I/MultiDex( 3679): install
I/MultiDex( 3679): VM has multidex support, MultiDex support library is disabled.
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3643): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 3679): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3679): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1489): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Finsky  ( 3643): [370] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,D/AuthorizationBluetoothService( 1489): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1734): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  821): Start proc 3707:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1734): Restart initialization of location
,W/ResourcesManager( 3707): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3707): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3707): VM with version 2.1.0 has multidex support
I/MultiDex( 3707): install
I/MultiDex( 3707): VM has multidex support, MultiDex support library is disabled.
,I/art     (  821): Explicit concurrent mark sweep GC freed 16178(719KB) AllocSpace objects, 4(346KB) LOS objects, 32% free, 33MB/49MB, paused 1.085ms total 71.244ms
,V/JNIHelp ( 3707): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3707): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1489): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1489): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1734): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3707): callingUid 10011, callindPid: 3707
,V/Finsky  ( 3643): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/MDM     ( 1705): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1734): Restart initialization of location
,E/MDM     ( 1705): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3643): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3643): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  821): Killing 2847:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/Finsky  ( 3643): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 21670(1192KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 1.387ms total 55.823ms
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3643): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3643): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3643): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3643): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3643): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3643): [1] DailyHygiene.reschedule: Scheduling new run in 802 minutes (failures=5)
,D/DeviceConnectionService( 1705): client connected with version: 7571000,
,I/ActivityManager(  821): Killing 3350:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  821): Killing 3428:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=1.21 rxSuccessRate=4.20 targetRoamBSSID=any RSSI=-49
,E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.992117 seconds
,I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,V/GoogleAuthProtoRequest( 3185): [323] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3185): [324] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3185): [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3185): [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,I/GoogleURLConnFactory( 1489): Using platform SSLCertificateSocketFactory
,W/Uploader( 1489): No account for auth token provided
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3643): [1] 5.onFinished: Installation state replication failed.,
D/Finsky  ( 3643): [1] 5.onFinished: Scheduling replication attempt 3.
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489):  no longer exists, so no auth token.
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 28202(1347KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.569ms total 88.795ms
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1489): No account for auth token provided
,W/Uploader( 1489): No account for auth token provided
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1489): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1489): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1489): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1489): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1489): No account for auth token provided
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=20.95 rxSuccessRate=14.76 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/Keyboard.Facilitator.LanguageModelFlusher( 1214): run()
I/Keyboard.Facilitator( 1214): flushDynamicLanguageModels()
,I/ConfigService( 1489): onCreate
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3643): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3643): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ConfigService( 1489): onDestroy
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.71 rxSuccessRate=4.88 targetRoamBSSID=any RSSI=-49
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3211): Connecting to GoogleApiClient
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): 	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecut,or$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
,V/KeepSync( 3211): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 67402(3MB) AllocSpace objects, 7(424KB) LOS objects, 37% free, 27MB/43MB, paused 935us total 39.319ms
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 119670, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/BooksSync( 3405): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3405): GmsCore Version = 7.8.99 (2134222-430)
,E/KeepSync( 3211): IOException
E/KeepSync( 3211): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3211): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3211): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3211): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3211): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3211): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3211): 	... 10 more
W/KeepSync( 3211): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 121937, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3405): Soft error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3405): Sync error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3405): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 122327, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/PowerManagerService(  821): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  821): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  260): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (225 us)
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3643): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3643): [1] 5.onFinished: Scheduling replication attempt 5.
,D/SurfaceFlinger(  260): Set power mode=0, type=0 flinger=0xb6082000
I/DisplayManagerService(  821): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/qdhwcomposer(  260): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  821): Display changed displayId=0
,I/qdhwcomposer(  260): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  260): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  821): Excessive delay in setPowerMode(): 255ms
,I/DreamManagerService(  821): Entering dreamland.,
,I/PowerManagerService(  821): Dozing...
,I/DreamController(  821): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  821): cancelDelayedScan -> 8,
,E/native  (  821): do suspend false
,I/Keyboard.Facilitator( 1214): onFinishInput()
,E/WifiStateMachine(  821): cancelDelayedScan -> 10
,E/native  (  821): do suspend true
,D/audio_hw_primary(  356): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  356): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 9, 10 -> obsolete
,E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  821): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 10 -> obsolete
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3185): [325] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3185): [326] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 48444(2MB) AllocSpace objects, 15(522KB) LOS objects, 31% free, 34MB/50MB, paused 1.921ms total 78.530ms
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3185): [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3185): [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3643): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3643): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3643): [1] 5.onFinished: Giving up after 6 failures.
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406),
E/HttpOperation( 3011): 	,at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143),
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): ,	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): ,	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237),
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091),
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication,
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
,E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406),
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): 	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 209665, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1214): run()
I/Keyboard.Facilitator( 1214): flushDynamicLanguageModels()
,I/ConfigService( 1489): onCreate
,I/ConfigService( 1489): onDestroy
,I/BooksSync( 3405): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3211): Connecting to GoogleApiClient
,I/BooksConfig( 3405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
,V/KeepSync( 3211): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3405): Soft error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3405): Sync error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3405): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 213801, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3211): IOException
E/KeepSync( 3211): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3211): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3211): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3211): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3211): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3211): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3211): 	... 10 more
W/KeepSync( 3211): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 213439, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3185): [327] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3185): [328] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3185): [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3185): [328] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [328] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 51976(2MB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 27MB/43MB, paused 1.688ms total 56.945ms
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
,E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): 	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 331677, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/BooksSync( 3405): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3211): Connecting to GoogleApiClient
,I/art     (  821): Explicit concurrent mark sweep GC freed 40363(1757KB) AllocSpace objects, 9(521KB) LOS objects, 32% free, 33MB/49MB, paused 1.400ms total 79.129ms
,I/BooksConfig( 3405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): ,	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
V/KeepSync( 3211): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3405): Soft error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3405): Sync error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3405): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 369369, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/KeepSync( 3211): IOException
E/KeepSync( 3211): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3211): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3211): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3211): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3211): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3211): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3211): 	... 10 more
,W/KeepSync( 3211): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 368977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1489): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1489): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1489): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1489): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1489): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3643): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3643): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3643): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3643): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3643): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3643): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3643): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3643): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3185): [329] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3185): [330] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3185): [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3185): [330] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [330] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
,E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token,
,E/HttpOperation( 3011): ,	,at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
,E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9087)
E/HttpOperation( 3011): 	at czq.run(PG:1686),
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
,E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): 	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 332144, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
,E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
,E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): ,	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): ,	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): ,	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more,
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 607504, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/BooksSync( 3405): Starting books sync for 61035162, extras: ade
,V/KeepSync( 3211): Connecting to GoogleApiClient
,I/art     (  821): Explicit concurrent mark sweep GC freed 39452(1749KB) AllocSpace objects, 9(332KB) LOS objects, 31% free, 34MB/50MB, paused 2.013ms total 73.744ms
,I/BooksConfig( 3405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 54071(2MB) AllocSpace objects, 10(1102KB) LOS objects, 37% free, 27MB/43MB, paused 1.061ms total 38.121ms
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
,V/KeepSync( 3211): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3405): Soft error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3405): Sync error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3405): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 650955, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3211): IOException
E/KeepSync( 3211): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3211): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3211): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3211): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3211): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3211): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3211): 	... 10 more
W/KeepSync( 3211): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 650096, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception,
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	,at jdm.a(PG:82)
E/HttpOperation( 3011): 	,at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379),
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	,at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
,E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686),
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): ,	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 699220, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	,at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): 	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 853100, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3167): Stopping oneshot timer
,D/GCM     ( 1489): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3185): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova,
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3185): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3185): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3185): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110)
,V/GoogleAuthProtoRequest( 3185): [332] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ExperimentUpdateService( 3185): [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3185): [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3185): ,	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3185): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
,W/ExperimentUpdateService( 3185): 	,at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3185): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3185): 	,at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3185): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3185): ,	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3185): 	at com.a.a.k.run(SourceFile:110),
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3011): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at blb.a(PG:3937)
E/HttpOperation( 3011): 	at czp.a(PG:18188)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 12 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 14 more
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  821): Explicit concurrent mark sweep GC freed 43696(1981KB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 1.453ms total 58.418ms
,E/HttpOperation( 3011): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3011): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3011): 	at jdm.a(PG:82)
E/HttpOperation( 3011): 	at jcs.o(PG:406)
E/HttpOperation( 3011): 	at jcn.a(PG:1379)
E/HttpOperation( 3011): 	at jcs.i(PG:143)
E/HttpOperation( 3011): 	at hec.a(PG:42)
E/HttpOperation( 3011): 	at hee.a(PG:102)
E/HttpOperation( 3011): 	at czr.a(PG:65)
E/HttpOperation( 3011): 	at kka.a(PG:108)
E/HttpOperation( 3011): 	at czp.a(PG:19176)
E/HttpOperation( 3011): 	at czp.a(PG:9081)
E/HttpOperation( 3011): 	at czq.run(PG:1686)
E/HttpOperation( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3011): 	at jdj.a(PG:4091)
E/HttpOperation( 3011): 	at jdj.a(PG:1125)
E/HttpOperation( 3011): 	at jdm.a(PG:77)
E/HttpOperation( 3011): 	... 15 more
E/HttpOperation( 3011): Caused by: faj: BadAuthentication
E/HttpOperation( 3011): 	at fal.a(PG:38)
E/HttpOperation( 3011): 	at jdj.a(PG:4089)
E/HttpOperation( 3011): 	... 17 more
E/ExperimentLoader( 3011): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3011): 	at jdm.a(PG:82)
E/ExperimentLoader( 3011): 	at jcs.o(PG:406)
E/ExperimentLoader( 3011): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3011): 	at jcs.i(PG:143)
E/ExperimentLoader( 3011): 	at hec.a(PG:42)
E/ExperimentLoader( 3011): 	at hee.a(PG:102)
E/ExperimentLoader( 3011): 	at czr.a(PG:65)
E/ExperimentLoader( 3011): 	at kka.a(PG:108)
E/ExperimentLoader( 3011): 	at czp.a(PG:19176)
E/ExperimentLoader( 3011): 	at czp.a(PG:9081)
E/ExperimentLoader( 3011): 	at czq.run(PG:1686)
E/ExperimentLoader( 3011): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3011): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3011): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3011): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3011): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3011): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3011): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3011): 	at jdm.a(PG:77)
E/ExperimentLoader( 3011): 	... 15 more
E/ExperimentLoader( 3011): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3011): 	at fal.a(PG:38)
E/ExperimentLoader( 3011): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3011): 	... 17 more
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1108375, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1489): Explicit concurrent mark sweep GC freed 59717(3MB) AllocSpace objects, 9(993KB) LOS objects, 37% free, 27MB/43MB, paused 1.833ms total 48.812ms
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,V/KeepSync( 3211): Connecting to GoogleApiClient
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1734): Handling authorization failure
E/ClientConnectionOperation( 1734): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1734): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1734): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1734): 	... 7 more
,V/KeepSync( 3211): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3211): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 3211): IOException
E/KeepSync( 3211): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3211): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3211): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3211): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3211): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3211): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3211): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3211): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3211): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3211): 	... 10 more
W/KeepSync( 3211): Sync result 2
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1181185, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/BooksSync( 3405): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 3405): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1489): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1489): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1489): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1489): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1489): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3405): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3405): Soft error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 3405): Sync error
E/BooksSync( 3405): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3405): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3405): Finished books sync
,D/SyncManager(  821): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1182998, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,I/UsageStatsService(  821): User[0] Flushing usage stats to disk
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3167): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 4034): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 4034): CheckJNI is OFF
D/AndroidRuntime( 4034): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  821): Killing 3101:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  821): Skipping PackageSetting{28a6208a com.example.hello/10273} due to missing metadata
D/WifiService(  821): Client connection lost with reason: 4
I/WindowState(  821): WIN DEATH: Window{29da865 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/libprocessgroup(  821): failed to kill 1 processes for processgroup 3101
W/ActivityManager(  821): Force removing ActivityRecord{79fc259 u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
V/ActivityManager(  821): Display changed displayId=0
I/ActivityManager(  821): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  821): Spurious death for ProcessRecord{1811905d 3101:com.test.thalitest/u0a265}, curProc for 3101: null
I/Keyboard.Facilitator( 1214): resetDictionaries() : en_US
D/TaskPersister(  821): removeObsoleteFile: deleting file=28_task.xml
D/BuaReceiver( 2907): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator.DecoderInitializer( 1214): run()
I/InputReader(  821): Reconfiguring input devices.  changes=0x00000010
I/Decoder ( 1214): createOrResetDecoder
W/InputMethodManagerService(  821): Got RemoteException sending setActive(false) notification to pid 3101 uid 10265
I/Keyboard.Facilitator( 1214): onFinishInput()
I/art     ( 1066): Explicit concurrent mark sweep GC freed 66504(2MB) AllocSpace objects, 0(0B) LOS objects, 13% free, 101MB/117MB, paused 1.332ms total 64.599ms
I/art     ( 1516): Explicit concurrent mark sweep GC freed 2501(178KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 635us total 76.251ms
I/ActivityManager(  821): Start proc 4050:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
I/ConfigService( 1489): onCreate
I/art     (  821): Explicit concurrent mark sweep GC freed 28634(1607KB) AllocSpace objects, 11(364KB) LOS objects, 31% free, 34MB/50MB, paused 5.135ms total 101.969ms
I/art     (  821): WaitForGcToComplete blocked for 93.740ms for cause Explicit
I/art     (  367): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 208us total 18.292ms
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 9.464ms
I/art     ( 1307): Explicit concurrent mark sweep GC freed 4992(364KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 1.383ms total 25.939ms
I/art     (  367): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 10.288ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): run()
W/LocationOracleImpl( 1516): Best location was null
I/HotwordRecognitionRnr( 1516): Starting hotword detection.
I/MicrophoneInputStream( 1516): mic_starting com.google.android.apps.gsa.speech.audio.u@5ac4f96
I/AudioFlinger(  356): AudioFlinger's thread 0xb4fba000 ready to run
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/MicrophoneInputStream( 1516): mic_started com.google.android.apps.gsa.speech.audio.u@5ac4f96
I/Keyboard.Facilitator.MainLanguageModelLoader( 1214): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
D/audio_hw_primary(  356): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  356): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  356): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  356): enable_snd_device: snd_device(55: voice-rec-mic)
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run()
D/JobSchedulerService(  821): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = contacts
D/BackupManagerService(  821): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/audio_hw_primary(  356): enable_audio_route: apply and update mixer path: audio-record
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1214): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1214): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1214): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1214): run()
I/StatsUtilsManager( 1214): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1214): shouldRecordStats() = Too Soon
I/art     (  821): Explicit concurrent mark sweep GC freed 6170(301KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.659ms total 140.343ms
D/VoicemailCleanupService( 4050): Cleaning up data for package: com.test.thalitest
I/WebViewFactory( 1516): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/HotwordWorker( 1516): onReady
I/ContactLocale( 4050): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  821): Start proc 4090:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
D/WifiService(  821): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@52cf397}
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
I/LibraryLoader( 1516): Time to load native libraries: 1 ms (timestamps 1717-1718)
I/LibraryLoader( 1516): Expected native library version number "",actual native library version number ""
W/art     ( 1516): Attempt to remove local handle scope entry from IRT, ignoring
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660626195
E/LocSvc_IzatApiV02(  821): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
E/WifiStateMachine(  821): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=85.00 rxSuccessRate=262.50 targetRoamBSSID=any RSSI=-49
I/art     ( 4034): System.exit called, status: 0
I/AndroidRuntime( 4034): VM exiting with result code 0.
I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
I/ActivityManager(  821): Start proc 4116:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
W/ContextImpl( 4116): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
E/NetworkScheduler.SchedulerReceiver( 1489): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1489): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/art     ( 1516): Attempt to remove local handle scope entry from IRT, ignoring
E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
D/Launcher.Workspace( 1307): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1307): 11683562 - stripEmptyScreens()
D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1734): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1734): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1734): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1734): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1734): Clearing selected account for com.test.thalitest
I/UpdateIcingCorporaServi( 1516): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/Launcher( 1307): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@39d6e961 new=com.google.android.velvet.VelvetApplication@39d6e961
I/ActivityManager(  821): Start proc 4151:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
I/LocationSettingsChecker( 1734): Removing dialog suppression flag for package com.test.thalitest
I/ActivityManager(  821): Killing 3500:com.android.chrome/u0a40 (adj 15): empty #17
D/GOOGLEHELP_CompatibleDatabase( 1734): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1734): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1734): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1734): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1734): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1734): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
E/SQLiteLog( 1734): (3850) statement aborts at 21: [DELETE FROM help_responses WHERE app_package_name="com.test.thalitest"] disk I/O error
D/GOOGLEHELP_CompatibleDatabase( 1734): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
--------- beginning of crash
E/AndroidRuntime( 1734): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 1734): Process: com.google.android.gms, PID: 1734
E/AndroidRuntime( 1734): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1734): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1734): 	at com.google.android.gms.googlehelp.c.b.d(SourceFile:535)
E/AndroidRuntime( 1734): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:52)
E/AndroidRuntime( 1734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1734): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
W/ResourcesManager(  821): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  821): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/SQLiteLog( 1516): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AppDataSearchHelper( 1516): Exception thrown from onTableChanged
E/AppDataSearchHelper( 1516): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 1516): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AppDataSearchHelper( 1516): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 1516): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 1516): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 1516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 1516): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 1516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 1516): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 1516): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 1516): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 1516): 	... 16 more
W/AppDataSearchHelper( 1516): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 1516): UpdateCorporaTask done [took 193 ms] updated apps [took 193 ms] 
D/OpenGLRenderer(  821): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  821): Validating map...
E/SQLiteDatabase( 1734): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1734): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1734): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1734): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1734): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1734): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1734): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1734): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1734): Opened phenotype.db in read-only mode
W/BaseAppContext( 1734): Using Auth Proxy for data requests.
I/ConfigFetchService( 1734): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
E/SharedPreferencesImpl( 1734): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/config_removals.xml to backup file /data/data/com.google.android.gms/shared_prefs/config_removals.xml.bak
I/OpenGLRenderer(  821): Initialized EGL, version 1.4
W/BaseAppContext( 1734): Using Auth Proxy for data requests.
D/OpenGLRenderer(  821): Enabling debug mode 0
I/ConfigFetchService( 1734): service connected
E/SQLiteDatabase( 1734): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/SQLiteDatabase( 1734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/SQLiteDatabase( 1734): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/SQLiteDatabase( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1734): 	at java.lang.Thread.run(Thread.java:818)
E/ClearPendingStateOp( 1734): Runtime exception while performing operation
E/ClearPendingStateOp( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/ClearPendingStateOp( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/ClearPendingStateOp( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
E/ClearPendingStateOp( 1734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/ClearPendingStateOp( 1734): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1734): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1734): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1734): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
F/ClearPendingStateOp( 1734): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
F/ClearPendingStateOp( 1734): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
F/ClearPendingStateOp( 1734): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.i.a.delete(SourceFile:272)
F/ClearPendingStateOp( 1734): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
F/ClearPendingStateOp( 1734): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1734): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
F/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1734): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1734): 	at java.lang.Thread.run(Thread.java:818)
I/PeopleContactsSync( 1734): CP2 sync disabled
I/Icing   ( 1734): doRemovePackageData com.test.thalitest
E/DropBoxManagerService(  821): Can't write: system_app_wtf
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
I/HotwordDetector( 1516): Closing mic
I/MicrophoneInputStream( 1516): mic_close com.google.android.apps.gsa.speech.audio.u@5ac4f96
E/Search.SharedPreferencesProto( 1516): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
D/audio_hw_primary(  356): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  356): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  356): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1516): Stopping hotword detection.
I/HotwordRecognitionRnr( 1516): Hotword detection finished
I/GAv4    ( 4151): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4151):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4151):   adb logcat -s GAv4
W/GAv4    ( 4151): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4151): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4151): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4151): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4151): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4151): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4151): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4151): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4151): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4151): 	at aen.run(PG:536)
E/SQLiteDatabase( 4151): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4151): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4151): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4151): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4151): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4151): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4151): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4151): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4151): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4151): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4151): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4151): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4151): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4151): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4151): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4151): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4151): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/Search.SharedPreferencesProto( 1516): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
I/ActivityManager(  821): Killing 3574:com.qualcomm.timeservice/1000 (adj 15): empty #17
W/GAv4    ( 4151): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4151): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SQLiteDatabase( 4151): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4151): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4151): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4151): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4151): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4151): 	at aej.c(PG:139)
E/SQLiteDatabase( 4151): 	at aej.b(PG:398)
E/SQLiteDatabase( 4151): 	at agf.f(PG:417)
E/SQLiteDatabase( 4151): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4151): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4151): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AbstractDatabaseInstance( 4151): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4151): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4151): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4151): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4151): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4151): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4151): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4151): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4151): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4151): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4151): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4151): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4151): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4151): 	at java.lang.Thread.run(Thread.java:818)
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4151): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4151): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4151): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4151): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4151): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4151): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4151): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/CAKEMIX_CRASHED( 4151): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4151): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4151): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4151): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4151): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4151): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4151): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4151): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4151): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/ActivityManager(  821): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
W/ResourcesManager( 4151): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4151): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/WindowManager(  821): addAppToken: AppWindowToken{332c459d token=Token{154b3c74 ActivityRecord{3b78fc47 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
I/Process ( 4151): Sending signal. PID: 4151 SIG: 9
E/lowmemorykiller(  257): Error writing /proc/4151/oom_score_adj; errno=22
E/JavaBinder(  821): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  821): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  821): android.os.TransactionTooLargeException
W/ActivityManager(  821): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  821): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  821): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  821): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  821): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  821): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  821): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager(  821): Start proc 4203:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
W/ActivityManager(  821): Spurious death for ProcessRecord{21a364ae 4203:com.google.android.apps.docs/u0a46}, curProc for 4151: null
E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1214): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
W/OpenGLRenderer( 1307): Incorrectly called buildLayer on View: ew, destroying layer...
I/ActivityManager(  821): Start proc 4221:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
E/SQLiteDatabase( 4221): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4221): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4221): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4221): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4221): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4221): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4221): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4221): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4221): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4221): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4221): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4221): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4221): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4221): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4221): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4221): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4221): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4221): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4221): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 4221): Shutting down VM
I/ActivityManager(  821): Killing 3532:com.google.android.apps.photos/u0a71 (adj 15): empty #17
E/AndroidRuntime( 4221): FATAL EXCEPTION: main
E/AndroidRuntime( 4221): Process: com.android.documentsui, PID: 4221
E/AndroidRuntime( 4221): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4221): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4221): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4221): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4221): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4221): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4221): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4221): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4221): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4221): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4221): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4221): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4221): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4221): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4221): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4221): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4221): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4221): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4221): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4221): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4221): 	at android.app.ActivityThread.handleReceiver(ActivityThread.jav,a:2609)
E/AndroidRuntime( 4221): 	... 9 more
I/ActivityManager(  821): Start proc 4240:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
E/DropBoxManagerService(  821): Can't write: system_app_crash
E/DropBoxManagerService(  821): java.io.FileNotFoundException: /data/system/dropbox/drop100.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  821): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  821): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  821): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  821): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  821): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  821): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  821): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  821): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  821): 	... 5 more
I/ActivityManager(  821): Killing 3549:com.google.android.calendar/u0a37 (adj 15): empty #17
I/GAv4    ( 4203): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4203):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4203):   adb logcat -s GAv4
W/GAv4    ( 4203): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4203): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4203): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4203): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4203): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4203): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
D/ExternalStorage( 4240): After updating volumes, found 1 active roots
E/SQLiteDatabase( 4203): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4203): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4203): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4203): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4203): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4203): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4203): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4203): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4203): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4203): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4203): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4203): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4203): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4203): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4203): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4203): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4203): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4203): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4203): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 4203): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 4203): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4203): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4203): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4203): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4203): 	at aen.run(PG:536)
D/WifiService(  821): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@52cf397}
E/SQLiteDatabase( 4203): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4203): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4203): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4203): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4203): 	at aej.c(PG:139)
E/SQLiteDatabase( 4203): 	at aej.b(PG:398)
E/SQLiteDatabase( 4203): 	at agf.f(PG:417)
E/SQLiteDatabase( 4203): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4203): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4203): 	at java.lang.Thread.run(Thread.java:818)

```
