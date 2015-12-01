#### Test 519863408c638e9_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2713): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2713): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2713): [1] 5.onFinished: Scheduling replication attempt 2.
D/AndroidRuntime( 3205): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3205): CheckJNI is OFF
D/AndroidRuntime( 3205): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  823): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  823): addAppToken: AppWindowToken{72c9d14 token=Token{20b6fb67 ActivityRecord{cdf6326 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3205): Shutting down VM
V/WindowManager(  823): Adding window Window{350da4b9 u0 Starting com.test.thalitest} at 3 of 8 (after Window{36595e62 u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/HotwordDetector( 1528): Closing mic
I/MicrophoneInputStream( 1528): mic_close com.google.android.apps.gsa.speech.audio.u@7e58a13
I/ActivityManager(  823): Start proc 3219:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1528): Hotword detection finished
I/HotwordRecognitionRnr( 1528): Stopping hotword detection.
I/ActivityManager(  823): Killing 2672:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
I/art     ( 1748): Explicit concurrent mark sweep GC freed 12997(748KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 985us total 41.715ms
E/DataBuffer( 1748): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@387d7231)
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660843283
E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  876): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  876): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  876): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/ActivityManager(  823): Killing 2806:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
I/WebViewFactory( 3219): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 3219): Time to load native libraries: 2 ms (timestamps 7958-7960)
I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 3219): Binding Chromium to main looper Looper (main, tid 1) {1f2a75ed}
I/LibraryLoader( 3219): Expected native library version number "",actual native library version number ""
I/chromium( 3219): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3219): Initializing chromium process, singleProcess=true
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3219): ApplicationContext is null in ApplicationStatus
W/chromium( 3219): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3219): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3219): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3219): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16042e29:true
D/BluetoothAdapter( 3219): 130975644: getState() :  mService = null. Returning STATE_OFF
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 3219): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 3219): CordovaWebView is running on device made by: motorola
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3219): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 3219): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 3219): Validating map...
V/WindowManager(  823): Adding window Window{3d27f399 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{350da4b9 u0 Starting com.test.thalitest})
W/chromium( 3219): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  823): Explicit concurrent mark sweep GC freed 16706(815KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.395ms total 48.654ms
,I/OpenGLRenderer( 3219): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3219): Enabling debug mode 0
,I/ActivityManager(  823): Displayed com.test.thalitest/.MainActivity: +1s242ms (total +1m45s434ms)
I/Keyboard.Facilitator( 1202): onFinishInput()
,W/BindingManager( 3219): Cannot call determinedVisibility() - never saw a connection for the pid: 3219
,I/kickstart(  876): STATUS: Received file 'm9kefs2'
I/kickstart(  876): STATUS: 950272 bytes transferred in 0.991623 seconds
I/kickstart(  876): STATUS: Successfully downloaded files from target 
I/kickstart(  876): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  876): STATUS: Sahara protocol completed
,D/JsMessageQueue( 3219): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3219): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576254592
D/JX-Cordova( 3219): jxcore cordova android initializing
,W/jxcore-log( 3219): Initializing JXcore engine
W/jxcore-log( 3219): JXcore engine is ready
,W/jxcore-log( 3219): Starting JXcore engine,
,W/.test.thalitest( 3219): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[12908]" dev="sockfs" ino=12908 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3219): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
W/.test.thalitest( 3219): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[11650]" dev="sockfs" ino=11650 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 3219): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20013]" dev="sockfs" ino=20013 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,W/jxcore-log( 3219): Platform android
W/jxcore-log( 3219): ,
W/jxcore-log( 3219): Process ARCH arm
W/jxcore-log( 3219): 
,I/jxcore-log( 3219): JXcore Cordova bridge is ready!
I/jxcore-log( 3219): 
W/jxcore-log( 3219): JXcore engine is started
,I/chromium( 3219): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Choreographer( 3219): Skipped 132 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3219): Toggling radios to true
I/jxcore-log( 3219): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  823): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  823): Message: 1
,D/BluetoothManagerService(  823): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  823): New client listening to asynchronous messages
D/WifiService(  823): setWifiEnabled: true pid=3219, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
,D/SoftapController(  354): Softap fwReload - Ok
I/ActivityManager(  823): Start proc 3274:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
D/CommandListener(  354): Clearing all IP addresses on wlan0
I/jxcore-log( 3219): Radios toggled
I/jxcore-log( 3219): 
E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  823): startMonitoring(wlan0) with mConnected = false
,E/WifiHW  (  823): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,I/wpa_supplicant( 3284): Successfully initialized wpa_supplicant
,I/ActivityManager(  823): Start proc 3293:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3274): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3284): rfkill: Cannot open RFKILL control device
,D/AdapterServiceConfig( 3274): Adding HeadsetService
D/AdapterServiceConfig( 3274): Adding A2dpService
D/AdapterServiceConfig( 3274): Adding HidService
D/AdapterServiceConfig( 3274): Adding HealthService
D/AdapterServiceConfig( 3274): Adding PanService
D/AdapterServiceConfig( 3274): Adding GattService
D/AdapterServiceConfig( 3274): Adding BluetoothMapService
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a731cc2:true
,D/BluetoothAdapterState( 3274): make
,I/bluedroid( 3274): init
I/BluetoothAdapterState( 3274): Entering OffState
,I/bte_conf( 3274): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3274): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3274): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,I/bte_conf( 3274): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3274): get_profile_interface socket
I/bluedroid( 3274): get_profile_interface map_client
I/GKI_LINUX( 3274): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3274): Address is:F8:CF:C5:D9:E5:61,
D/BluetoothManagerService(  823): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  823): Message: 40
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3274): config_hci_snoop_log,
D/BluetoothManagerService(  823): Bluetooth Adapter name changed to Nexus 6
D/BluetoothAdapterProperties( 3274): Name is: Nexus 6
D/BluetoothManagerService(  823): Stored Bluetooth name: Nexus 6
,D/BluetoothManagerService(  823): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  823): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3274): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON,
D/BluetoothAdapterProperties( 3274): Setting state to 11
I/BluetoothAdapterState( 3274): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  823): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 3274): make
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 23794(1245KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.533ms total 40.634ms
,I/BluetoothAdapterState( 3274): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
,D/HeadsetService( 3274): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3274): classInitNative: succeeds
D/HeadsetStateMachine( 3274): make
,D/HeadsetStateMachine( 3274): max_hf_connections = 1
I/bluedroid( 3274): get_profile_interface handsfree
,D/HeadsetStateMachine( 3274): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
,D/BluetoothA2dp(  823): Proxy object connected
D/A2dpService( 3274): Received start request. Starting profile...
D/BluetoothA2dp( 1064): Proxy object connected
,I/BluetoothAvrcpServiceJni( 3274): classInitNative: succeeds
I/bluedroid( 3274): get_profile_interface avrcp
,E/RemoteController( 3274): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3274): classInitNative: succeeds
D/A2dpStateMachine( 3274): make
,I/bluedroid( 3274): get_profile_interface a2dp
,I/GKI_LINUX( 3274): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3274): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3274): classInitNative: succeeds
D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
,I/ActivityManager(  823): Start proc 3332:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
I/ActivityManager(  823): Killing 2839:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 8.574ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 8.745ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 8.262ms
,D/BluetoothInputDevice( 1064): Proxy object connected
D/HidService( 3274): Received start request. Starting profile...
I/bluedroid( 3274): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3274): classInitNative: succeeds
,D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
D/HealthService( 3274): Received start request. Starting profile...
,I/bluedroid( 3274): get_profile_interface health
I/BluetoothPanServiceJni( 3274): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
D/PanService( 3274): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3274): initializeNative(L110): pan
I/bluedroid( 3274): get_profile_interface pan
I/BtGatt.JNI( 3274): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
,D/BtGatt.DebugUtils( 3274): handleDebugAction() action=null
D/BtGatt.GattService( 3274): Received start request. Starting profile...
D/BtGatt.GattService( 3274): start()
I/bluedroid( 3274): get_profile_interface gatt
D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
D/BtGatt.AdvertiseManager( 3274): advertise manager created
D/BluetoothPan( 1064): BluetoothPAN Proxy object connected
D/BluetoothAdapterService( 3274): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@17509c22
D/BluetoothMap( 1064): Proxy object connected
D/BluetoothMapService( 3274): Received start request. Starting profile...
D/BluetoothMapService( 3274): start()
D/BluetoothMapEmailSettingsLoader( 3274): Found 0 applications
D/BluetoothMapEmailAppObserver( 3274): createReceiver()
D/BluetoothMapEmailAppObserver( 3274): initObservers()
D/BluetoothMapEmailAppObserver( 3274): getEnabledAccountItems()
D/HeadsetStateMachine( 3274): Proxy object connected
D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3274): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3274): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3274): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3274): enable
I/bt_hci_bdroid( 3274): init
I/GKI_LINUX( 3274): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3274): btu_task pending for preload complete event
,I/bt_vendor( 3274): init
I/bt_vnd_conf( 3274): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3274): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3274): userial_init
,I/ActivityManager(  823): Start proc 3362:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/bt_userial_vendor( 3274): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3274): device fd = 53 open
I/ActivityManager(  823): Killing 2771:com.google.android.gm/u0a78 (adj 15): empty #17
,D/bt_userial( 3274): Entering userial_read_thread()
,I/bt_hwcfg( 3274): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3274): Chipset BCM4354A2
D/bt_hwcfg( 3274): Target name = [BCM4354A2]
,I/bt_hwcfg( 3274): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/wpa_supplicant( 3284): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3284): Could not read interface p2p-dev-wlan0 flags: No such device
,D/Tethering(  823): sendTetherStateChangedBroadcast 1, 0, 0
,D/WifiConfigStore(  823): Loading config and enabling all networks 
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@243e157a}
,E/WifiConfigStore(  823): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
I/ActivityManager(  823): Killing 2352:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/bt_hwcfg( 3274): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3274): Settlement delay -- 100 ms
I/bt_hwcfg( 3274): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3274): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3274): Setting local bd addr to F8:CF:C5:D9:E5:61
,W/Settings( 2632): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  823): Setting external_sim to 1
,D/WifiStateMachine(  823): Setting OUI to 92-68-C3
I/WifiNative-HAL(  823): startHal
D/wifi    (  823): setting scan oui 0xb4b7bd30
D/WifiHAL (  823): Sending mac address OUI
,I/bt_hwcfg( 3274): vendor lib fwcfg completed
,I/bt-btu  ( 3274): btu_task received preload complete event
I/        ( 3274): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3274): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3274): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3274): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 3274): BTE_InitTraceLevels -- TRC_AVRC,
I/        ( 3274): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3274): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3274): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3274): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3274): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3274): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3274): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3274): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3274): BTE_InitTraceLevels -- TRC_BTAPP,
I/        ( 3274): BTE_InitTraceLevels -- TRC_BTIF
,I/ActivityManager(  823): Start proc 3382:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,E/WifiStateMachine(  823): cancelDelayedScan -> 1
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/CommandListener(  354): Setting iface cfg
,D/WifiScanningService(  823): SCAN_AVAILABLE : 3
D/RttService(  823): SCAN_AVAILABLE : 3
D/WifiScanningService(  823): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  823): startHal
D/RttService(  823): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  823): getting scan capabilities on interface[0] = 0xb4b7bd30
D/WifiHAL (  823): Creating message to get scan capablities; iface = 5
D/WifiHAL (  823): In GetCapabilities::handleResponse
D/WifiHAL (  823): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  823): StartedState
E/WifiP2pService(  823): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  823): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3284): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,E/native  (  823): do suspend false
,D/WifiNative-HAL(  823): p2pGetDeviceAddress
,D/WifiNative-HAL(  823): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/bt-btm  ( 3274): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2df2085 
E/bt-btm  ( 3274): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2df2085 
,D/BluetoothAdapterProperties( 3274): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3274): Calling BTA_HhEnable,
E/bt-btif ( 3274): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 3274): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3274): Name is: Nexus 6
,D/BluetoothManagerService(  823): Bluetooth Adapter name changed to Nexus 6
D/BluetoothAdapterProperties( 3274): Scan Mode:20
,D/BluetoothAdapterProperties( 3274): Discoverable Timeout:120
D/BluetoothManagerService(  823): Stored Bluetooth name: Nexus 6
,D/bte_conf( 3274): Device ID record 1 : primary,
D/bte_conf( 3274):   vendorId            = 000f
D/bte_conf( 3274):   vendorIdSource      = 0001,
D/bte_conf( 3274):   product             = 1200
,D/bte_conf( 3274):   version             = 1436
D/bte_conf( 3274):   clientExecutableURL = 
,D/bte_conf( 3274):   serviceDescription  = 
D/bte_conf( 3274):   documentationURL    = 
,D/bte_conf( 3274): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3274): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3274): ScanMode =  20,
D/BluetoothPanServiceJni( 3274): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterProperties( 3274): State =  11
,D/BluetoothAdapterProperties( 3274): Setting state to 12
I/BluetoothAdapterState( 3274): Bluetooth adapter state changed: 11-> 12
,I/BluetoothAdapterState( 3274): Entering On State
D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  823): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothAdapterProperties( 3274): Scan Mode:21
,D/BluetoothAdapterProperties( 3274): Discoverable Timeout:120
D/BluetoothHeadset( 1276): onBluetoothStateChange: up=true
,E/bt_h4   ( 3274): vendor lib postload completed,
W/bt-btm  ( 3274): Stopping oneshot timer
,D/BluetoothManagerService(  823): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothHeadset(  823): onBluetoothStateChange: up=true,
D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
D/BluetoothMap( 1064): onBluetoothStateChange: up=true
D/BluetoothA2dp(  823): onBluetoothStateChange: up=true
D/BluetoothHeadset(  823): onBluetoothStateChange: up=true
,D/BluetoothHeadset( 1064): onBluetoothStateChange: up=true
,D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=true
,E/BluetoothAvrcpController( 1064): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=true
,E/BluetoothA2dpSink( 1064): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1064): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothA2dp( 1064): onBluetoothStateChange: up=true
D/BluetoothPan( 1064): onBluetoothStateChange(on) call bindService
,W/bt-btm  ( 3274): Stopping oneshot timer
,D/BluetoothManagerService(  823): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  823): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  823): Message: 40
,D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 3274): onReceive
D/BluetoothMapService( 3274): STATE_ON
W/bt-btm  ( 3274): Stopping oneshot timer
D/BluetoothMapMasInstance( 3274): Map Service startRfcommSocketListener
,W/bt-btm  ( 3274): Stopping oneshot timer
,D/BluetoothMapMasInstance( 3274): MAS initSocket()
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3274): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3274): Accepting socket connection...,
W/bt-btm  ( 3274): Stopping oneshot timer
,W/bt-btm  ( 3274): Stopping oneshot timer
,W/bt-btm  ( 3274): Stopping oneshot timer
,D/BluetoothManagerService(  823): Message: 400
,D/BluetoothHeadset( 1276): Proxy object connected
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
,D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset(  823): Proxy object connected
D/BluetoothManagerService(  823): Message: 400
D/BluetoothHeadset( 1064): Proxy object connected
,D/StrictMode( 3382): StrictMode policy violation; ~duration=288 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3382): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3382): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3382): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3382): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3382): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3382): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3382): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3382): StrictMode policy violation; ~duration=288 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3382): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3382): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3382): 	,at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3382): StrictMode policy violation; ~duration=285 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3382): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3382): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3382): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77),
D/StrictMode( 3382): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3382): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3382): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3382): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3382): StrictMode policy violation; ~duration=240 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3382): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3382): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3382): StrictMode policy violation; ~duration=225 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3382): 	,at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3382): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3382): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3382): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3382): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	,at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3382): StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3382): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3382): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3382): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3382): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3382): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
,D/StrictMode( 3382): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3382): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3382): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3382): # via Binder call with stack:
D/StrictMode( 3382): android.os.StrictMode$LogStackTrace
D/StrictMode( 3382): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3382): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3382): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3382): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3382): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3382): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 3382): 	at com.google.android.c.c.a(PG:87),
D/StrictMode( 3382): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3382): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3382): StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3382): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3382): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3382): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3382): 	,at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3382): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3382): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012),
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3382): StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3382): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3382): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3382): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3382): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	,at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3382): StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3382): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3382): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3382): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3382): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
,D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3382): StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3382): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3382): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3382): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3382): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3382): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3382): 	,at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3382): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3382): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3382): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3382): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3382): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3382): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3382): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3382): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3382): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3382): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3382): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364),
D/StrictMode( 3382): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3382): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3382): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3382): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3382): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/com.google.a.a.a.b.a( 3382): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23f2e291:true
,I/ActivityManager(  823): Killing 2873:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1503): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3362): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3219): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): my name is : motorola-Nexus 6_PT3700
,I/jxcore-log( 3219): 
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e90adce:true
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3274): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1503): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3274): getBluetoothService() called with no BluetoothManagerCallback
D/LocalBluetoothProfileManager( 3362): Adding local A2DP profile
,I/BtOppRfcommListener( 3274): Accept thread started.
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3362): Adding local HEADSET profile
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 3362): Adding local MAP profile
D/BluetoothMap( 3362): Create BluetoothMap proxy object
,D/BluetoothManagerService(  823): Message: 30
,D/BluetoothManagerService(  823): Message: 30
,I/jxcore-log( 3219): attempting to connect to test coordinator
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): check test folder
I/jxcore-log( 3219): 
,D/LocalBluetoothProfileManager( 3362): LocalBluetoothProfileManager construction complete
,I/jxcore-log( 3219): found test : ./testFindPeers.js
I/jxcore-log( 3219): 
,D/DockEventReceiver( 3362): finishStartingService: stopping service
,D/BluetoothA2dp( 3362): Proxy object connected
,D/A2dpProfile( 3362): Bluetooth service connected
,D/BluetoothInputDevice( 3362): Proxy object connected
D/HidProfile( 3362): Bluetooth service connected
,D/BluetoothPan( 3362): BluetoothPAN Proxy object connected
,D/PanProfile( 3362): Bluetooth service connected
D/BluetoothMap( 3362): Proxy object connected
D/MapProfile( 3362): Bluetooth service connected
D/BluetoothMap( 3362): getConnectedDevices()
,D/BluetoothPbap( 3362): Proxy object connected
,D/PbapServerProfile( 3362): Bluetooth service connected
,I/jxcore-log( 3219): found test : ./testReConnect.js
I/jxcore-log( 3219): ,
,I/jxcore-log( 3219): found test : ./testSendData.js
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Test app app.js loaded
,I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3219): 
,I/Choreographer( 3219): Skipped 132 frames!  The application may be doing too much work on its main thread.
,I/chromium( 3219): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  823): Message: 400
,D/BluetoothHeadset( 3362): Proxy object connected
,D/HeadsetProfile( 3362): Bluetooth service connected
,I/wpa_supplicant( 3284): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  823): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  823):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  823):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
E/WifiConfigStore(  823): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,E/WifiStateMachine(  823): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  823): will read network variables netId=0
,I/wpa_supplicant( 3284): wlan0: Trying to associate with SSID 'NG7005g'
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/wpa_supplicant( 3284): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3284): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3284): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  823): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  823): Start Dhcp Watchdog 1
,E/WifiStateMachine(  823):  WifiLinkLayerStats: 
,E/WifiStateMachine(  823):  my bss beacon rx: 1
E/WifiStateMachine(  823):  RSSI mgmt: -46
E/WifiStateMachine(  823):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  823):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  VI :  rx=0 tx=0 lost=0 retries=0
,E/WifiStateMachine(  823):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  823):  on_time : 0 tx_time=58 rx_time=167 scan_time=0
,D/ConnectivityService(  823): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  823): do suspend false
,E/WifiStateMachine(  823): scanCount==0 - aborting
,I/dhcpcd  ( 3424): version 5.5.6 starting
,I/dhcpcd  ( 3424): wlan0: rebinding lease of 192.168.1.110
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/dhcpcd  ( 3424): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3424): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  823): Adding iface wlan0 to network 100
,E/WifiStateMachine(  823): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  823): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  823): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  823): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,D/ConnectivityService(  823): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  823): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  823): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  823): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823):    accepting network in place of null
,D/ConnectivityService(  823): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  823): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,D/CSLegacyTypeTracker(  823): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,V/BackupManagerService(  823): Scheduling immediate backup pass
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  823): getDataEnabled: retVal=false
,I/ActivityManager(  823): Start proc 3461:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver
,V/BackupManagerService(  823): Running a backup pass
V/BackupManagerService(  823): clearing pending backups
,D/NetworkChangeNotifierAutoDetect( 1528): Network connectivity changed, type is: 2
E/GpsLocationProvider(  823): No APN found to select.
,V/PerformBackupTask(  823): Beginning backup of 14 targets
,D/AlarmManagerService(  823): Setting time of day to sec=1448966980
W/AlarmManagerService(  823): Unable to set rtc to 1448966980: Invalid argument
,D/PerformBackupTask(  823): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  823): doBackup() invoked
,I/PMBA    (  823): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 01 Dec 2015 10:49:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448966980201], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448966980184]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Validated
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  823): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  823): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524290
,I/ConfigFetchService( 1782): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,D/GpsLocationProvider(  823): NTP server returned: 1448966980161 (Tue Dec 01 11:49:40 GMT+01:00 2015) reference: 146816 certainty: 5 system time offset: -72
,I/ConfigFetchService( 1782): running network task: configservice_periodic
,E/WakeLock( 1782): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1782): launchTask
,I/BackupRestoreController(  823): Getting widget state for user: 0
,I/GoogleURLConnFactory( 1503): Using platform SSLCertificateSocketFactory
,I/MusicStore( 3461): Database version: 120
,I/art     (  823): Explicit concurrent mark sweep GC freed 50152(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.341ms total 68.214ms
,I/ConfigService( 1503): onCreate
,W/GmsBackupTransport( 1748): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1748): starting performBackup for @pm@
,V/GmsBackupTransport( 1748): performBackup done for @pm@
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1782): [CredentialSyncAdapter] Unknown sync event.
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 14612(800KB) AllocSpace objects, 2(32KB) LOS objects, 37% free, 26MB/42MB, paused 2.292ms total 44.418ms
,W/DriveInitializer( 1782): Background init thread started
,I/ConfigFetchService( 1782): service connected
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ConfigFetchService( 1782): ConfigApi connection successful.
,W/GmsBackupTransport( 1748): Error sending final backup to server: 
W/GmsBackupTransport( 1748): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1748): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1748): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1748): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1748): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1748): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1748): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1748): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1748): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1748): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1748): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1748): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1748): 	... 1 more
D/BackupManagerService(  823): Now staging backup of com.google.android.talk
,W/DriveInitializer( 1782): Awaiting to be initialized
,D/BackupManagerService(  823): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  823): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  823): Now staging backup of com.android.sharedstoragebackup
W/ResourcesManager( 3461): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3461): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  823): Now staging backup of com.google.android.gm
,D/BackupManagerService(  823): Now staging backup of com.android.providers.userdictionary
,W/DriveInitializer( 1782): Background init thread ended
,D/BackupManagerService(  823): Now staging backup of com.android.nfc
,D/BackupManagerService(  823): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  823): Now staging backup of com.google.android.marvin.talkback
,V/JNIHelp ( 3461): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/BackupManagerService(  823): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  823): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  823): Now staging backup of com.android.vending
,D/BackupManagerService(  823): Now staging backup of android
,D/BackupManagerService(  823): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1748): Next backup will happen in 43199871 millis.
,I/BackupManagerService(  823): Backup pass finished.
,I/ProviderInstaller( 3461): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3461): GMSCore installation verified
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ConfigStore( 3461): Config Database version: 1
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2983): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2983): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2983): 	at jdm.a(PG:82)
E/HttpOperation( 2983): 	at jcs.o(PG:406)
E/HttpOperation( 2983): 	at jcn.a(PG:1379)
E/HttpOperation( 2983): 	at jcs.i(PG:143)
E/HttpOperation( 2983): 	at blb.a(PG:3937)
E/HttpOperation( 2983): 	at czp.a(PG:18188)
E/HttpOperation( 2983): 	at czp.a(PG:9081)
E/HttpOperation( 2983): 	at czq.run(PG:1686)
E/HttpOperation( 2983): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2983): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2983): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2983): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2983): 	at jdj.a(PG:4091)
E/HttpOperation( 2983): 	at jdj.a(PG:1125)
E/HttpOperation( 2983): 	at jdm.a(PG:77)
E/HttpOperation( 2983): 	... 12 more
E/HttpOperation( 2983): Caused by: faj: BadAuthentication
E/HttpOperation( 2983): 	at fal.a(PG:38)
E/HttpOperation( 2983): 	at jdj.a(PG:4089)
E/HttpOperation( 2983): 	... 14 more
,I/ActivityManager(  823): Start proc 3521:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2983): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2983): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2983): 	at jdm.a(PG:82)
E/HttpOperation( 2983): 	at jcs.o(PG:406)
E/HttpOperation( 2983): 	at jcn.a(PG:1379)
E/HttpOperation( 2983): 	at jcs.i(PG:143)
E/HttpOperation( 2983): 	at hec.a(PG:42)
E/HttpOperation( 2983): 	at hee.a(PG:102)
E/HttpOperation( 2983): 	at czr.a(PG:65)
E/HttpOperation( 2983): 	at kka.a(PG:108)
E/HttpOperation( 2983): 	at czp.a(PG:19176)
E/HttpOperation( 2983): 	at czp.a(PG:9081)
E/HttpOperation( 2983): 	at czq.run(PG:1686)
E/HttpOperation( 2983): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2983): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2983): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2983): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2983): 	at jdj.a(PG:4091)
E/HttpOperation( 2983): 	at jdj.a(PG:1125)
E/HttpOperation( 2983): 	at jdm.a(PG:77)
E/HttpOperation( 2983): 	... 15 more
E/HttpOperation( 2983): Caused by: faj: BadAuthentication
E/HttpOperation( 2983): 	at fal.a(PG:38)
E/HttpOperation( 2983): 	at jdj.a(PG:4089)
E/HttpOperation( 2983): 	... 17 more
E/ExperimentLoader( 2983): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2983): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2983): 	at jdm.a(PG:82)
E/ExperimentLoader( 2983): 	at jcs.o(PG:406)
E/ExperimentLoader( 2983): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2983): 	at jcs.i(PG:143)
E/ExperimentLoader( 2983): 	at hec.a(PG:42)
E/ExperimentLoader( 2983): 	at hee.a(PG:102)
E/ExperimentLoader( 2983): 	at czr.a(PG:65)
E/ExperimentLoader( 2983): 	at kka.a(PG:108)
E/ExperimentLoader( 2983): 	at czp.a(PG:19176)
E/ExperimentLoader( 2983): 	at czp.a(PG:9081)
E/ExperimentLoader( 2983): 	at czq.run(PG:1686)
E/ExperimentLoader( 2983): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2983): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2983): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2983): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2983): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2983): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2983): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2983): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2983): 	at jdm.a(PG:77)
E/ExperimentLoader( 2983): 	... 15 more
E/ExperimentLoader( 2983): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2983): 	at fal.a(PG:38)
E/ExperimentLoader( 2983): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2983): 	... 17 more
,I/MediaRouter( 3461): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3461): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3461): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 3461): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  823): Start proc 3545:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,I/ActivityManager(  823): Start proc 3562:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 37502, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/GHttpClientFactory( 3461): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ResourcesManager( 3545): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3545): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GoogleURLConnFactory( 3461): Using platform SSLCertificateSocketFactory
,D/SprintDMReceiver( 3562): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,V/JNIHelp ( 3545): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3545): Installed default security provider GmsCore_OpenSSL
,D/SprintDMHelper( 3562): simOperator:  IMSI: null
,D/SprintDMReceiver( 3562): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/CheckinService( 1782): Checking schedule, now: 1448966981152 next: 1448918066205
I/CheckinService( 1782): active receiver: enabled
,I/ValidateNoPeople(  823): skipping global notification
,I/CheckinService( 1782): Preparing to send checkin request
I/EventLogService( 1782): Accumulating logs since 1448966798163
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599940 ms
,I/iu.SyncManager( 1782): SYNC; picasa accounts
,D/NetworkLogImpl( 1782): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/SystemUpdateService( 1782): onDestroy
V/KeepSync( 3332): Connecting to GoogleApiClient
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/YouTube MDX( 3545): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/EventLogService( 1782): Opted in for usage reporting
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/GAV2    ( 3521): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GcmGroups( 1782): Failed to subscribe to group.
I/GcmGroups( 1782): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1782): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1782): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1782): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1782): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1782): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1782): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 1782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/iu.UploadsManager( 1782): num queued entries: 0
I/iu.UploadsManager( 1782): num updated entries: 0
I/iu.SyncManager( 1782): NEXT; no task
,I/ActivityManager(  823): Start proc 3622:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GcmGroups( 1782): Groups upload failed, retrying in 24000:00:00
,I/BooksApp( 3521): Created application version: 3.6.8 (30608)
,I/dex2oat ( 3604): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads107547702.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads107547702.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 22441(1326KB) AllocSpace objects, 2(55KB) LOS objects, 37% free, 26MB/42MB, paused 1.887ms total 25.677ms
,I/art     (  823): Explicit concurrent mark sweep GC freed 28804(1336KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.175ms total 56.498ms
,I/Babel   ( 2632): connection state changed from DISCONNECTED to CONNECTED
,I/dex2oat ( 3604): dex2oat took 48.739ms (threads: 4) arena alloc=135KB java alloc=12KB native alloc=1223KB free=6MB
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/Kids    ( 1782): [AccountUtils] Account not ready
W/Kids    ( 1782): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1782): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1782): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1782): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1782): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1782): 	at java.lang.Thread.run(Thread.java:818)
I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1782): Handling authorization failure
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
,D/GCM     ( 1503): Connected
,V/KeepSync( 3332): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 3332): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3332): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3332): (284) automatic index on blob_node(is_deleted)
,W/InstanceID/Rpc( 3545): Found 10011
,I/BooksSync( 3521): Starting books sync for 61035162, extras: ade
,D/GCM     ( 1503): Message class com.google.f.a.a.p
,W/EventLogAggregator( 1782): Unknown tag: snet_gcore
W/EventLogAggregator( 1782): Unknown tag: snet_launch_service
,I/GAv4    ( 3622): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3622):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3622):   adb logcat -s GAv4
,W/GAv4    ( 3622): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3622): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3622): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 1782): Explicit concurrent mark sweep GC freed 14990(1179KB) AllocSpace objects, 16(256KB) LOS objects, 35% free, 29MB/45MB, paused 3.374ms total 45.604ms
,I/CheckinRequestBuilder( 1782): Checkin reason type: 12 attempt count: 1
,D/WifiService(  823): New client listening to asynchronous messages
,E/ActivityThread( 1782): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 3521): GmsCore Version = 7.8.99 (2134222-430)
,I/jxcore-log( 3219): BLE supported!!
I/jxcore-log( 3219): 
,E/KeepSync( 3332): IOException
E/KeepSync( 3332): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3332): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3332): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3332): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3332): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3332): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3332): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3332): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3332): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3332): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3332): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3332): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3332): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3332): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3332): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3332): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3332): 	... 10 more
W/KeepSync( 3332): Sync result 2
,I/WebViewFactory( 3622): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Killing 2925:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/LibraryLoader( 3622): Time to load native libraries: 3 ms (timestamps 8372-8375)
I/LibraryLoader( 3622): Expected native library version number "",actual native library version number ""
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 37505, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/WebViewChromiumFactoryProvider( 3622): Binding Chromium to main looper Looper (main, tid 1) {dc37f56}
,I/LibraryLoader( 3622): Expected native library version number "",actual native library version number ""
,I/chromium( 3622): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3622): Initializing chromium process, singleProcess=true
,W/art     ( 3622): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3622): ApplicationContext is null in ApplicationStatus
,W/chromium( 3622): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3622): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3622): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3622): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/NSApplication( 3622): Starting up...
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/AudioManagerAndroid( 3622): Requires BLUETOOTH permission
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleURLConnFactory( 1782): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  823): Killing 1436:android.process.acore/u0a5 (adj 15): empty #17
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3521): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3521): Soft error
E/BooksSync( 3521): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3521): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3521): Sync error
E/BooksSync( 3521): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3521): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3521): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 37505, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 3096:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Start proc 3751:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,I/ActivityManager(  823): Start proc 3769:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/art     (  823): Explicit concurrent mark sweep GC freed 20115(835KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.217ms total 58.507ms
,E/SQLiteLog( 3751): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  823): Start proc 3790:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,W/SubscribedFeeds( 1782): Hard error
,W/ResourcesManager( 3790): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/CheckinRequestBuilder( 1782): awaiting user notification for token
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 41841, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,V/GoogleAuthProtoRequest( 3293): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 180339, reason: Periodic
,I/CalendarProvider2( 3790): Created com.android.providers.calendar.CalendarAlarmManager@10bdbc04(com.android.providers.calendar.CalendarProvider2@1f2a75ed)
,I/ActivityManager(  823): Start proc 3811:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 10.853ms
,I/AnalyticsLogBase( 3751): PlayLogger.onLoggerConnected
,I/AnalyticsLogBase( 3751): PlayLogger.onLoggerConnected
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 217us total 11.180ms
,W/ResourcesManager( 3811): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3811): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 206us total 9.629ms
,I/MultiDex( 3811): VM with version 2.1.0 has multidex support
,I/MultiDex( 3811): install
I/MultiDex( 3811): VM has multidex support, MultiDex support library is disabled.
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 3811): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 28317(1556KB) AllocSpace objects, 5(362KB) LOS objects, 36% free, 27MB/43MB, paused 834us total 24.739ms
,I/ProviderInstaller( 3811): Installed default security provider GmsCore_OpenSSL
,W/ExperimentUpdateService( 3293): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3293): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3293): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3293): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3293): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3293): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3293): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3293): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3293): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3293): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3293): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3293): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  823): Killing 3119:com.android.musicfx/u0a18 (adj 15): empty #17
,W/ResourcesManager( 3751): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3751): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GCoreUlr( 1748): Uploading GCM registration ID for account#2#
,V/JNIHelp ( 3751): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/WVCdm   (  358): Instantiating CDM.
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,W/BaseAppContext( 1748): Using Auth Proxy for data requests.
,I/ProviderInstaller( 3751): Installed default security provider GmsCore_OpenSSL
,W/AbstractGoogleClient( 3751): Application name is not set. Call Builder#setApplicationName.
,I/GoogleURLConnFactory( 3811): Using platform SSLCertificateSocketFactory
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/GLSUser ( 1748): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1748): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Killing 1820:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/ActivityManager(  823): Start proc 3847:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,E/GCoreUlr( 1748): 
E/GCoreUlr( 1748): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1748): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1748): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1748): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1748): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1748): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1748): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1748): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1748): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1748): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1748): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1748): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1748): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1748): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1748): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1748): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 41852, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 180403, reason: Periodic
,D/TimeService( 3847): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448966983107
D/        ( 3847): TimeServiceNative: User Time to be set is 1448966983107
D/QC-time-services( 3847): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3847): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3847): Lib:time_genoff_operation: pargs->ts_val = 1448966983107
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448966983107
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1448966983107, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/18/70 7:2:41
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 9270161000
D/QC-time-services(  373): Daemon:new time 1448966983107 
D/QC-time-services(  373): Daemon: delta 1439696822107 genoff 1439696822107 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696822107 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services( 3847): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  373): Updating the TOD offset
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696822107 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1133002183107
,E/QC-time-services( 3847): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  823): Killing 3147:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1448966983
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 152379790
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1448966983; nsec = 152379790
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xb3f01940
,D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb4c4e348, dataLength=8
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4cd1000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec40, idLength=0xb3e03710
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
,D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
,D/WVCdm   (  358): PrepareKeyRequest: nonce=130683105
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4020600
D/DrmWidevineDash(  358): message_length=1598, signature=0xb58809c0, signature_length=3017815796
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  823): Start proc 3869:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/ActivityManager(  823): Start proc 3887:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,E/CalendarSyncAdapter( 3751): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 3751): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 3751): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 3751): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 3751): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 3751): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 3751): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 3751): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 3751): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
E/CalendarSyncAdapter( 3751): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
E/CalendarSyncAdapter( 3751): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
E/CalendarSyncAdapter( 3751): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
E/CalendarSyncAdapter( 3751): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
E/CalendarSyncAdapter( 3751): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 3751): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 3751): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 3751): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 3751): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 3751): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 3751): 	... 12 more
,I/GAv4    ( 3869): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3869):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3869):   adb logcat -s GAv4
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 41850, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 183026, reason: Periodic
,I/CalendarProvider2( 3790): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3790): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  823): Killing 3047:com.android.defcontainer/u0a7 (adj 15): empty #17
,I/Gmail   ( 3887): getAccountsCursor
,D/ActivityThread( 3887): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  823): Start proc 3910:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,I/ActivityManager(  823): Killing 2713:com.android.vending/u0a19 (adj 15): empty #17
,I/art     (  823): Explicit concurrent mark sweep GC freed 20760(906KB) AllocSpace objects, 4(346KB) LOS objects, 32% free, 33MB/49MB, paused 1.467ms total 85.623ms
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11,
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,W/GAv4    ( 3869): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3869): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3869): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/GAV2    ( 3887): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  823): Start proc 3937:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,W/ActivityManager(  823): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 3910): EasService.onCreate
,I/Exchange( 3910): RestartPingTask
,W/Gmail   ( 3887): Sync started for account: account:61035162
I/Gmail   ( 3887): Observing account changes for notifications
,I/Gmail   ( 3887): getAccountsCursor
,I/ActivityManager(  823): Killing 3362:com.android.settings/1000 (adj 15): empty #17
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ContactLocale( 3937): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[@@    ] SyncAdapterProxy( 1503): Delagator disabled, using the (deprecated) GData sync adapter
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b83000
,I/Exchange( 3910): RestartPingsTask did not start any pings.
,I/Exchange( 3910): PSS stopIfIdle
I/Exchange( 3910): PSS has no active accounts; stopping service.
,D/DrmLibTime(  313): got the req here! ret=0
,D/DrmLibTime(  313): command id, time_cmd_id = 770
,D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1448966983
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 911174217
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1448966983; nsec = 911174217
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/GCM     ( 1503): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
V/Herrevad( 1782): NQAS connected
D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,I/Exchange( 3910): onDestroy
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xbed6a520
D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb4c4e348, dataLength=8
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb400b000, wrapped_rsa_key_length=1280
D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@243e157a}
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
,I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb583ec80, idLength=0xbed6a2f0
,D/AuthorizationBluetoothService( 1503): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1782): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=1675820001
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4020d00
D/DrmWidevineDash(  358): message_length=1634, signature=0xb5880380, signature_length=3201737428
D/GCM     ( 1503): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/SQLiteLog( 3887): (283) recovered 15 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  823): Start proc 3980:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1782): Restart initialization of location
,V/GoogleAuthProtoRequest( 3293): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,W/ResourcesManager( 3980): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3980): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/MultiDex( 3980): VM with version 2.1.0 has multidex support
I/MultiDex( 3980): install
,I/MultiDex( 3980): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3980): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/dex2oat ( 4003): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ProviderInstaller( 3980): Installed default security provider GmsCore_OpenSSL
,I/Gmail   ( 3887): notifyAccountChanged
,I/dex2oat ( 4003): dex2oat took 39.816ms (threads: 4) arena alloc=108KB java alloc=18KB native alloc=1115KB free=6MB
I/Gmail   ( 3887): getAccountsCursor
,I/Adreno  ( 3811): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/WearableService( 3980): callingUid 10011, callindPid: 3980
,I/Gmail   ( 3887): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 16079(810KB) AllocSpace objects, 13(1433KB) LOS objects, 37% free, 26MB/42MB, paused 1.807ms total 33.651ms
,E/MDM     ( 1748): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3887): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Gmail   ( 3887): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 3887): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Adreno  ( 3811): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2632): UserRecoverableAuthException.
E/Babel   ( 2632): eei: BadAuthentication
E/Babel   ( 2632): 	at eeg.a(Unknown Source)
E/Babel   ( 2632): 	at eeg.a(Unknown Source)
E/Babel   ( 2632): 	at eeg.a(Unknown Source)
E/Babel   ( 2632): 	at g.a(Unknown Source)
E/Babel   ( 2632): 	at cae.a(SourceFile:3089)
E/Babel   ( 2632): 	at cae.a(SourceFile:1131)
E/Babel   ( 2632): 	at cws.a(SourceFile:4333)
E/Babel   ( 2632): 	at cws.a(SourceFile:1419)
E/Babel   ( 2632): 	at crl.a(SourceFile:492)
E/Babel   ( 2632): 	at crl.a(SourceFile:1468)
E/Babel   ( 2632): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2632): 	at cas.b(SourceFile:106)
E/Babel   ( 2632): 	at cap.d(SourceFile:335)
E/Babel   ( 2632): 	at caq.run(SourceFile:81)
E/Babel   ( 2632): Error getting auth token
E/Babel   ( 2632): dvm
E/Babel   ( 2632): 	at g.a(Unknown Source)
E/Babel   ( 2632): 	at cae.a(SourceFile:3089)
E/Babel   ( 2632): 	at cae.a(SourceFile:1131)
E/Babel   ( 2632): 	at cws.a(SourceFile:4333)
E/Babel   ( 2632): 	at cws.a(SourceFile:1419)
E/Babel   ( 2632): 	at crl.a(SourceFile:492)
E/Babel   ( 2632): 	at crl.a(SourceFile:1468)
E/Babel   ( 2632): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2632): 	at cas.b(SourceFile:106)
E/Babel   ( 2632): 	at cap.d(SourceFile:335)
E/Babel   ( 2632): 	at caq.run(SourceFile:81)
,E/Babel   ( 2632): Account registration failed 1-Redacted-21
E/Babel   ( 2632): cyp: null -- null
E/Babel   ( 2632): 	at cae.a(SourceFile:3121)
E/Babel   ( 2632): 	at cae.a(SourceFile:1131)
E/Babel   ( 2632): 	at cws.a(SourceFile:4333)
E/Babel   ( 2632): 	at cws.a(SourceFile:1419)
E/Babel   ( 2632): 	at crl.a(SourceFile:492)
E/Babel   ( 2632): 	at crl.a(SourceFile:1468)
E/Babel   ( 2632): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2632): 	at cas.b(SourceFile:106)
E/Babel   ( 2632): 	at cap.d(SourceFile:335)
E/Babel   ( 2632): 	at caq.run(SourceFile:81)
,I/Gmail   ( 3887): notifyAccountChanged
,I/art     ( 2632): Note: end time exceeds epoch: 
,W/ExperimentUpdateService( 3293): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3293): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3293): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3293): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3293): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3293): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3293): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3293): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3293): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3293): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3293): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3293): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 1782): Opted in for usage reporting
,I/art     (  823): Explicit concurrent mark sweep GC freed 13406(600KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.398ms total 50.036ms
,D/GCM     ( 1503): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1503): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1782): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1748): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1782): Restart initialization of location
,W/ResourcesManager( 1503): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 1503): innerSync failed
D/ContactsSyncAdapter( 1503): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1503): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1503): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1503): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1503): 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
D/ContactsSyncAdapter( 1503): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1503): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1503): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1503): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
D/ContactsSyncAdapter( 1503): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1503): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
D/ContactsSyncAdapter( 1503): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,E/Babel   ( 2632): Unexpected exception while authenticating.
E/Babel   ( 2632): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2632): 	at eeg.b(Unknown Source)
E/Babel   ( 2632): 	at eeg.b(Unknown Source)
E/Babel   ( 2632): 	at g.a(Unknown Source)
E/Babel   ( 2632): 	at cae.b(SourceFile:1146)
E/Babel   ( 2632): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2632): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2632): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2632): 	at java.lang.Thread.run(Thread.java:818)
,I/Gmail   ( 3887): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 41860, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 181252, reason: Periodic
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1782): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/Gmail   ( 3887): getAccountsCursor
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1782): Explicit concurrent mark sweep GC freed 17577(1081KB) AllocSpace objects, 9(144KB) LOS objects, 35% free, 29MB/45MB, paused 1.008ms total 30.176ms
,W/ResourcesManager( 3887): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3887): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3887): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3887): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ReminderSync( 1782): AuthError [T SyncAdapterThread-1:id=236:priority=5:group=main]
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 41862, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 182910, reason: Periodic
,I/SyncAdapterService( 3622): Ignoring sync request for non-current account
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 28224(1619KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 27MB/43MB, paused 793us total 28.299ms
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Gmail   ( 3887): notifyAccountChanged
,I/Gmail   ( 3887): getAccountsCursor
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinTask( 1782): Sending checkin request (9911 bytes)
,I/Gmail   ( 3887): notifyAccountChanged
,W/Gmail   ( 3887): Sync complete for account: account:61035162
I/Gmail   ( 3887): getAccountsCursor
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 41855, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 184229, reason: Periodic
,I/ActivityManager(  823): Killing 3382:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,D/DelayedSyncController( 1230): Delaying sync.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,I/GHttpClientFactory( 3461): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3461): Using platform SSLCertificateSocketFactory
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,I/MusicLifecycle( 3461): Sync started
,E/SQLiteLog( 3790): (284) automatic index on view_events(_id)
,I/ActivityManager(  823): Start proc 4047:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,I/CheckinResponseProcessor( 1782): From server: 1 gservices updates and 0 deletes
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 29026(1284KB) AllocSpace objects, 2(32KB) LOS objects, 32% free, 33MB/49MB, paused 1.100ms total 66.802ms
,I/CertBlacklister(  823): Certificate blacklist changed, updating...
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,I/CertBlacklister(  823): Certificate blacklist updated
,I/GservicesProvider( 1503): main difference update completed
,I/MusicLifecycle( 3461): Sync ended
W/MusicSyncAdapter( 3461): Sync failed due to an authentication issue.
,I/CheckinRequestBuilder( 1782): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1782): Failed to find provider info for com.google.android.wearable.settings
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 41872, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  823): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 185073, reason: Periodic
,I/ActivityManager(  823): Start proc 4070:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,W/Telecom (  823): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 2632): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2632): BAM#gBA: invalid account id: -1
W/Babel   ( 2632): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2632): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,I/ActivityManager(  823): Start proc 4088:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,I/MusicLeanback( 3461): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3461): Stop autocaching.
I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 4047): Sync request not initiated by GCP app. Dropping
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 16612(832KB) AllocSpace objects, 9(992KB) LOS objects, 37% free, 26MB/42MB, paused 865us total 25.218ms
,I/ActivityManager(  823): Killing 1528:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  823): Client connection lost with reason: 4
,I/ActivityManager(  823): Start proc 4122:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  823): Killing 3562:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,E/Auth.Api.Credentials( 1782): [CredentialSyncAdapter] Unknown sync event.
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=57.66 rxSuccessRate=60.69 targetRoamBSSID=any RSSI=-47
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=57.66 rxSuccessRate=60.69 targetRoamBSSID=any RSSI=-47
,E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,E/UpdateRequestReceiver( 4122): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4122): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4122): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4122): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  823): Killing 3521:com.google.android.apps.books/u0a34 (adj 15): empty #17
,I/ActivityManager(  823): Killing 2983:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,I/SystemUpdateService( 1782): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/GCM     ( 1503): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/SystemUpdateService( 1782): active receiver: enabled
,D/SystemEventReceiver( 1782): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1782): Updating ocr activity enabled=false
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 6493(291KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 2.223ms total 65.487ms
,I/GCoreUlr( 1748): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/SystemUpdateService( 1782): showing system update notification
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599898 ms
,I/art     ( 1748): Explicit concurrent mark sweep GC freed 13198(770KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 1.264ms total 44.711ms
,D/SystemUpdateService( 1782): onDestroy
,I/GCoreUlr( 1748): DispatchingService.onCreate()
,W/CheckinRequestBuilder( 1782): awaiting user notification for token
,I/art     ( 1782): Explicit concurrent mark sweep GC freed 20980(1908KB) AllocSpace objects, 11(175KB) LOS objects, 35% free, 29MB/45MB, paused 2.314ms total 58.409ms
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/art     (  823): Explicit concurrent mark sweep GC freed 16486(740KB) AllocSpace objects, 6(473KB) LOS objects, 32% free, 33MB/49MB, paused 1.739ms total 63.850ms
,I/GCoreUlr( 1748): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 5320(247KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 986us total 19.537ms
,I/GCoreUlr( 1748): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1748): Unbound from all location providers
,I/EventLogService( 1782): Opted in for usage reporting
,I/CheckinTask( 1782): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/ActivityManager(  823): Start proc 4164:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,I/GCoreUlr( 1748): DispatchingService.onDestroy()
,I/GCoreUlr( 1748): Unbound from all location providers
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 9.357ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 202us total 8.908ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 200us total 8.904ms
,I/CheckinService( 1782): Checking schedule, now: 1448966987152 next: 1449008130094
I/CheckinService( 1782): active receiver: disabled
,I/CheckinService( 1782): Checking schedule, now: 1448966987169 next: 1449008130094
I/CheckinService( 1782): active receiver: disabled
,I/GAV2    ( 3751): Thread[GAThread,5,main]: No campaign data found.
,I/GservicesUpdateTask( 4164): Updating Gservices keys
,I/MusicLeanback( 3461): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3461): Stop autocaching.
,E/GmsUtils( 3461): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 3461): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3461): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3461): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1503): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1782): [AccountUtils] Account not ready
W/Kids    ( 1782): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1782): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1782): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1782): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1782): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1782): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  823): Killing 3332:com.google.android.keep/u0a79 (adj 15): empty #17
,I/GAV2    ( 3887): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  823): Killing 3847:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3545:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/ActivityManager(  823): Start proc 4221:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/ActivityManager(  823): Killing 3869:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3910:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,V/ConfigFetchTask( 1782): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VsbxPrz5IUi1DNtU3kJWWYukvEXW7Cyh-cvYtouzx6a6bAY3jVoKa9Y0uMFCJDebmfjm1jcHjpiJtzch9Ve1_qj6mUSU_l1d5lHoIzD4AWqEPQUaEvybyUP8z1cxIrHv3CoRBBEik4t8PVTX4kIQ4ND63AG3C1-EEzCMVtQE_BmmRkrifpokGFKMv5NOwj_i5lCBKZrGyfJilILa43w0rre6M8kFg5AK3R7o8Yk6j1OcIXnfUf_YuY-jLFwmA_Q9u_1gijLLjq8qPWE_aGA3b9nB-1PHmHyka797H5OiGhC1eOSHQ
,I/GoogleURLConnFactory( 1782): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 4221): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4221): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager(  823): Start proc 4258:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 4221): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4221): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 4258): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4258): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4221): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4221): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4221): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/MultiDex( 4258): VM with version 2.1.0 has multidex support
I/MultiDex( 4258): install
I/MultiDex( 4258): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4221): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/JNIHelp ( 4258): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4258): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1503): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1503): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1782): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ConfigFetchTask( 1782): updating config table for com.google.android.gms
,E/MDM     ( 1748): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1782): Restart initialization of location
,I/ConfigFetchService( 1782): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1782): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1782): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1782): fetch service done; releasing wakelock
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 8706(442KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.311ms total 34.546ms
,I/ConfigFetchService( 1782): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1782): stopping self
,I/VacuumService( 1503): Vacuum at: now=1448966990791 tag=VacuumService
,I/GoogleURLConnFactory( 1503): Using platform SSLCertificateSocketFactory
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 4221): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/art     (  823): Explicit concurrent mark sweep GC freed 19385(918KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 871us total 51.521ms
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4221): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4221): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4221): [1] 5.onFinished: Scheduling replication attempt 3.
,I/ActivityManager(  823): Killing 3293:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/Finsky  ( 4221): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
W/Uploader( 1503): No account for auth token provided
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4221): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1503): No account for auth token provided
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4221): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Uploader( 1503): No account for auth token provided
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4221): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
,D/Finsky  ( 4221): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,W/Uploader( 1503): No account for auth token provided
,D/Finsky  ( 4221): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4221): [1] DailyHygiene.reschedule: Scheduling new run in 27 minutes (failures=2)
,D/DeviceConnectionService( 1748): client connected with version: 7571000
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
,E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided,
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503):  no longer exists, so no auth token.
,W/Uploader( 1503): No account for auth token provided
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1503): No account for auth token provided,
,W/Uploader( 1503): No account for auth token provided,
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,W/Uploader( 1503): No account for auth token provided
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.,
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508),
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	,at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1503): No account for auth token provided
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/ActivityManager(  823): Killing 2632:com.google.android.talk/u0a61 (adj 15): empty #17
,I/ConfigService( 1503): onDestroy
,W/PackageSettings(  823): Skipping PackageSetting{149cf9f9 com.example.hello/10272} due to missing metadata
I/ActivityManager(  823): Killing 3937:android.process.acore/u0a5 (adj 15): empty #17
,W/Uploader( 1503): No account for auth token provided
,I/PowerManagerService(  823): Going to sleep due to screen timeout (uid 1000)...
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
I/Adreno  (  823): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PermissionCache(  270): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (214 us)
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
,E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1503): No account for auth token provided
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1503): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1503): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1503): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1503): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1503): No account for auth token provided,
,W/Uploader( 1503): No account for auth token provided
,I/DisplayManagerService(  823): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  270): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  270): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  823): Display changed displayId=0
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/qdhwcomposer(  270): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  270): hwc_setPowerMode: Done setting mode 0 on display 0,
D/SurfaceControl(  823): Excessive delay in setPowerMode(): 269ms
,I/DreamManagerService(  823): Entering dreamland.
I/PowerManagerService(  823): Dozing...
,I/DreamController(  823): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  823): cancelDelayedScan -> 5
,E/native  (  823): do suspend false
,I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  823): Start proc 4307:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,D/WifiService(  823): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2651575a}
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=38.49 rxSuccessRate=27.43 targetRoamBSSID=any RSSI=-48
,W/ResourcesManager( 4307): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  823): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  823): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/Keyboard.Facilitator( 1202): onFinishInput()
,V/BackupManagerService(  823): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  823): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1ad41fe5
V/BackupManagerService(  823): Scheduling immediate backup pass
E/WifiStateMachine(  823): cancelDelayedScan -> 7
,E/native  (  823): do suspend true
V/GmsNetworkLocationProvi( 1748): DISABLE
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,V/BackupManagerService(  823): Running a backup pass
V/BackupManagerService(  823): clearing pending backups
,V/PerformBackupTask(  823): Beginning backup of 14 targets,
,D/PerformBackupTask(  823): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  823): doBackup() invoked
,I/PMBA    (  823): Previous metadata 1570415 mismatch vs 1743759 - rewriting,
,I/BackupRestoreController(  823): Getting widget state for user: 0
,I/art     (  823): Explicit concurrent mark sweep GC freed 38097(2MB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 1.674ms total 57.785ms
,V/GmsNetworkLocationProvi( 1748): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
I/Launcher( 1294): Deferring update until onResume
,V/GmsNetworkLocationProvi( 1748): ENABLE
,V/GmsNetworkLocationProvi( 1748): SET-REQUEST
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 123674(7MB) AllocSpace objects, 21(1414KB) LOS objects, 36% free, 28MB/44MB, paused 1.076ms total 58.389ms
,V/GmsNetworkLocationProvi( 1748): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/Babel_SMS( 4307): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4307): MmsConfig.loadMmsSettings
,W/GmsBackupTransport( 1748): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1748): starting performBackup for @pm@
,I/Babel_SMS( 4307): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
I/Babel_SMS( 4307): MmsConfig.loadFromDatabase
,V/GmsBackupTransport( 1748): performBackup done for @pm@
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel_SMS( 4307): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4307): MmsConfig.loadFromResources
,E/Babel_SMS( 4307): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4307): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1748): Error sending final backup to server: 
W/GmsBackupTransport( 1748): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1748): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1748): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1748): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1748): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1748): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1748): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1748): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1748): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1748): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1748): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1748): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1748): 	... 1 more
,D/BackupManagerService(  823): Now staging backup of com.google.android.talk
,W/Settings( 4307): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BackupManagerService(  823): Now staging backup of com.google.android.dialer
,I/Babel_Crash( 4307): startup - clean
,D/BackupManagerService(  823): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  823): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  823): Now staging backup of com.google.android.gm
,D/BackupManagerService(  823): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  823): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  823): Now staging backup of com.android.nfc
,D/BackupManagerService(  823): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  823): Now staging backup of com.android.vending
,D/BackupManagerService(  823): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  823): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  823): Now staging backup of android
,D/BackupManagerService(  823): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1748): Next backup will happen in 43199964 millis.
,I/BackupManagerService(  823): Backup pass finished.
,I/Babel   ( 4307): deleted: false for 0,
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,I/Babel_telephony( 4307): TeleModule.launchCompleted
,W/Telecom (  823): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 4307): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,W/Babel   ( 4307): BAM#gBA: invalid account id: -1
W/Babel   ( 4307): BAM#gBA: invalid account id: -1
I/Babel_telephony( 4307): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,W/Telecom (  823): TelecomServiceImpl: null is not visible for the calling user
,I/ActivityManager(  823): Start proc 4340:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,W/VideoCapabilities( 4307): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4307): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4307): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4307): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4307): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4307): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1782): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 4164): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 1782): Null package name or gms related package.  Ignoreing.
,W/Launcher( 1294): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@7ce879c new=com.google.android.velvet.VelvetApplication@7ce879c
,I/Icing   ( 1782): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  823): Start proc 4367:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/vclib   ( 4307): onServiceConnected
W/Babel   ( 4307): Attempted to change video mute state without an active call.
,I/ContactLocale( 4340): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/ResourcesManager( 4307): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4307): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 4367): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 4164): UpdateCorporaTask done [took 71 ms] updated apps [took 71 ms] 
,V/JNIHelp ( 4307): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4307): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  823): Killing 3622:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,I/GoogleURLConnFactory( 1748): Using platform SSLCertificateSocketFactory
,W/GoogleHttpClient( 1748): Ignoring unsupported parameter: http.conn-manager.max-per-route,
,D/WifiService(  823): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2651575a}
,E/LocSvc_IzatApiV02(  823): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,E/WifiStateMachine(  823): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-48
E/WifiStateMachine(  823): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/ActivityManager(  823): Killing 3887:com.google.android.gm/u0a78 (adj 15): empty #17
,I/ActivityManager(  823): Killing 3790:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 4221): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4221): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 4221): [1] 5.onFinished: Scheduling replication attempt 4.
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/ActivityManager(  823): Start proc 4403:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,I/ActivityManager(  823): Start proc 4429:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/ActivityManager(  823): Start proc 4446:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/KeepSync( 4403): Connecting to GoogleApiClient
,I/art     (  823): Explicit concurrent mark sweep GC freed 26150(1224KB) AllocSpace objects, 12(946KB) LOS objects, 32% free, 33MB/49MB, paused 1.229ms total 48.718ms
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 15552(947KB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 26MB/42MB, paused 1.199ms total 27.984ms
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at blb.a(PG:3937)
E/HttpOperation( 4367): 	at czp.a(PG:18188)
E/HttpOperation( 4367): 	at czp.a(PG:9087)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 12 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 14 more
,W/ResourcesManager( 4446): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4446): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 4221): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4221): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4221): [1] 5.onFinished: Scheduling replication attempt 5.
,V/JNIHelp ( 4446): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GoogleAuthProtoRequest( 4429): [485] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ProviderInstaller( 4446): Installed default security provider GmsCore_OpenSSL
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1782): Handling authorization failure
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
,V/KeepSync( 4403): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at blb.a(PG:3937)
E/HttpOperation( 4367): 	at czp.a(PG:18188)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 12 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 14 more
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/YouTube MDX( 4446): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at hec.a(PG:42)
E/HttpOperation( 4367): 	at hee.a(PG:102)
E/HttpOperation( 4367): 	at czr.a(PG:65)
E/HttpOperation( 4367): 	at kka.a(PG:108)
E/HttpOperation( 4367): 	at czp.a(PG:19176)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 15 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 17 more
,W/ExperimentUpdateService( 4429): [485] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
E/ExperimentLoader( 4367): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): 	at jdm.a(PG:82)
E/ExperimentLoader( 4367): 	at jcs.o(PG:406)
E/ExperimentLoader( 4367): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4367): 	at jcs.i(PG:143)
E/ExperimentLoader( 4367): 	at hec.a(PG:42)
E/ExperimentLoader( 4367): 	at hee.a(PG:102)
E/ExperimentLoader( 4367): 	at czr.a(PG:65)
E/ExperimentLoader( 4367): 	at kka.a(PG:108)
E/ExperimentLoader( 4367): 	at czp.a(PG:19176)
E/ExperimentLoader( 4367): 	at czp.a(PG:9081)
E/ExperimentLoader( 4367): 	at czq.run(PG:1686)
E/ExperimentLoader( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4367): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4367): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4367): 	at jdm.a(PG:77)
E/ExperimentLoader( 4367): 	... 15 more
E/ExperimentLoader( 4367): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4367): 	at fal.a(PG:38)
E/ExperimentLoader( 4367): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4367): 	... 17 more
,W/ExperimentUpdateService( 4429): [485] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4429): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4429): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4429): 	at com.a.a.k.run(SourceFile:110)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 4492): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads107547702.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads107547702.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/KeepSync( 4403): IOException
E/KeepSync( 4403): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4403): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4403): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4403): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4403): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4403): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4403): 	... 10 more
W/KeepSync( 4403): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 179249, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/dex2oat ( 4492): dex2oat took 40.275ms (threads: 4) arena alloc=129KB java alloc=12KB native alloc=1089KB free=6MB
,I/ActivityManager(  823): Start proc 4518:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  823): Killing 3751:com.google.android.calendar/u0a37 (adj 15): empty #17
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 147598, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,W/InstanceID/Rpc( 4446): Found 10011
,V/GoogleAuthProtoRequest( 4429): [486] a.<init>: mAccountName set to: thalitester@gmail.com
,W/GAV2    ( 4518): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4518): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4429): [486] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4429): [486] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4429): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4429): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4429): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  823): Killing 4088:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,I/BooksSync( 4518): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4518): Soft error,
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4518): Sync error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4518): Finished books sync
,I/ActivityManager(  823): Killing 4122:com.google.android.configupdater/u0a42 (adj 15): empty #17
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 180347, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  823): Killing 4047:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #18
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/GAV2    ( 4518): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,D/Finsky  ( 4221): [444] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 26726(1214KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.386ms total 92.512ms
,D/Finsky  ( 4221): [444] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1202): run()
I/Keyboard.Facilitator( 1202): flushDynamicLanguageModels()
,I/ConfigService( 1503): onCreate
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3219): 
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 26740(1609KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.974ms total 40.816ms
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4221): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4221): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4221): [1] 5.onFinished: Giving up after 6 failures.
,I/ConfigService( 1503): onDestroy
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at blb.a(PG:3937)
E/HttpOperation( 4367): 	at czp.a(PG:18188)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 12 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 14 more
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at hec.a(PG:42)
E/HttpOperation( 4367): 	at hee.a(PG:102)
E/HttpOperation( 4367): 	at czr.a(PG:65)
E/HttpOperation( 4367): 	at kka.a(PG:108)
E/HttpOperation( 4367): 	at czp.a(PG:19176)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 15 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 17 more
E/ExperimentLoader( 4367): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): 	at jdm.a(PG:82)
E/ExperimentLoader( 4367): ,	at jcs.o(PG:406)
E/ExperimentLoader( 4367): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4367): 	at jcs.i(PG:143)
E/ExperimentLoader( 4367): 	at hec.a(PG:42)
E/ExperimentLoader( 4367): 	at hee.a(PG:102)
E/ExperimentLoader( 4367): 	at czr.a(PG:65)
E/ExperimentLoader( 4367): 	at kka.a(PG:108)
E/ExperimentLoader( 4367): 	at czp.a(PG:19176)
E/ExperimentLoader( 4367): 	at czp.a(PG:9081)
E/ExperimentLoader( 4367): 	at czq.run(PG:1686)
E/ExperimentLoader( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4367): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4367): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4367): 	at jdm.a(PG:77)
E/ExperimentLoader( 4367): 	... 15 more
E/ExperimentLoader( 4367): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4367): 	at fal.a(PG:38)
E/ExperimentLoader( 4367): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4367): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 240075, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,V/GoogleAuthProtoRequest( 4429): [487] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4429): [487] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4429): [487] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4429): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4429): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4429): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/BooksSync( 4518): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4403): Connecting to GoogleApiClient
,I/BooksConfig( 4518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1782): Handling authorization failure
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
V/KeepSync( 4403): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted),
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4518): Soft error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4518): Sync error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4518): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 272160, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4403): IOException
E/KeepSync( 4403): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4403): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4403): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4403): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4403): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4403): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4403): 	... 10 more
,W/KeepSync( 4403): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 269527, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector connect called
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Coordinator is now connected to the server!
I/jxcore-log( 3219): 
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4367): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at blb.a(PG:3937)
E/HttpOperation( 4367): 	at czp.a(PG:18188)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	,at jdj.a(PG:1125)
,E/HttpOperation( 4367): 	at jdm.a(PG:77)
,E/HttpOperation( 4367): 	,... 12 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication,
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 14 more
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at hec.a(PG:42)
E/HttpOperation( 4367): 	at hee.a(PG:102)
E/HttpOperation( 4367): 	at czr.a(PG:65)
E/HttpOperation( 4367): 	at kka.a(PG:108)
E/HttpOperation( 4367): 	at czp.a(PG:19176)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 15 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 17 more
E/ExperimentLoader( 4367): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): 	at jdm.a(PG:82)
E/ExperimentLoader( 4367): 	at jcs.o(PG:406)
E/ExperimentLoader( 4367): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4367): 	at jcs.i(PG:143)
E/ExperimentLoader( 4367): 	at hec.a(PG:42)
E/ExperimentLoader( 4367): 	at hee.a(PG:102)
E/ExperimentLoader( 4367): 	at czr.a(PG:65)
E/ExperimentLoader( 4367): 	at kka.a(PG:108)
E/ExperimentLoader( 4367): 	at czp.a(PG:19176)
E/ExperimentLoader( 4367): 	at czp.a(PG:9081)
E/ExperimentLoader( 4367): 	at czq.run(PG:1686)
E/ExperimentLoader( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4367): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4367): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4367): 	at jdm.a(PG:77)
E/ExperimentLoader( 4367): 	... 15 more
E/ExperimentLoader( 4367): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4367): 	at fal.a(PG:38)
E/ExperimentLoader( 4367): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4367): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 331969, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 4429): [488] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  823): Explicit concurrent mark sweep GC freed 36140(1565KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.945ms total 82.924ms
,W/ExperimentUpdateService( 4429): [488] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4429): [488] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4429): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4429): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4429): 	at com.a.a.k.run(SourceFile:110)
,V/KeepSync( 4403): Connecting to GoogleApiClient
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1782): Handling authorization failure
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
,E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	,at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689),
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
V/KeepSync( 4403): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4403): IOException
E/KeepSync( 4403): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4403): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4403): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4403): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4403): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4403): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4403): 	... 10 more
W/KeepSync( 4403): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 420874, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): DBG, CoordinatorConnector command called
I/jxcore-log( 3219): 
I/jxcore-log( 3219): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":50000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":21,"addressList":[{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"08:EC:A9:50:75:41","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"58:3F:54:73:64:C0","tryCount":0},{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"38:94:96:B5:06:DC","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"80:01:84:8A:B3
,I/jxcore-log( 3219): Start now : testSendData.js
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":50000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 21
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): check server
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): serverPort is 43283
I/jxcore-log( 3219): 
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): stop: Stopping Bluetooth and peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): initialize: F8:CF:C5:D9:E5:61 motorola-Nexus 6_PT3700
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 3219): initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): initialize: Bluetooth and Wi-Fi OK
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: INITIALIZED
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): verifyIdentityString: Identity string created: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT3700","ra":"F8:CF:C5:D9:E5:61"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): startListeningForIncomingConnections: Starting...
,D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): start: OK
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 3219): start: OK
I/jxcore-log( 3219): StartBroadcasting started ok
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/jxcore-log( 3219): 2015-12-01T10:54:32.164Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:54:32.165Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:54:32.165Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address B0:C5:59:3F:75:69,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address B0:C5:59:3F:75:69
I/jxcore-log( 3219): 2015-12-01T10:54:32.176Z SendDataTCPServer.js: TCP/IP server is bound to port: 43283,
I/jxcore-log( 3219): 
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onWifiStateChanged: State changed to 2,
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi peer discovery...
I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: INITIALIZED
,I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: RUNNING
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [f4:f1:e1:5c:3b:e2]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,D/btif_config( 3274): btif_get_device_type: Device [f4:f1:e1:5c:3b:e2] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State,
,I/ActivityManager(  823): Start proc 4659:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
,D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16aa8d9e:true
,I/ActivityManager(  823): Killing 4070:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: F4:F1:E1:5C:3B:E2 newState: 0
D/BluetoothAdapterProperties( 3274): Failed to remove device: F4:F1:E1:5C:3B:E2
,W/bt-btif ( 3274): info:x10,
,D/        ( 3274): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c,
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:F4:F1:E1:5C:3B:E2 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 339)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f69eb4 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 339)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 339
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 339)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID F4:F1:E1:5C:3B:E2
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/jxcore-log( 3219): 2015-12-01T10:54:35.836Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a244 rs_disc_pending=0
W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1,
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1,
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0,
,D/BluetoothAdapterProperties( 3274): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a244 rs_disc_pending=1,
E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3274): onReceive
,D/BluetoothManagerService(  823): Message: 20,
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12fd384c:true
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: ALE-L21
,D/btif_config( 3274): btif_get_device_type: Device [b0:c5:59:3f:75:69] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
D/BluetoothAdapterProperties( 3274): Failed to remove device: B0:C5:59:3F:75:69
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,D/btif_config( 3274): btif_get_device_type: Device [f8:95:c7:87:85:54] type 1,
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
D/BluetoothAdapterProperties( 3274): Failed to remove device: F8:95:C7:87:85:54
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 343)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 343
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 343)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 343)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT4827, Bluetooth address: F8:95:C7:87:85:54
,I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:85:54
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread,
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK,
,I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:54:40.348Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BooksSync( 4518): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 50224(2MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 2.151ms total 53.121ms
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4518): Soft error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4518): Sync error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4518): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 424090, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3274): invalid rfc slot id: 4
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 340
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed,
,E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T10:54:46.274Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x43
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 347)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 347
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 347)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 347)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2,
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread,
I/jxcore-log( 3219): 2015-12-01T10:54:46.908Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1503): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1503): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1503): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1503): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1503): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 4221): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4221): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4221): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 4221): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4221): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 4221): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4221): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 4221): Ignoring header User-Agent because its value was null.
,W/bt-btif ( 3274): invalid rfc slot id: 6
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 344
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams,
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T10:54:50.985Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x48
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 351)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 351)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 351)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 351
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 351)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 351)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT4827, Bluetooth address: F8:95:C7:87:85:54
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:54:51.175Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1,
W/bt-btif ( 3274): invalid rfc slot id: 7
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 348
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/jxcore-log( 3219): 2015-12-01T10:54:57.269Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 355)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 355,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 355)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 355)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/jxcore-log( 3219): 2015-12-01T10:54:58.419Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,W/bt-btif ( 3274): invalid rfc slot id: 8
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1,
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 352
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/jxcore-log( 3219): 2015-12-01T10:55:01.954Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4c
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 359)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 359
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 359)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT4827, Bluetooth address: F8:95:C7:87:85:54
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 359)
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:55:02.094Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
E/bt-btif ( 3274): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:5, channel:6
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Cancelled: Connection timeout [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:55:02.182Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:02.183Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:02.184Z SendDataConnector.js: tryAgain afer: 5000 ms.
,I/jxcore-log( 3219): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/jxcore-log( 3219): 2015-12-01T10:55:07.188Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:07.190Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 9
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 356
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T10:55:09.268Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4e
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 363)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 363)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 363
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 363),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 363)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2],
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:55:09.896Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f69eb4 rs_disc_pending=0
E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy S5)
,I/jxcore-log( 3219): 2015-12-01T10:55:12.195Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:12.196Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:12.198Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:12.199Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): invalid rfc slot id: 10
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 360
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T10:55:12.422Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x41
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 368)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 368),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 368
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 368)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT4827, Bluetooth address: F8:95:C7:87:85:54
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 368)
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:55:13.513Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 11
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 364
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/jxcore-log( 3219): 2015-12-01T10:55:20.264Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x44
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 372
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 372)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 372)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:55:20.944Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 14
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 373
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/jxcore-log( 3219): 2015-12-01T10:55:21.344Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btif ( 3274): invalid rfc slot id: 12
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 369
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
,E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T10:55:23.906Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x47
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 376)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 376
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 376)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 376)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT4827 F8:95:C7:87:85:54]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: F8:95:C7:87:85:54, name: LGE-LG-D722_PT4827, Bluetooth address: F8:95:C7:87:85:54
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/jxcore-log( 3219): 2015-12-01T10:55:24.123Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,W/bt-btif ( 3274): invalid rfc slot id: 15
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 377
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T10:55:24.465Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: XT1039
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,E/bt-btif ( 3274): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:13, channel:-1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Cancelled: Connection timeout
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Cancelled: Connection timeout [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:55:42.215Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:42.216Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:42.217Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524],
I/BluetoothClassifier( 4164): Bluetooth Device Name: G3s-1
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at blb.a(PG:3937)
E/HttpOperation( 4367): 	at czp.a(PG:18188)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 12 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 14 more
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at hec.a(PG:42)
E/HttpOperation( 4367): 	at hee.a(PG:102)
E/HttpOperation( 4367): 	at czr.a(PG:65)
E/HttpOperation( 4367): 	at kka.a(PG:108)
E/HttpOperation( 4367): 	at czp.a(PG:19176)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 15 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 17 more
E/ExperimentLoader( 4367): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): 	at jdm.a(PG:82)
E/ExperimentLoader( 4367): 	at jcs.o(PG:406)
E/ExperimentLoader( 4367): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4367): 	at jcs.i(PG:143)
E/ExperimentLoader( 4367): 	at hec.a(PG:42)
E/ExperimentLoader( 4367): 	at hee.a(PG:102)
E/ExperimentLoader( 4367): 	at czr.a(PG:65)
E/ExperimentLoader( 4367): 	at kka.a(PG:108)
E/ExperimentLoader( 4367): 	at czp.a(PG:19176)
E/ExperimentLoader( 4367): 	at czp.a(PG:9081)
E/ExperimentLoader( 4367): 	at czq.run(PG:1686)
E/ExperimentLoader( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4367): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4367): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4367): 	at jdm.a(PG:77)
E/ExperimentLoader( 4367): 	... 15 more
E/ExperimentLoader( 4367): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4367): 	at fal.a(PG:38)
E/ExperimentLoader( 4367): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4367): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 486264, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3219): 2015-12-01T10:55:47.219Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:47.220Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:52.224Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:52.225Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:52.225Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:52.226Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:17, failed to find channle,                                       status:2, scn:-115529554
W/bt-btif ( 3274): invalid rfc slot id: 17
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T10:55:52.256Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B0:C5:59:3F:75:69 failed,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:52.256Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:55:52.257Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): ,
,I/jxcore-log( 3219): 2015-12-01T10:55:57.259Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:55:57.260Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:02.264Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:02.265Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:02.265Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:02.266Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:18, failed to find channle,                                       status:2, scn:-115529554
W/bt-btif ( 3274): invalid rfc slot id: 18
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T10:56:02.287Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:02.288Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:02.288Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x8  CID 0x45
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:13, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 13
,I/jxcore-log( 3219): 2015-12-01T10:56:07.290Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:07.291Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:12.295Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:12.296Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:12.296Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:12.297Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B0:C5:59:3F:75:69
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy S5) B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy S5) in address B0:C5:59:3F:75:69
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10,
,D/        ( 3274): remote version info [b0:c5:59:3f:75:69]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Connection timeout
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Cancelled: Connection timeout
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Cancelled: Connection timeout [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
E/bt-btif ( 3274): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:19, channel:6
W/bt-btif ( 3274): invalid rfc slot id: 19
I/jxcore-log( 3219): 2015-12-01T10:56:42.317Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:42.318Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B0:C5:59:3F:75:69 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:42.326Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:42.330Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:42.336Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:42.337Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:42.337Z SendDataConnector.js: do connect now,
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68,
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 80:01:84:8A:B3:68,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 80:01:84:8A:B3:68
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: Connection to peer with ID B0:C5:59:3F:75:69 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: socket closed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: socket closed
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:300)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	,at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: socket closed [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
I/jxcore-log( 3219): 2015-12-01T10:56:42.348Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:42.348Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:42.348Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:47.349Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:47.349Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3274): info:x10,
,D/        ( 3274): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy S5)
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:255
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 384),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1007 B0:C5:59:3F:75:69]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 384
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 384)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1007 B0:C5:59:3F:75:69]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 384)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1007 B0:C5:59:3F:75:69]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: B0:C5:59:3F:75:69, name: samsung-SM-G900F_PT1007, Bluetooth address: B0:C5:59:3F:75:69
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID B0:C5:59:3F:75:69
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:56:50.398Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): ,
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3219): 2015-12-01T10:56:52.353Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:52.354Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:56:52.354Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:56:52.355Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,W/bt-btm  ( 3274): btm_sec_clr_temp_auth_service() - no dev CB
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:21, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 21
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T10:57:02.389Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:02.390Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:02.390Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:07.392Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:07.392Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:12.396Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:12.397Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:12.398Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:12.399Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 22
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T10:57:17.557Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:17.558Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:17.558Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): 2015-12-01T10:57:22.561Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:22.562Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:27.565Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:27.566Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:27.567Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:27.567Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x41
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 23
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T10:57:32.727Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:32.729Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:32.730Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:37.733Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:37.733Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:42.737Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:42.738Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:42.738Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:42.739Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 80:01:84:8A:B3:68
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 80:01:84:8A:B3:68
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 80:01:84:8A:B3:68
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:24, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 24
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [80:01:84:8A:B3:68 80:01:84:8A:B3:68 80:01:84:8A:B3:68]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T10:57:47.905Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:47.906Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 80:01:84:8A:B3:68 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:47.914Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:47.920Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3219): ,
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:47.923Z SendDataConnector.js: Start called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:47.924Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:47.924Z SendDataConnector.js: do connect now
,I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: Connection to peer with ID 80:01:84:8A:B3:68 failed", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x44
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:25, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3274): invalid rfc slot id: 25
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [B4:CE:F6:AB:A4:6A B4:CE:F6:AB:A4:6A B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T10:57:53.067Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:53.068Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID B4:CE:F6:AB:A4:6A failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:53.070Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:57:58.073Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:57:58.074Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
,V/GoogleAuthProtoRequest( 4429): [489] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4429): [489] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 4429): [489] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4429): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4429): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4429): 	at com.a.a.k.run(SourceFile:110)
,I/art     (  823): Explicit concurrent mark sweep GC freed 32905(1476KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.491ms total 107.479ms
,I/jxcore-log( 3219): 2015-12-01T10:58:03.079Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:03.079Z SendDataConnector.js: Connect (retry count 1) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:03.080Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:03.081Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f69eb4 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): info:x10,
D/        ( 3274): remote version info [b4:ce:f6:ab:a4:6a]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [b4:ce:f6:ab:a4:6a] type 1
,W/bt-btif ( 3274): invalid rfc slot id: 16
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 385
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 1
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/jxcore-log( 3219): 2015-12-01T10:58:04.008Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: B4:CE:F6:AB:A4:6A newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: B4:CE:F6:AB:A4:6A
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:B4:CE:F6:AB:A4:6A OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 394)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 84 bytes successfully (thread ID: 394)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A,
,I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID B4:CE:F6:AB:A4:6A,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 394)
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 45753
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 45753
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:58:04.473Z SendDataConnector.js: CLIENT connected to 45753, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:04.474Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:04.475Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a964 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btif ( 3274): bta_dm_pm_btm_status  hci_status=31
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4e
E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy S5),
,W/bt-btif ( 3274): dm_pm_timer expires,
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T10:58:09.475Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:09.476Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3219): close,
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/jxcore-log( 3219): 2015-12-01T10:58:14.485Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:14.485Z SendDataConnector.js: Connect (retry count 2) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:14.486Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:14.487Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 397)
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,V/KeepSync( 4403): Connecting to GoogleApiClient
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1782): Handling authorization failure
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
,V/KeepSync( 4403): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 84 bytes successfully (thread ID: 397)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 397)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 58407
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 58407
,I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,E/KeepSync( 4403): IOException
E/KeepSync( 4403): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4403): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4403): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4403): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4403): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4403): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4403): 	... 10 more
W/KeepSync( 4403): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 668324, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3219): 2015-12-01T10:58:22.273Z SendDataConnector.js: CLIENT connected to 58407, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:22.274Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:22.275Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T10:58:27.277Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:27.279Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	,at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:58:32.292Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:32.293Z SendDataConnector.js: Connect (retry count 3) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:32.294Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:32.294Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 400)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 84 bytes successfully (thread ID: 400)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 400)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 37441
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 37441
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:58:35.664Z SendDataConnector.js: CLIENT connected to 37441, error: Listening for incoming connections,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:35.665Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:35.665Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T10:58:40.667Z SendDataConnector.js: re-try now : B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:40.668Z SendDataConnector.js: ReStart called with peer B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T10:58:45.678Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:45.679Z SendDataConnector.js: Connect (retry count 4) to peer B4:CE:F6:AB:A4:6A with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:45.680Z SendDataConnector.js: doConnect called with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:45.681Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: HTC Desire 820 B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to HTC Desire 820 in address B4:CE:F6:AB:A4:6A
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...,
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND,
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 403)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 403)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 403)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 84 bytes successfully (thread ID: 403)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 403)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [B4:CE:F6:AB:A4:6A HTC-HTC Desire 820_PT6617 B4:CE:F6:AB:A4:6A]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: B4:CE:F6:AB:A4:6A, name: HTC-HTC Desire 820_PT6617, Bluetooth address: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 56851
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 56851
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:58:46.235Z SendDataConnector.js: CLIENT connected to 56851, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:46.236Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:46.240Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: B4:CE:F6:AB:A4:6A
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T10:58:46.248Z SendDataConnector.js: Mobile.Disconnect() callback with peer B4:CE:F6:AB:A4:6A
I/jxcore-log( 3219): 
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : B4:CE:F6:AB:A4:6A, try count now: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:46.253Z SendDataConnector.js: Start called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:46.253Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:46.253Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 00:F4:6F:30:E0:6C
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B4:CE:F6:AB:A4:6A done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a964 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a964 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND,
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [00:f4:6f:30:e0:6c]: 6, f, 410d
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a964 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6ab2c rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6ab2c rs_disc_pending=0
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B4:CE:F6:AB:A4:6A, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: HTC Desire 820
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [00:f4:6f:30:e0:6c] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 00:F4:6F:30:E0:6C newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: 00:F4:6F:30:E0:6C
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:00:F4:6F:30:E0:6C OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 406),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 406)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 406)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 406),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 406)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
,I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 59626
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 59626
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:58:52.318Z SendDataConnector.js: CLIENT connected to 59626, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:52.319Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:58:52.320Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T10:58:57.320Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:58:57.321Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams,
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/jxcore-log( 3219): 2015-12-01T10:59:02.325Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T10:59:02.326Z SendDataConnector.js: Connect (retry count 1) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:02.328Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:02.331Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 409)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 409)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 409)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 49184
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 49184
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:59:02.895Z SendDataConnector.js: CLIENT connected to 49184, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:02.896Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:02.896Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T10:59:07.897Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:07.898Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T10:59:12.903Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:12.904Z SendDataConnector.js: Connect (retry count 2) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:12.905Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T10:59:12.905Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 412)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 412)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 412)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 412),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 412)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully,
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 58868
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 58868
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:59:13.851Z SendDataConnector.js: CLIENT connected to 58868, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:13.852Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:13.852Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T10:59:18.854Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:18.855Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/BooksSync( 4518): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4518): Soft error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4518): Sync error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4518): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 704867, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): ,	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T10:59:23.862Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:23.863Z SendDataConnector.js: Connect (retry count 3) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:23.864Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:23.866Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 415)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 415)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 415)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 415)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 415)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 37899
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 37899
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:59:26.171Z SendDataConnector.js: CLIENT connected to 37899, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:26.172Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:26.173Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T10:59:31.173Z SendDataConnector.js: re-try now : 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:31.174Z SendDataConnector.js: ReStart called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method),
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T10:59:36.189Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:36.190Z SendDataConnector.js: Connect (retry count 4) to peer 00:F4:6F:30:E0:6C with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:36.190Z SendDataConnector.js: doConnect called with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:36.191Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: S5mini-1 00:F4:6F:30:E0:6C
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to S5mini-1 in address 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 418)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 418)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 418)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 418)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 418)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [00:F4:6F:30:E0:6C samsung-SM-G800F_PT3325 00:F4:6F:30:E0:6C]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 00:F4:6F:30:E0:6C, name: samsung-SM-G800F_PT3325, Bluetooth address: 00:F4:6F:30:E0:6C
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 36412
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 36412
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T10:59:36.847Z SendDataConnector.js: CLIENT connected to 36412, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:36.848Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:36.852Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 00:F4:6F:30:E0:6C
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
I/jxcore-log( 3219): 2015-12-01T10:59:36.857Z SendDataConnector.js: Mobile.Disconnect() callback with peer 00:F4:6F:30:E0:6C
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
,E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): ---- gotta redo : 00:F4:6F:30:E0:6C, try count now: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:36.863Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:36.864Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:36.865Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 34:FC:EF:11:AE:67
W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1d):jv handle:0x0 not FOUND
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 00:F4:6F:30:E0:6C done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btm  ( 3274): btm_sec_clr_temp_auth_service() - no dev CB
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:35, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 35
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:AE:67 34:FC:EF:11:AE:67 34:FC:EF:11:AE:67]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T10:59:46.522Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:46.523Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:AE:67 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:46.524Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:51.525Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T10:59:51.526Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): ,
,I/jxcore-log( 3219): 2015-12-01T10:59:56.533Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:56.534Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:56.535Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T10:59:56.535Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): info:x10,
D/        ( 3274): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
D/BluetoothAdapterProperties( 3274): Failed to remove device: 34:FC:EF:11:AE:67
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 422)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 422)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 422)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 422)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 422)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:AE:67, name: LGE-Nexus 5_PT5003, Bluetooth address: 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 48202
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 48202
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:00:00.944Z SendDataConnector.js: CLIENT connected to 48202, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:00.944Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:00.945Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/ActivityManager(  823): Start proc 4849:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 350us total 22.094ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 348us total 17.644ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 226us total 14.485ms
,I/GAv4    ( 4849): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4849):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4849):   adb logcat -s GAv4
,W/GAv4    ( 4849): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4849): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4849): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  823): Killing 3769:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=0
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3274): dm_pm_timer expires,
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:00:05.947Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:05.948Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140),
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:00:10.962Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:10.962Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3219): ,
I/jxcore-log( 3219): 2015-12-01T11:00:10.963Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:10.967Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Nexus 5 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 425)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 425)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 425)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 425)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 425)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:AE:67, name: LGE-Nexus 5_PT5003, Bluetooth address: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 55024
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 55024
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:00:14.086Z SendDataConnector.js: CLIENT connected to 55024, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:14.086Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:14.087Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=0
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:00:19.089Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:19.090Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at blb.a(PG:3937)
E/HttpOperation( 4367): 	at czp.a(PG:18188)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 12 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 14 more
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	,at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at hec.a(PG:42)
,E/HttpOperation( 4367): 	at hee.a(PG:102)
E/HttpOperation( 4367): 	at czr.a(PG:65)
E/HttpOperation( 4367): 	,at kka.a(PG:108)
E/HttpOperation( 4367): 	at czp.a(PG:19176)
E/HttpOperation( 4367): 	at czp.a(PG:9081),
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): ,	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	,at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
,E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
,E/HttpOperation( 4367): 	... 15 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	,at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 17 more
E/ExperimentLoader( 4367): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 4367): 	at jdm.a(PG:82)
E/ExperimentLoader( 4367): 	at jcs.o(PG:406)
E/ExperimentLoader( 4367): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4367): ,	at jcs.i(PG:143)
E/ExperimentLoader( 4367): 	at hec.a(PG:42)
,E/ExperimentLoader( 4367): 	at hee.a(PG:102)
E/ExperimentLoader( 4367): 	at czr.a(PG:65)
E/ExperimentLoader( 4367): 	at kka.a(PG:108)
E/ExperimentLoader( 4367): ,	at czp.a(PG:19176)
E/ExperimentLoader( 4367): 	at czp.a(PG:9081)
E/ExperimentLoader( 4367): 	at czq.run(PG:1686)
E/ExperimentLoader( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4367): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4367): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4367): 	at jdm.a(PG:77)
E/ExperimentLoader( 4367): 	... 15 more
E/ExperimentLoader( 4367): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4367): 	at fal.a(PG:38)
E/ExperimentLoader( 4367): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4367): 	... 17 more
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 769070, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:00:24.106Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:24.108Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:24.109Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:24.112Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Nexus 5 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 428)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=1,
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 428)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 428)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:AE:67, name: LGE-Nexus 5_PT5003, Bluetooth address: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 51497
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 51497
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3219): 2015-12-01T11:00:27.282Z SendDataConnector.js: CLIENT connected to 51497, error: Listening for incoming connections
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:27.283Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:27.283Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=00:F4:6F:30:E0:6C, alias=null, name=S5mini-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: S5mini-1
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): 2015-12-01T11:00:32.285Z SendDataConnector.js: re-try now : 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:32.286Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 34:FC:EF:11:AE:67
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:00:37.296Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:37.297Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:AE:67 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:37.298Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:37.298Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Nexus 5 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Nexus 5 in address 34:FC:EF:11:AE:67
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 431)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 431)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT5003 34:FC:EF:11:AE:67]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 34:FC:EF:11:AE:67, name: LGE-Nexus 5_PT5003, Bluetooth address: 34:FC:EF:11:AE:67
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 46765
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 46765
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:00:37.930Z SendDataConnector.js: CLIENT connected to 46765, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:37.930Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:37.934Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:00:37.943Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- gotta redo : 34:FC:EF:11:AE:67, try count now: 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:37.946Z SendDataConnector.js: Start called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:37.947Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:37.947Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:40, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3274): invalid rfc slot id: 40
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:00:38.273Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): ,
I/jxcore-log( 3219): 2015-12-01T11:00:38.274Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:38.274Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14),
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6aebc rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3219): 2015-12-01T11:00:43.275Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:43.276Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:48.280Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:48.281Z SendDataConnector.js: Connect (retry count 1) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:48.282Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:48.283Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 34:FC:EF:11:B1:66,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): info:x10,
D/        ( 3274): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:41, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 41
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T11:00:48.882Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:48.882Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:48.883Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6aebc rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3219): 2015-12-01T11:00:53.885Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:53.886Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:58.890Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:58.890Z SendDataConnector.js: Connect (retry count 2) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:58.891Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:58.892Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 34:FC:EF:11:B1:66,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): info:x10,
D/        ( 3274): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0,
W/bt-btif ( 3274): invalid rfc slot id: 42
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T11:00:59.910Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:00:59.911Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:00:59.912Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3219): 2015-12-01T11:01:04.913Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:04.914Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:09.918Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:09.919Z SendDataConnector.js: Connect (retry count 3) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:09.920Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:09.920Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:43, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 43
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:01:10.219Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:10.221Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:10.222Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3219): 2015-12-01T11:01:15.225Z SendDataConnector.js: re-try now : 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:15.225Z SendDataConnector.js: ReStart called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:20.229Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:20.230Z SendDataConnector.js: Connect (retry count 4) to peer 34:FC:EF:11:B1:66 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:20.230Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:20.231Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 34:FC:EF:11:B1:66
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 34:FC:EF:11:B1:66
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 34:FC:EF:11:B1:66
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [34:fc:ef:11:b1:66]: 6, f, 6109,
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:44, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3274): invalid rfc slot id: 44
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [34:FC:EF:11:B1:66 34:FC:EF:11:B1:66 34:FC:EF:11:B1:66]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:01:20.996Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:20.996Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 34:FC:EF:11:B1:66 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:21.000Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:21.003Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:B1:66
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- gotta redo : 34:FC:EF:11:B1:66, try count now: 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:21.006Z SendDataConnector.js: Start called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:21.007Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:21.007Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 08:EC:A9:50:75:41
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:B1:66 done with result: Connection to peer with ID 34:FC:EF:11:B1:66 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6aebc rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [08:ec:a9:50:75:41]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [08:ec:a9:50:75:41] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:75:41 newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: 08:EC:A9:50:75:41
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:08:EC:A9:50:75:41 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 439)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 439)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 439)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 439)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 439)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT3175, Bluetooth address: 08:EC:A9:50:75:41
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed,
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 48998
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 48998
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:01:31.110Z SendDataConnector.js: CLIENT connected to 48998, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:31.111Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:31.112Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:01:36.113Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:36.114Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
,E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:01:41.124Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:41.125Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:41.125Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:41.126Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 442)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 442)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 442)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 442)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 442)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:75:41, name: samsung-SM-A300FU_PT3175, Bluetooth address: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 33210
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 33210
,I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:01:42.120Z SendDataConnector.js: CLIENT connected to 33210, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:42.121Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:42.122Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): info:x10,
D/        ( 3274): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b24c rs_disc_pending=0,
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:01:47.123Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:01:47.124Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:75:41
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:01:52.132Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:52.133Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:75:41 with availability status: true
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:52.133Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:52.134Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A3-1 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:47, failed to find channle,                                       status:1, scn:0
E/bt-btm  ( 3274): invalid rfc slot id: 47
,W/bt-btif ( 3274): invalid rfc slot id: 47
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T11:01:56.921Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:56.922Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:01:56.922Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:75:41, alias=null, name=A3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: A3-1
,I/jxcore-log( 3219): 2015-12-01T11:02:01.923Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:01.924Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:06.928Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:06.929Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:06.930Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:06.930Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A3-1 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x4f
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:48, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 48
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:02:12.097Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:12.098Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:12.098Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:17.100Z SendDataConnector.js: re-try now : 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:17.100Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): 2015-12-01T11:02:22.103Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:22.103Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:75:41 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:22.103Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:22.103Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: ,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A3-1 in address 08:EC:A9:50:75:41,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A3-1 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A3-1 in address 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/art     ( 1503): Explicit concurrent mark sweep GC freed 60590(3MB) AllocSpace objects, 10(1102KB) LOS objects, 36% free, 27MB/43MB, paused 1.595ms total 62.733ms
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:49, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 49
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [08:EC:A9:50:75:41 samsung-SM-A300FU_PT3175 08:EC:A9:50:75:41]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:02:27.251Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:27.252Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 08:EC:A9:50:75:41 failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:27.257Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:27.261Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:75:41
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : 08:EC:A9:50:75:41, try count now: 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:27.263Z SendDataConnector.js: Start called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:27.263Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:27.263Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 58:3F:54:73:64:C0
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:75:41 done with result: Connection to peer with ID 08:EC:A9:50:75:41 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [58:3f:54:73:64:c0]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [58:3f:54:73:64:c0] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 58:3F:54:73:64:C0 newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: 58:3F:54:73:64:C0
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:58:3F:54:73:64:C0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 448)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 448)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 448)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 448)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 448)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT4768, Bluetooth address: 58:3F:54:73:64:C0
,I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 58:3F:54:73:64:C0
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 51189
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 51189
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:02:28.788Z SendDataConnector.js: CLIENT connected to 51189, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:28.789Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:28.789Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): dm_pm_timer expires,
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:02:33.791Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:33.792Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [34:fc:ef:11:ae:67]: 7, f, 2205
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:02:38.797Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:38.798Z SendDataConnector.js: Connect (retry count 1) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:38.799Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:38.799Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: G3-1 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback,
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xb):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 451)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 451)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 451)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 451)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 451)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT4768, Bluetooth address: 58:3F:54:73:64:C0
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 35430
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 35430
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:02:42.233Z SendDataConnector.js: CLIENT connected to 35430, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:42.234Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:42.234Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:02:47.235Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:47.236Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:02:52.244Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:52.245Z SendDataConnector.js: Connect (retry count 2) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:52.246Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:52.246Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: G3-1 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 454)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 454)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 454)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT4768, Bluetooth address: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully,
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 37899
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 37899
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:02:54.780Z SendDataConnector.js: CLIENT connected to 37899, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:02:54.781Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:54.782Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:02:59.782Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:02:59.783Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T11:03:04.788Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:03:04.789Z SendDataConnector.js: Connect (retry count 3) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:04.789Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:04.790Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: G3-1 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND,
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 457)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 457)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 457)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 457)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 457)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT4768, Bluetooth address: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 48707
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 48707
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:03:08.588Z SendDataConnector.js: CLIENT connected to 48707, error: Listening for incoming connections
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:08.589Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:08.589Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btm  ( 3274): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=2
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5,
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:03:13.590Z SendDataConnector.js: re-try now : 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:13.591Z SendDataConnector.js: ReStart called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b414 rs_disc_pending=0
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): info:x10,
D/        ( 3274): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 58:3F:54:73:64:C0,
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams,
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
,E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): ,	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:03:18.600Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:18.601Z SendDataConnector.js: Connect (retry count 4) to peer 58:3F:54:73:64:C0 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:18.601Z SendDataConnector.js: doConnect called with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:18.602Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: G3-1 58:3F:54:73:64:C0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to G3-1 in address 58:3F:54:73:64:C0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,I/art     (  823): Explicit concurrent mark sweep GC freed 40972(1925KB) AllocSpace objects, 8(410KB) LOS objects, 32% free, 33MB/49MB, paused 1.467ms total 88.173ms
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b414 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-l2cap( 3274): L2CAP - unknown CID: 0x0047
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 460)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 460)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 460)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 77 bytes successfully (thread ID: 460)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 460)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [58:3F:54:73:64:C0 LGE-LG-D855_PT4768 58:3F:54:73:64:C0]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 58:3F:54:73:64:C0, name: LGE-LG-D855_PT4768, Bluetooth address: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 49288
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 49288
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:03:47.337Z SendDataConnector.js: CLIENT connected to 49288, error: Listening for incoming connections,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:47.338Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:47.342Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 58:3F:54:73:64:C0
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T11:03:47.345Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:3F:54:73:64:C0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- gotta redo : 58:3F:54:73:64:C0, try count now: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:47.348Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:47.349Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:47.349Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: ,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:3F:54:73:64:C0 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63),
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b414 rs_disc_pending=0
W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,D/btif_config( 3274): btif_get_device_type: Device [7c:f9:0e:51:18:22] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
D/BluetoothAdapterProperties( 3274): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 463)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 463)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 463)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 463)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 463)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:51:18:22
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 39639
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 39639
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b414 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3219): 2015-12-01T11:03:51.412Z SendDataConnector.js: CLIENT connected to 39639, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:51.413Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:03:51.414Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:3F:54:73:64:C0, alias=null, name=G3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: G3-1
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:03:56.414Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:03:56.415Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:51:18:22
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	,at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:04:01.422Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:01.423Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:01.423Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:01.424Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback,
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND,
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 466)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 466)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 466)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 466)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 466)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 50840
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 50840
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:04:03.853Z SendDataConnector.js: CLIENT connected to 50840, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:03.853Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:03.854Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:04:08.855Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:08.856Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:51:18:22,
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140),
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:04:13.861Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:13.863Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:13.865Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:13.867Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 469)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 50311
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 50311
,I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:04:16.079Z SendDataConnector.js: CLIENT connected to 50311, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:16.080Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:16.081Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:04:21.081Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:21.082Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:04:26.090Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:26.091Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:26.092Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:26.092Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x12):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 472)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 472)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 472)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 472)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 472)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 57067
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 57067
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:04:27.976Z SendDataConnector.js: CLIENT connected to 57067, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:27.976Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:27.977Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btm  ( 3274): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=2
E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5,
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): 2015-12-01T11:04:32.978Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:32.979Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:04:37.985Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:37.988Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:37.990Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:37.990Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A5) 7C:F9:0E:51:18:22
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A5) in address 7C:F9:0E:51:18:22
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback,
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 475)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 475)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 475)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 475)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 475)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4930 7C:F9:0E:51:18:22]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:51:18:22, name: samsung-SM-A500FU_PT4930, Bluetooth address: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 60109
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 60109
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:04:41.521Z SendDataConnector.js: CLIENT connected to 60109, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:41.522Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:41.527Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:51:18:22
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T11:04:41.533Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22,
I/jxcore-log( 3219): 
W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): ---- gotta redo : 7C:F9:0E:51:18:22, try count now: 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:41.546Z SendDataConnector.js: Start called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:41.546Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:41.546Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/GCM     ( 1782): Message from null null
E/GCM     ( 1782): Dropping message from null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:51:18:22 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/GCM     ( 1503): Message class com.google.f.a.a.i,
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x49
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:60, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 60
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:04:46.681Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:46.682Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:46.682Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:51.684Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:51.685Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:04:56.688Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:56.688Z SendDataConnector.js: Connect (retry count 1) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:56.689Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:04:56.690Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:61, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 61
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T11:05:01.848Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:01.848Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:01.849Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:06.850Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:06.850Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,W/bt-btm  ( 3274): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6acf4 rs_disc_pending=2
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3219): 2015-12-01T11:05:11.854Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): ,
,I/jxcore-log( 3219): 2015-12-01T11:05:11.855Z SendDataConnector.js: Connect (retry count 2) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:11.856Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:11.856Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x45
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:62, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3274): invalid rfc slot id: 62
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	,at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T11:05:17.012Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:17.012Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:17.171Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:22.172Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): ,
I/jxcore-log( 3219): 2015-12-01T11:05:22.173Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:27.177Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:27.178Z SendDataConnector.js: Connect (retry count 3) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:27.179Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:27.182Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: ALE-L21 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x4a
E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:63, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 63
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:05:32.343Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:32.344Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:32.344Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): 2015-12-01T11:05:37.346Z SendDataConnector.js: re-try now : 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:37.348Z SendDataConnector.js: ReStart called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:42.353Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:42.354Z SendDataConnector.js: Connect (retry count 4) to peer 58:2A:F7:ED:96:BE with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:42.355Z SendDataConnector.js: doConnect called with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:42.355Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 58:2A:F7:ED:96:BE
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to ALE-L21 in address 58:2A:F7:ED:96:BE,
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: ALE-L21 58:2A:F7:ED:96:BE,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to ALE-L21 in address 58:2A:F7:ED:96:BE
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x4  CID 0x4d
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:64, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 64
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE 58:2A:F7:ED:96:BE],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:05:47.516Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:47.517Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID 58:2A:F7:ED:96:BE failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:47.525Z SendDataConnector.js: CLIENT Stop now
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:47.528Z SendDataConnector.js: Mobile.Disconnect() callback with peer 58:2A:F7:ED:96:BE
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : 58:2A:F7:ED:96:BE, try count now: 1
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:47.532Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:47.532Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:47.532Z SendDataConnector.js: do connect now
,I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 58:2A:F7:ED:96:BE done with result: Connection to peer with ID 58:2A:F7:ED:96:BE failed", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [08:ec:a9:50:76:27] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3274): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
D/BluetoothAdapterProperties( 3274): Failed to remove device: 08:EC:A9:50:76:27
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 483)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 483)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 483)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 483)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 483)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 54465
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 54465
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:05:58.027Z SendDataConnector.js: CLIENT connected to 54465, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:05:58.028Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:05:58.028Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,V/GoogleAuthProtoRequest( 4429): [490] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4429): [490] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4429): [490] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4429): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4429): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4429): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4429): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4429): 	at com.a.a.k.run(SourceFile:110)
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:06:03.030Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:03.030Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b7a4 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89),
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:06:08.040Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:08.041Z SendDataConnector.js: Connect (retry count 1) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:08.041Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:08.042Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 486)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 486)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 486)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 486)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 486)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 40921
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 40921
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:06:08.467Z SendDataConnector.js: CLIENT connected to 40921, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:08.468Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:08.470Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:06:13.472Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:13.473Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): ,	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:06:18.482Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:18.482Z SendDataConnector.js: Connect (retry count 2) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:18.483Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:18.484Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND,
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 489)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 489)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 489)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 489)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 489)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 45332
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 45332
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:06:21.147Z SendDataConnector.js: CLIENT connected to 45332, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:21.148Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:21.149Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:06:26.151Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:26.152Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27,
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
,E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:06:31.167Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:31.167Z SendDataConnector.js: Connect (retry count 3) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:31.168Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:31.169Z SendDataConnector.js: do connect now,
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 492)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 492)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 492)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 492)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 492)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 54858
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 54858
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:06:31.839Z SendDataConnector.js: CLIENT connected to 54858, error: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:31.840Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:31.840Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,V/KeepSync( 4403): Connecting to GoogleApiClient
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1782): Handling authorization failure
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
,V/KeepSync( 4403): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4403): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4403): IOException
E/KeepSync( 4403): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4403): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4403): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4403): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4403): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4403): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4403): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4403): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4403): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4403): 	... 10 more
W/KeepSync( 4403): Sync result 2
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1162660, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:06:36.841Z SendDataConnector.js: re-try now : 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:36.842Z SendDataConnector.js: ReStart called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T11:06:41.850Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:41.852Z SendDataConnector.js: Connect (retry count 4) to peer 08:EC:A9:50:76:27 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:41.854Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:06:41.854Z SendDataConnector.js: do connect now
,I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Thali Test (Galaxy A3) 08:EC:A9:50:76:27
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Thali Test (Galaxy A3) in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 495)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 495)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 495)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 495)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 495)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 56358
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 56358
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:06:44.217Z SendDataConnector.js: CLIENT connected to 56358, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:44.218Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:44.221Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams,
I/jxcore-log( 3219): 2015-12-01T11:06:44.228Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): ---- gotta redo : 08:EC:A9:50:76:27, try count now: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Connect to fake peer: E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:44.233Z SendDataConnector.js: Start called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:06:44.233Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:06:44.233Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 08:EC:A9:50:76:27 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b7a4 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): cancel: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): ,	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readInt(BluetoothSocket.java:523)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:315)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 3274): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:70, channel:-1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Cancelled: Connection timeout
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Cancelled: Connection timeout [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
,W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/jxcore-log( 3219): 2015-12-01T11:07:14.246Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:14.247Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:14.248Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-sdp  ( 3274): SDP - Rcvd conn cnf with error: 0x22  CID 0x4e
,E/bt-btif ( 3274): DISCOVERY_COMP_EVT slot id:70, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3274): invalid rfc slot id: 70
,I/jxcore-log( 3219): 2015-12-01T11:07:19.248Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:19.249Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): 2015-12-01T11:07:24.254Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:24.254Z SendDataConnector.js: Connect (retry count 1) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:24.255Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:24.256Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E,
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btif ( 3274): PORT_StartCnf failed result:5
W/bt-rfcomm( 3274): PORT_StartCnf failed result:5
W/bt-btif ( 3274): invalid rfc slot id: 71
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/BluetoothBondStateMachine( 3274): No record of the device:null
I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 9 Address: E0:DB:10:1F:C9:5E newState: 0
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3274): Device not in IRK list
E/BluetoothBondStateMachine( 3274): In stable state, received invalid newState: 10
E/bt-btif ( 3274): Do not find the bg connection mask for the remote device
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/jxcore-log( 3219): 2015-12-01T11:07:28.969Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:28.969Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:28.970Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3219): 2015-12-01T11:07:33.971Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:33.972Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:38.976Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:38.977Z SendDataConnector.js: Connect (retry count 2) to peer E0:DB:10:1F:C9:5E with availability status: true,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:38.977Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:38.978Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10,
D/        ( 3274): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,W/bt-rfcomm( 3274): PORT_StartCnf failed result:5
,W/bt-btif ( 3274): invalid rfc slot id: 72
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3274): Device not in IRK list
E/bt-btif ( 3274): Do not find the bg connection mask for the remote device
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
I/BluetoothBondStateMachine( 3274): No record of the device:null
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 9 Address: E0:DB:10:1F:C9:5E newState: 0
I/jxcore-log( 3219): 2015-12-01T11:07:43.992Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
E/BluetoothBondStateMachine( 3274): In stable state, received invalid newState: 10
I/jxcore-log( 3219): 2015-12-01T11:07:43.992Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
I/jxcore-log( 3219): 2015-12-01T11:07:43.995Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/UsageStatsService(  823): User[0] Flushing usage stats to disk
,I/jxcore-log( 3219): 2015-12-01T11:07:48.996Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:48.997Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/BooksSync( 4518): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4518): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4518): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4518): Soft error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4518): Sync error
E/BooksSync( 4518): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4518): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4518): Finished books sync
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1235860, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3219): 2015-12-01T11:07:54.000Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:54.001Z SendDataConnector.js: Connect (retry count 3) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:07:54.003Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:54.004Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null E0:DB:10:1F:C9:5E
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-rfcomm( 3274): check_cod: remote_cod = 0x5a0
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
W/bt-btif ( 3274): invalid rfc slot id: 73
E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3274): Device not in IRK list
E/bt-btif ( 3274): Do not find the bg connection mask for the remote device
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1,
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at android.bluetooth.BluetoothSocket.connect(BluetoothSocket.java:319)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread.run(BluetoothClientThread.java:84)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Failed to connect to socket/initiate handshake
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1
,I/BluetoothBondStateMachine( 3274): No record of the device:null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 9 Address: E0:DB:10:1F:C9:5E newState: 0
,E/BluetoothBondStateMachine( 3274): In stable state, received invalid newState: 10
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Either the socket connection or the construction of a handshake thread failed: read failed, socket might closed or timeout, read ret: -1 [E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): shutdown
,I/jxcore-log( 3219): 2015-12-01T11:07:58.010Z SendDataConnector.js: CLIENT connected to -1, error: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,I/jxcore-log( 3219): 2015-12-01T11:07:58.011Z SendDataConnector.js: CLIENT Can not Connect: Connection to peer with ID E0:DB:10:1F:C9:5E failed
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:07:58.012Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:03.012Z SendDataConnector.js: re-try now : E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:03.013Z SendDataConnector.js: ReStart called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:08.018Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:08.018Z SendDataConnector.js: Connect (retry count 4) to peer E0:DB:10:1F:C9:5E with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:08.019Z SendDataConnector.js: doConnect called with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:08.020Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID E0:DB:10:1F:C9:5E
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address E0:DB:10:1F:C9:5E
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3274): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
D/BluetoothAdapterProperties( 3274): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 502)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 502)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 502)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 502)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 502)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [E0:DB:10:1F:C9:5E samsung-SM-N9005_PT5487 E0:DB:10:1F:C9:5E]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: E0:DB:10:1F:C9:5E, name: samsung-SM-N9005_PT5487, Bluetooth address: E0:DB:10:1F:C9:5E
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 49017
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 49017
,I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:08:09.723Z SendDataConnector.js: CLIENT connected to 49017, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:09.724Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:09.728Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: E0:DB:10:1F:C9:5E
I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:08:09.736Z SendDataConnector.js: Mobile.Disconnect() callback with peer E0:DB:10:1F:C9:5E
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : E0:DB:10:1F:C9:5E, try count now: 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:09.742Z SendDataConnector.js: Start called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:09.742Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:09.742Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer E0:DB:10:1F:C9:5E done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a5d4 rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [f4:f1:e1:5c:3b:e2]: 7, 1d, 7d3
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: XT1039
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Note3-1
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 505)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 505)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 505)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 505)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 505)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 57832
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 57832
,I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:08:14.141Z SendDataConnector.js: CLIENT connected to 57832, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:14.142Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:14.142Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:08:19.144Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:19.146Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F4:F1:E1:5C:3B:E2
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams,
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:08:24.155Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:24.156Z SendDataConnector.js: Connect (retry count 1) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:24.157Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:24.158Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 508)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 508)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 508)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 508)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 508)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 37590
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 37590
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:08:24.928Z SendDataConnector.js: CLIENT connected to 37590, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:24.928Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:24.929Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:08:29.931Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:29.932Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F4:F1:E1:5C:3B:E2
,I/io.jxcore.node.OutgoingSocketThread( 3219): close,
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:08:34.937Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:34.941Z SendDataConnector.js: Connect (retry count 2) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:34.942Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:34.944Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x7):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 511)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 511)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 511)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 511)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 511)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 49159
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 49159
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:08:36.041Z SendDataConnector.js: CLIENT connected to 49159, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:36.042Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:36.043Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:08:41.043Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:41.044Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 513)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 513)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 513)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 513)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 513
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 513)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 513)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283,
I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:08:45.828Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/jxcore-log( 3219): 2015-12-01T11:08:46.050Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:08:46.050Z SendDataConnector.js: Connect (retry count 3) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:46.051Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:46.052Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=0
W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 518)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 518)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 518)
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 518),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 518)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 34407
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 34407
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:08:48.819Z SendDataConnector.js: CLIENT connected to 34407, error: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:48.819Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:48.820Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
,W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:08:53.821Z SendDataConnector.js: re-try now : F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:53.822Z SendDataConnector.js: ReStart called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 20
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 514
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/jxcore-log( 3219): 2015-12-01T11:08:57.197Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b7a4 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4e
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 520)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 520)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b7a4 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at blb.a(PG:3937)
E/HttpOperation( 4367): 	at czp.a(PG:18188)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 12 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 14 more
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 520)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 520)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 520
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 520)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 520)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:08:58.095Z SendDataTCPServer.js: TCP/IP server connected,
I/jxcore-log( 3219): 
,I/art     (  823): Explicit concurrent mark sweep GC freed 37884(1828KB) AllocSpace objects, 8(316KB) LOS objects, 32% free, 33MB/49MB, paused 2.218ms total 90.851ms,
,I/GLSUser ( 1503): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1503): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1503): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1503): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1503): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4367): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4367): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4367): 	at jdm.a(PG:82)
E/HttpOperation( 4367): 	at jcs.o(PG:406)
E/HttpOperation( 4367): 	at jcn.a(PG:1379)
E/HttpOperation( 4367): 	at jcs.i(PG:143)
E/HttpOperation( 4367): 	at hec.a(PG:42)
E/HttpOperation( 4367): 	at hee.a(PG:102)
E/HttpOperation( 4367): 	at czr.a(PG:65)
E/HttpOperation( 4367): 	at kka.a(PG:108)
E/HttpOperation( 4367): 	at czp.a(PG:19176)
E/HttpOperation( 4367): 	at czp.a(PG:9081)
E/HttpOperation( 4367): 	at czq.run(PG:1686)
E/HttpOperation( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4367): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4367): 	at jdj.a(PG:4091)
E/HttpOperation( 4367): 	at jdj.a(PG:1125)
E/HttpOperation( 4367): 	at jdm.a(PG:77)
E/HttpOperation( 4367): 	... 15 more
E/HttpOperation( 4367): Caused by: faj: BadAuthentication
E/HttpOperation( 4367): 	at fal.a(PG:38)
E/HttpOperation( 4367): 	at jdj.a(PG:4089)
E/HttpOperation( 4367): 	... 17 more
,E/ExperimentLoader( 4367): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
,E/ExperimentLoader( 4367): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4367): 	at jdm.a(PG:82)
E/ExperimentLoader( 4367): 	at jcs.o(PG:406)
E/ExperimentLoader( 4367): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4367): 	,at jcs.i(PG:143)
E/ExperimentLoader( 4367): 	at hec.a(PG:42)
E/ExperimentLoader( 4367): 	at hee.a(PG:102)
E/ExperimentLoader( 4367): 	at czr.a(PG:65)
,E/ExperimentLoader( 4367): 	at kka.a(PG:108),
E/ExperimentLoader( 4367): 	at czp.a(PG:19176)
E/ExperimentLoader( 4367): 	at czp.a(PG:9081)
E/ExperimentLoader( 4367): 	at czq.run(PG:1686)
E/ExperimentLoader( 4367): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 4367): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4367): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4367): 	at java.lang.Thread.run(Thread.java:818),
E/ExperimentLoader( 4367): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4367): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4367): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4367): 	at jdm.a(PG:77)
E/ExperimentLoader( 4367): 	,... 15 more
E/ExperimentLoader( 4367): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4367): 	at fal.a(PG:38)
E/ExperimentLoader( 4367): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4367): ,	... 17 more
E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,D/SyncManager(  823): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1304450, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F4:F1:E1:5C:3B:E2
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:08:58.832Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:58.832Z SendDataConnector.js: Connect (retry count 4) to peer F4:F1:E1:5C:3B:E2 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:08:58.833Z SendDataConnector.js: doConnect called with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:08:58.833Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: XT1039 F4:F1:E1:5C:3B:E2
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to XT1039 in address F4:F1:E1:5C:3B:E2
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 525)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 525)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 525)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=1
W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 525)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 525)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F4:F1:E1:5C:3B:E2 motorola-XT1039_PT7559 F4:F1:E1:5C:3B:E2]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F4:F1:E1:5C:3B:E2, name: motorola-XT1039_PT7559, Bluetooth address: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 47245
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 47245
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:09:00.063Z SendDataConnector.js: CLIENT connected to 47245, error: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:00.064Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections,
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:00.067Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F4:F1:E1:5C:3B:E2
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
,E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:09:00.073Z SendDataConnector.js: Mobile.Disconnect() callback with peer F4:F1:E1:5C:3B:E2
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : F4:F1:E1:5C:3B:E2, try count now: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:00.080Z SendDataConnector.js: Start called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:00.082Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:00.082Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F4:F1:E1:5C:3B:E2 done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6a07c rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F4:F1:E1:5C:3B:E2, alias=null, name=XT1039, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: XT1039
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 1
W/bt-btif ( 3274): proc dm_pm_timer expires
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [38:94:96:b5:06:dc]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b96c rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 1
,E/bt-btif ( 3274): check_cod: remote_cod = 0x001f00
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:38:94:96:B5:06:DC OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 38:94:96:B5:06:DC newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: 38:94:96:B5:06:DC
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:38:94:96:B5:06:DC OldState: 11 NewState: 10
,W/BackupManagerService(  823): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 528)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 528)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 528)
,W/BackupManagerService(  823): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,W/BackupManagerService(  823): dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 528),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 528)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT5358, Bluetooth address: 38:94:96:B5:06:DC
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 38:94:96:B5:06:DC
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 41452
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 41452
,I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:09:06.672Z SendDataConnector.js: CLIENT connected to 41452, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:06.672Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:06.673Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 78
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 521
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T11:09:08.763Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4a
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 530)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 530),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 530),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 530)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 530
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 530)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 530)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:09:08.863Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:09:11.674Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:11.675Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 38:94:96:B5:06:DC
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:09:16.684Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:16.684Z SendDataConnector.js: Connect (retry count 1) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:16.685Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:16.686Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 535)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 535)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 535),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 535),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 535)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT5358, Bluetooth address: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 45560
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 45560
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:09:17.223Z SendDataConnector.js: CLIENT connected to 45560, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:17.224Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:17.224Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 80
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 531
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/jxcore-log( 3219): 2015-12-01T11:09:19.193Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0
W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x44
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 537)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 537)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 537)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 537)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 537
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 537)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 537)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
,I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:09:20.297Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:09:22.225Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:22.226Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:09:27.232Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:27.233Z SendDataConnector.js: Connect (retry count 2) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:27.234Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:27.234Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND,
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 542)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 542),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 542)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 542),
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 542)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT5358, Bluetooth address: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 42502
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 42502
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:09:28.615Z SendDataConnector.js: CLIENT connected to 42502, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:28.615Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:28.616Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 83
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 538
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
,E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T11:09:30.702Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x49
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 544)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 544)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 544)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 544)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 544
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 544)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 544)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT4311 08:EC:A9:50:76:27]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 08:EC:A9:50:76:27, name: samsung-SM-A300FU_PT4311, Bluetooth address: 08:EC:A9:50:76:27
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
,I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:09:31.281Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 85
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 545
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
,E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4d
,I/jxcore-log( 3219): 2015-12-01T11:09:31.606Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6b7a4 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,I/jxcore-log( 3219): 2015-12-01T11:09:33.617Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:33.618Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Thali Test (Galaxy A3)
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:09:38.628Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:38.629Z SendDataConnector.js: Connect (retry count 3) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:38.630Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:38.630Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...,
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 549)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 549),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 549)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 549),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 549)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT5358, Bluetooth address: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed,
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 51096
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 51096
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:09:39.964Z SendDataConnector.js: CLIENT connected to 51096, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:39.964Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:39.965Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:09:44.967Z SendDataConnector.js: re-try now : 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:44.967Z SendDataConnector.js: ReStart called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 38:94:96:B5:06:DC
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:09:49.981Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:49.982Z SendDataConnector.js: Connect (retry count 4) to peer 38:94:96:B5:06:DC with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:49.983Z SendDataConnector.js: doConnect called with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:49.983Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: Galaxy S5-2 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to Galaxy S5-2 in address 38:94:96:B5:06:DC
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x13):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 552)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 552)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 552)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 82 bytes successfully (thread ID: 552)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 552)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [38:94:96:B5:06:DC samsung-SM-G800H_PT5358 38:94:96:B5:06:DC]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 38:94:96:B5:06:DC, name: samsung-SM-G800H_PT5358, Bluetooth address: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 36603
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 36603
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:09:50.860Z SendDataConnector.js: CLIENT connected to 36603, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:50.860Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:50.866Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 38:94:96:B5:06:DC
I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T11:09:50.871Z SendDataConnector.js: Mobile.Disconnect() callback with peer 38:94:96:B5:06:DC
I/jxcore-log( 3219): 
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/jxcore-log( 3219): ---- round done--------
I/jxcore-log( 3219): 
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): ---- gotta redo : 38:94:96:B5:06:DC, try count now: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:50.877Z SendDataConnector.js: Start called with peer 7C:F9:0E:37:96:AB,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:50.878Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x14):jv handle:0x0 not FOUND
I/jxcore-log( 3219): 2015-12-01T11:09:50.879Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
,W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 38:94:96:B5:06:DC done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): info:x10
D/        ( 3274): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,D/btif_config( 3274): btif_get_device_type: Device [7c:f9:0e:37:96:ab] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 1
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 10 NewState: 11,
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:37:96:AB newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: 7C:F9:0E:37:96:AB
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:7C:F9:0E:37:96:AB OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 555)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 555)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 555)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 555)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 555)
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT6469, Bluetooth address: 7C:F9:0E:37:96:AB
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 58900
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 58900
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:09:52.409Z SendDataConnector.js: CLIENT connected to 58900, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:52.410Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:09:52.410Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=38:94:96:B5:06:DC, alias=null, name=Galaxy S5-2, majorDeviceClass=7936, deviceClass=7936]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: Galaxy S5-2
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:09:57.412Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:09:57.413Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89),
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:10:02.421Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): ,
I/jxcore-log( 3219): 2015-12-01T11:10:02.422Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:02.423Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:02.423Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A5-1 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 558)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 558)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 558)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 558)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 558)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT6469, Bluetooth address: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 52108
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 52108
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:10:04.133Z SendDataConnector.js: CLIENT connected to 52108, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:04.134Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:04.134Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:10:09.135Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:09.136Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
,I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:10:14.146Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:14.146Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:37:96:AB with availability status: true,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:14.147Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:14.147Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: ,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A5-1 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND,
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 561)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 561)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 561)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 561)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 561)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT6469, Bluetooth address: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 43765
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 43765
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:10:20.438Z SendDataConnector.js: CLIENT connected to 43765, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:20.438Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:20.439Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): dm_pm_timer expires,
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:10:25.440Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:25.441Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:10:30.451Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:30.453Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:30.454Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:30.455Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): ,
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A5-1 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x17):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6bb34 rs_disc_pending=0
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 564)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 564)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 564)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 564)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 564)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT6469, Bluetooth address: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 36446
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 36446
,I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:10:31.661Z SendDataConnector.js: CLIENT connected to 36446, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:31.662Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:31.663Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:10:36.664Z SendDataConnector.js: re-try now : 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:36.665Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,I/jxcore-log( 3219): 2015-12-01T11:10:41.669Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:10:41.672Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:37:96:AB with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:41.676Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:41.677Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to A5-1 in address 7C:F9:0E:37:96:AB
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: A5-1 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to A5-1 in address 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
,W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 567)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 567)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 567)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 83 bytes successfully (thread ID: 567)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 567)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT6469 7C:F9:0E:37:96:AB]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: 7C:F9:0E:37:96:AB, name: samsung-SM-A500FU_PT6469, Bluetooth address: 7C:F9:0E:37:96:AB
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 49835
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 49835
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:10:42.191Z SendDataConnector.js: CLIENT connected to 49835, error: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:42.192Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:42.195Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: 7C:F9:0E:37:96:AB
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	,at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:10:42.199Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:37:96:AB
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- round done--------,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ---- gotta redo : 7C:F9:0E:37:96:AB, try count now: 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): do fake peer & start
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:42.202Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:42.203Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:42.204Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
W/io.jxcore.node.ConnectionHelper( 3219): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to null in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: null F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to null in address F8:95:C7:87:3C:51
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:37:96:AB done with result: Listening for incoming connections", source: file:///android_asset/www/js/thali_main.js (63)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6bb34 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x19):jv handle:0x0 not FOUND
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6bb34 rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6bcfc rs_disc_pending=1
,W/bt-btif ( 3274): bta_dm_check_av:0
W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: A5-1
,D/btif_config( 3274): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3274): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: F8:95:C7:87:3C:51
I/BluetoothBondStateMachine( 3274): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State
,E/bt-btm  ( 3274): tBTM_SEC_DEV:0xa2f6bcfc rs_disc_pending=0,
W/bt-btif ( 3274): bta_dm_check_av:0
,W/bt-btif ( 3274): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 570)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 570)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 570)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 76 bytes successfully (thread ID: 570)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 570)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 47831
I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 47831
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:10:48.618Z SendDataConnector.js: CLIENT connected to 47831, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:48.618Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:48.619Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3274): dm_pm_timer expires
,W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:10:53.621Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:53.622Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
,I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:10:58.632Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:58.634Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:58.635Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:58.635Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1a):jv handle:0x0 not FOUND
,W/bt-sdp  ( 3274): process_service_search_attr_rsp
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 573)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 573)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 573)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 76 bytes successfully (thread ID: 573)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 573)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 34626
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 34626
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:10:59.590Z SendDataConnector.js: CLIENT connected to 34626, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:10:59.591Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:10:59.591Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): dm_pm_timer expires
W/bt-btif ( 3274): dm_pm_timer expires 0
W/bt-btif ( 3274): proc dm_pm_timer expires
,I/jxcore-log( 3219): 2015-12-01T11:11:04.592Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:11:04.593Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
,I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
I/jxcore-log( 3219): 2015-12-01T11:11:09.598Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
,E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed,
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	,at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	,at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	,at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
,I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:11:09.599Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:11:09.599Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:11:09.600Z SendDataConnector.js: do connect now
I/jxcore-log( 3219): 
I/io.jxcore.node.ConnectionHelper( 3219): hasConnection: No connection with peer with ID F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): connect: 
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Trying to start connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnecting: G4-1 F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): connect: Started connecting to G4-1 in address F8:95:C7:87:3C:51
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Entering thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Trying to connect...
W/BluetoothAdapter( 3219): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3274): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND,
,W/bt-sdp  ( 3274): process_service_search_attr_rsp,
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:1,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Outgoing connection initialized (thread ID: 576)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 576)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 576)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): onBytesRead: Read 76 bytes successfully (thread ID: 576)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 3219): Handshake succeeded with [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 576)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [F8:95:C7:87:3C:51 LGE-LG-H815_PT920 F8:95:C7:87:3C:51]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing connection, peer ID: F8:95:C7:87:3C:51, name: LGE-LG-H815_PT920, Bluetooth address: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Outgoing socket thread created successfully
,I/io.jxcore.node.OutgoingSocketThread( 3219): Server socket local port: 50107
,I/io.jxcore.node.ConnectionHelper( 3219): Outgoing connection is using port 50107
I/io.jxcore.node.OutgoingSocketThread( 3219): Now accepting connections...
,I/jxcore-log( 3219): 2015-12-01T11:11:10.477Z SendDataConnector.js: CLIENT connected to 50107, error: Listening for incoming connections
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): 2015-12-01T11:11:10.477Z SendDataConnector.js: CLIENT Can not Connect: Listening for incoming connections
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:11:10.478Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): timeout now
I/jxcore-log( 3219): 
I/jxcore-log( 3219): dun
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): weAreDoneNow , resultArray.length: 0
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): done, now sending data to server
I/jxcore-log( 3219): 
I/jxcore-log( 3219): DBG, CoordinatorConnector sendData called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): -- RESULT DATA {"name:":"motorola-Nexus 6_PT3700","time":1000087,"result":"TIMEOUT","sendList":[{"connections":1,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:9D:93:0B","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":1,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":1,"name":"80:01:84:8A:B3:68","time":0,"result":"Fail"},{"connections":1,"name":"B4:CE:F6:AB:A4:6A","time":0,"result":"Fail"},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":1,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":1,"name":"34:FC:EF:11:B1:66","time":0,"result":"Fail"},{"connections":1,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":1,
,I/jxcore-log( 3219): sendList : 100% : undefined ms, 99% : undefined ms, 95 : undefined ms, 90% : undefined ms.
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): Results list does not contain any items
I/jxcore-log( 3219): 
I/jxcore-log( 3219): sendList failed peers count : 16 [100 %]
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : F8:95:C7:87:3C:51, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : B0:C5:59:3F:75:69, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : 80:01:84:8A:B3:68, Tried : 1
,I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : B4:CE:F6:AB:A4:6A, Tried : 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : 34:FC:EF:11:AE:67, Tried : 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : 34:FC:EF:11:B1:66, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : 08:EC:A9:50:75:41, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : 58:3F:54:73:64:C0, Tried : 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : 7C:F9:0E:51:18:22, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : 58:2A:F7:ED:96:BE, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : 08:EC:A9:50:76:27, Tried : 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : E0:DB:10:1F:C9:5E, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : F4:F1:E1:5C:3B:E2, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : 38:94:96:B5:06:DC, Tried : 1
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : 7C:F9:0E:37:96:AB, Tried : 1
I/jxcore-log( 3219): 
I/jxcore-log( 3219): sendList never tried peers count : 5 [23.80952380952381 %]
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : E0:DB:10:14:E2:C0
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : F8:95:C7:87:85:54
I/jxcore-log( 3219): 
I/jxcore-log( 3219): - Peer ID : 34:FC:EF:9D:93:0B
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): - Peer ID : 44:80:EB:7B:5A:05
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:11:12.213Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3219): 
I/jxcore-log( 3219): 2015-12-01T11:11:12.213Z SendDataConnector.js: Stop retry timer
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveOutgoingConnectionThread: Disconnecting connection, peer ID: F8:95:C7:87:3C:51
I/io.jxcore.node.OutgoingSocketThread( 3219): close
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
E/io.jxcore.node.OutgoingSocketThread( 3219): Failed to create local streams: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): java.net.SocketException: Socket closed
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.Posix.accept(Native Method)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at libcore.io.BlockGuardOs.accept(BlockGuardOs.java:63)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.PlainSocketImpl.accept(PlainSocketImpl.java:89)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at java.net.ServerSocket.implAccept(ServerSocket.java:216)
E/io.jxcore.node.OutgoingSocketThread( 3219): ,	at java.net.ServerSocket.accept(ServerSocket.java:140)
E/io.jxcore.node.OutgoingSocketThread( 3219): 	at io.jxcore.node.OutgoingSocketThread.run(OutgoingSocketThread.java:57)
I/io.jxcore.node.OutgoingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:11:12.215Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3219): 
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback *** TIMEOUT ***", source: file:///android_asset/www/js/thali_main.js (63)
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback ---- finished : send-data -- ", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3274): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive,
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: G4-1
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btif ( 3274): info:x10
,D/        ( 3274): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3274): aclStateChangeCallback: Device is NULL
,D/btif_config( 3274): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
E/bt-btif ( 3274): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3274): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3274): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3274): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterProperties( 3274): Failed to remove device: 44:80:EB:7B:5A:05
I/BluetoothBondStateMachine( 3274): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3274): StableState(): Entering Off State,
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3274): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3274): bta_dm_pm_ssr:2, lat:1200
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 578)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 578)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 578),
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 578)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 578
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 578)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 578)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
I/io.jxcore.node.ConnectionHelper( 3219): addNewPeerToListAndNotify: Adding peer with ID 44:80:EB:7B:5A:05,
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed,
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:11:31.248Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): ,
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
W/bt-btif ( 3274): invalid rfc slot id: 87
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 579
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
,I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0
W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x41
I/jxcore-log( 3219): 2015-12-01T11:11:41.688Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 582)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 582)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 582)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 582)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 582
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 582)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 582)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
,I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
,I/jxcore-log( 3219): 2015-12-01T11:11:41.758Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
,I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
,E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,W/bt-btif ( 3274): invalid rfc slot id: 98
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 583
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams,
W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
I/jxcore-log( 3219): 2015-12-01T11:11:52.183Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): ,
W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x48,
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 586)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 586)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 586)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 586)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 586
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 586)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 586)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
,I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
,I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
,I/jxcore-log( 3219): 2015-12-01T11:11:52.302Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 99
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
,I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 587
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T11:12:02.684Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x43
,W/bt-btif ( 3274): new conn_srvc id:26, app_id:255
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection accepted,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Incoming connection initialized (thread ID: 590)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Entering thread (ID: 590)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesRead: Read 81 bytes successfully (thread ID: 590)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Got valid identity from [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): onBytesWritten: 82 bytes successfully written (thread ID: 590)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): removeThreadFromList: Removing thread with ID 590
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Handshake thread disposed (thread ID: 590)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothSocketIoThread( 3219): Exiting thread (ID: 590),
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnected: [44:80:EB:7B:5A:05 motorola-XT1072_PT6938 44:80:EB:7B:5A:05]
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming connection, peer ID: 44:80:EB:7B:5A:05, name: motorola-XT1072_PT6938, Bluetooth address: 44:80:EB:7B:5A:05
I/io.jxcore.node.IncomingSocketThread( 3219): Constructed
I/io.jxcore.node.ConnectionHelper( 3219): onConnected: Incoming socket thread using port 0 and is now connected
,I/io.jxcore.node.IncomingSocketThread( 3219): Entering thread
I/io.jxcore.node.IncomingSocketThread( 3219): Local host address: localhost/127.0.0.1, port: 43283
I/io.jxcore.node.IncomingSocketThread( 3219): Local streams created successfully, starting stream copying threads...
,I/io.jxcore.node.SocketThreadBase( 3219): startStreamCopyingThreads: OK
I/io.jxcore.node.IncomingSocketThread( 3219): Exiting thread
I/jxcore-log( 3219): 2015-12-01T11:12:02.777Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3219): 
,W/bt-btif ( 3274): invalid rfc slot id: 100
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: bt socket closed, read return: -1
E/io.jxcore.node.SocketThreadBase( 3219): The receiving thread failed with error "onDisconnected: bt socket closed, read return: -1", this is likely due to peer having disconnected
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: bt socket closed, read return: -1
I/io.jxcore.node.ConnectionHelper( 3219): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 591
,I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping receiving thread...
I/io.jxcore.node.SocketThreadBase( 3219): close: Stopping sending thread...
I/io.jxcore.node.SocketThreadBase( 3219): closeLocalSocketAndStreams
I/io.jxcore.node.SocketThreadBase( 3219): closeBluetoothSocketAndStreams
,W/io.jxcore.node.StreamCopyingThread( 3219): onDisconnected: Socket closed
E/io.jxcore.node.SocketThreadBase( 3219): Unidentified stream copying thread failed with error: onDisconnected: Socket closed
I/io.jxcore.node.ConnectionHelper( 3219): onDisconnected: onDisconnected: Socket closed
,I/jxcore-log( 3219): 2015-12-01T11:12:03.111Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3219): 
,W/bt-rfcomm( 3274): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0,
W/bt-rfcomm( 3274): RFCOMM_DisconnectInd LCID:0x4e
,E/bt-btm  ( 3274): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3274): onReceive
,I/BTConnectionReceiver( 4164): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 4164): Bluetooth Device Name: XT1072
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3274): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3274): Stopping oneshot timer
,I/jxcore-log( 3219): DBG, CoordinatorConnector command called
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): command received : {"command":"stop","testName":"","testData":"","devices":"","addressList":[]},
I/jxcore-log( 3219): ,
I/jxcore-log( 3219): stop tests now !
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): stop current!
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): testSendData stopped
I/jxcore-log( 3219): 
,I/io.jxcore.node.ConnectionHelper( 3219): stop
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: INITIALIZED
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): 	,at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread.run(BluetoothServerThread.java:91)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Socket is null
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onIncomingConnectionFailed: Socket is null
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 3219): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 3219): onServerStopped
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): setState: NOT_INITIALIZED
I/jxcore-log( 3219): StopBroadcasting went ok
I/jxcore-log( 3219): ,
,I/jxcore-log( 3219): 2015-12-01T11:15:32.216Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
,I/jxcore-log( 3219): 
I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback stop", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: INITIALIZED
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Failed to accept socket: read failed, socket might closed or timeout, read ret: -1
W/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 3219): onConnectionFailed: Socket is null
,I/io.jxcore.node.ConnectionHelper( 3219): onConnectionManagerStateChanged: NOT_INITIALIZED
,I/jxcore-log( 3219): DBG, CoordinatorConnector command called,
I/jxcore-log( 3219): 
,I/jxcore-log( 3219): command received : {"command":"end","testName":"results","testData":"{\"result\":{\"sendList\":[],\"sendError\":{\"failedPeer\":[{\"connections\":1,\"name\":\"F8:95:C7:87:3C:51\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B0:C5:59:3F:75:69\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"80:01:84:8A:B3:68\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"B4:CE:F6:AB:A4:6A\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"00:F4:6F:30:E0:6C\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:AE:67\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"34:FC:EF:11:B1:66\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"08:EC:A9:50:75:41\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:3F:54:73:64:C0\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"7C:F9:0E:51:18:22\",\"time\":0,\"result\":\"Fail\"},{\"connections\":1,\"name\":\"58:2A:F7:ED:96:BE\",\"time\":0,\"result\":\",
,I/jxcore-log( 3219): ****TEST TOOK:  ms ****,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3219): 
I/jxcore-log( 3219): stop tests now !
I/jxcore-log( 3219): 
I/jxcore-log( 3219): end, event received,
I/jxcore-log( 3219): 
I/jxcore-log( 3219): CoordinatorConnector close called
I/jxcore-log( 3219): 
I/jxcore-log( 3219): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3219): 
I/jxcore-log( 3219): The Coordinator has disconnected!
I/jxcore-log( 3219): 
I/jxcore-log( 3219): The Coordinator has closed!
I/jxcore-log( 3219): 
I/jxcore-log( 3219): stop tests now !
I/jxcore-log( 3219): 
I/jxcore-log( 3219): turning Radios off
I/jxcore-log( 3219): 
I/jxcore-log( 3219): Toggling radios to false
I/jxcore-log( 3219): 
D/BluetoothManagerService(  823): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
D/BluetoothManagerService(  823): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2600f40c mBinding = false
,D/BluetoothManagerService(  823): Message: 2
,D/BluetoothManagerService(  823): Sending off request.
D/WifiService(  823): setWifiEnabled: false pid=3219, uid=10265
E/WifiService(  823): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterState( 3274): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3274): Setting state to 13
I/BluetoothAdapterState( 3274): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3274): onBluetoothDisable()
I/BluetoothAdapterState( 3274): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3274): Scan Mode:20
D/BluetoothAdapterState( 3274): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothMapMasInstance( 3274): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3274): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3274): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 3274): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 3274): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 3274): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3274): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3274): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 3274): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 3274): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 3274): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 3274): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3274): L2CAP - PSM: 0x0017 not found for deregistration
,E/WifiStateMachine(  823): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  823): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/jxcore-log( 3219): Radios toggled
I/jxcore-log( 3219): 
E/native  (  823): do suspend true
,I/chromium( 3219): [INFO:CONSOLE(63)] "logCallback fully-closed", source: file:///android_asset/www/js/thali_main.js (63)
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1503): Read error: ssl=0xaed02400: I/O error during system call, Connection timed out
V/NativeCrypto( 1503): SSL shutdown failed: ssl=0xaed02400: I/O error during system call, Broken pipe
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  823): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  823): scanCount==0 - aborting
,D/ConnectivityService(  823): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  823): Bluetooth State Change Intent: 12 -> 13
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/WifiScanningService(  823): SCAN_AVAILABLE : 1
D/RttService(  823): SCAN_AVAILABLE : 1
D/WifiScanningService(  823): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  823): DefaultState
D/RttService(  823): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothMapService( 3274): onReceive
D/BluetoothMapService( 3274): STATE_TURNING_OFF
D/BluetoothMapService( 3274): MAP Service closeService in
D/BluetoothMapMasInstance( 3274): MAP Service shutdown
I/BtOppRfcommListener( 3274): stopping Accept Thread
I/BtOppRfcommListener( 3274): BluetoothSocket listen thread finished
D/WifiNetworkAgent(  823): NetworkAgent: NetworkAgent channel lost
E/native  (  823): do suspend true
,W/ContextImpl( 4659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,I/ActivityManager(  823): Start proc 5236:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/ConnectivityService(  823): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
E/WifiStateMachine(  823): SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
D/CSLegacyTypeTracker(  823): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1064): CM callback handler got msg 524292
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  823): Disconnected - quitting
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  823): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/ConnectivityService(  823): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering(  823): MasterInitialState.processMessage what=3
,D/ConnectivityService(  823): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
D/BluetoothManagerService(  823): Message: 30
,I/wpa_supplicant( 3284): p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,I/wpa_supplicant( 3284): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 4659): Adding local MAP profile
,D/BluetoothMap( 4659): Create BluetoothMap proxy object
,D/BluetoothManagerService(  823): Message: 30
,E/GpsLocationProvider(  823): No APN found to select.
,D/BluetoothManagerService(  823): Message: 30
,D/LocalBluetoothProfileManager( 4659): LocalBluetoothProfileManager construction complete
D/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1276): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  823): getDataEnabled: retVal=false
,D/DockEventReceiver( 4659): finishStartingService: stopping service
E/GpsLocationProvider(  823): No APN found to select.
,D/BluetoothInputDevice( 4659): Proxy object connected
D/HidProfile( 4659): Bluetooth service connected
D/BluetoothPan( 4659): BluetoothPAN Proxy object connected
D/PanProfile( 4659): Bluetooth service connected
D/BluetoothMap( 4659): Proxy object connected
D/MapProfile( 4659): Bluetooth service connected
D/BluetoothMap( 4659): getConnectedDevices()
,D/BluetoothMap( 4659): Bluetooth is Not enabled
,D/AndroidRuntime( 5226): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 5226): CheckJNI is OFF
,W/bt-btif ( 3274): ag scb idx 1 not allocated
E/bt-btif ( 3274): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3274): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3274): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3274): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3274): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3274): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3274): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 3274): RX termination
W/bt_userial( 3274): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3274): Leaving userial_read_thread()
D/bt_userial( 3274): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 3274): hw_epilog_process
I/bt_userial_vendor( 3274): device fd = 53 close
,D/AndroidRuntime( 5226): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
,I/ActivityManager(  823): Killing 3219:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,I/GKI_LINUX( 3274): gki_task task_id=0 [BTU] terminating
,W/PackageSettings(  823): Skipping PackageSetting{149cf9f9 com.example.hello/10272} due to missing metadata
,D/Tethering(  823): InitialState.processMessage what=4
,I/wpa_supplicant( 3284): wlan0: CTRL-EVENT-TERMINATING 
E/WifiMonitor(  823): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/GKI_LINUX( 3274): GKI_exit_task 0 done
I/GKI_LINUX( 3274): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3274): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,I/WindowState(  823): WIN DEATH: Window{3d27f399 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  823): Client connection lost with reason: 4
,W/ActivityManager(  823): Force removing ActivityRecord{cdf6326 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
,V/ActivityManager(  823): Display changed displayId=0
,D/Tethering(  823): sendTetherStateChangedBroadcast 0, 0, 0
W/ActivityManager(  823): Spurious death for ProcessRecord{4ac3a4b 3219:com.test.thalitest/u0a265}, curProc for 3219: null
,D/HeadsetService( 3274): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 3274): Exit Disconnected: -1
,I/ActivityManager(  823): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,W/Settings( 4307): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Keyboard.Facilitator( 1202): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1202): run()
I/Decoder ( 1202): createOrResetDecoder
,D/TaskPersister(  823): removeObsoleteFile: deleting file=24_task.xml
I/InputReader(  823): Reconfiguring input devices.  changes=0x00000010
D/BluetoothAdapterState( 3274): Stopping profile services that were post enabled
,W/Settings( 1748): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/A2dpService( 3274): Received stop request...Stopping profile...
D/A2dpStateMachine( 3274): Exit Disconnected: -1
,D/HidService( 3274): Received stop request...Stopping profile...
,D/HeadsetStateMachine( 3274): Unbinding service...
,W/BluetoothHeadsetServiceJni( 3274): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3274): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 3274): Received stop request...Stopping profile...
D/PanService( 3274): Received stop request...Stopping profile...
,D/BtGatt.DebugUtils( 3274): handleDebugAction() action=null
,D/BtGatt.GattService( 3274): Received stop request...Stopping profile...
D/BtGatt.GattService( 3274): stop()
D/BtGatt.AdvertiseManager( 3274): advertise clients cleared
,D/BluetoothMapService( 3274): Received stop request...Stopping profile...
,D/BluetoothMapService( 3274): stop()
D/BluetoothMapEmailAppObserver( 3274): deinitObservers()
D/BluetoothMapEmailAppObserver( 3274): removeReceiver()
I/GKI_LINUX( 3274): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3274): GKI_exit_task 2 done
I/GKI_LINUX( 3274): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 3274): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3274): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3274): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3274): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3274): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3274): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3274): Cleaning up Bluetooth PAN callback object
,D/BluetoothMapService( 3274): MAP Service closeService in
D/BluetoothAdapterState( 3274): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothMapService( 3274): cleanup()
D/BluetoothAdapterProperties( 3274): Setting state to 10
D/BluetoothMapService( 3274): MAP Service closeService in
I/BluetoothAdapterState( 3274): Bluetooth adapter state changed: 13-> 10
D/BluetoothManagerService(  823): Message: 60
D/BluetoothManagerService(  823): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  823): Broadcasting onBluetoothStateChange(false) to 17 receivers.
,I/BluetoothAdapterState( 3274): Entering OffState
D/BluetoothHeadset( 1276): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1276): Proxy object disconnected
D/BluetoothHeadset(  823): onBluetoothStateChange: up=false
D/BluetoothHeadset(  823): Proxy object disconnected
D/BluetoothHeadset(  823): onBluetoothStateChange: up=false
D/BluetoothHeadset(  823): Proxy object disconnected
D/BluetoothPbap( 4659): onBluetoothStateChange: up=false
,D/BluetoothMap( 1064): onBluetoothStateChange: up=false
D/BluetoothA2dp(  823): onBluetoothStateChange: up=false
D/BluetoothHeadset(  823): onBluetoothStateChange: up=false
D/BluetoothHeadset(  823): Proxy object disconnected
D/BluetoothHeadset( 1064): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1064): Proxy object disconnected
,D/BluetoothAvrcpController( 1064): onBluetoothStateChange: up=false
E/BluetoothAvrcpController( 1064): 
E/BluetoothAvrcpController( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothAvrcpController$2@949591f
E/BluetoothAvrcpController( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothAvrcpController( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothAvrcpController( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.BluetoothAvrcpController$1.onBluetoothStateChange(BluetoothAvrcpController.java:80)
E/BluetoothAvrcpController( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothAvrcpController( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
,D/BluetoothInputDevice( 4659): onBluetoothStateChange: up=false
D/BluetoothA2dpSink( 1064): onBluetoothStateChange: up=false
E/BluetoothA2dpSink( 1064): 
E/BluetoothA2dpSink( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothA2dpSink$2@1a5c946c
E/BluetoothA2dpSink( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothA2dpSink( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothA2dpSink( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.BluetoothA2dpSink$1.onBluetoothStateChange(BluetoothA2dpSink.java:139)
E/BluetoothA2dpSink( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothA2dpSink( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothInputDevice( 1064): onBluetoothStateChange: up=false
,D/BluetoothMap( 4659): onBluetoothStateChange: up=false
,D/BluetoothHeadsetClient( 1064): onBluetoothStateChange: up=false
,E/BluetoothHeadsetClient( 1064): 
E/BluetoothHeadsetClient( 1064): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothHeadsetClient$2@262c4a35
E/BluetoothHeadsetClient( 1064): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1029)
E/BluetoothHeadsetClient( 1064): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1808)
E/BluetoothHeadsetClient( 1064): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:551)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.BluetoothHeadsetClient$1.onBluetoothStateChange(BluetoothHeadsetClient.java:382)
E/BluetoothHeadsetClient( 1064): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55),
E/BluetoothHeadsetClient( 1064): 	at android.os.Binder.execTransact(Binder.java:446)
D/BluetoothA2dp( 1064): onBluetoothStateChange: up=false
D/BluetoothManagerService(  823): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  823): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  823): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2600f40c mBinding = false
,D/BluetoothManagerService(  823): Sending unbind request.
,D/BluetoothManagerService(  823): Bluetooth State Change Intent: 13 -> 10
,I/art     ( 1064): Explicit concurrent mark sweep GC freed 76595(3MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 74MB/90MB, paused 1.258ms total 60.679ms
,D/BluetoothAdapter( 1064): 520772658: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1064): 520772658: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1064): 520772658: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 3274): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3274): GKI_exit_task 1 done
I/GKI_LINUX( 3274): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3274): cleanupNative: return from cleanup
,I/art     ( 3274): System.exit called, status: 0
I/AndroidRuntime( 3274): VM exiting with result code 0, cleanup skipped.
,I/art     (  823): Explicit concurrent mark sweep GC freed 39202(2MB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.526ms total 110.926ms
,W/InputMethodManagerService(  823): Got RemoteException sending setActive(false) notification to pid 3219 uid 10265
,I/Keyboard.Facilitator( 1202): onFinishInput()
,I/ConfigService( 1503): onCreate
,I/ActivityManager(  823): Process com.android.bluetooth (pid 3274) has died
,D/JobSchedulerService(  823): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  823): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     ( 1294): Explicit concurrent mark sweep GC freed 11979(677KB) AllocSpace objects, 9(1078KB) LOS objects, 31% free, 35MB/51MB, paused 1.654ms total 20.582ms
,D/StrictMode( 5236): StrictMode policy violation; ~duration=554 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5236): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5236): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5236): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 5236): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 5236): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 5236): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 5236): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=553 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5236): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5236): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5236): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=550 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5236): 	at libcore.io.IoUtils,.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5236): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5236): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5236): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5236): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 5236): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 5236): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=546 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 5236): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 5236): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=540 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5236): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 5236): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 5236): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 5236): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 5236): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=211 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 5236): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 5236): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 5236): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 5236): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 5236): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 5236): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 5236): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 5236): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 5236): # via Binder call with stack:
D/StrictMode( 5236): android.os.StrictMode$LogStackTrace
D/StrictMode( 5236): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 5236): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 5236): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 5236): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 5236): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 5236): 	at android.content.ContentResolver.query(ContentResolver.java:422)
D/StrictMode( 5236): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 5236): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 5236): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 5236): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 5236): 	at java.io.File.exists(File.java:363)
D/StrictMode( 5236): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 5236): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 5236): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 5236): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 5236): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 5236): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5236): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 5236): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 5236): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 5236): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 5236): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 5236): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 5236): StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 5236): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 5236): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 5236): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 5236): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 5236): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 5236): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 5236): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 5236): 	at com.google.p.j.a(PG:121)
D/StrictMode( 5236): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 5236): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 5236): 	at com.google.p.e.a(PG:170)
D/StrictMode( 5236): 	at com.google.p.e.b(PG:21)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 5236): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 5236): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 5236): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 5236): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 5236): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 5236): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 5236): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 5236): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 5236): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 5236): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
I/art     ( 1503): Explicit concurrent mark sweep GC freed 79646(3MB) AllocSpace objects, 9(993KB) LOS objects, 36% free, 27MB/43MB, paused 1.304ms total 32.845ms
I/art     ( 1748): Explicit concurrent mark sweep GC freed 23997(1386KB) AllocSpace objects, 10(183KB) LOS objects, 37% free, 27MB/43MB, paused 13.321ms total 94.938ms
W/com.google.a.a.a.b.a( 5236): Application name is not set. Call Builder#setApplicationName.
E/DataBuffer( 1748): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@205eb6a6)
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1202): run()
D/BluetoothManagerService(  823): Message: 20
D/BluetoothManagerService(  823): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f78bf06:true
D/AuthorizationBluetoothService( 1503): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/MusicLeanback( 3461): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1202): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1202): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1202): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1202): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1202): run()
I/StatsUtilsManager( 1202): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1202): shouldRecordStats() = Too Soon
,I/art     (  823): Explicit concurrent mark sweep GC freed 8084(400KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.401ms total 189.285ms
,I/ActivityManager(  823): Start proc 5291:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/Launcher.Workspace( 1294): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1294): 11683562 - stripEmptyScreens()
,D/SprintDMReceiver( 5291): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 5291): simOperator:  IMSI: null
D/SprintDMReceiver( 5291): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,I/art     ( 5226): System.exit called, status: 0
,I/AndroidRuntime( 5226): VM exiting with result code 0.
D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ValidateNoPeople(  823): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599988 ms
I/iu.UploadsManager( 1782): num queued entries: 0
I/iu.UploadsManager( 1782): num updated entries: 0
,I/iu.SyncManager( 1782): NEXT; no task
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,I/ActivityManager(  823): Start proc 5316:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/Babel   ( 4307): connection state changed from UNKNOWN to DISCONNECTED
,I/VS.Container( 4164): create_recognizer
,E/Search.SharedPreferencesProto( 4164): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/Icing   ( 1782): Received bad json for section weights override -- ignoring.
W/Icing   ( 1782): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 1782): Received bad json for section weights override -- ignoring.
W/Icing   ( 1782): Received bad json for corpus context scoring override -- ignoring.
I/HotwordRecognitionRnr( 4164): Starting hotword detection.
,I/MicrophoneInputStream( 4164): mic_starting com.google.android.apps.gsa.speech.audio.u@19d3c8bd
,I/AudioFlinger(  358): AudioFlinger's thread 0xb4098000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 4164): mic_started com.google.android.apps.gsa.speech.audio.u@19d3c8bd
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,I/GAv4    ( 5316): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5316):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5316):   adb logcat -s GAv4
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,W/GAv4    ( 5316): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5316): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5316): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5316): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5316): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5316): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5316): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5316): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 5316): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5316): Failed to open database '/data/data/com.google.android.apps.magazines/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5316): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5316): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5316): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5316): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj$zza.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.zzb(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.zzie(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzj.isEmpty(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzl.zzis(Unknown Source)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.analytics.internal.zzl$3.run(Unknown Source)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5316): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5316): 	at com.google.android.gms.measurement.MeasurementService$zzc.run(Unknown Source)
E/GAv4    ( 5316): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/GAv4    ( 5316): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5316): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5316): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 5316): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 5316): Couldn't rename file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.magazines/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,I/HotwordWorker( 4164): onReady
,E/NSDepend( 5316): Could not load library: pdflib.dex.jar
E/NSDepend( 5316): java.io.FileNotFoundException: /data/data/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
E/NSDepend( 5316): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/NSDepend( 5316): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/NSDepend( 5316): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:202)
E/NSDepend( 5316): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:190)
E/NSDepend( 5316): 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:138)
E/NSDepend( 5316): 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:1368)
E/NSDepend( 5316): 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:1315)
E/NSDepend( 5316): 	at com.google.apps.dots.android.newsstand.NSDepend$3.doInBackground(NSDepend.java:1348)
E/NSDepend( 5316): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
E/NSDepend( 5316): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
E/NSDepend( 5316): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/NSDepend( 5316): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/NSDepend( 5316): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/NSDepend( 5316): 	at com.google.android.libraries.bind.async.Queue$3$1.run(Queue.java:103)
E/NSDepend( 5316): 	at java.lang.Thread.run(Thread.java:818)
E/NSDepend( 5316): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/NSDepend( 5316): 	at libcore.io.Posix.open(Native Method)
E/NSDepend( 5316): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/NSDepend( 5316): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/NSDepend( 5316): 	... 14 more
,I/WebViewFactory( 5316): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5316): Time to load native libraries: 1 ms (timestamps 257-258)
,I/LibraryLoader( 5316): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5316): Binding Chromium to main looper Looper (main, tid 1) {204d9718}
I/LibraryLoader( 5316): Expected native library version number "",actual native library version number ""
,I/chromium( 5316): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5316): Initializing chromium process, singleProcess=true
,W/art     ( 5316): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5316): ApplicationContext is null in ApplicationStatus
,W/chromium( 5316): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 5316): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 5316): Requires BLUETOOTH permission
,I/NSApplication( 5316): Starting up...
,I/ActivityManager(  823): Killing 3811:com.google.android.gms.unstable/u0a11 (adj 15): empty #17

```
