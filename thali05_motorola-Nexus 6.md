#### Test 613623660556c10_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GLSActivity( 1533): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1533): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1533): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1533): 	at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 2677): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2677): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2677): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2677): Ignoring header User-Agent because its value was null.
D/AndroidRuntime( 3179): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3179): CheckJNI is OFF
D/AndroidRuntime( 3179): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  822): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  822): addAppToken: AppWindowToken{27a4f435 token=Token{d05a66c ActivityRecord{3b83731f u0 com.test.thalitest/.MainActivity t34}}} to stack=1 task=34 at 0
D/AndroidRuntime( 3179): Shutting down VM
I/MicrophoneInputStream( 1486): mic_close com.google.android.apps.gsa.speech.audio.u@18f4f64e
I/HotwordDetector( 1486): Closing mic
I/ActivityManager(  822): Start proc 3195:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
V/ActivityManager(  822): Display changed displayId=0
I/HotwordRecognitionRnr( 1486): Hotword detection finished
I/HotwordRecognitionRnr( 1486): Stopping hotword detection.
I/ActivityManager(  822): Killing 2636:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1700369683
E/LocSvc_IzatApiV02(  822): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/WebViewFactory( 3195): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  822): Killing 2715:com.google.android.gms:car/u0a11 (adj 15): empty #18
,I/LibraryLoader( 3195): Time to load native libraries: 4 ms (timestamps 714-718)
,I/LibraryLoader( 3195): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3195): Binding Chromium to main looper Looper (main, tid 1) {2e9e6488}
,I/LibraryLoader( 3195): Expected native library version number "",actual native library version number ""
,I/chromium( 3195): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3195): Initializing chromium process, singleProcess=true
W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3195): ApplicationContext is null in ApplicationStatus
,W/chromium( 3195): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3195): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 3195): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3195): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3195): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  822): Message: 20,
,D/BluetoothAdapter( 3195): 713388451: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5d8807a:true
,W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3195): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3195): CordovaWebView is running on device made by: motorola
,W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 3195): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3195): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3195): Validating map...
,V/WindowManager(  822): Adding window Window{343c04a0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 7 (after Window{3e00570f u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
,W/chromium( 3195): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3195): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3195): Enabling debug mode 0
,I/ActivityManager(  822): Displayed com.test.thalitest/.MainActivity: +966ms
,I/Keyboard.Facilitator( 1221): onFinishInput()
,W/IInputConnectionWrapper( 3195): showStatusIcon on inactive InputConnection
,W/BindingManager( 3195): Cannot call determinedVisibility() - never saw a connection for the pid: 3195
,D/JsMessageQueue( 3195): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3195): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576388864
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3195): load: 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3195):     - Connection timeout in milliseconds: 15000
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3195):     - Insecure RFCOMM socket port number: -1,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3195):     - Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3195):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 3195): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15ef6c32 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Advertise mode: 2,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@112a5f39 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 3195): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  822): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3195): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3195): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 3195): setDiscoveryMode: Discovery mode BLE is supported
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3195): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3195): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 3195): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 3195): Initializing JXcore engine
W/jxcore-log( 3195): JXcore engine is ready
,W/Thread-330( 3251): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12895]" dev="sockfs" ino=12895 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-330( 3251): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-330( 3251): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[13013]" dev="sockfs" ino=13013 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-330( 3251): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21753]" dev="sockfs" ino=21753 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3195): Starting JXcore engine
,W/jxcore-log( 3195): Platform android
W/jxcore-log( 3195): 
,W/jxcore-log( 3195): Process ARCH arm
W/jxcore-log( 3195): 
,I/jxcore-log( 3195): JXcore Cordova bridge is ready!
I/jxcore-log( 3195): 
W/jxcore-log( 3195): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 3195): execute: REQUEST_ACCESS_COARSE_LOCATION
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3195): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 3195): isBleMultipleAdvertisementSupported: NOT_RESOLVED
I/jxcore-log( 3195): BLE multiple advertisement supported
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): INFO testUtils Toggling radios to: true
,I/jxcore-log( 3195): 
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
D/BluetoothManagerService(  822): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  822): Message: 1
,D/BluetoothManagerService(  822): MESSAGE_ENABLE: mBluetooth = null,
I/jxcore-log( 3195): Unit Test app is loaded
I/jxcore-log( 3195): ,
,D/WifiService(  822): setWifiEnabled: true pid=3195, uid=10265
,E/WifiService(  822): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  822): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/chromium( 3195): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/ActivityManager(  822): Start proc 3257:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
D/WifiMonitor(  822): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3256): Successfully initialized wpa_supplicant
,I/ActivityManager(  822): Start proc 3272:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3257): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3256): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  822): Start proc 3300:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  822): Killing 2805:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/AdapterServiceConfig( 3257): Adding HeadsetService
D/AdapterServiceConfig( 3257): Adding A2dpService
D/AdapterServiceConfig( 3257): Adding HidService
D/AdapterServiceConfig( 3257): Adding HealthService
,D/AdapterServiceConfig( 3257): Adding PanService,
D/AdapterServiceConfig( 3257): Adding GattService
D/AdapterServiceConfig( 3257): Adding BluetoothMapService
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bb0f6:true
D/BluetoothAdapterState( 3257): make
,I/bluedroid( 3257): init
I/BluetoothAdapterState( 3257): Entering OffState
,I/bte_conf( 3257): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3257): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3257): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3257): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3257): get_profile_interface socket
I/bluedroid( 3257): get_profile_interface map_client
I/GKI_LINUX( 3257): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3257): Address is:F8:CF:C5:D9:E5:61,
,D/BluetoothAdapterProperties( 3257): Name is: Nexus 6,
,D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6,
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3257): config_hci_snoop_log
D/BluetoothManagerService(  822): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  822): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapterState( 3257): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3257): Setting state to 11
I/BluetoothAdapterState( 3257): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  822): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3257): make
,I/BluetoothBondStateMachine( 3257): StableState(): Entering Off State
,I/BluetoothAdapterState( 3257): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
,D/HeadsetService( 3257): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3257): classInitNative: succeeds
D/HeadsetStateMachine( 3257): make
,D/HeadsetStateMachine( 3257): max_hf_connections = 1
I/bluedroid( 3257): get_profile_interface handsfree
,D/HeadsetStateMachine( 3257): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
,D/BluetoothA2dp(  822): Proxy object connected
D/BluetoothA2dp( 1073): Proxy object connected
D/A2dpService( 3257): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3257): classInitNative: succeeds,
I/bluedroid( 3257): get_profile_interface avrcp
,E/RemoteController( 3257): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3257): classInitNative: succeeds
D/A2dpStateMachine( 3257): make
,I/bluedroid( 3257): get_profile_interface a2dp,
I/GKI_LINUX( 3257): gki_task_entry task_id=2 [A2DP-MEDIA] starting,
D/A2dpStateMachine( 3257): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3257): classInitNative: succeeds
,D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
,D/BluetoothInputDevice( 1073): Proxy object connected
,D/HidService( 3257): Received start request. Starting profile...
I/bluedroid( 3257): get_profile_interface hidhost
,I/BluetoothHealthServiceJni( 3257): classInitNative: succeeds
,D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
D/HealthService( 3257): Received start request. Starting profile...
,I/bluedroid( 3257): get_profile_interface health
,I/BluetoothPanServiceJni( 3257): classInitNative(L105): succeeds
,D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
,D/BluetoothPan( 1073): BluetoothPAN Proxy object connected
,D/PanService( 3257): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3257): initializeNative(L110): pan
I/bluedroid( 3257): get_profile_interface pan
,I/BtGatt.JNI( 3257): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
D/BtGatt.DebugUtils( 3257): handleDebugAction() action=null
,D/BtGatt.GattService( 3257): Received start request. Starting profile...
D/BtGatt.GattService( 3257): start()
I/bluedroid( 3257): get_profile_interface gatt
D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
D/BtGatt.AdvertiseManager( 3257): advertise manager created
,D/BluetoothAdapterService( 3257): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@295d2246
,D/BluetoothMap( 1073): Proxy object connected
,D/BluetoothMapService( 3257): Received start request. Starting profile...
D/BluetoothMapService( 3257): start()
,D/BluetoothMapEmailSettingsLoader( 3257): Found 0 applications
D/BluetoothMapEmailAppObserver( 3257): createReceiver()
,D/BluetoothMapEmailAppObserver( 3257): initObservers()
D/BluetoothMapEmailAppObserver( 3257): getEnabledAccountItems()
,D/HeadsetStateMachine( 3257): Proxy object connected
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 3257): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/BluetoothAdapterState( 3257): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
D/HeadsetStateMachine( 3257): Disconnected process message: 11, size: 0
I/bluedroid( 3257): enable
,I/GKI_LINUX( 3257): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3257): btu_task pending for preload complete event
,I/bt_hci_bdroid( 3257): init
,I/bt_vendor( 3257): init
I/bt_vnd_conf( 3257): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3257): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3257): userial_init
,I/ActivityManager(  822): Start proc 3341:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/art     (  822): Explicit concurrent mark sweep GC freed 19826(969KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.218ms total 57.715ms
,I/ActivityManager(  822): Killing 2736:com.google.android.gm/u0a78 (adj 15): empty #17
,I/bt_userial_vendor( 3257): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3257): device fd = 53 open
D/bt_userial( 3257): Entering userial_read_thread()
,I/bt_hwcfg( 3257): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3257): Chipset BCM4354A2
,D/bt_hwcfg( 3257): Target name = [BCM4354A2],
I/bt_hwcfg( 3257): Found patchfile: /vendor/firmware//bcm4354A2.hcd,
,D/Tethering(  822): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 3256): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 3256): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  822): Loading config and enabling all networks 
,E/WifiConfigStore(  822): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/ActivityManager(  822): Killing 2309:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/WifiService(  822): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1397e62e}
,I/ActivityManager(  822): Start proc 3360:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  822): Setting external_sim to 1
D/WifiStateMachine(  822): Setting OUI to 92-68-C3
I/WifiNative-HAL(  822): startHal
D/wifi    (  822): setting scan oui 0xb4a0d460
D/WifiHAL (  822): Sending mac address OUI
,W/Settings( 2605): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/native  (  822): do suspend true
,D/WifiScanningService(  822): SCAN_AVAILABLE : 3
D/RttService(  822): SCAN_AVAILABLE : 3
,D/RttService(  822): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  822): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  822): startHal
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 326us total 18.133ms
,D/CommandListener(  354): Setting iface cfg
,D/wifi    (  822): getting scan capabilities on interface[0] = 0xb4a0d460
D/WifiHAL (  822): Creating message to get scan capablities; iface = 5
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 237us total 11.539ms
,I/wpa_supplicant( 3256): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
D/WifiHAL (  822): In GetCapabilities::handleResponse
D/WifiHAL (  822): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  822): StartedState
E/WifiP2pService(  822): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  822): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  822): p2pGetDeviceAddress
,D/WifiNative-HAL(  822): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 209us total 14.533ms
,I/bt_hwcfg( 3257): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3257): Settlement delay -- 100 ms
I/bt_hwcfg( 3257): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3257): bt vendor lib: set UART baud 3000000
,I/bt_hwcfg( 3257): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3257): vendor lib fwcfg completed
I/bt-btu  ( 3257): btu_task received preload complete event
,I/        ( 3257): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3257): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3257): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3257): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3257): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3257): BTE_InitTraceLevels -- TRC_A2D
,I/        ( 3257): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3257): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3257): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3257): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3257): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3257): BTE_InitTraceLevels -- TRC_GATT
,I/        ( 3257): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3257): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3257): BTE_InitTraceLevels -- TRC_BTIF
,D/StrictMode( 3360): StrictMode policy violation; ~duration=292 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3360): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3360): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3360): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3360): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3360): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3360): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3360): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3360): StrictMode policy violation; ~duration=291 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3360): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3360): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3360): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=289 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3360): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3360): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3360): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3360): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3360): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3360): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3360): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=285 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3360): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3360): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=278 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3360): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3360): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3360): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3360): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3360): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=196 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3360): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3360): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3360): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3360): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3360): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3360): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3360): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3360): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3360): # via Binder call with stack:
D/StrictMode( 3360): android.os.StrictMode$LogStackTrace
D/StrictMode( 3360): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3360): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3360): 	,at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3360): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3360): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3360): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3360): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3360): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3360): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3360): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3360): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3360): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3360): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3360): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3360): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3360): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3360): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3360): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3360): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3360): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3360): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3360): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3360): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3360): StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3360): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3360): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3360): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3360): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3360): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3360): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3360): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3360): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3360): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3360): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3360): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3360): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3360): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3360): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3360): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3360): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3360): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3360): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3360): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/bt-btm  ( 3257): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e82085 
,E/bt-btm  ( 3257): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e82085 
,W/com.google.a.a.a.b.a( 3360): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  822): Message: 20
,D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cea8d06:true
,I/ActivityManager(  822): Killing 2836:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/BluetoothAdapterProperties( 3257): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3257): Calling BTA_HhEnable,
E/bt-btif ( 3257): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3257): Address is:F8:CF:C5:D9:E5:61
,W/bt-btm  ( 3257): Stopping oneshot timer,
,D/AuthorizationBluetoothService( 1533): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapterProperties( 3257): Name is: Nexus 6
,D/BluetoothManagerService(  822): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  822): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3257): Scan Mode:20,
D/BluetoothAdapterProperties( 3257): Discoverable Timeout:120
,D/bte_conf( 3257): Device ID record 1 : primary
D/bte_conf( 3257):   vendorId            = 000f
D/bte_conf( 3257):   vendorIdSource      = 0001
D/bte_conf( 3257):   product             = 1200
D/bte_conf( 3257):   version             = 1436
D/bte_conf( 3257):   clientExecutableURL = 
D/bte_conf( 3257):   serviceDescription  = 
D/bte_conf( 3257):   documentationURL    = 
D/bte_conf( 3257): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3257): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3257): ScanMode =  20
D/BluetoothAdapterProperties( 3257): State =  11
D/BluetoothPanServiceJni( 3257): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/BluetoothAdapterProperties( 3257): Scan Mode:21
D/BluetoothAdapterProperties( 3257): Setting state to 12
D/BluetoothAdapterProperties( 3257): Discoverable Timeout:120
,I/BluetoothAdapterState( 3257): Bluetooth adapter state changed: 11-> 12
I/BluetoothAdapterState( 3257): Entering On State
D/BluetoothManagerService(  822): Message: 60
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  822): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothHeadset( 1073): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  822): Creating new ProfileServiceConnections object for profile: 1,
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1073): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 1073): onBluetoothStateChange: up=true
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
D/BluetoothMap( 1073): onBluetoothStateChange: up=true
,D/BluetoothA2dpSink( 1073): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1073): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothHeadsetClient( 1073): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1073): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothHeadset(  822): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1073): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1073): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothPan( 1073): onBluetoothStateChange(on) call bindService
,D/BluetoothA2dp(  822): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1268): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  822): Bluetooth State Change Intent: 11 -> 12,
,D/BluetoothMapService( 3257): onReceive
D/BluetoothManagerService(  822): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 3257): STATE_ON
D/BluetoothMapMasInstance( 3257): Map Service startRfcommSocketListener
,D/BluetoothManagerService(  822): Message: 40
D/BluetoothManagerService(  822): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3257): MAS initSocket()
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
E/bt_h4   ( 3257): vendor lib postload completed
,W/ContextImpl( 3341): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
W/BluetoothAdapter( 3257): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3257): Accepting socket connection...
,D/BluetoothManagerService(  822): Message: 20
D/BluetoothManagerService(  822): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fa419db:true
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3257): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1533): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/LocalBluetoothProfileManager( 3341): Adding local A2DP profile
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/LocalBluetoothProfileManager( 3341): Adding local HEADSET profile
W/BluetoothAdapter( 3257): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothManagerService(  822): Message: 30
,I/BtOppRfcommListener( 3257): Accept thread started.
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3341): Adding local MAP profile
,D/BluetoothMap( 3341): Create BluetoothMap proxy object
,D/BluetoothManagerService(  822): Message: 30
,D/BluetoothManagerService(  822): Message: 30
,D/LocalBluetoothProfileManager( 3341): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3341): finishStartingService: stopping service
,D/BluetoothA2dp( 3341): Proxy object connected
,D/A2dpProfile( 3341): Bluetooth service connected
,D/BluetoothInputDevice( 3341): Proxy object connected
D/HidProfile( 3341): Bluetooth service connected
,D/BluetoothPan( 3341): BluetoothPAN Proxy object connected
,D/PanProfile( 3341): Bluetooth service connected
D/BluetoothMap( 3341): Proxy object connected
D/MapProfile( 3341): Bluetooth service connected
D/BluetoothMap( 3341): getConnectedDevices()
,D/BluetoothPbap( 3341): Proxy object connected
D/PbapServerProfile( 3341): Bluetooth service connected
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 1073): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset(  822): Proxy object connected
D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset(  822): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400,
D/BluetoothHeadset( 1268): Proxy object connected
,D/BluetoothManagerService(  822): Message: 400
,D/BluetoothHeadset( 3341): Proxy object connected
D/HeadsetProfile( 3341): Bluetooth service connected
,I/wpa_supplicant( 3256): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiConfigStore(  822):  rewrite network history for "NG700"WPA_PSK
,I/jxcore-log( 3195): My device name is: motorola-Nexus 6,
,I/jxcore-log( 3195): 
,I/art     ( 1533): Explicit concurrent mark sweep GC freed 21677(1076KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 1.122ms total 30.734ms
,D/WifiService(  822): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1397e62e}
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3195): 
I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 3195): 
I/jxcore-log( 3195): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 3195): 
,I/io.jxcore.node.ConnectivityInfo( 3195): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 3195):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 3195):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 3195):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 3195):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 3195):     - BSSID name: null
I/io.jxcore.node.ConnectivityInfo( 3195):     - is connected/connecting to active network: false
I/io.jxcore.node.ConnectivityInfo( 3195):     - active network type is Wi-Fi: false
I/io.jxcore.node.ConnectivityInfo( 3195):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 3195): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,I/jxcore-log( 3195): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 3195): 
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3195): 
,I/jxcore-log( 3195): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
I/jxcore-log( 3195): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1221): run()
I/Keyboard.Facilitator( 1221): flushDynamicLanguageModels()
,I/ConfigService( 1533): onCreate
,I/ConfigService( 1533): onDestroy
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1533): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1533): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1533): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1533): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2677): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2677): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2677): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2677): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,I/EventLogService( 1741): Opted in for usage reporting
,I/EventLogService( 1741): Aggregate from 1456907662709 (log), 1456907662709 (data)
,W/EventLogAggregator( 1741): Unknown tag: snet_gcore
W/EventLogAggregator( 1741): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1741): dumping service [account]
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,I/art     (  822): Explicit concurrent mark sweep GC freed 40758(2MB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.479ms total 98.050ms
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/GLSActivity( 1533): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1533): ,	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1533): 	,at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1533): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1533): 	,at android.os.Binder.execTransact(Binder.java:446)
E/PlayEventLogger( 2677): Failed to get auth token: User intervention required. Notification has been pushed.
,E/PlayEventLogger( 2677): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867),
E/PlayEventLogger( 2677): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2677): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 2677): Ignoring header User-Agent because its value was null.
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,I/UsageStatsService(  822): User[0] Flushing usage stats to disk
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1533): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1533): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1533): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1533): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2677): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2677): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2677): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2677): Ignoring header User-Agent because its value was null.
,W/bt-btm  ( 3257): Stopping oneshot timer
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,I/art     ( 1533): Explicit concurrent mark sweep GC freed 74127(3MB) AllocSpace objects, 3(331KB) LOS objects, 36% free, 27MB/43MB, paused 1.781ms total 82.570ms
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3257): Disconnected process message: 10, size: 0
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1533): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1533): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1533): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1533): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1533): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1533): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1533): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1533): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1533): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1533): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 2677): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 2677): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 2677): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 2677): 	at android.os.Binder.execTransact(Binder.java:446)
W/System  ( 2677): Ignoring header User-Agent because its value was null.
,TIME-OUT KILL (timeout was 1200000ms)
```
