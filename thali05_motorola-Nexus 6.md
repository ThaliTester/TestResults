#### Test 51790364a0f6051_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 23821(1252KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 1.316ms total 28.264ms
I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2726): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2726): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2726): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3186): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3186): CheckJNI is OFF
D/AndroidRuntime( 3186): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{2f054726 token=Token{20529a81 ActivityRecord{261c0668 u0 com.test.thalitest/.MainActivity t24}}} to stack=1 task=24 at 0
D/AndroidRuntime( 3186): Shutting down VM
I/HotwordDetector( 1511): Closing mic
I/MicrophoneInputStream( 1511): mic_close com.google.android.apps.gsa.speech.audio.u@30f77aaa
V/WindowManager(  820): Adding window Window{1ed53b03 u0 Starting com.test.thalitest} at 3 of 8 (after Window{2866641b u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
I/ActivityManager(  820): Start proc 3200:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1511): Hotword detection finished
I/HotwordRecognitionRnr( 1511): Stopping hotword detection.
W/GCoreFlp( 1747): No location to return for getLastLocation()
I/ActivityManager(  820): Killing 2685:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660839187
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/ActivityManager(  820): Killing 2818:com.google.android.gm.exchange/u0a77 (adj 15): empty #18
,I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
,E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,I/WebViewFactory( 3200): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3200): Time to load native libraries: 3 ms (timestamps 1083-1086)
I/LibraryLoader( 3200): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3200): Binding Chromium to main looper Looper (main, tid 1) {7866f6c}
,I/LibraryLoader( 3200): Expected native library version number "",actual native library version number ""
I/chromium( 3200): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3200): Initializing chromium process, singleProcess=true
W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3200): ApplicationContext is null in ApplicationStatus
,W/chromium( 3200): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3200): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3200): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 3200): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3200): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b8aeaf3:true
,D/BluetoothAdapter( 3200): 801739799: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3200): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3200): CordovaWebView is running on device made by: motorola
,W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring,
W/art     ( 3200): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3200): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3200): Validating map...
,V/WindowManager(  820): Adding window Window{11c476e3 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 3 of 9 (before Window{1ed53b03 u0 Starting com.test.thalitest})
,W/chromium( 3200): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3200): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3200): Enabling debug mode 0
,I/Keyboard.Facilitator( 1208): onFinishInput()
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +749ms (total +1m48s953ms)
,W/BindingManager( 3200): Cannot call determinedVisibility() - never saw a connection for the pid: 3200
,D/JsMessageQueue( 3200): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3200): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576401152
,D/JX-Cordova( 3200): jxcore cordova android initializing
,I/kickstart(  871): STATUS: Received file 'm9kefs1'
I/kickstart(  871): STATUS: 950272 bytes transferred in 0.984281 seconds
I/kickstart(  871): STATUS: Successfully downloaded files from target 
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  871): STATUS: Sahara protocol completed
,W/jxcore-log( 3200): Initializing JXcore engine
W/jxcore-log( 3200): JXcore engine is ready
,W/jxcore-log( 3200): Starting JXcore engine
,W/.test.thalitest( 3200): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10707]" dev="sockfs" ino=10707 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3200): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 3200): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10859]" dev="sockfs" ino=10859 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 3200): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[21945]" dev="sockfs" ino=21945 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0,
,W/jxcore-log( 3200): Platform android
W/jxcore-log( 3200): 
W/jxcore-log( 3200): Process ARCH arm
W/jxcore-log( 3200): 
,I/jxcore-log( 3200): JXcore Cordova bridge is ready!
I/jxcore-log( 3200): 
W/jxcore-log( 3200): JXcore engine is started
,I/Choreographer( 3200): Skipped 139 frames!  The application may be doing too much work on its main thread.,
,I/chromium( 3200): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 3200): Toggling radios to true
I/jxcore-log( 3200): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,D/BluetoothManagerService(  820): enable():  mBluetooth =null mBinding = false,
,D/BluetoothManagerService(  820): Message: 1,
,D/BluetoothManagerService(  820): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  820): setWifiEnabled: true pid=3200, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  820): New client listening to asynchronous messages
,D/SoftapController(  354): Softap fwReload - Ok
,I/jxcore-log( 3200): Radios toggled
I/jxcore-log( 3200): 
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0,
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  820): Start proc 3260:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3266): Successfully initialized wpa_supplicant
,I/ActivityManager(  820): Start proc 3277:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,W/ResourcesManager( 3260): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3266): rfkill: Cannot open RFKILL control device
,I/art     (  820): Explicit concurrent mark sweep GC freed 19685(991KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.264ms total 69.515ms
,D/AdapterServiceConfig( 3260): Adding HeadsetService
D/AdapterServiceConfig( 3260): Adding A2dpService
D/AdapterServiceConfig( 3260): Adding HidService
D/AdapterServiceConfig( 3260): Adding HealthService
D/AdapterServiceConfig( 3260): Adding PanService
D/AdapterServiceConfig( 3260): Adding GattService
D/AdapterServiceConfig( 3260): Adding BluetoothMapService
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5c767a4:true
D/BluetoothAdapterState( 3260): make
,I/bluedroid( 3260): init
I/BluetoothAdapterState( 3260): Entering OffState
,I/bte_conf( 3260): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3260): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3260): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3260): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 3260): get_profile_interface socket
I/bluedroid( 3260): get_profile_interface map_client
I/GKI_LINUX( 3260): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 3260): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
,D/BluetoothAdapterProperties( 3260): Name is: Nexus 6
,D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  820): Message: 40
,D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 3260): config_hci_snoop_log
,D/BluetoothManagerService(  820): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceUp() to 7 receivers.
,D/BluetoothAdapterState( 3260): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 3260): Setting state to 11
,I/BluetoothAdapterState( 3260): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  820): Message: 60
,D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3260): make
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,I/BluetoothAdapterState( 3260): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
,D/HeadsetService( 3260): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3260): classInitNative: succeeds
D/HeadsetStateMachine( 3260): make
,I/ActivityManager(  820): Start proc 3312:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  820): Killing 2849:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/HeadsetStateMachine( 3260): max_hf_connections = 1
I/bluedroid( 3260): get_profile_interface handsfree
D/HeadsetStateMachine( 3260): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
,D/BluetoothA2dp(  820): Proxy object connected
D/BluetoothA2dp( 1059): Proxy object connected
,D/A2dpService( 3260): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3260): classInitNative: succeeds
I/bluedroid( 3260): get_profile_interface avrcp
,E/RemoteController( 3260): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3260): classInitNative: succeeds
D/A2dpStateMachine( 3260): make
,I/bluedroid( 3260): get_profile_interface a2dp
I/GKI_LINUX( 3260): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3260): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3260): classInitNative: succeeds
D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
,D/BluetoothInputDevice( 1059): Proxy object connected
D/HidService( 3260): Received start request. Starting profile...,
I/bluedroid( 3260): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3260): classInitNative: succeeds
D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
,D/HealthService( 3260): Received start request. Starting profile...
,I/bluedroid( 3260): get_profile_interface health
,I/BluetoothPanServiceJni( 3260): classInitNative(L105): succeeds
,D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
,D/BluetoothPan( 1059): BluetoothPAN Proxy object connected,
,D/PanService( 3260): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3260): initializeNative(L110): pan
I/bluedroid( 3260): get_profile_interface pan
I/BtGatt.JNI( 3260): classInitNative(L873): classInitNative: Success!
D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
D/BtGatt.DebugUtils( 3260): handleDebugAction() action=null
D/BtGatt.GattService( 3260): Received start request. Starting profile...
D/BtGatt.GattService( 3260): start()
I/bluedroid( 3260): get_profile_interface gatt
D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
D/BtGatt.AdvertiseManager( 3260): advertise manager created
,D/BluetoothAdapterService( 3260): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b88935
,D/BluetoothMap( 1059): Proxy object connected
D/BluetoothMapService( 3260): Received start request. Starting profile...
D/BluetoothMapService( 3260): start()
,D/BluetoothMapEmailSettingsLoader( 3260): Found 0 applications
D/BluetoothMapEmailAppObserver( 3260): createReceiver()
,D/BluetoothMapEmailAppObserver( 3260): initObservers()
D/BluetoothMapEmailAppObserver( 3260): getEnabledAccountItems()
,D/HeadsetStateMachine( 3260): Proxy object connected
D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3260): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3260): Disconnected process message: 11, size: 0
D/BluetoothAdapterState( 3260): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3260): enable
I/bt_hci_bdroid( 3260): init
,I/GKI_LINUX( 3260): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3260): btu_task pending for preload complete event
,I/bt_vendor( 3260): init
I/bt_vnd_conf( 3260): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3260): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3260): userial_init
,I/bt_userial_vendor( 3260): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3260): device fd = 53 open,
D/bt_userial( 3260): Entering userial_read_thread()
,I/bt_hwcfg( 3260): bt vendor lib: set UART baud 3000000
,I/ActivityManager(  820): Start proc 3347:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  820): Killing 2784:com.google.android.gm/u0a78 (adj 15): empty #17
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 12.817ms
,D/bt_hwcfg( 3260): Chipset BCM4354A2
D/bt_hwcfg( 3260): Target name = [BCM4354A2]
I/bt_hwcfg( 3260): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 278us total 11.709ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 205us total 8.987ms
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  820): Killing 2356:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/wpa_supplicant( 3266): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3266): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3260): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 3260): Settlement delay -- 100 ms
I/bt_hwcfg( 3260): Setting fw settlement delay to 100 
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@835d39c}
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,I/bt_hwcfg( 3260): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3260): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/ActivityManager(  820): Start proc 3365:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/WifiNative-HAL(  820): Setting external_sim to 1
,D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xb4bbad18
D/WifiHAL (  820): Sending mac address OUI
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/bt_hwcfg( 3260): vendor lib fwcfg completed
I/bt-btu  ( 3260): btu_task received preload complete event
,I/        ( 3260): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3260): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3260): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3260): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3260): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3260): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3260): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3260): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3260): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3260): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3260): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3260): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3260): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3260): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3260): BTE_InitTraceLevels -- TRC_BTIF
,E/WifiStateMachine(  820): cancelDelayedScan -> 1,
,D/WifiScanningService(  820): SCAN_AVAILABLE : 3
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/RttService(  820): SCAN_AVAILABLE : 3
D/WifiScanningService(  820): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4bbad18
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
,D/CommandListener(  354): Setting iface cfg
,E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,I/wpa_supplicant( 3266): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  820): p2pGetDeviceAddress
D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/native  (  820): do suspend false
,E/bt-btm  ( 3260): BTM_SecRegister:p_cb_info->p_le_callback == 0xa2e0a085 
E/bt-btm  ( 3260): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa2e0a085 
,D/BluetoothAdapterProperties( 3260): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3260): Calling BTA_HhEnable
,E/bt-btif ( 3260): btif_storage_get_adapter_property service_mask:0x2140040
,D/BluetoothAdapterProperties( 3260): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
,D/BluetoothAdapterProperties( 3260): Name is: Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
,W/bt-btm  ( 3260): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3260): Scan Mode:20
,D/BluetoothAdapterProperties( 3260): Discoverable Timeout:120
,D/bte_conf( 3260): Device ID record 1 : primary
,D/bte_conf( 3260):   vendorId            = 000f
,D/bte_conf( 3260):   vendorIdSource      = 0001
D/bte_conf( 3260):   product             = 1200
D/bte_conf( 3260):   version             = 1436
D/bte_conf( 3260):   clientExecutableURL = 
D/bte_conf( 3260):   serviceDescription  = 
D/bte_conf( 3260):   documentationURL    = 
D/bte_conf( 3260): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3260): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3260): ScanMode =  20
D/BluetoothAdapterProperties( 3260): State =  11
D/BluetoothAdapterProperties( 3260): Setting state to 12
,I/BluetoothAdapterState( 3260): Bluetooth adapter state changed: 11-> 12
D/BluetoothPanServiceJni( 3260): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(true) to 13 receivers.
I/BluetoothAdapterState( 3260): Entering On State
D/BluetoothA2dp( 1059): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1059): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 3260): Scan Mode:21
D/BluetoothAdapterProperties( 3260): Discoverable Timeout:120
,E/BluetoothAvrcpController( 1059): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothManagerService(  820): Creating new ProfileServiceConnections object for profile: 1
,D/BluetoothMap( 1059): onBluetoothStateChange: up=true
D/BluetoothPan( 1059): onBluetoothStateChange(on) call bindService
,E/bt_h4   ( 3260): vendor lib postload completed
,D/BluetoothHeadsetClient( 1059): onBluetoothStateChange: up=true
,E/BluetoothHeadsetClient( 1059): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1059): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothInputDevice( 1059): onBluetoothStateChange: up=true
D/BluetoothA2dp(  820): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1059): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1059): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
,D/BluetoothHeadset( 1272): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  820): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  820): Message: 40
,D/BluetoothMapService( 3260): onReceive
D/BluetoothMapService( 3260): STATE_ON
D/BluetoothMapMasInstance( 3260): Map Service startRfcommSocketListener
,D/BluetoothMapMasInstance( 3260): MAS initSocket()
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3260): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 3260): Accepting socket connection...
,D/StrictMode( 3365): StrictMode policy violation; ~duration=239 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3365): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3365): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3365): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3365): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3365): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3365): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3365): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=239 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3365): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3365): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3365): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3365): StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3365): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3365): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3365): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3365): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3365): 	at java.lang.System.loadLibrary(System.java:988)
,D/StrictMode( 3365): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3365): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	,at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3365): StrictMode policy violation; ~duration=232 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202)
D/StrictMode( 3365): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3365): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
D/StrictMode( 3365): ,	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	,at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3365): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3365): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3365): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3365): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3365): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): ,	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3365): 	,at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3365): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3365): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3365): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
D/StrictMode( 3365): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3365): # via Binder call with stack:
D/StrictMode( 3365): android.os.StrictMode$LogStackTrace
D/StrictMode( 3365): 	,at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3365): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3365): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3365): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3365): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3365): 	at android.content.ContentResolver.query(ContentResolver.java:422),
D/StrictMode( 3365): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3365): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3365): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323),
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	,at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3365): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3365): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3365): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3365): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3365): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3365): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149),
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3365): ,	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3365): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3365): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3365): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	,at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	,at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3365): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3365): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3365): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3365): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
,D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
,D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3365): StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3365): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3365): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229),
D/StrictMode( 3365): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3365): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3365): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3365): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3365): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3365): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3365): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3365): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3365): 	,at com.google.p.e.a(PG:170)
D/StrictMode( 3365): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3365): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3365): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3365): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553),
D/StrictMode( 3365): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3365): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3365): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3365): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3365): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3365): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3365): 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3365): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
W/com.google.a.a.a.b.a( 3365): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b4ed559:true
,I/ActivityManager(  820): Killing 2887:com.google.android.music:main/u0a66 (adj 15): empty #17
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 1059): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset( 1272): Proxy object connected
,D/AuthorizationBluetoothService( 1483): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3347): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ecb1693:true
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3260): getBluetoothService() called with no BluetoothManagerCallback
,D/AuthorizationBluetoothService( 1483): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LocalBluetoothProfileManager( 3347): Adding local A2DP profile
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3347): Adding local HEADSET profile
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): Message: 30
,W/BluetoothAdapter( 3260): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3260): Accept thread started.
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3347): Adding local MAP profile
,D/BluetoothMap( 3347): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3347): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3347): finishStartingService: stopping service
,D/BluetoothA2dp( 3347): Proxy object connected
,D/A2dpProfile( 3347): Bluetooth service connected
,D/BluetoothInputDevice( 3347): Proxy object connected
D/HidProfile( 3347): Bluetooth service connected
,D/BluetoothPan( 3347): BluetoothPAN Proxy object connected
D/PanProfile( 3347): Bluetooth service connected
D/BluetoothMap( 3347): Proxy object connected
D/MapProfile( 3347): Bluetooth service connected
D/BluetoothMap( 3347): getConnectedDevices()
,D/BluetoothPbap( 3347): Proxy object connected
D/PbapServerProfile( 3347): Bluetooth service connected
,D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 3347): Proxy object connected
D/HeadsetProfile( 3347): Bluetooth service connected
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/jxcore-log( 3200): Got Device Bluetooth address: F8:CF:C5:D9:E5:61
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): my name is : motorola-Nexus 6_PT2145
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): attempting to connect to test coordinator
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): check test folder
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): found test : ./testFindPeers.js
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): found test : ./testReConnect.js
I/jxcore-log( 3200): ,
,I/jxcore-log( 3200): found test : ./testSendData.js
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Test app app.js loaded
I/jxcore-log( 3200): 
,I/Choreographer( 3200): Skipped 136 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/wpa_supplicant( 3266): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 3266): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3266): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3266): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3266): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 1
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -43
E/WifiStateMachine(  820):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=58 rx_time=98 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3407): version 5.5.6 starting
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/dhcpcd  ( 3407): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 3407): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 3407): wlan0: leased 192.168.1.110 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 100
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 100
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,D/ConnectivityService(  820): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  820): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/BackupManagerService(  820): Scheduling immediate backup pass
D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/ActivityManager(  820): Start proc 3445:com.google.android.music:main/u0a66 for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver,
,V/BackupManagerService(  820): Running a backup pass
V/BackupManagerService(  820): clearing pending backups
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 2
,V/PerformBackupTask(  820): Beginning backup of 14 targets
,E/GpsLocationProvider(  820): No APN found to select.
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,V/BackupServiceBinder(  820): doBackup() invoked
,D/AlarmManagerService(  820): Setting time of day to sec=1448520630
W/AlarmManagerService(  820): Unable to set rtc to 1448520630: Invalid argument
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 26 Nov 2015 06:50:30 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448520630043], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448520630394]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/GpsLocationProvider(  820): NTP server returned: 1448520630047 (Thu Nov 26 07:50:30 GMT+01:00 2015) reference: 150190 certainty: 22 system time offset: -35
,I/BackupRestoreController(  820): Getting widget state for user: 0
,I/GoogleURLConnFactory( 1483): Using platform SSLCertificateSocketFactory
,I/MusicStore( 3445): Database version: 120
,W/GmsBackupTransport( 1747): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1747): starting performBackup for @pm@
,V/GmsBackupTransport( 1747): performBackup done for @pm@
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Auth.Api.Credentials( 1782): [CredentialSyncAdapter] Unknown sync event.
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 14128(769KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 1.012ms total 22.427ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 49704(2MB) AllocSpace objects, 3(48KB) LOS objects, 32% free, 33MB/49MB, paused 1.674ms total 84.100ms
,W/DriveInitializer( 1782): Background init thread started
,I/ConfigService( 1483): onCreate
,I/ConfigFetchService( 1782): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1782): running network task: configservice_periodic
,E/WakeLock( 1782): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1782): launchTask
,I/ConfigFetchService( 1782): service connected
,D/ConfigFetchService( 1782): ConfigApi connection successful.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,W/DriveInitializer( 1782): Awaiting to be initialized
W/DriveInitializer( 1782): Background init thread ended
,W/GmsBackupTransport( 1747): Error sending final backup to server: 
W/GmsBackupTransport( 1747): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1747): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1747): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1747): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1747): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1747): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1747): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1747): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1747): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1747): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1747): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1747): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1747): 	... 1 more
,D/BackupManagerService(  820): Now staging backup of com.google.android.talk
,D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  820): Now staging backup of com.google.android.gm
,W/ResourcesManager( 3445): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3445): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  820): Now staging backup of com.android.nfc
,D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  820): Now staging backup of com.android.vending
,D/BackupManagerService(  820): Now staging backup of android
,D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1747): Next backup will happen in 43199941 millis.
,I/BackupManagerService(  820): Backup pass finished.
,V/JNIHelp ( 3445): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3445): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 3445): GMSCore installation verified
,I/ConfigStore( 3445): Config Database version: 1
,I/MediaRouter( 3445): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GoogleAuthProtoRequest( 3277): [331] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2974): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 2974): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2974): 	at jdm.a(PG:82)
E/HttpOperation( 2974): 	at jcs.o(PG:406)
E/HttpOperation( 2974): 	at jcn.a(PG:1379)
E/HttpOperation( 2974): 	at jcs.i(PG:143)
E/HttpOperation( 2974): 	at blb.a(PG:3937)
E/HttpOperation( 2974): 	at czp.a(PG:18188)
E/HttpOperation( 2974): 	at czp.a(PG:9081)
E/HttpOperation( 2974): 	at czq.run(PG:1686)
E/HttpOperation( 2974): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2974): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2974): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2974): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2974): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2974): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2974): 	at jdj.a(PG:4091)
E/HttpOperation( 2974): 	at jdj.a(PG:1125)
E/HttpOperation( 2974): 	at jdm.a(PG:77)
E/HttpOperation( 2974): 	... 12 more
E/HttpOperation( 2974): Caused by: faj: BadAuthentication
E/HttpOperation( 2974): 	at fal.a(PG:38)
E/HttpOperation( 2974): 	at jdj.a(PG:4089)
E/HttpOperation( 2974): 	... 14 more
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,V/KeepSync( 3312): Connecting to GoogleApiClient
,I/ActivityManager(  820): Start proc 3512:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/GHttpClientFactory( 3445): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GoogleURLConnFactory( 3445): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 2974): [getmobileexperiments] Unexpected exception
E/HttpOperation( 2974): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 2974): 	at jdm.a(PG:82)
E/HttpOperation( 2974): 	at jcs.o(PG:406)
E/HttpOperation( 2974): 	at jcn.a(PG:1379)
E/HttpOperation( 2974): 	at jcs.i(PG:143)
E/HttpOperation( 2974): 	at hec.a(PG:42)
E/HttpOperation( 2974): 	at hee.a(PG:102)
E/HttpOperation( 2974): 	at czr.a(PG:65)
E/HttpOperation( 2974): 	at kka.a(PG:108)
E/HttpOperation( 2974): 	at czp.a(PG:19176)
E/HttpOperation( 2974): 	at czp.a(PG:9081)
E/HttpOperation( 2974): 	at czq.run(PG:1686)
E/HttpOperation( 2974): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 2974): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 2974): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 2974): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 2974): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 2974): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 2974): 	at jdj.a(PG:4091)
E/HttpOperation( 2974): 	at jdj.a(PG:1125)
E/HttpOperation( 2974): 	at jdm.a(PG:77)
E/HttpOperation( 2974): 	... 15 more
E/HttpOperation( 2974): Caused by: faj: BadAuthentication
E/HttpOperation( 2974): 	at fal.a(PG:38)
E/HttpOperation( 2974): 	at jdj.a(PG:4089)
E/HttpOperation( 2974): 	... 17 more
,E/ExperimentLoader( 2974): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2974): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 2974): 	at jdm.a(PG:82)
E/ExperimentLoader( 2974): 	at jcs.o(PG:406)
E/ExperimentLoader( 2974): 	at jcn.a(PG:1379)
E/ExperimentLoader( 2974): 	at jcs.i(PG:143)
E/ExperimentLoader( 2974): 	at hec.a(PG:42)
E/ExperimentLoader( 2974): 	at hee.a(PG:102)
E/ExperimentLoader( 2974): 	at czr.a(PG:65)
E/ExperimentLoader( 2974): 	at kka.a(PG:108)
E/ExperimentLoader( 2974): 	at czp.a(PG:19176)
E/ExperimentLoader( 2974): 	at czp.a(PG:9081)
E/ExperimentLoader( 2974): 	at czq.run(PG:1686)
E/ExperimentLoader( 2974): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 2974): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 2974): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 2974): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 2974): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 2974): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 2974): 	at jdj.a(PG:4091)
E/ExperimentLoader( 2974): 	at jdj.a(PG:1125)
E/ExperimentLoader( 2974): 	at jdm.a(PG:77)
E/ExperimentLoader( 2974): 	... 15 more
E/ExperimentLoader( 2974): Caused by: faj: BadAuthentication
E/ExperimentLoader( 2974): 	at fal.a(PG:38)
E/ExperimentLoader( 2974): 	at jdj.a(PG:4089)
E/ExperimentLoader( 2974): 	... 17 more
W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,W/BaseAppContext( 1782): Using Auth Proxy for data requests.
,D/SprintDMReceiver( 3512): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3512): simOperator:  IMSI: null
,D/SprintDMReceiver( 3512): Not Sprint UICC, don't do anything.
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 19691(1136KB) AllocSpace objects, 2(55KB) LOS objects, 37% free, 26MB/42MB, paused 2.748ms total 39.503ms
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/SystemUpdateService( 1782): active receiver: enabled
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
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/KeepSync( 3312): GoogleApiClient failed to connect with error code: 4
,I/CheckinService( 1782): Checking schedule, now: 1448520630832 next: 1448484404816
I/CheckinService( 1782): active receiver: enabled
,I/iu.SyncManager( 1782): SYNC; picasa accounts
,E/SQLiteLog( 3312): (284) automatic index on blob_node(is_deleted)
,I/SystemUpdateService( 1782): showing system update notification
D/NetworkLogImpl( 1782): Loaded NetworkSpeedPredictor
,E/SQLiteLog( 3312): (284) automatic index on blob_node(is_deleted)
D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 36157, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
E/SQLiteLog( 3312): (284) automatic index on blob_node(is_deleted)
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/CheckinService( 1782): Preparing to send checkin request
,I/EventLogService( 1782): Accumulating logs since 1448520291069
,I/iu.UploadsManager( 1782): num queued entries: 0
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/iu.UploadsManager( 1782): num updated entries: 0
,I/iu.SyncManager( 1782): NEXT; no task
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599946 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,I/EventLogService( 1782): Opted in for usage reporting
,W/ExperimentUpdateService( 3277): [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  820): Start proc 3546:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,I/ActivityManager(  820): Start proc 3566:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 2640): connection state changed from DISCONNECTED to CONNECTED
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
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/EventLogAggregator( 1782): Unknown tag: snet_gcore
W/EventLogAggregator( 1782): Unknown tag: snet_launch_service
,I/GAv4    ( 3566): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3566):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3566):   adb logcat -s GAv4
,W/GAv4    ( 3566): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3566): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  820): Explicit concurrent mark sweep GC freed 26226(1213KB) AllocSpace objects, 5(121KB) LOS objects, 32% free, 33MB/49MB, paused 1.613ms total 60.668ms
,D/GCM     ( 1483): Connected
,W/GAv4    ( 3566): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinRequestBuilder( 1782): Checkin reason type: 12 attempt count: 1
,D/GCM     ( 1483): Message class com.google.f.a.a.p
,D/WifiService(  820): New client listening to asynchronous messages
,E/ActivityThread( 1782): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  820): Start proc 3596:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,W/ResourcesManager( 3596): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3596): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/KeepSync( 3312): IOException
E/KeepSync( 3312): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3312): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3312): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3312): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3312): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3312): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3312): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3312): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3312): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3312): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3312): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3312): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3312): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3312): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3312): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3312): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3312): 	... 10 more
W/KeepSync( 3312): Sync result 2
,I/MultiDex( 3596): VM with version 2.1.0 has multidex support
I/MultiDex( 3596): install
I/MultiDex( 3596): VM has multidex support, MultiDex support library is disabled.
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 36159, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
I/ActivityManager(  820): Killing 2206:com.android.providers.calendar/u0a3 (adj 15): empty #17
,V/JNIHelp ( 3596): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/WebViewFactory( 3566): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 1782): Explicit concurrent mark sweep GC freed 12745(1022KB) AllocSpace objects, 13(208KB) LOS objects, 35% free, 29MB/45MB, paused 1.254ms total 44.160ms
,I/ProviderInstaller( 3596): Installed default security provider GmsCore_OpenSSL
,I/LibraryLoader( 3566): Time to load native libraries: 1 ms (timestamps 1512-1513)
I/LibraryLoader( 3566): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 3566): Binding Chromium to main looper Looper (main, tid 1) {2e5ccc39}
,I/LibraryLoader( 3566): Expected native library version number "",actual native library version number ""
I/chromium( 3566): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3566): Initializing chromium process, singleProcess=true
W/art     ( 3566): Attempt to remove local handle scope entry from IRT, ignoring
I/jxcore-log( 3200): BLE supported!!
I/jxcore-log( 3200): 
E/SysUtils( 3566): ApplicationContext is null in ApplicationStatus
W/chromium( 3566): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3566): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3566): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3566): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/WVCdm   (  358): Instantiating CDM.
,I/WVCdm   (  358): CdmEngine::OpenSession
,I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,W/GAV2    ( 3546): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 3546): Created application version: 3.6.8 (30608)
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,W/AudioManagerAndroid( 3566): Requires BLUETOOTH permission
,I/GoogleURLConnFactory( 3596): Using platform SSLCertificateSocketFactory
,I/NSApplication( 3566): Starting up...
,I/ActivityManager(  820): Killing 1366:android.process.acore/u0a5 (adj 15): empty #17
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
,D/DrmLibTime(  313): got the req here! ret=0,
D/DrmLibTime(  313): command id, time_cmd_id = 770
,D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1448520631
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 724759218
,D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1448520631; nsec = 724759218
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xb3e03940
,D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb5876770, dataLength=8
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4010000, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d67440, idLength=0xbefeb2f0
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=183059820
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4067200
D/DrmWidevineDash(  358): message_length=1598, signature=0xb4029c80, signature_length=3204362964
,I/ActivityManager(  820): Start proc 3666:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/BooksSync( 3546): Starting books sync for 61035162, extras: ade
,W/CheckinRequestBuilder( 1782): awaiting user notification for token
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 25921(1434KB) AllocSpace objects, 5(362KB) LOS objects, 37% free, 26MB/42MB, paused 6.781ms total 29.765ms
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,I/GoogleURLConnFactory( 3596): Using platform SSLCertificateSocketFactory
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/BooksConfig( 3546): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3546): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
E/BooksSync( 3546): Soft error
E/BooksSync( 3546): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3546): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3546): Sync error
E/BooksSync( 3546): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3546): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 3546): Finished books sync
,D/DrmLibTime(  313): got the req here! ret=0
D/DrmLibTime(  313): command id, time_cmd_id = 770
D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
,D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1448520632
D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 245293749
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1448520632; nsec = 245293749
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 36160, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
I/ActivityManager(  820): Killing 3085:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xb3e03940
D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb58766c8, dataLength=8
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb400fa00, wrapped_rsa_key_length=1280
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d67440, idLength=0xb3085710
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9,
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=2959191498
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4067900
D/DrmWidevineDash(  358): message_length=1599, signature=0xb5880100, signature_length=3003668212
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
,D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
,D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/ActivityManager(  820): Killing 3107:com.android.musicfx/u0a18 (adj 15): empty #17
,I/dex2oat ( 3691): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 3691): dex2oat took 40.112ms (threads: 4) arena alloc=123KB java alloc=18KB native alloc=1243KB free=6MB
,I/Adreno  ( 3596): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ActivityManager(  820): Start proc 3697:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,V/Herrevad( 1782): NQAS connected
,I/Adreno  ( 3596): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,E/SQLiteLog( 3697): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  820): Start proc 3718:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,I/art     (  820): Explicit concurrent mark sweep GC freed 18508(772KB) AllocSpace objects, 3(142KB) LOS objects, 32% free, 33MB/49MB, paused 1.532ms total 67.614ms
,W/ResourcesManager( 3718): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/CalendarProvider2( 3718): Created com.android.providers.calendar.CalendarAlarmManager@9d5c01f(com.android.providers.calendar.CalendarProvider2@7866f6c)
,I/ActivityManager(  820): Start proc 3743:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/AnalyticsLogBase( 3697): PlayLogger.onLoggerConnected
,D/TimeService( 3743): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448520632964
,D/        ( 3743): TimeServiceNative: User Time to be set is 1448520632964
D/QC-time-services( 3743): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3743): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3743): Lib:time_genoff_operation: pargs->ts_val = 1448520632964
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448520632964
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1448520632964, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/13/70 3:3:33
,D/QC-time-services(  373): Daemon:Value read from RTC seconds = 8823813000
D/QC-time-services(  373): Daemon:new time 1448520632964 
D/QC-time-services(  373): Daemon: delta 1439696819964 genoff 1439696819964 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696819964 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3743): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  373): Updating the TOD offset,
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696819964 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,I/ActivityManager(  820): Killing 1815:com.google.android.gms.wearable/u0a11 (adj 15): empty #17,
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1132555832964
,E/QC-time-services( 3743): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3,
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb3b90000
,D/DrmLibTime(  313): got the req here! ret=0,
D/DrmLibTime(  313): command id, time_cmd_id = 770
,D/DrmLibTime(  313): time_getutcsec starts!
D/DrmLibTime(  313): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  313): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  313): QSEE Time Listener: seconds: 1448520633
,D/DrmLibTime(  313): QSEE Time Listener: nano seconds: 59037603
D/DrmLibTime(  313): time_getutcsec returns 0, sec = 1448520633; nsec = 59037603
D/DrmLibTime(  313): time_getutcsec finished! 
D/DrmLibTime(  313): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  313): before calling ioctl to read the next time_cmd,
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0,
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!,
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0,
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xb3e03940
D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb4daa0a8, dataLength=8
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb400f400, wrapped_rsa_key_length=1280
,I/ActivityManager(  820): Killing 3135:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb4d67480, idLength=0xb3f01710
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
,D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=3193015229
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4d7f200
D/DrmWidevineDash(  358): message_length=1634, signature=0xb4c3f2c0, signature_length=3018856180
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  358): CdmEngine::CloseSession,
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  358): Service_Uninitialize: starts!
,D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/EventLogService( 1782): Opted in for usage reporting
,I/ActivityManager(  820): Start proc 3766:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 358us total 16.789ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 334us total 14.719ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 231us total 12.185ms
,I/GAv4    ( 3766): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3766):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3766):   adb logcat -s GAv4
,W/GAv4    ( 3766): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3766): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3766): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 3040:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@835d39c}
,I/CheckinTask( 1782): Sending checkin request (9955 bytes)
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1483): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1782): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  820): Start proc 3793:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1782): Restart initialization of location
,W/ResourcesManager( 3793): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3793): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3718): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3718): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/MultiDex( 3793): VM with version 2.1.0 has multidex support
I/MultiDex( 3793): install
I/MultiDex( 3793): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3793): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3793): Installed default security provider GmsCore_OpenSSL
,D/AuthorizationBluetoothService( 1483): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GmsCoreStatsServiceLauncher( 1782): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3793): callingUid 10011, callindPid: 3793
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1782): Restart initialization of location
,E/MDM     ( 1747): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1747): [136] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/Babel   ( 2640): UserRecoverableAuthException.
,E/Babel   ( 2640): eei: BadAuthentication
E/Babel   ( 2640): 	at eeg.a(Unknown Source)
E/Babel   ( 2640): 	at eeg.a(Unknown Source)
E/Babel   ( 2640): 	at eeg.a(Unknown Source)
E/Babel   ( 2640): 	at g.a(Unknown Source)
E/Babel   ( 2640): 	at cae.a(SourceFile:3089)
E/Babel   ( 2640): 	at cae.a(SourceFile:1131)
E/Babel   ( 2640): 	at cws.a(SourceFile:4333)
E/Babel   ( 2640): 	at cws.a(SourceFile:1419)
E/Babel   ( 2640): 	at crl.a(SourceFile:492)
E/Babel   ( 2640): 	at crl.a(SourceFile:1468)
E/Babel   ( 2640): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2640): 	at cas.b(SourceFile:106)
E/Babel   ( 2640): 	at cap.d(SourceFile:335)
E/Babel   ( 2640): 	at caq.run(SourceFile:81)
,E/Babel   ( 2640): Error getting auth token
E/Babel   ( 2640): dvm
E/Babel   ( 2640): 	at g.a(Unknown Source)
E/Babel   ( 2640): 	at cae.a(SourceFile:3089)
E/Babel   ( 2640): 	at cae.a(SourceFile:1131)
E/Babel   ( 2640): 	at cws.a(SourceFile:4333)
E/Babel   ( 2640): 	at cws.a(SourceFile:1419)
E/Babel   ( 2640): 	at crl.a(SourceFile:492)
E/Babel   ( 2640): 	at crl.a(SourceFile:1468)
E/Babel   ( 2640): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2640): 	at cas.b(SourceFile:106)
E/Babel   ( 2640): 	at cap.d(SourceFile:335)
E/Babel   ( 2640): 	at caq.run(SourceFile:81)
,E/Babel   ( 2640): Account registration failed 1-Redacted-21
E/Babel   ( 2640): cyp: null -- null
E/Babel   ( 2640): 	at cae.a(SourceFile:3121)
E/Babel   ( 2640): 	at cae.a(SourceFile:1131)
E/Babel   ( 2640): 	at cws.a(SourceFile:4333)
E/Babel   ( 2640): 	at cws.a(SourceFile:1419)
E/Babel   ( 2640): 	at crl.a(SourceFile:492)
E/Babel   ( 2640): 	at crl.a(SourceFile:1468)
E/Babel   ( 2640): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2640): 	at cas.b(SourceFile:106)
E/Babel   ( 2640): 	at cap.d(SourceFile:335)
E/Babel   ( 2640): 	at caq.run(SourceFile:81)
,I/art     ( 2640): Note: end time exceeds epoch: 
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 1483): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2640): Unexpected exception while authenticating.
E/Babel   ( 2640): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2640): 	at eeg.b(Unknown Source)
E/Babel   ( 2640): 	at eeg.b(Unknown Source)
E/Babel   ( 2640): 	at g.a(Unknown Source)
E/Babel   ( 2640): 	at cae.b(SourceFile:1146)
E/Babel   ( 2640): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2640): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2640): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2640): 	at java.lang.Thread.run(Thread.java:818)
,I/CheckinResponseProcessor( 1782): From server: 1 gservices updates and 0 deletes
,I/GservicesProvider( 1483): main difference update completed
,I/ActivityManager(  820): Start proc 3831:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,I/CheckinRequestBuilder( 1782): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1782): Failed to find provider info for com.google.android.wearable.settings
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 2640): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2640): BAM#gBA: invalid account id: -1
W/Babel   ( 2640): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2640): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 31423(1672KB) AllocSpace objects, 8(882KB) LOS objects, 37% free, 26MB/42MB, paused 1.117ms total 24.832ms
,I/ActivityManager(  820): Start proc 3856:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,E/UpdateRequestReceiver( 3856): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/art     (  820): Explicit concurrent mark sweep GC freed 15226(726KB) AllocSpace objects, 3(330KB) LOS objects, 32% free, 33MB/49MB, paused 1.396ms total 48.174ms
,E/UpdateRequestReceiver( 3856): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3856): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 3856): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  820): Killing 2726:com.android.vending/u0a19 (adj 15): empty #17
,I/SystemUpdateService( 1782): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/GCM     ( 1483): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1782): Explicit concurrent mark sweep GC freed 24003(2MB) AllocSpace objects, 11(175KB) LOS objects, 35% free, 29MB/45MB, paused 1.485ms total 72.342ms
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 9218(400KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 1.189ms total 22.633ms
,D/SystemEventReceiver( 1782): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1782): Updating ocr activity enabled=false
,I/GCoreUlr( 1747): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1782): showing system update notification
,I/GCoreUlr( 1747): DispatchingService.onCreate()
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599932 ms
,D/SystemUpdateService( 1782): onDestroy
,W/CheckinRequestBuilder( 1782): awaiting user notification for token
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 13496(773KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 1.448ms total 42.512ms
,I/EventLogService( 1782): Opted in for usage reporting
,E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f533a5f)
,I/GCoreUlr( 1747): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/CheckinTask( 1782): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1782): Checking schedule, now: 1448520635104 next: 1448561778073
I/CheckinService( 1782): active receiver: disabled
,I/GCoreUlr( 1747): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1747): Unbound from all location providers
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 6355(288KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.415ms total 34.095ms
,I/GCoreUlr( 1747): DispatchingService.onDestroy()
,I/GCoreUlr( 1747): Unbound from all location providers
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=49.66 rxSuccessRate=57.44 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=49.66 rxSuccessRate=57.44 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/art     ( 1782): Explicit concurrent mark sweep GC freed 9600(603KB) AllocSpace objects, 7(112KB) LOS objects, 35% free, 29MB/45MB, paused 1.183ms total 47.276ms
,I/CheckinService( 1782): Checking schedule, now: 1448520635497 next: 1448561778073
I/CheckinService( 1782): active receiver: disabled
,I/GservicesUpdateTask( 1511): Updating Gservices keys
,E/SQLiteLog( 3718): (284) automatic index on view_events(_id)
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/MusicLeanback( 3445): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3445): Stop autocaching.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GmsUtils( 3445): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3445): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    ( 3546): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 3697): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  820): Killing 3347:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3365:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3512:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3566:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,V/ConfigFetchTask( 1782): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XG91JW59eQESrKHhUz6ovqlACif2mf_6UAmvg3jdZF7y8crV_FbCqtS69ENc_rte_GrArFs9aIVgIf5httHibZc4M0evS3iexnoy9pY22z2swIbp1ipJ2ev9Pzkq3UVZlFDAIqY8ZX0_a91uJTPTu5cl1VNYy4bPn0a3K8606UHmUIeZC5EzledtPqcIHCGjP5bJTuorIxe1JMVhwYV4ckWUdxkSRvSQZukZNIrqzBVH5JTLU
,I/GoogleURLConnFactory( 1782): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  820): Start proc 3928:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/ConfigFetchTask( 1782): updating config table for com.google.android.gms
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...,
,I/art     (  820): Explicit concurrent mark sweep GC freed 17158(850KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.695ms total 74.197ms
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/ConfigFetchService( 1782): fetch service done; releasing wakelock
,I/ConfigFetchService( 1782): stopping self
,I/ConfigFetchService( 1782): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,D/PermissionCache(  259): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (156 us)
,I/ConfigFetchService( 1782): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1782): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1782): service connected
,D/ConfigFetchService( 1782): ConfigApi connection successful.
,I/ConfigFetchService( 1782): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1782): stopping self
,I/ActivityManager(  820): Killing 2974:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3951:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,D/Finsky  ( 3928): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 3928): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/ResourcesManager( 3951): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3951): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3951): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  820): Start proc 3989:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,W/Settings( 3928): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3928): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GoogleAuthProtoRequest( 3277): [332] a.<init>: mAccountName set to: thalitester@gmail.com
,W/ResourcesManager( 3989): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3989): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ProviderInstaller( 3951): Installed default security provider GmsCore_OpenSSL
,I/MultiDex( 3989): VM with version 2.1.0 has multidex support
I/MultiDex( 3989): install
I/MultiDex( 3989): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 10419(520KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.175ms total 35.421ms
,V/JNIHelp ( 3989): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 3928): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3928): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 3928): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ProviderInstaller( 3989): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1483): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1483): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Finsky  ( 3928): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  259): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  259): hwc_setPowerMode: Setting mode 0 on display: 0
V/ActivityManager(  820): Display changed displayId=0
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1782): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 3793): callingUid 10011, callindPid: 3793
,E/MDM     ( 1747): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1782): Restart initialization of location
E/YouTube MDX( 3951): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ExperimentUpdateService( 3277): [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,I/dex2oat ( 4022): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1927949561.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads1927949561.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4022): dex2oat took 54.599ms (threads: 4) arena alloc=165KB java alloc=12KB native alloc=1090KB free=6MB
,D/Finsky  ( 3928): [405] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 3928): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 3928): [405] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,W/InstanceID/Rpc( 3951): Found 10011
,I/qdhwcomposer(  259): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  259): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl(  820): Excessive delay in setPowerMode(): 248ms
I/DreamManagerService(  820): Entering dreamland.
I/PowerManagerService(  820): Dozing...
I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 5
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1208): onFinishInput()
,E/WifiStateMachine(  820): cancelDelayedScan -> 7
,E/native  (  820): do suspend true
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@390e4292}
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3928): [1] 5.onFinished: Scheduling replication attempt 4.
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,D/Finsky  ( 3928): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3928): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 23221(1141KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 2.862ms total 90.680ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1483): Vacuum at: now=1448520642772 tag=VacuumService
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1782): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,W/Finsky  ( 3928): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GoogleURLConnFactory( 1483): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3928): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3928): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3928): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3928): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,I/ActivityManager(  820): Killing 3546:com.google.android.apps.books/u0a34 (adj 15): empty #17
,E/lowmemorykiller(  256): Error writing /proc/3546/oom_score_adj; errno=22
,D/DeviceConnectionService( 1747): client connected with version: 7571000
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 38649(2MB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.670ms total 55.294ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@390e4292}
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/PackageSettings(  820): Skipping PackageSetting{2f8d60a8 com.example.hello/10272} due to missing metadata
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided,
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,W/Uploader( 1483): No account for auth token provided
,I/ActivityManager(  820): Start proc 4107:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,V/GmsNetworkLocationProvi( 1747): DISABLE
,D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  820): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  820): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  820): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  820): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@b8fe821
,V/BackupManagerService(  820): Scheduling immediate backup pass
,V/BackupManagerService(  820): Running a backup pass
,V/BackupManagerService(  820): clearing pending backups
,V/PerformBackupTask(  820): Beginning backup of 14 targets
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,D/PackageBroadcastService( 1782): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,V/BackupServiceBinder(  820): doBackup() invoked
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/UpdateIcingCorporaServi( 1511): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageBroadcastService( 1782): Null package name or gms related package.  Ignoreing.
,V/GmsNetworkLocationProvi( 1747): ENABLE
,W/Uploader( 1483): No account for auth token provided
,V/GmsNetworkLocationProvi( 1747): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
V/GmsNetworkLocationProvi( 1747): SET-REQUEST
I/ContactLocale( 4107): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/Launcher( 1300): Deferring update until onResume
W/Launcher( 1300): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2fc99417 new=com.google.android.velvet.VelvetApplication@2fc99417
,I/Icing   ( 1782): updateResources: need to parse f{com.google.android.gms}
,V/GmsNetworkLocationProvi( 1747): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,I/BackupRestoreController(  820): Getting widget state for user: 0
I/UpdateIcingCorporaServi( 1511): UpdateCorporaTask done [took 37 ms] updated apps [took 37 ms] 
,I/ActivityManager(  820): Start proc 4133:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,W/ResourcesManager( 4133): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GmsBackupTransport( 1747): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1747): starting performBackup for @pm@
,V/GmsBackupTransport( 1747): performBackup done for @pm@
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     (  820): Explicit concurrent mark sweep GC freed 29416(1809KB) AllocSpace objects, 6(96KB) LOS objects, 31% free, 34MB/50MB, paused 915us total 54.441ms
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1747): Error sending final backup to server: 
W/GmsBackupTransport( 1747): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1747): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1747): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1747): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1747): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1747): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1747): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1747): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1747): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1747): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1747): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1747): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1747): 	... 1 more
,D/BackupManagerService(  820): Now staging backup of com.google.android.talk
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
,D/BackupManagerService(  820): Now staging backup of com.google.android.gm
,D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
,D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  820): Now staging backup of com.android.nfc
,D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  820): Now staging backup of com.android.vending
,D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  820): Now staging backup of android
,D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1747): Next backup will happen in 43199962 millis.
,I/BackupManagerService(  820): Backup pass finished.
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1483): No account for auth token provided
,I/ActivityManager(  820): Killing 3312:com.google.android.keep/u0a79 (adj 15): empty #17
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,I/ConfigService( 1483): onDestroy,
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided,
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483):  no longer exists, so no auth token.
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,I/ActivityManager(  820): Killing 3743:com.qualcomm.timeservice/1000 (adj 15): empty #17
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1483): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1483): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1483): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1483): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1483): No account for auth token provided
,W/Uploader( 1483): No account for auth token provided
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=14.00 rxSuccessRate=11.50 targetRoamBSSID=any RSSI=-44
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 4, 7 -> obsolete
,I/ActivityManager(  820): Killing 3766:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3697:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3200): 
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
,I/jxcore-log( 3200): 
,V/GoogleAuthProtoRequest( 3277): [333] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3277): [334] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [333] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [333] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3277): [334] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [334] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3928): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/ActivityManager(  820): Start proc 4168:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4168): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4168): Created application version: 3.6.8 (30608)
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 98910(5MB) AllocSpace objects, 20(1314KB) LOS objects, 36% free, 28MB/44MB, paused 1.455ms total 33.304ms
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9087)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/art     (  820): Explicit concurrent mark sweep GC freed 33102(1481KB) AllocSpace objects, 4(346KB) LOS objects, 31% free, 34MB/50MB, paused 2.457ms total 50.082ms
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 182985, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  820): Start proc 4206:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
,E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 150990, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3831:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 183688, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 3856:com.google.android.configupdater/u0a42 (adj 15): empty #17
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3928): [1] 5.onFinished: Giving up after 6 failures.
,I/GAV2    ( 4168): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,D/Finsky  ( 3928): [430] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 22275(1424KB) AllocSpace objects, 17(1874KB) LOS objects, 37% free, 26MB/42MB, paused 1.564ms total 60.728ms
,D/Finsky  ( 3928): [430] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError,
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/Keyboard.Facilitator.LanguageModelFlusher( 1208): run()
I/Keyboard.Facilitator( 1208): flushDynamicLanguageModels()
,I/ConfigService( 1483): onCreate
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/ConfigService( 1483): onDestroy
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
,E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 241296, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,V/GoogleAuthProtoRequest( 3277): [335] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3277): [336] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [335] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [335] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3277): [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/art     (  820): Explicit concurrent mark sweep GC freed 30854(1396KB) AllocSpace objects, 12(851KB) LOS objects, 32% free, 33MB/49MB, paused 1.438ms total 69.622ms
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 272088, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 276593, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0,
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Coordinator is now connected to the server!
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	,at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
,E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 331420, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,V/GoogleAuthProtoRequest( 3277): [337] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3277): [338] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [338] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [338] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3277): [337] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [337] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
,W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
,E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 423070, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/jxcore-log( 3200): DBG, CoordinatorConnector start_tests called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): DBG, CoordinatorConnector command called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): command received : {"command":"start","testName":"testSendData.js","testData":"{\"timeout\":1000000,\"rounds\":1,\"dataTimeout\":10000,\"dataAmount\":100000,\"conReTryTimeout\":5000,\"conReTryCount\":5}","devices":20,"addressList":[{"address":"F8:95:C7:87:3C:51","tryCount":0},{"address":"50:2E:6C:AC:21:50","tryCount":0},{"address":"80:01:84:8A:B3:68","tryCount":0},{"address":"7C:F9:0E:51:18:22","tryCount":0},{"address":"E0:DB:10:14:E2:C0","tryCount":0},{"address":"F8:95:C7:87:85:54","tryCount":0},{"address":"34:FC:EF:11:AE:67","tryCount":0},{"address":"B4:CE:F6:AB:A4:6A","tryCount":0},{"address":"58:2A:F7:ED:96:BE","tryCount":0},{"address":"E0:DB:10:1F:C9:5E","tryCount":0},{"address":"08:EC:A9:50:76:27","tryCount":0},{"address":"34:FC:EF:9D:93:0B","tryCount":0},{"address":"7C:F9:0E:34:8A:A0","tryCount":0},{"address":"7C:F9:0E:37:96:AB","tryCount":0},{"address":"44:80:EB:7B:5A:05","tryCount":0},{"address":"34:FC:EF:11:B1:66","tryCount":0},{"address":"B0:C5:59:3F:75:69","tryCount":0},{"address":"08:EC:A9:50:75
,I/jxcore-log( 3200): Start now : testSendData.js
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): testSendData created {"timeout":1000000,"rounds":1,"dataTimeout":10000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5}, bt-address lenght : 20
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): check server
I/jxcore-log( 3200): 
I/jxcore-log( 3200): serverPort is 41177
I/jxcore-log( 3200): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
I/        ( 3200): Start-My BT: F8:CF:C5:D9:E5:61
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0,
,I/        ( 3200):  mInstanceString : {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3200): All stuff available and enabled
,I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
I/        ( 3200): Starting All
I/        ( 3200): Stopping services
,I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@6b82210
I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3200): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3200): peerDiscoveryTimer timeout value:7146
,I/        ( 3200): Stop Bluetooth
,I/        ( 3200): StartBluetooth listener
I/        ( 3200): StartBluetooth listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/jxcore-log( 3200): StartBroadcasting started ok
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): do fake peer & start
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Connect to fake peer: 34:FC:EF:11:AE:67
I/jxcore-log( 3200): 
I/BTListenerThread( 3200): starting to listen
I/BTListenerThread( 3200): waiting to accept incoming Connection
I/jxcore-log( 3200): 2015-11-26T06:55:07.789Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:55:07.790Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:07.790Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
I/        ( 3200): Selected device address: 34:FC:EF:11:AE:67, name: null
,I/        ( 3200): Connecting to null, at 34:FC:EF:11:AE:67,
I/jxcore-log( 3200): 2015-11-26T06:55:07.802Z SendDataTCPServer.js: TCP/IP server is bound to port: 41177
I/jxcore-log( 3200): 
,I/BTConnectToThread( 3200): Starting to connect
I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/WB      ( 3200): We already were running, thus doing nothing
I/        ( 3200): Added local service
I/        ( 3200): Cleared service requests
,I/        ( 3200): Stopped peer discovery
I/        ( 3200): Started peer discovery
I/        ( 3200): Discovery state changed to Started.
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,W/bt-btif ( 3260): info:x10,
D/        ( 3260): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 1 peers.
,I/SS      ( 3200): Peer(1): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,D/btif_config( 3260): btif_get_device_type: Device [34:fc:ef:11:ae:67] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: 34:FC:EF:11:AE:67
,I/ActivityManager(  820): Start proc 4307:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.BluetoothPairingRequest
I/BluetoothBondStateMachine( 3260): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 351us total 16.625ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 340us total 15.080ms
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 229us total 14.229ms
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f255d95:true
,I/ActivityManager(  820): Killing 3666:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3200): HandshakeOk : LGE-Nexus 5_PT1108
,I/HS      ( 3200): Hand Shake finished outgoing for : LGE-Nexus 5_PT1108
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, LGE-Nexus 5_PT1108
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 46441
,I/BtConnectorHelper( 3200): Request socket is using : 46441
I/BtToRequestSocket( 3200): Now accepting connections
,I/wpa_supplicant( 3266): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/        ( 3200): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2627, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2627, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :46441
,I/jxcore-log( 3200): 2015-11-26T06:55:11.406Z SendDataConnector.js: CLIENT connected to 46441, error: null,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:11.407Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 46441
I/BtToRequestSocket( 3200): Set local streams
,I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T06:55:11.426Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:23852
,I/jxcore-log( 3200): 2015-11-26T06:55:12.076Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:12.425Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:13952
,I/jxcore-log( 3200): 2015-11-26T06:55:12.720Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:12.808Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:4052
,I/jxcore-log( 3200): 2015-11-26T06:55:13.030Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:13.273Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:13.562Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5029","ra":"7C:F9:0E:51:18:22"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5029","ra":"7C:F9:0E:51:18:22"} -- peerIdentifier:7C:F9:0E:51:18:22, peerName: samsung-SM-A500FU_PT5029, peerAddress: 7C:F9:0E:51:18:22
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:51:18:22, Name: samsung-SM-A500FU_PT5029, WifiDirectName: , WifiDirect Address: 7e:f9:0e:51:18:23, peerId: 7C:F9:0E:51:18:22
,I/jxcore-log( 3200): 2015-11-26T06:55:13.866Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:13.952Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:13.965Z SendDataConnector.js: CLIENT is data received : 100000,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:13.968Z SendDataConnector.js: got all data for this round
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:13.974Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): 2015-11-26T06:55:13.974Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/BtConnectorHelper( 3200): Disconnect outgoing peer: 34:FC:EF:11:AE:67
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToRequestSocket( 3200): Close server socket
I/jxcore-log( 3200): 2015-11-26T06:55:13.979Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): ---- round done--------
I/jxcore-log( 3200): 
I/jxcore-log( 3200): do fake peer & start
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Connect to fake peer: 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:13.981Z SendDataConnector.js: Start called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:55:13.981Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:55:13.981Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 80:01:84:8A:B3:68, name: null
W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x8):jv handle:0x0 not FOUND
I/        ( 3200): Connecting to null, at 80:01:84:8A:B3:68
I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 34:FC:EF:11:AE:67 done with result: OK", source: file:///android_asset/www/js/thali_main.js (63)
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14),
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [80:01:84:8a:b3:68]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8207c rs_disc_pending=1,
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
,D/btif_config( 3260): btif_get_device_type: Device [80:01:84:8a:b3:68] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36c51a9b:true
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 80:01:84:8A:B3:68 newState: 0
D/BluetoothAdapterProperties( 3260): Failed to remove device: 80:01:84:8A:B3:68
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:80:01:84:8A:B3:68 OldState: 11 NewState: 10,
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3200): Starting to Handshake
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3200): HandshakeOk : HTC-HTC Desire 820_PT2159
I/HS      ( 3200): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT2159
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2159
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 49637
,I/BtConnectorHelper( 3200): Request socket is using : 49637
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :49637
,I/jxcore-log( 3200): 2015-11-26T06:55:17.986Z SendDataConnector.js: CLIENT connected to 49637, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:17.987Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 49637
,I/BtToRequestSocket( 3200): Set local streams
,I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T06:55:18.000Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:1392
,I/jxcore-log( 3200): 2015-11-26T06:55:18.606Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:18.731Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:18.786Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:18.859Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:19.007Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:19.406Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:19.682Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:19.974Z SendDataConnector.js: CLIENT is data received : 80000,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:20.217Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3200): 
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3260): dm_pm_timer expires
W/bt-btif ( 3260): dm_pm_timer expires 0
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3200): Found 2 peers.
,I/SS      ( 3200): Peer(1): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3200): Peer(2): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,I/wpa_supplicant( 3266): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/        ( 3200): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2159, peerAddress: 80:01:84:8A:B3:68
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2159, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3200): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"}, typeCordovap2p._tcp.local.:,
,I/        ( 3200): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5404, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5404, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3200): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1366"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1366"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT1366, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT1366, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/jxcore-log( 3200): 2015-11-26T06:55:30.217Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:30.218Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:30.221Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:30.222Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:30.224Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3200): Disconnect outgoing peer: HTC-HTC Desire 820_PT2159
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToRequestSocket( 3200): Close server socket
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x9):jv handle:0x0 not FOUND
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 52226(2MB) AllocSpace objects, 6(661KB) LOS objects, 36% free, 27MB/43MB, paused 2.621ms total 63.712ms
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/art     (  820): Explicit concurrent mark sweep GC freed 34517(1506KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 2.048ms total 90.584ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException,
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	,at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89),
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): ,	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410),
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): ,	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 429942, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3200): 2015-11-26T06:55:35.229Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:35.231Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: HTC Desire 820
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,I/jxcore-log( 3200): 2015-11-26T06:55:40.236Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:40.237Z SendDataConnector.js: Connect (retry count 1) to peer 80:01:84:8A:B3:68 with availability status: true
,I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:55:40.238Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:55:40.238Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
I/        ( 3200): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3200): Starting to connect,
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback,
,I/        ( 3200): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1483): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1483): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1483): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1483): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1483): 	at android.os.Binder.execTransact(Binder.java:446)
,E/PlayEventLogger( 3928): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3928): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3928): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
E/PlayEventLogger( 3928): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3928): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
E/PlayEventLogger( 3928): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3928): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System  ( 3928): Ignoring header User-Agent because its value was null.
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x4  CID 0x46
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:7, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3260): invalid rfc slot id: 7
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T06:55:45.396Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:45.397Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:45.398Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 44:80:eb:7b:5a:07 p2p_dev_addr=44:80:eb:7b:5a:07 pri_dev_type=10-0050F204-5 name='XT1072_23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/SS      ( 3200): Found 4 peers.
,I/SS      ( 3200): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3200): Peer(2): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3200): Peer(3): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3200): Peer(4): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/wpa_supplicant( 3266): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3200): 2015-11-26T06:55:50.399Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:55:50.400Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8186","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8186","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT8186, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT8186, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/        ( 3200): Found Service, :{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8305","ra":"E0:DB:10:14:E2:C0"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8305","ra":"E0:DB:10:14:E2:C0"} -- peerIdentifier:E0:DB:10:14:E2:C0, peerName: samsung-SM-N910C_PT8305, peerAddress: E0:DB:10:14:E2:C0
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : E0:DB:10:14:E2:C0, Name: samsung-SM-N910C_PT8305, WifiDirectName: , WifiDirect Address: 92:b6:86:43:73:1c, peerId: E0:DB:10:14:E2:C0
,I/        ( 3200): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2159, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2159, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3200): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1366"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1366"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT1366, peerAddress: B4:CE:F6:AB:A4:6A
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT1366, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3200): 2015-11-26T06:55:55.403Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): 2015-11-26T06:55:55.404Z SendDataConnector.js: Connect (retry count 2) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:55:55.405Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:55:55.405Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3200): Starting to connect,
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3200): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: , WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5029","ra":"7C:F9:0E:51:18:22"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5029","ra":"7C:F9:0E:51:18:22"} -- peerIdentifier:7C:F9:0E:51:18:22, peerName: samsung-SM-A500FU_PT5029, peerAddress: 7C:F9:0E:51:18:22,
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:51:18:22, Name: samsung-SM-A500FU_PT5029, WifiDirectName: , WifiDirect Address: 7e:f9:0e:51:18:23, peerId: 7C:F9:0E:51:18:22,
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:8, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3260): invalid rfc slot id: 8
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T06:56:00.562Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:00.563Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:56:00.563Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
,E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): ,	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	,at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 481959, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3200): 2015-11-26T06:56:05.564Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:05.565Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3200): Found 6 peers.
I/SS      ( 3200): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3200): Peer(2): S5-1 ee:1f:72:63:11:86,
I/SS      ( 3200): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3200): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(6): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,I/        ( 3200): Started service discovery
,I/jxcore-log( 3200): 2015-11-26T06:56:10.569Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
,I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:10.569Z SendDataConnector.js: Connect (retry count 3) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:10.570Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:10.570Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3200): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: , WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: , WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3200): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x4  CID 0x48
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:9, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3260): invalid rfc slot id: 9
,I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T06:56:15.731Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:56:15.731Z SendDataConnector.js: CLIENT Can not Connect: Connection to 80:01:84:8A:B3:68 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:15.732Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): ,
,I/        ( 3200): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2159, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2159, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3200): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5404, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5404, WifiDirectName: , WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3200): 2015-11-26T06:56:20.734Z SendDataConnector.js: re-try now : 80:01:84:8A:B3:68,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:20.735Z SendDataConnector.js: ReStart called with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/jxcore-log( 3200): 2015-11-26T06:56:25.740Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:25.741Z SendDataConnector.js: Connect (retry count 4) to peer 80:01:84:8A:B3:68 with availability status: true
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:56:25.742Z SendDataConnector.js: doConnect called with peer 80:01:84:8A:B3:68,
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): 2015-11-26T06:56:25.743Z SendDataConnector.js: do connect now,
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 80:01:84:8A:B3:68, name: HTC Desire 820
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to HTC Desire 820, at 80:01:84:8A:B3:68
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [80:01:84:8a:b3:68]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: HTC Desire 820
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 84 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3200): HandshakeOk : HTC-HTC Desire 820_PT2159
I/HS      ( 3200): Hand Shake finished outgoing for : HTC-HTC Desire 820_PT2159
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, HTC-HTC Desire 820_PT2159
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 55730
,I/BtConnectorHelper( 3200): Request socket is using : 55730
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :55730
,I/jxcore-log( 3200): 2015-11-26T06:56:31.131Z SendDataConnector.js: CLIENT connected to 55730, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:56:31.132Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 55730
,I/BtToRequestSocket( 3200): Set local streams
I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T06:56:31.146Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3200): 
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 7 peers.
,I/SS      ( 3200): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
I/SS      ( 3200): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(3): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(5): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3200): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(7): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3260): dm_pm_timer expires,
W/bt-btif ( 3260): dm_pm_timer expires 0
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/        ( 3200): Started service discovery
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2126"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2126"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT2126, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT2126, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3200): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3200): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2159, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2159, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3200): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5404, peerAddress: 00:F4:6F:30:E0:6C
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5404, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3200): Found Service, :{"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1366"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"B4:CE:F6:AB:A4:6A","pi":"B4:CE:F6:AB:A4:6A","pn":"HTC-HTC Desire 820_PT1366"} -- peerIdentifier:B4:CE:F6:AB:A4:6A, peerName: HTC-HTC Desire 820_PT1366, peerAddress: B4:CE:F6:AB:A4:6A
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B4:CE:F6:AB:A4:6A, Name: HTC-HTC Desire 820_PT1366, WifiDirectName: , WifiDirect Address: b6:ce:f6:ad:a4:6b, peerId: B4:CE:F6:AB:A4:6A
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3200): 2015-11-26T06:56:41.203Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:56:41.204Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:56:41.206Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:41.209Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:41.210Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:41.211Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/BtConnectorHelper( 3200): Disconnect outgoing peer: 80:01:84:8A:B3:68
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
,I/jxcore-log( 3200): 2015-11-26T06:56:41.222Z SendDataConnector.js: Mobile.Disconnect() callback with peer 80:01:84:8A:B3:68
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): ---- round done--------
I/jxcore-log( 3200): 
I/jxcore-log( 3200): ---- gotta redo : 80:01:84:8A:B3:68, try count now: 1
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): do fake peer & start
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Connect to fake peer: F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:56:41.226Z SendDataConnector.js: Start called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:56:41.227Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): 2015-11-26T06:56:41.227Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: F8:95:C7:87:3C:51, name: null
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3200): Connecting to null, at F8:95:C7:87:3C:51
,I/jxcore-log( 3200): 2015-11-26T06:56:41.239Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 80:01:84:8A:B3:68 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63)
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,W/bt-btif ( 3260): info:x10,
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=1,
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3260): process_service_search_attr_rsp,
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND,
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1,
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c,
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=80:01:84:8A:B3:68, alias=null, name=HTC Desire 820, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: HTC Desire 820
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 92:b6:86:43:73:1c p2p_dev_addr=92:b6:86:43:73:1c pri_dev_type=10-0050F204-5 name='Note4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 11 peers.
I/SS      ( 3200): Peer(1): XT1072_23d5 44:80:eb:7b:5a:07
,I/SS      ( 3200): Peer(2): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(3): Note4-1 92:b6:86:43:73:1c
I/SS      ( 3200): Peer(4): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(6): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3200): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3200): Peer(8): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/wpa_supplicant( 3266): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
,I/wpa_supplicant( 3266): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 3266): P2P-DEVICE-LOST p2p_dev_addr=44:80:eb:7b:5a:07
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 3266): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,--------- beginning of crash
F/libc    ( 3266): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 3266 (wpa_supplicant)
I/libc    ( 3266): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,I/        ( 3200): Cleared service requests
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/WifiHW  (  820): 'P2P_FIND 120' command timed out.
,I/        ( 3200): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  820): Connection lost, restart supplicant
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): failed to set BSSID: any
E/native  (  820): do suspend true
D/CommandListener(  354): Clearing all IP addresses on wlan0
,W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NativeCrypto( 1483): Read error: ssl=0xaecfc600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1483): SSL shutdown failed: ssl=0xaecfc600: I/O error during system call, Broken pipe
I/jxcore-log( 3200): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): The Coordinator has disconnected!
I/jxcore-log( 3200): 
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  820): Unexpected BatchedScanResults :null
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  820): DefaultState
D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
,I/SS      ( 3200): We got empty peers list
I/        ( 3200): Discovery state changed to Stopped.
I/WB      ( 3200): Wifi is DISABLED !!
I/        ( 3200): Stoping All
,I/        ( 3200): Stopping services
I/        ( 3200): Stopping services
,I/        ( 3200): Stop Bluetooth
I/        ( 3200): Stop Bluetooth
I/BTListenerThread( 3200): Stopped
E/bt-btif ( 3260): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:11, channel:7
I/        ( 3200): Starting peer discovery failed, error code 2
I/        ( 3200): Clearing local services failed, error code 2
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-btif ( 3260): invalid rfc slot id: 11
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/        ( 3200): Clearing service requests failed, error code 2
I/        ( 3200): Stopping peer discovery failed, error code 2
I/jxcore-log( 3200): 2015-11-26T06:57:14.237Z SendDataConnector.js: CLIENT connected to -1, error: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:57:14.237Z SendDataConnector.js: CLIENT Can not Connect: Connection to F8:95:C7:87:3C:51 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:57:14.237Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Disconnected - quitting
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 6
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/ActivityManager(  820): Start proc 4396:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1782): num queued entries: 0,
I/iu.UploadsManager( 1782): num updated entries: 0
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599946 ms
,I/iu.SyncManager( 1782): NEXT; no task
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,I/Babel   ( 2640): connection state changed from CONNECTED to DISCONNECTED
,I/ActivityManager(  820): Start proc 4416:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,I/ActivityManager(  820): Killing 3718:com.android.providers.calendar/u0a3 (adj 15): empty #17
,I/GAv4    ( 4416): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4416):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4416):   adb logcat -s GAv4
,W/GAv4    ( 4416): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4416): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4416): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/bt-btif ( 3260): btm_sec_disconnected - Clearing 
E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 3260): Device not in IRK list
E/bt-btif ( 3260): Do not find the bg connection mask for the remote device
I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 9 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,D/BluetoothMapService( 3260): onReceive
I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,I/WebViewFactory( 4416): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4416): Time to load native libraries: 1 ms (timestamps 5261-5262)
I/LibraryLoader( 4416): Expected native library version number "",actual native library version number ""
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
D/WifiService(  820): setWifiEnabled: false pid=3200, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,V/WebViewChromiumFactoryProvider( 4416): Binding Chromium to main looper Looper (main, tid 1) {3fc3e283}
I/LibraryLoader( 4416): Expected native library version number "",actual native library version number ""
I/chromium( 4416): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/WifiService(  820): setWifiEnabled: true pid=3200, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/BrowserStartupController( 4416): Initializing chromium process, singleProcess=true
W/art     ( 4416): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4416): ApplicationContext is null in ApplicationStatus
D/WifiController(  820): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 484ms
I/jxcore-log( 3200): Wifi toggled for connection repairment
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/chromium( 4416): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4416): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4416): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 4416): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/AudioManagerAndroid( 4416): Requires BLUETOOTH permission
,I/NSApplication( 4416): Starting up...
,I/ActivityManager(  820): Killing 3596:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 4476:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,D/WifiController(  820): DEFERRED_TOGGLE handled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
,D/CommandListener(  354): Trying to bring down wlan0
,D/Tethering(  820): InitialState.processMessage what=4
D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/wpa_supplicant( 4493): Successfully initialized wpa_supplicant
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/ActivityManager(  820): Killing 3951:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/wpa_supplicant( 4493): rfkill: Cannot open RFKILL control device
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
,D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599933 ms
,D/SystemUpdateService( 1782): onDestroy
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4493): rfkill: Cannot open RFKILL control device,
E/wpa_supplicant( 4493): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2e49e682}
,D/WifiNative-HAL(  820): Setting external_sim to 1
W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xb4bbad18
D/WifiHAL (  820): Sending mac address OUI
,E/native  (  820): do suspend true
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
,D/CommandListener(  354): Setting iface cfg
D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
,E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '56 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 56 Failed to set address (No such device)'
,D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
D/WifiScanningService(  820): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4bbad18
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
,D/WifiScanningService(  820): StartedState
,I/WB      ( 3200): Wifi is now enabled !
,I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
D/WifiNative-HAL(  820): p2pGetDeviceAddress
I/        ( 3200): Stop Bluetooth
I/        ( 3200): Starting All
I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@6b82210
,I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}
D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
I/        ( 3200): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, length : 82
I/        ( 3200): peerDiscoveryTimer timeout value:7395
I/        ( 3200): Stop Bluetooth
I/        ( 3200): StartBluetooth listener
I/        ( 3200): StartBluetooth listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Discovery state changed to Stopped.
,I/        ( 3200): Added local service
I/        ( 3200): Cleared service requests
I/BTListenerThread( 3200): starting to listen
,I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/        ( 3200): Stopped peer discovery
,I/wpa_supplicant( 4493): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/        ( 3200): Started peer discovery
,I/        ( 3200): Discovery state changed to Started.
,I/        ( 3200): Started peer discovery
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4493): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/jxcore-log( 3200): 2015-11-26T06:57:19.238Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:19.238Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4493): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4493): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3200): Found 1 peers.
I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
,I/wpa_supplicant( 4493): wlan0: Trying to associate with SSID 'NG7005g'
,D/WifiP2pManager( 3200): Ignored { when=-2ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4493): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4493): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4493): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} },
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any,
,D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  820): Start Dhcp Watchdog 2
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -44
E/WifiStateMachine(  820):  BE :  rx=0 tx=2 lost=0 retries=2
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=172 rx_time=517 scan_time=0
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting,
I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4493): P2P-FIND-STOPPED 
,I/        ( 3200): Discovery state changed to Stopped.
,I/        ( 3200): Starting peer discovery failed, error code 2
,I/dhcpcd  ( 4507): version 5.5.6 starting
,I/dhcpcd  ( 4507): wlan0: rebinding lease of 192.168.1.110
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@2e49e682}
,I/art     (  820): Explicit concurrent mark sweep GC freed 63650(2MB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 2.597ms total 92.841ms
,I/dhcpcd  ( 4507): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 4507): wlan0: leased 192.168.1.110 for 86400 seconds
,E/native  (  820): do suspend true
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 101
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/ConnectivityService(  820): Setting Dns servers for network 101 to [/192.168.1.1]
,V/NativeCrypto( 1483): SSL shutdown failed: ssl=0x9d0e5200: I/O error during system call, Connection timed out
,V/NativeCrypto( 1782): SSL shutdown failed: ssl=0xb4be2e00: I/O error during system call, Connection timed out
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820):    accepting network in place of null
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1,
D/Tethering(  820): MasterInitialState.processMessage what=3
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 2
I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1782): num queued entries: 0
I/iu.UploadsManager( 1782): num updated entries: 0
,I/iu.SyncManager( 1782): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599976 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 26 Nov 2015 06:57:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448521043439], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448521043426]},
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,V/Herrevad( 1782): NQAS connected
,I/art     ( 1747): Explicit concurrent mark sweep GC freed 13988(820KB) AllocSpace objects, 10(160KB) LOS objects, 37% free, 26MB/42MB, paused 943us total 41.298ms
,E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b05b7ed)
,I/Babel   ( 2640): connection state changed from DISCONNECTED to CONNECTED
I/wpa_supplicant( 4493): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3200): Found 2 peers.
I/SS      ( 3200): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3200): Peer(2): S5-1 ee:1f:72:63:11:86
,D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,D/GCM     ( 1483): Connected
,D/GCM     ( 1483): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,F/libc    ( 4493): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 4493 (wpa_supplicant)
,I/libc    ( 4493): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,I/        ( 3200): Adding service request failed, error code 0
,I/jxcore-log( 3200): 2015-11-26T06:57:24.242Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:24.244Z SendDataConnector.js: Connect (retry count 1) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:24.244Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:24.245Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to G4-1, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Coordinator is now connected to the server!
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1,
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : LGE-LG-H815_PT5432
,I/HS      ( 3200): Hand Shake finished outgoing for : LGE-LG-H815_PT5432
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 60747
I/BtConnectorHelper( 3200): Request socket is using : 60747
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :60747
,I/jxcore-log( 3200): 2015-11-26T06:57:28.675Z SendDataConnector.js: CLIENT connected to 60747, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:28.675Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 60747
,I/BtToRequestSocket( 3200): Set local streams
I/BtToRequestSocket( 3200): rin ended ---------------------------;
I/jxcore-log( 3200): 2015-11-26T06:57:28.693Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:538
,I/jxcore-log( 3200): 2015-11-26T06:57:29.236Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:29.356Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:29.587Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:29.865Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:30.323Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:30.526Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3200): ,
,I/jxcore-log( 3200): 2015-11-26T06:57:30.585Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:30.597Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3200): 
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3260): dm_pm_timer expires
W/bt-btif ( 3260): dm_pm_timer expires 0
,W/bt-btif ( 3260): proc dm_pm_timer expires
,I/jxcore-log( 3200): 2015-11-26T06:57:40.596Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:40.597Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:40.599Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:40.600Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:40.601Z SendDataConnector.js: ----------------- closeClientSocket
,I/jxcore-log( 3200): 
I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3200): Disconnect outgoing peer: LGE-LG-H815_PT5432
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0xd):jv handle:0x0 not FOUND
,I/jxcore-log( 3200): 2015-11-26T06:57:45.601Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:45.602Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,I/jxcore-log( 3200): 2015-11-26T06:57:50.607Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): 2015-11-26T06:57:50.608Z SendDataConnector.js: Connect (retry count 2) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:50.608Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:57:50.609Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to G4-1, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : LGE-LG-H815_PT5432
I/HS      ( 3200): Hand Shake finished outgoing for : LGE-LG-H815_PT5432
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 56743
I/BtConnectorHelper( 3200): Request socket is using : 56743
,I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :56743
,I/jxcore-log( 3200): 2015-11-26T06:57:53.169Z SendDataConnector.js: CLIENT connected to 56743, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:57:53.169Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 56743
,I/BtToRequestSocket( 3200): Set local streams
,I/jxcore-log( 3200): 2015-11-26T06:57:53.184Z SendDataConnector.js: CLIENT now sending 10000 bytes of data,
I/jxcore-log( 3200): 
I/BtToRequestSocket( 3200): rin ended ---------------------------;
,E/WifiStateMachine(  820): Connection lost, restart supplicant
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): failed to set BSSID: any
E/native  (  820): do suspend true
D/CommandListener(  354): Clearing all IP addresses on wlan0
,W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NativeCrypto( 1483): Read error: ssl=0x9d0e3e00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
E/WifiStateMachine(  820): Unexpected BatchedScanResults :null
,I/jxcore-log( 3200): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): The Coordinator has disconnected!,
I/jxcore-log( 3200): 
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
V/NativeCrypto( 1483): SSL shutdown failed: ssl=0x9d0e3e00: I/O error during system call, Broken pipe
D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/RttService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
I/WB      ( 3200): Wifi is DISABLED !!
I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
I/        ( 3200): Stop Bluetooth
I/BTListenerThread( 3200): Stopped
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10011
I/SS      ( 3200): We got empty peers list
I/        ( 3200): Clearing local services failed, error code 2
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/        ( 3200): Clearing service requests failed, error code 2
I/        ( 3200): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 101](  820): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=false
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 6
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/Tethering(  820): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SystemUpdateService( 1782): onCreate
,E/GpsLocationProvider(  820): No APN found to select.
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1782): num queued entries: 0
,I/iu.UploadsManager( 1782): num updated entries: 0
I/iu.SyncManager( 1782): NEXT; no task
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599983 ms
,D/SystemUpdateService( 1782): onDestroy
,I/Babel   ( 2640): connection state changed from CONNECTED to DISCONNECTED
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599952 ms
,D/SystemUpdateService( 1782): onDestroy
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server,
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3260): dm_pm_timer expires
W/bt-btif ( 3260): dm_pm_timer expires 0
,W/bt-btif ( 3260): proc dm_pm_timer expires
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
,D/CommandListener(  354): Trying to bring down wlan0
,D/Tethering(  820): InitialState.processMessage what=4
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/wpa_supplicant( 4591): Successfully initialized wpa_supplicant
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 4591): rfkill: Cannot open RFKILL control device
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4591): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 4591): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@331563a8},
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-HAL(  820): Setting external_sim to 1
,D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
,D/wifi    (  820): setting scan oui 0xb4bbad18,
D/WifiHAL (  820): Sending mac address OUI
,E/native  (  820): do suspend true
,D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
D/WifiScanningService(  820): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
,D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4bbad18
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
,D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState,
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/RttService(  820): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  354): Setting iface cfg
E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  820): p2pGetDeviceAddress,
,I/WB      ( 3200): Wifi is now enabled !
,I/        ( 3200): Stoping All
D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
I/        ( 3200): Starting All
I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@6b82210
,I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}
,I/        ( 3200): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3200): peerDiscoveryTimer timeout value:6202
,I/        ( 3200): Stop Bluetooth
,I/        ( 3200): StartBluetooth listener
I/        ( 3200): StartBluetooth listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Discovery state changed to Stopped.,
,I/BTListenerThread( 3200): starting to listen,
,I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/wpa_supplicant( 4591): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/        ( 3200): Added local service
,I/        ( 3200): Cleared service requests
I/        ( 3200): Stopped peer discovery
,I/        ( 3200): Started peer discovery
,I/        ( 3200): Discovery state changed to Started.
,I/        ( 3200): Started peer discovery
,I/wpa_supplicant( 4591): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
,E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0,
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0,
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4591): wlan0: Trying to associate with SSID 'NG7005g'
,I/SS      ( 3200): Found 1 peers.
I/SS      ( 3200): Peer(1): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/jxcore-log( 3200): 2015-11-26T06:58:03.242Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:03.243Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:03.245Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:03.245Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:03.246Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3200): Disconnect outgoing peer: LGE-LG-H815_PT5432
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4591): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4591): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 4591): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND,
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 3
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 4
E/WifiStateMachine(  820):  RSSI mgmt: -44
E/WifiStateMachine(  820):  BE :  rx=3 tx=3 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=183 rx_time=509 scan_time=0
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/wpa_supplicant( 4591): P2P-FIND-STOPPED ,
,I/        ( 3200): Discovery state changed to Stopped.
I/        ( 3200): Starting peer discovery failed, error code 2
,I/dhcpcd  ( 4601): version 5.5.6 starting
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@331563a8}
,I/dhcpcd  ( 4601): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 4601): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 2 peers.
,I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(2): G3s-1 a2:39:f7:70:12:80
,D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/dhcpcd  ( 4601): wlan0: leased 192.168.1.110 for 86400 seconds
,I/        ( 3200): Added service request
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63),
,E/native  (  820): do suspend true
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 102
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 102
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102,
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
D/ConnectivityService(  820): Setting Dns servers for network 102 to [/192.168.1.1],
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Connected
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 2
V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
,I/iu.UploadsManager( 1782): num queued entries: 0
I/iu.UploadsManager( 1782): num updated entries: 0
,I/iu.SyncManager( 1782): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599980 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 26 Nov 2015 06:58:07 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448521087755], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448521087739]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1782): NQAS connected
,I/Babel   ( 2640): connection state changed from DISCONNECTED to CONNECTED
,I/art     (  820): Explicit concurrent mark sweep GC freed 66816(3MB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.668ms total 81.060ms
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
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 39786(2MB) AllocSpace objects, 10(914KB) LOS objects, 36% free, 27MB/43MB, paused 1.046ms total 27.912ms
,D/GCM     ( 1483): Connected
,D/GCM     ( 1483): Message class com.google.f.a.a.p
,I/        ( 3200): Started service discovery
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,I/jxcore-log( 3200): 2015-11-26T06:58:08.257Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:08.262Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network,
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Coordinator is now connected to the server!
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63),
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3200): 2015-11-26T06:58:13.286Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:13.287Z SendDataConnector.js: Connect (retry count 3) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:13.288Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:13.288Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
I/        ( 3200): Selected device address: F8:95:C7:87:3C:51, name: G4-1
,I/BTConnectToThread( 3200): Starting to connect,
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3200): Connecting to G4-1, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,I/        ( 3200): Discovery state changed to Started.
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 77 bytes.,
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : LGE-LG-H815_PT5432
I/HS      ( 3200): Hand Shake finished outgoing for : LGE-LG-H815_PT5432
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 45004
I/BtConnectorHelper( 3200): Request socket is using : 45004
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :45004
,I/jxcore-log( 3200): 2015-11-26T06:58:15.664Z SendDataConnector.js: CLIENT connected to 45004, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:15.665Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 45004
,I/BtToRequestSocket( 3200): Set local streams
,I/jxcore-log( 3200): 2015-11-26T06:58:15.675Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/        ( 3200): Cleared service requests
,I/wpa_supplicant( 4591): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started peer discovery
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3260): dm_pm_timer expires
W/bt-btif ( 3260): dm_pm_timer expires 0
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 5 peers.,
I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
,I/SS      ( 3200): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3200): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0,
,I/wpa_supplicant( 4591): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2126"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2126"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT2126, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT2126, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:,
,I/        ( 3200): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/jxcore-log( 3200): 2015-11-26T06:58:25.732Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:25.733Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:25.737Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:25.738Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:25.742Z SendDataConnector.js: ----------------- closeClientSocket,
I/jxcore-log( 3200): 
,I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3200): Disconnect outgoing peer: LGE-LG-H815_PT5432,
I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x10):jv handle:0x0 not FOUND
,F/libc    ( 4591): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 4591 (wpa_supplicant)
,I/libc    ( 4591): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
I/        ( 3200): Cleared service requests
,I/jxcore-log( 3200): 2015-11-26T06:58:30.742Z SendDataConnector.js: re-try now : F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:30.743Z SendDataConnector.js: ReStart called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,I/jxcore-log( 3200): 2015-11-26T06:58:35.747Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:35.747Z SendDataConnector.js: Connect (retry count 4) to peer F8:95:C7:87:3C:51 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:35.749Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:35.751Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: F8:95:C7:87:3C:51, name: G4-1,
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to G4-1, at F8:95:C7:87:3C:51
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1,
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5,
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=0,
W/bt-btif ( 3260): bta_dm_check_av:0,
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1,
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTConnectToThread( 3200): Starting to Handshake
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3200): HandshakeOk : LGE-LG-H815_PT5432
I/HS      ( 3200): Hand Shake finished outgoing for : LGE-LG-H815_PT5432
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, LGE-LG-H815_PT5432
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket,
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 41718,
,I/BtConnectorHelper( 3200): Request socket is using : 41718
,I/BtToRequestSocket( 3200): Now accepting connections
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT1108
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-Nexus 5_PT1108
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T06:58:38.660Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :41718
,I/jxcore-log( 3200): 2015-11-26T06:58:38.834Z SendDataConnector.js: CLIENT connected to 41718, error: null
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:38.834Z SendDataConnector.js: CLIENT starting client ,
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 41718
,I/BtToRequestSocket( 3200): Set local streams
I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T06:58:38.846Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.458Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.462Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.465Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.475Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.487Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.493Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.508Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.545Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.553Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.584Z SendDataTCPServer.js: TCP/IP server has received 36728 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.590Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.602Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.634Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.641Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.674Z SendDataTCPServer.js: TCP/IP server has received 64448 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.680Z SendDataTCPServer.js: TCP/IP server has received 66428 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.715Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 3200): ,
,I/jxcore-log( 3200): 2015-11-26T06:58:39.755Z SendDataTCPServer.js: TCP/IP server has received 78308 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.761Z SendDataTCPServer.js: TCP/IP server has received 82268 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.794Z SendDataTCPServer.js: TCP/IP server has received 90188 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.801Z SendDataTCPServer.js: TCP/IP server has received 92168 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:39.835Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,D/WifiHW  (  820): 'P2P_FIND 120' command timed out.
,I/        ( 3200): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  820): Connection lost, restart supplicant
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): failed to set BSSID: any
,E/native  (  820): do suspend true
D/CommandListener(  354): Clearing all IP addresses on wlan0
,W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/NativeCrypto( 1483): Read error: ssl=0x9d0e3e00: I/O error during system call, Connection timed out
,I/jxcore-log( 3200): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): The Coordinator has disconnected!
I/jxcore-log( 3200): 
V/NativeCrypto( 1483): SSL shutdown failed: ssl=0x9d0e3e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  820): Unexpected BatchedScanResults :null
D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/RttService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/RttService(  820): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/        ( 3200): Discovery state changed to Stopped.
I/WB      ( 3200): Wifi is DISABLED !!
I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
,I/        ( 3200): Stop Bluetooth
,I/BTListenerThread( 3200): Stopped
I/SS      ( 3200): We got empty peers list
I/        ( 3200): Starting peer discovery failed, error code 2
I/        ( 3200): Clearing local services failed, error code 2
I/        ( 3200): Clearing service requests failed, error code 2
,I/        ( 3200): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): OfflineState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 102](  820): Disconnected - quitting
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3,
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=false
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 6
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,E/GpsLocationProvider(  820): No APN found to select.
I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1782): num queued entries: 0
I/iu.UploadsManager( 1782): num updated entries: 0
I/iu.SyncManager( 1782): NEXT; no task
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599983 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,I/Babel   ( 2640): connection state changed from CONNECTED to DISCONNECTED
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599984 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
D/WifiService(  820): setWifiEnabled: false pid=3200, uid=10265
,E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  820): setWifiEnabled: true pid=3200, uid=10265
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  820): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 474ms,
,I/jxcore-log( 3200): Wifi toggled for connection repairment
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  820): DEFERRED_TOGGLE handled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
,D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/Tethering(  820): InitialState.processMessage what=4
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,I/wpa_supplicant( 4688): Successfully initialized wpa_supplicant
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false,
,I/wpa_supplicant( 4688): rfkill: Cannot open RFKILL control device
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4688): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 4688): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@6d27175}
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  820): Setting external_sim to 1
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xb4bbad18
D/WifiHAL (  820): Sending mac address OUI
,E/native  (  820): do suspend true
,D/WifiScanningService(  820): SCAN_AVAILABLE : 3,
D/RttService(  820): SCAN_AVAILABLE : 3,
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiScanningService(  820): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4bbad18
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
D/RttService(  820): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  354): Setting iface cfg
E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '112 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 112 Failed to set address (No such device)'
,D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 3200): Wifi is now enabled !
,I/        ( 3200): Stoping All
,I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
I/        ( 3200): Starting All
,I/        ( 3200): Stopping services
,I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@6b82210
I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"},
I/        ( 3200): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, length : 82
,I/        ( 3200): peerDiscoveryTimer timeout value:5891
D/WifiNative-HAL(  820): p2pGetDeviceAddress
D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/        ( 3200): Stop Bluetooth
I/        ( 3200): StartBluetooth listener
I/        ( 3200): StartBluetooth listener
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3200): Discovery state changed to Stopped.
,I/BTListenerThread( 3200): starting to listen
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/wpa_supplicant( 4688): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/        ( 3200): Added local service,
I/        ( 3200): Cleared service requests
,I/        ( 3200): Stopped peer discovery,
,I/        ( 3200): Started peer discovery
,I/        ( 3200): Discovery state changed to Started.
I/        ( 3200): Started peer discovery
,W/bt-btif ( 3260): dm_pm_timer expires,
,W/bt-btif ( 3260): dm_pm_timer expires 0
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/wpa_supplicant( 4688): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
,E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): will read network variables netId=0,
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): wlan0: Trying to associate with SSID 'NG7005g'
,I/SS      ( 3200): Found 2 peers.,
,I/SS      ( 3200): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(2): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4688): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4688): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
E/WifiStateMachine(  820): Start Dhcp Watchdog 4
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -44
E/WifiStateMachine(  820):  BE :  rx=0 tx=3 lost=0 retries=1
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=175 rx_time=665 scan_time=0
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/wpa_supplicant( 4688): P2P-FIND-STOPPED 
,I/        ( 3200): Discovery state changed to Stopped.
,I/        ( 3200): Starting peer discovery failed, error code 2
,I/dhcpcd  ( 4695): version 5.5.6 starting
,I/dhcpcd  ( 4695): wlan0: rebinding lease of 192.168.1.110
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 3 peers.
,I/SS      ( 3200): Peer(1): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@6d27175}
,I/        ( 3200): Added service request
,I/jxcore-log( 3200): 2015-11-26T06:58:48.919Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:48.920Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:48.921Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:48.925Z SendDataConnector.js: CLIENT Stop now,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:48.925Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:48.926Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/BtConnectorHelper( 3200): Disconnect outgoing peer: F8:95:C7:87:3C:51
I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToRequestSocket( 3200): Close server socket
I/jxcore-log( 3200): 2015-11-26T06:58:48.947Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:3C:51
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): ---- round done--------
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): ---- gotta redo : F8:95:C7:87:3C:51, try count now: 1
I/jxcore-log( 3200): 
I/jxcore-log( 3200): do fake peer & start
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): Connect to fake peer: 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:48.955Z SendDataConnector.js: Start called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:48.955Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:48.955Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 50:2E:6C:AC:21:50, name: null
I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at 50:2E:6C:AC:21:50,
I/jxcore-log( 3200): 2015-11-26T06:58:48.964Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Round of send data to peer F8:95:C7:87:3C:51 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63),
,I/dhcpcd  ( 4695): wlan0: acknowledged 192.168.1.110 from 192.168.1.1,
,I/dhcpcd  ( 4695): wlan0: leased 192.168.1.110 for 86400 seconds,
,I/        ( 3200): Starting service discovery failed, error code 2
,I/        ( 3200): Cleared service requests,
,W/bt-btif ( 3260): invalid rfc slot id: 15
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT1108
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed,
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T06:58:49.868Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 3200): 
,E/native  (  820): do suspend true,
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x11):jv handle:0x0 not FOUND
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  820): Adding iface wlan0 to network 103
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 103
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,D/ConnectivityService(  820): Setting Dns servers for network 103 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 2
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
,D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x43 current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x43
I/iu.UploadsManager( 1782): num queued entries: 0
,I/iu.UploadsManager( 1782): num updated entries: 0
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599983 ms
I/iu.SyncManager( 1782): NEXT; no task
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 26 Nov 2015 06:58:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448521130107], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448521130091]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Validated
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 103] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 103]
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1782): NQAS connected
,I/Babel   ( 2640): connection state changed from DISCONNECTED to CONNECTED
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
,D/GCM     ( 1483): Connected
,D/GCM     ( 1483): Message class com.google.f.a.a.p
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Coordinator is now connected to the server!
I/jxcore-log( 3200): 
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x4  CID 0x47
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:20, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3260): invalid rfc slot id: 20
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3200): 2015-11-26T06:58:54.097Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:58:54.098Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:54.100Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 5 peers.
,I/SS      ( 3200): Peer(1): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
I/SS      ( 3200): Peer(2): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(3): Android_2dc2 52:55:27:f0:ff:f0,
I/SS      ( 3200): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78,
I/SS      ( 3200): Peer(5): G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,I/        ( 3200): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8186","ra":"08:EC:A9:50:76:27"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT8186","ra":"08:EC:A9:50:76:27"} -- peerIdentifier:08:EC:A9:50:76:27, peerName: samsung-SM-A300FU_PT8186, peerAddress: 08:EC:A9:50:76:27
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:76:27, Name: samsung-SM-A300FU_PT8186, WifiDirectName: Thali Test (Galaxy A3), WifiDirect Address: 0a:ec:a9:50:76:28, peerId: 08:EC:A9:50:76:27
,I/jxcore-log( 3200): 2015-11-26T06:58:59.102Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:58:59.103Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2126"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"34:FC:EF:11:B1:66","pi":"34:FC:EF:11:B1:66","pn":"LGE-Nexus 5_PT2126"} -- peerIdentifier:34:FC:EF:11:B1:66, peerName: LGE-Nexus 5_PT2126, peerAddress: 34:FC:EF:11:B1:66
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:11:B1:66, Name: LGE-Nexus 5_PT2126, WifiDirectName: Android_2dc2, WifiDirect Address: 52:55:27:f0:ff:f0, peerId: 34:FC:EF:11:B1:66
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,V/GoogleAuthProtoRequest( 3277): [339] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3277): [340] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [340] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [340] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
W/ExperimentUpdateService( 3277): [339] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [339] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT1108
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-Nexus 5_PT1108
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T06:59:02.023Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:02.421Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:02.428Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:02.432Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:02.442Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:02.447Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"samsung-SM-G800F_PT5404"} -- peerIdentifier:00:F4:6F:30:E0:6C, peerName: samsung-SM-G800F_PT5404, peerAddress: 00:F4:6F:30:E0:6C
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 00:F4:6F:30:E0:6C, Name: samsung-SM-G800F_PT5404, WifiDirectName: S5mini-1, WifiDirect Address: 02:f4:6f:30:e0:6d, peerId: 00:F4:6F:30:E0:6C
,I/jxcore-log( 3200): 2015-11-26T06:59:04.108Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:04.109Z SendDataConnector.js: Connect (retry count 1) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:04.109Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:04.110Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at 50:2E:6C:AC:21:50
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3200): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2159, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2159, WifiDirectName: , WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 69105(3MB) AllocSpace objects, 4(158KB) LOS objects, 31% free, 34MB/50MB, paused 1.448ms total 70.364ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 668160, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x4  CID 0x4b,
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:22, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3260): invalid rfc slot id: 22
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T06:59:09.710Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:09.710Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:09.711Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/        ( 3200): Cleared service requests
I/        ( 3200): Started peer discovery
,I/        ( 3200): Discovery state changed to Started.
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 10 peers.,
I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3200): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(4): Android_2dc2 52:55:27:f0:ff:f0,
I/SS      ( 3200): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(6): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(8): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3200): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): invalid rfc slot id: 19
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT1108
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3200): 2015-11-26T06:59:12.430Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x49
,I/wpa_supplicant( 4688): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/jxcore-log( 3200): 2015-11-26T06:59:14.711Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:14.712Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,I/jxcore-log( 3200): 2015-11-26T06:59:19.716Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:19.716Z SendDataConnector.js: Connect (retry count 2) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:19.717Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:19.717Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 50:2E:6C:AC:21:50, name: null
,I/        ( 3200): Connecting to null, at 50:2E:6C:AC:21:50
I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0xd  CID 0x4a
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:23, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3260): invalid rfc slot id: 23
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1,
,I/jxcore-log( 3200): 2015-11-26T06:59:23.779Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed,
I/jxcore-log( 3200): ,
,I/jxcore-log( 3200): 2015-11-26T06:59:23.780Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:23.780Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT1108
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-Nexus 5_PT1108
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
,I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended,
I/jxcore-log( 3200): 2015-11-26T06:59:24.208Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:24.659Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:24.664Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:24.668Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:24.671Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:24.698Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3200): 2015-11-26T06:59:28.783Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:28.785Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:33.790Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:33.791Z SendDataConnector.js: Connect (retry count 3) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:33.791Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:33.792Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 50:2E:6C:AC:21:50, name: null,
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at 50:2E:6C:AC:21:50
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [50:2e:6c:ac:21:50]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3260): invalid rfc slot id: 21
I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT1108
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3200): 2015-11-26T06:59:34.673Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4d
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8240c rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,D/btif_config( 3260): btif_get_device_type: Device [50:2e:6c:ac:21:50] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3260): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 10 NewState: 11,
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 50:2E:6C:AC:21:50 newState: 0
D/BluetoothAdapterProperties( 3260): Failed to remove device: 50:2E:6C:AC:21:50
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:50:2E:6C:AC:21:50 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
I/BTConnectToThread( 3200): Starting to Handshake
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8240c rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3200): got MESSAGE_READ 80 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : HTC-HTC One_M8_PT6155
I/HS      ( 3200): Hand Shake finished outgoing for : HTC-HTC One_M8_PT6155
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, HTC-HTC One_M8_PT6155
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3200): mHTTPPort  set to : 57120
I/BtConnectorHelper( 3200): Request socket is using : 57120
,I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :57120
,I/jxcore-log( 3200): 2015-11-26T06:59:36.183Z SendDataConnector.js: CLIENT connected to 57120, error: null
,I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:36.184Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 57120
,I/BtToRequestSocket( 3200): Set local streams
I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T06:59:36.196Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:12832
,I/jxcore-log( 3200): 2015-11-26T06:59:36.698Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:19174
,I/jxcore-log( 3200): 2015-11-26T06:59:37.065Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:37.146Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:7294
,I/jxcore-log( 3200): 2015-11-26T06:59:37.191Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:5314
,I/jxcore-log( 3200): 2015-11-26T06:59:37.201Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:37.246Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:37.323Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:37.363Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:37.401Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3200): Cleared service requests
I/        ( 3200): Started peer discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0,
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3260): dm_pm_timer expires
W/bt-btif ( 3260): dm_pm_timer expires 0
,W/bt-btif ( 3260): proc dm_pm_timer expires
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 7e:f9:0e:37:96:ac p2p_dev_addr=7e:f9:0e:37:96:ac pri_dev_type=10-0050F204-5 name='A5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT1108,
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-Nexus 5_PT1108
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/jxcore-log( 3200): 2015-11-26T06:59:46.379Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
I/BtToRequestSocket( 3200): --DoOneRunRound ended
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8240c rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T06:59:46.785Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:46.797Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:46.800Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:46.816Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:46.840Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:47.401Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:47.402Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:47.407Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:47.409Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:47.410Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3200): Disconnect outgoing peer: HTC-HTC One_M8_PT6155
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8240c rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND,
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3200): 2015-11-26T06:59:52.409Z SendDataConnector.js: re-try now : 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:52.410Z SendDataConnector.js: ReStart called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=50:2E:6C:AC:21:50, alias=null, name=HTC One_M8, majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1511): Bluetooth Device Name: HTC One_M8
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
W/bt-btif ( 3260): invalid rfc slot id: 24
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT1108
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3200): 2015-11-26T06:59:57.269Z SendDataTCPServer.js: TCP/IP server is ended,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:57.415Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:57.415Z SendDataConnector.js: Connect (retry count 4) to peer 50:2E:6C:AC:21:50 with availability status: true
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T06:59:57.416Z SendDataConnector.js: doConnect called with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T06:59:57.417Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 50:2E:6C:AC:21:50, name: HTC One_M8,
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to HTC One_M8, at 50:2E:6C:AC:21:50
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x41 current:0x0,
W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x41
,I/ActivityManager(  820): Start proc 4782:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,I/GAv4    ( 4782): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4782):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4782):   adb logcat -s GAv4
,W/GAv4    ( 4782): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4782): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 4782): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Killing 3989:com.google.android.gms:car/u0a11 (adj 15): empty #17
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:27, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3260): invalid rfc slot id: 27
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T07:00:02.564Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:02.564Z SendDataConnector.js: CLIENT Can not Connect: Connection to 50:2E:6C:AC:21:50 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:02.569Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:02.569Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:02.572Z SendDataConnector.js: Mobile.Disconnect() callback with peer 50:2E:6C:AC:21:50
I/jxcore-log( 3200): 
I/jxcore-log( 3200): ---- round done--------
I/jxcore-log( 3200): 
I/jxcore-log( 3200): ---- gotta redo : 50:2E:6C:AC:21:50, try count now: 1
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): do fake peer & start
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Connect to fake peer: 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:02.576Z SendDataConnector.js: Start called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:02.577Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:02.577Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 7C:F9:0E:34:8A:A0, name: null
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3200): Connecting to null, at 7C:F9:0E:34:8A:A0
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 50:2E:6C:AC:21:50 done with result: Connection to 50:2E:6C:AC:21:50 failed", source: file:///android_asset/www/js/thali_main.js (63)
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,D/btif_config( 3260): btif_get_device_type: Device [7c:f9:0e:34:8a:a0] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3260): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: 7C:F9:0E:34:8A:A0
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTConnectToThread( 3200): HandshakeOk : samsung-SM-G900F_PT5166
I/HS      ( 3200): Hand Shake finished outgoing for : samsung-SM-G900F_PT5166
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, samsung-SM-G900F_PT5166
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 36487
,I/BtConnectorHelper( 3200): Request socket is using : 36487
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :36487
,I/jxcore-log( 3200): 2015-11-26T07:00:05.104Z SendDataConnector.js: CLIENT connected to 36487, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:05.105Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 36487
,I/BtToRequestSocket( 3200): Set local streams
I/jxcore-log( 3200): 2015-11-26T07:00:05.116Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T07:00:05.604Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:05.666Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:05.794Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:05.821Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:06.583Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:06.693Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:06.707Z SendDataConnector.js: CLIENT is data received : 70000
,I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:06.984Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3200): 
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [34:fc:ef:11:ae:67]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT1108","ra":"34:FC:EF:11:AE:67"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-Nexus 5_PT1108
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-Nexus 5_PT1108
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3200): --DoOneRunRound started
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/jxcore-log( 3200): 2015-11-26T07:00:08.140Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 698955, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
,W/KeepSync( 4206): Sync result 2
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 712027, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
,E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406),
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	,at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 725672, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/jxcore-log( 3200): 2015-11-26T07:00:08.693Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:08.699Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:08.749Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:08.754Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:08.801Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:08.814Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:08.858Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 82:01:84:6b:e8:5d p2p_dev_addr=82:01:84:6b:e8:5d pri_dev_type=10-0050F204-5 name='Android_63cc' config_methods=0x188 dev_capab=0x25 group_capab=0x0 wfd_dev_info=0x00101c440032
,I/SS      ( 3200): Found 13 peers.
I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(2): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3200): Peer(3): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/SS      ( 3200): Peer(4): Android_63cc 82:01:84:6b:e8:5d,
I/SS      ( 3200): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(6): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(7): A3-1 0a:ec:a9:50:75:42,
I/SS      ( 3200): Peer(8): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(9): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3200): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(11): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3200): Peer(12): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(13): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=ee:1f:72:63:11:86
I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:ff:f0
,W/bt-btif ( 3260): dm_pm_timer expires
,W/bt-btif ( 3260): dm_pm_timer expires 0
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/wpa_supplicant( 4688): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-btif ( 3260): invalid rfc slot id: 26
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT1108
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close localHostSocket
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt in
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-Nexus 5_PT1108
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt socket
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/jxcore-log( 3200): 2015-11-26T07:00:18.719Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:18.801Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:18.801Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:18.803Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:18.803Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:18.805Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3200): Disconnect outgoing peer: samsung-SM-G900F_PT5166
I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToRequestSocket( 3200): Close server socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f81eb4 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x46
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x18):jv handle:0x0 not FOUND
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT811, peerAddress: F8:95:C7:87:85:54
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT811, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Nexus 5
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: A5-1, WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,I/jxcore-log( 3200): 2015-11-26T07:00:23.805Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:23.805Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3200): Found Service, :{"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"80:01:84:8A:B3:68","pi":"80:01:84:8A:B3:68","pn":"HTC-HTC Desire 820_PT2159"} -- peerIdentifier:80:01:84:8A:B3:68, peerName: HTC-HTC Desire 820_PT2159, peerAddress: 80:01:84:8A:B3:68
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 80:01:84:8A:B3:68, Name: HTC-HTC Desire 820_PT2159, WifiDirectName: Android_63cc, WifiDirect Address: 82:01:84:6b:e8:5d, peerId: 80:01:84:8A:B3:68
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,D/btif_config( 3260): btif_get_device_type: Device [44:80:eb:7b:5a:05] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/jxcore-log( 3200): 2015-11-26T07:00:28.809Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:28.810Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:28.811Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:28.811Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0,
,D/BluetoothAdapterProperties( 3260): Failed to remove device: 44:80:EB:7B:5A:05
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8279c rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3200): we got incoming connection,
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3200): waiting to accept incoming Connection,
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started,
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8279c rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3200): got MESSAGE_READ 81 bytes.,
I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : motorola-XT1072_PT2627
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, motorola-XT1072_PT2627
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:00:31.163Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-sdp  ( 3260): process_service_search_attr_rsp,
,I/jxcore-log( 3200): 2015-11-26T07:00:32.096Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.147Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.234Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.268Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.272Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.297Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.363Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.435Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.441Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.446Z SendDataTCPServer.js: TCP/IP server has received 18092 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.530Z SendDataTCPServer.js: TCP/IP server has received 20072 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.538Z SendDataTCPServer.js: TCP/IP server has received 22052 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.575Z SendDataTCPServer.js: TCP/IP server has received 24032 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.583Z SendDataTCPServer.js: TCP/IP server has received 26012 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.591Z SendDataTCPServer.js: TCP/IP server has received 27992 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.640Z SendDataTCPServer.js: TCP/IP server has received 29972 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.652Z SendDataTCPServer.js: TCP/IP server has received 31952 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.669Z SendDataTCPServer.js: TCP/IP server has received 33932 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.736Z SendDataTCPServer.js: TCP/IP server has received 35912 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.800Z SendDataTCPServer.js: TCP/IP server has received 37892 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.825Z SendDataTCPServer.js: TCP/IP server has received 39872 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.832Z SendDataTCPServer.js: TCP/IP server has received 41852 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.839Z SendDataTCPServer.js: TCP/IP server has received 43832 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.875Z SendDataTCPServer.js: TCP/IP server has received 47792 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.986Z SendDataTCPServer.js: TCP/IP server has received 49772 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:32.992Z SendDataTCPServer.js: TCP/IP server has received 51752 bytes of data
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/jxcore-log( 3200): 2015-11-26T07:00:33.099Z SendDataTCPServer.js: TCP/IP server has received 53732 bytes of data
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 12 peers.
,I/SS      ( 3200): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3200): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3200): Peer(3): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3200): Peer(4): Android_63cc 82:01:84:6b:e8:5d
,I/SS      ( 3200): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3200): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3200): Peer(9): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3200): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
,I/SS      ( 3200): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f8279c rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:00:33.409Z SendDataTCPServer.js: TCP/IP server has received 55712 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.452Z SendDataTCPServer.js: TCP/IP server has received 57692 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.461Z SendDataTCPServer.js: TCP/IP server has received 59672 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.499Z SendDataTCPServer.js: TCP/IP server has received 61652 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.509Z SendDataTCPServer.js: TCP/IP server has received 63632 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.601Z SendDataTCPServer.js: TCP/IP server has received 65612 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.609Z SendDataTCPServer.js: TCP/IP server has received 67592 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.615Z SendDataTCPServer.js: TCP/IP server has received 69572 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.724Z SendDataTCPServer.js: TCP/IP server has received 71552 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.733Z SendDataTCPServer.js: TCP/IP server has received 73532 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.764Z SendDataTCPServer.js: TCP/IP server has received 75512 bytes of data
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3200): 2015-11-26T07:00:33.963Z SendDataTCPServer.js: TCP/IP server has received 77492 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:33.979Z SendDataTCPServer.js: TCP/IP server has received 79472 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.084Z SendDataTCPServer.js: TCP/IP server has received 81452 bytes of data
I/jxcore-log( 3200): 
,I/        ( 3200): Started service discovery
,I/jxcore-log( 3200): 2015-11-26T07:00:34.226Z SendDataTCPServer.js: TCP/IP server has received 83432 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.273Z SendDataTCPServer.js: TCP/IP server has received 85412 bytes of data
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:00:34.348Z SendDataTCPServer.js: TCP/IP server has received 87392 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.401Z SendDataTCPServer.js: TCP/IP server has received 89372 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.486Z SendDataTCPServer.js: TCP/IP server has received 91352 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.491Z SendDataTCPServer.js: TCP/IP server has received 93332 bytes of data
I/jxcore-log( 3200): 
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3200): 2015-11-26T07:00:34.533Z SendDataTCPServer.js: TCP/IP server has received 95312 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.586Z SendDataTCPServer.js: TCP/IP server has received 97292 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.592Z SendDataTCPServer.js: TCP/IP server has received 99272 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:34.600Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3200): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : samsung-SM-G900F_PT5166
I/HS      ( 3200): Hand Shake finished outgoing for : samsung-SM-G900F_PT5166
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, samsung-SM-G900F_PT5166
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3200): mHTTPPort  set to : 54002
I/BtConnectorHelper( 3200): Request socket is using : 54002
,I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :54002
,I/jxcore-log( 3200): 2015-11-26T07:00:35.229Z SendDataConnector.js: CLIENT connected to 54002, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:35.229Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 54002
,I/BtToRequestSocket( 3200): Set local streams
I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T07:00:35.239Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-btif ( 3260): dm_pm_timer expires
,W/bt-btif ( 3260): dm_pm_timer expires 1
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT811, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT811, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,D/Finsky  ( 3928): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3928): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3928): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 36641(1637KB) AllocSpace objects, 6(284KB) LOS objects, 31% free, 34MB/50MB, paused 1.651ms total 96.176ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 3928): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3928): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 3928): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3928): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1747): client connected with version: 7571000
,W/bt-btif ( 3260): invalid rfc slot id: 29
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT2627
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T07:00:44.696Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:45.310Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:45.311Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:45.312Z SendDataConnector.js: CLIENT closeClientSocket
,I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:45.313Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:45.314Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
,I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3200): Disconnect outgoing peer: samsung-SM-G900F_PT5166,
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4b current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4b
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x1b):jv handle:0x0 not FOUND
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: XT1072
,I/jxcore-log( 3200): 2015-11-26T07:00:50.314Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:50.315Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 0a:ec:a9:50:76:28 p2p_dev_addr=0a:ec:a9:50:76:28 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/SS      ( 3200): Found 12 peers.
,I/SS      ( 3200): Peer(1): A5-1 7e:f9:0e:37:96:ac
I/SS      ( 3200): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3200): Peer(3): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3200): Peer(4): Android_63cc 82:01:84:6b:e8:5d
I/SS      ( 3200): Peer(5): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3200): Peer(9): Note3-1 ea:50:8b:de:28:a3
,I/SS      ( 3200): Peer(10): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(11): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(12): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=-4ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,I/wpa_supplicant( 4688): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/jxcore-log( 3200): 2015-11-26T07:00:55.319Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:55.319Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:00:55.320Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:00:55.321Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3200): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 6, 1d, 7d3
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 53132(2MB) AllocSpace objects, 9(993KB) LOS objects, 36% free, 27MB/43MB, paused 2.281ms total 56.891ms
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3928): [1] 5.onFinished: Scheduling replication attempt 1.
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-LG-H815_PT5432
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
I/jxcore-log( 3200): 2015-11-26T07:00:59.639Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 82 bytes.
,I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : samsung-SM-G900F_PT5166
I/HS      ( 3200): Hand Shake finished outgoing for : samsung-SM-G900F_PT5166
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, samsung-SM-G900F_PT5166
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 36935
I/BtConnectorHelper( 3200): Request socket is using : 36935
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :36935
,I/jxcore-log( 3200): 2015-11-26T07:01:00.133Z SendDataConnector.js: CLIENT connected to 36935, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.134Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 36935
,I/BtToRequestSocket( 3200): Set local streams
I/BtToRequestSocket( 3200): rin ended ---------------------------;
,I/jxcore-log( 3200): 2015-11-26T07:01:00.155Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.500Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.615Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.681Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.690Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.769Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.847Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.852Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.885Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.915Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.923Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.927Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:00.993Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.024Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:01:01.060Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.063Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.069Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.105Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.111Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.115Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.119Z SendDataTCPServer.js: TCP/IP server has received 40960 bytes of data
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:01.123Z SendDataTCPServer.js: TCP/IP server has received 42940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.154Z SendDataTCPServer.js: TCP/IP server has received 46900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.183Z SendDataTCPServer.js: TCP/IP server has received 48880 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.186Z SendDataTCPServer.js: TCP/IP server has received 50860 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.191Z SendDataTCPServer.js: TCP/IP server has received 52840 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.224Z SendDataTCPServer.js: TCP/IP server has received 56800 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.321Z SendDataTCPServer.js: TCP/IP server has received 58780 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.324Z SendDataTCPServer.js: TCP/IP server has received 60760 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.329Z SendDataTCPServer.js: TCP/IP server has received 62740 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.365Z SendDataTCPServer.js: TCP/IP server has received 64720 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.397Z SendDataTCPServer.js: TCP/IP server has received 66700 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.401Z SendDataTCPServer.js: TCP/IP server has received 68680 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.405Z SendDataTCPServer.js: TCP/IP server has received 70660 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.412Z SendDataTCPServer.js: TCP/IP server has received 72640 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.471Z SendDataTCPServer.js: TCP/IP server has received 74620 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.582Z SendDataTCPServer.js: TCP/IP server has received 76600 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.586Z SendDataTCPServer.js: TCP/IP server has received 78580 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.743Z SendDataTCPServer.js: TCP/IP server has received 80560 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.763Z SendDataTCPServer.js: TCP/IP server has received 82540 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.819Z SendDataTCPServer.js: TCP/IP server has received 84520 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.822Z SendDataTCPServer.js: TCP/IP server has received 86500 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.829Z SendDataTCPServer.js: TCP/IP server has received 88480 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.837Z SendDataTCPServer.js: TCP/IP server has received 90460 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.842Z SendDataTCPServer.js: TCP/IP server has received 92440 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.958Z SendDataTCPServer.js: TCP/IP server has received 94420 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.963Z SendDataTCPServer.js: TCP/IP server has received 96400 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:01.968Z SendDataTCPServer.js: TCP/IP server has received 98380 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:02.017Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL,
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): dm_pm_timer expires
,W/bt-btif ( 3260): dm_pm_timer expires 1
W/bt-btif ( 3260): proc dm_pm_timer expires
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token,
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	,at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	,at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112),
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
,E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
,E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
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
,E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
,E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305),
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 760076, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 759069, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/jxcore-log( 3200): 2015-11-26T07:01:10.206Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:10.207Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:10.208Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:10.208Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:10.209Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
,I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read,
I/BtConnectorHelper( 3200): Disconnect outgoing peer: samsung-SM-G900F_PT5166
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToRequestSocket( 3200): Close server socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,W/bt-btm  ( 3260): btm_acl_role_changed -> Issuing delayed HCI_Disconnect!!!
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=2
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x1c):jv handle:0x0 not FOUND
,W/bt-btif ( 3260): invalid rfc slot id: 31,
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1,
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt out
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/jxcore-log( 3200): 2015-11-26T07:01:12.057Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4d current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4d
,I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=7e:f9:0e:37:96:ac
I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=82:01:84:6b:e8:5d
I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=52:55:27:f0:fd:0b
,I/jxcore-log( 3200): 2015-11-26T07:01:15.210Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:15.210Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1,
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure,
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3928): [1] 5.onFinished: Scheduling replication attempt 2.
,I/jxcore-log( 3200): 2015-11-26T07:01:20.214Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:20.215Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:34:8A:A0 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:20.215Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:20.216Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
I/        ( 3200): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66,
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 82 bytes.,
I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : samsung-SM-G900F_PT5166
I/HS      ( 3200): Hand Shake finished outgoing for : samsung-SM-G900F_PT5166
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, samsung-SM-G900F_PT5166
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
I/BtToRequestSocket( 3200): mHTTPPort  set to : 56249
,I/BtConnectorHelper( 3200): Request socket is using : 56249
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :56249
,I/jxcore-log( 3200): 2015-11-26T07:01:21.651Z SendDataConnector.js: CLIENT connected to 56249, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:21.652Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 56249,
,I/BtToRequestSocket( 3200): Set local streams,
,I/BtToRequestSocket( 3200): rin ended ---------------------------;,
,I/jxcore-log( 3200): 2015-11-26T07:01:21.661Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [e0:db:10:1f:c9:5e]: 7, f, 610c
E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,D/btif_config( 3260): btif_get_device_type: Device [e0:db:10:1f:c9:5e] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: E0:DB:10:1F:C9:5E newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: E0:DB:10:1F:C9:5E
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:E0:DB:10:1F:C9:5E OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 0, 0, 0
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,D/btif_config( 3260): btif_get_device_type: Device [58:2a:f7:ed:96:be] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
I/BluetoothBondStateMachine( 3260): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 58:2A:F7:ED:96:BE newState: 0
D/BluetoothAdapterProperties( 3260): Failed to remove device: 58:2A:F7:ED:96:BE
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:58:2A:F7:ED:96:BE OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,I/BTListenerThread( 3200): got MESSAGE_READ 82 bytes.
I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT4166
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, samsung-SM-N9005_PT4166
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.,
,I/BtToRequestSocket( 3200): --DoOneRunRound started,
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
I/jxcore-log( 3200): 2015-11-26T07:01:26.117Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
I/BtToRequestSocket( 3200): --DoOneRunRound ended
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3260): onReceive,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82b2c rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): dm_pm_timer expires
W/bt-btif ( 3260): dm_pm_timer expires 0
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/BTListenerThread( 3200): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2102","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT2102
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT2102
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:01:26.857Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.326Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.375Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.380Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.488Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.538Z SendDataTCPServer.js: TCP/IP server has received 10172 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.604Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.622Z SendDataTCPServer.js: TCP/IP server has received 12152 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.642Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.673Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.709Z SendDataTCPServer.js: TCP/IP server has received 14132 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.712Z SendDataTCPServer.js: TCP/IP server has received 16112 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.713Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.716Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.736Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.741Z SendDataTCPServer.js: TCP/IP server has received 16384 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.748Z SendDataTCPServer.js: TCP/IP server has received 18364 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.797Z SendDataTCPServer.js: TCP/IP server has received 15840 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.839Z SendDataTCPServer.js: TCP/IP server has received 17820 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.843Z SendDataTCPServer.js: TCP/IP server has received 19800 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.868Z SendDataTCPServer.js: TCP/IP server has received 20344 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.873Z SendDataTCPServer.js: TCP/IP server has received 22324 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.936Z SendDataTCPServer.js: TCP/IP server has received 24304 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.948Z SendDataTCPServer.js: TCP/IP server has received 21780 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:27.975Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:01:28.005Z SendDataTCPServer.js: TCP/IP server has received 26284 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.014Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.039Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.066Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.198Z SendDataTCPServer.js: TCP/IP server has received 33660 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.236Z SendDataTCPServer.js: TCP/IP server has received 35640 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.285Z SendDataTCPServer.js: TCP/IP server has received 37620 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.318Z SendDataTCPServer.js: TCP/IP server has received 39600 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.342Z SendDataTCPServer.js: TCP/IP server has received 40960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.347Z SendDataTCPServer.js: TCP/IP server has received 42940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.401Z SendDataTCPServer.js: TCP/IP server has received 44920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.434Z SendDataTCPServer.js: TCP/IP server has received 46900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.442Z SendDataTCPServer.js: TCP/IP server has received 48880 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.483Z SendDataTCPServer.js: TCP/IP server has received 50860 bytes of data
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:01:28.509Z SendDataTCPServer.js: TCP/IP server has received 52840 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.545Z SendDataTCPServer.js: TCP/IP server has received 56800 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.548Z SendDataTCPServer.js: TCP/IP server has received 58780 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.556Z SendDataTCPServer.js: TCP/IP server has received 60760 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.623Z SendDataTCPServer.js: TCP/IP server has received 28264 bytes of data
I/jxcore-log( 3200): ,
,I/jxcore-log( 3200): 2015-11-26T07:01:28.626Z SendDataTCPServer.js: TCP/IP server has received 62740 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.664Z SendDataTCPServer.js: TCP/IP server has received 68680 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.679Z SendDataTCPServer.js: TCP/IP server has received 30244 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.689Z SendDataTCPServer.js: TCP/IP server has received 32224 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.703Z SendDataTCPServer.js: TCP/IP server has received 70660 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.707Z SendDataTCPServer.js: TCP/IP server has received 72640 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.745Z SendDataTCPServer.js: TCP/IP server has received 76600 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.758Z SendDataTCPServer.js: TCP/IP server has received 34204 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.773Z SendDataTCPServer.js: TCP/IP server has received 78580 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.807Z SendDataTCPServer.js: TCP/IP server has received 80560 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.813Z SendDataTCPServer.js: TCP/IP server has received 82540 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.817Z SendDataTCPServer.js: TCP/IP server has received 84520 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.836Z SendDataTCPServer.js: TCP/IP server has received 36184 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.843Z SendDataTCPServer.js: TCP/IP server has received 38164 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.855Z SendDataTCPServer.js: TCP/IP server has received 86500 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.860Z SendDataTCPServer.js: TCP/IP server has received 88480 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.877Z SendDataTCPServer.js: TCP/IP server has received 40144 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.888Z SendDataTCPServer.js: TCP/IP server has received 90460 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.896Z SendDataTCPServer.js: TCP/IP server has received 92440 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.934Z SendDataTCPServer.js: TCP/IP server has received 94420 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.950Z SendDataTCPServer.js: TCP/IP server has received 42124 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.958Z SendDataTCPServer.js: TCP/IP server has received 96400 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.963Z SendDataTCPServer.js: TCP/IP server has received 98380 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.984Z SendDataTCPServer.js: TCP/IP server has received 44104 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:28.985Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.008Z SendDataTCPServer.js: TCP/IP server has received 46084 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.045Z SendDataTCPServer.js: TCP/IP server has received 48064 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.051Z SendDataTCPServer.js: TCP/IP server has received 50044 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.058Z SendDataTCPServer.js: TCP/IP server has received 54004 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.095Z SendDataTCPServer.js: TCP/IP server has received 57964 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.108Z SendDataTCPServer.js: TCP/IP server has received 59944 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.147Z SendDataTCPServer.js: TCP/IP server has received 61924 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.153Z SendDataTCPServer.js: TCP/IP server has received 63904 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.184Z SendDataTCPServer.js: TCP/IP server has received 65884 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.187Z SendDataTCPServer.js: TCP/IP server has received 67864 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.251Z SendDataTCPServer.js: TCP/IP server has received 69844 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.287Z SendDataTCPServer.js: TCP/IP server has received 71824 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.306Z SendDataTCPServer.js: TCP/IP server has received 73804 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.364Z SendDataTCPServer.js: TCP/IP server has received 75784 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.484Z SendDataTCPServer.js: TCP/IP server has received 77764 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.574Z SendDataTCPServer.js: TCP/IP server has received 79744 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.608Z SendDataTCPServer.js: TCP/IP server has received 81724 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.657Z SendDataTCPServer.js: TCP/IP server has received 83704 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.694Z SendDataTCPServer.js: TCP/IP server has received 85684 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.778Z SendDataTCPServer.js: TCP/IP server has received 87664 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.782Z SendDataTCPServer.js: TCP/IP server has received 89644 bytes of data,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:29.785Z SendDataTCPServer.js: TCP/IP server has received 91624 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.792Z SendDataTCPServer.js: TCP/IP server has received 93604 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.825Z SendDataTCPServer.js: TCP/IP server has received 99544 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:29.847Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data,
I/jxcore-log( 3200): 
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/jxcore-log( 3200): 2015-11-26T07:01:31.730Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:31.731Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:31.733Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:31.733Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:31.735Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
,I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read,
I/BtConnectorHelper( 3200): Disconnect outgoing peer: samsung-SM-G900F_PT5166
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToRequestSocket( 3200): Close server socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1,
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82b2c rs_disc_pending=1,
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x1e):jv handle:0x0 not FOUND
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:01:36.736Z SendDataConnector.js: re-try now : 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:36.737Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 610c
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 789376, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/bt-btif ( 3260): invalid rfc slot id: 35
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT2102
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T07:01:39.190Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3928): [1] 5.onFinished: Scheduling replication attempt 3.
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [44:80:eb:7b:5a:05]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: XT1072
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3200): got MESSAGE_READ 81 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3200): Incoming connection Hand Shake finished for : motorola-XT1072_PT2627
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, motorola-XT1072_PT2627
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:01:40.870Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): invalid rfc slot id: 33
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4166
I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3200): Close bt out
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt socket
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4166
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/jxcore-log( 3200): 2015-11-26T07:01:41.206Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:41.263Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:41.267Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:41.299Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:41.330Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:41.347Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x45 current:0x0,
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x45,
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x44 current:0x0,
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x44
,I/jxcore-log( 3200): 2015-11-26T07:01:41.744Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:41.759Z SendDataConnector.js: Connect (retry count 4) to peer 7C:F9:0E:34:8A:A0 with availability status: true,
,I/jxcore-log( 3200): ,
,I/jxcore-log( 3200): 2015-11-26T07:01:41.760Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:41.760Z SendDataConnector.js: do connect now
,I/jxcore-log( 3200): 
I/        ( 3200): Selected device address: 7C:F9:0E:34:8A:A0, name: S5-1
,I/BTConnectToThread( 3200): Starting to connect,
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to S5-1, at 7C:F9:0E:34:8A:A0
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [7c:f9:0e:34:8a:a0]: 0, 0, 0
,I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:70:12:80
I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=02:f4:6f:30:e0:6d
I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=36:fc:ef:de:0a:e2
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag,
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255,
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-LG-H815_PT5432
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:01:46.043Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:46.621Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:46.661Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:46.800Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:46.895Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:46.899Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:46.943Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1,
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTConnectToThread( 3200): got MESSAGE_READ 82 bytes.
I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : samsung-SM-G900F_PT5166
I/HS      ( 3200): Hand Shake finished outgoing for : samsung-SM-G900F_PT5166
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, samsung-SM-G900F_PT5166
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 38848
I/BtConnectorHelper( 3200): Request socket is using : 38848
,I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :38848
,I/jxcore-log( 3200): 2015-11-26T07:01:48.020Z SendDataConnector.js: CLIENT connected to 38848, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:48.021Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 38848
I/BtToRequestSocket( 3200): Set local streams
,I/jxcore-log( 3200): 2015-11-26T07:01:48.030Z SendDataConnector.js: CLIENT now sending 10000 bytes of data
I/jxcore-log( 3200): 
I/BtToRequestSocket( 3200): rin ended ---------------------------;
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21,
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2102","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT2102
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT2102
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177,
I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:01:50.810Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [e0:db:10:1f:c9:5e]: 6, 10f, 608
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Note3-1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1,
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:01:51.244Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:51.325Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data,
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:51.355Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:51.435Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:51.487Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): invalid rfc slot id: 36
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT2627
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3200): Close bt in
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt out
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :motorola-XT1072_PT2627
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/jxcore-log( 3200): 2015-11-26T07:01:51.688Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255,
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection,
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1,
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,W/bt-btif ( 3260): dm_pm_timer expires
,W/bt-btif ( 3260): dm_pm_timer expires 1
W/bt-btif ( 3260): proc dm_pm_timer expires
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 6 peers.
,I/SS      ( 3200): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3200): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
I/SS      ( 3200): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(4): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/SS      ( 3200): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(6): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x48
,I/BTListenerThread( 3200): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT4166
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, samsung-SM-N9005_PT4166
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/jxcore-log( 3200): 2015-11-26T07:01:53.354Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:01:53.861Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:53.876Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:53.879Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:53.887Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:53.910Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:54.029Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ea:50:8b:de:28:a3 p2p_dev_addr=ea:50:8b:de:28:a3 pri_dev_type=10-0050F204-5 name='Note3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3200): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): invalid rfc slot id: 37
I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt socket
I/jxcore-log( 3200): 2015-11-26T07:01:56.630Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive,
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: XT1072
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4c current:0x0
W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4c
,I/jxcore-log( 3200): 2015-11-26T07:01:58.092Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:58.093Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:58.094Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:58.099Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:58.100Z SendDataConnector.js: Stop data retrieving timer
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:58.101Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/BtConnectorHelper( 3200): Disconnect outgoing peer: 7C:F9:0E:34:8A:A0
,I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3200): 2015-11-26T07:01:58.106Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:34:8A:A0
I/jxcore-log( 3200): 
I/jxcore-log( 3200): ---- round done--------
I/jxcore-log( 3200): 
I/jxcore-log( 3200): ---- gotta redo : 7C:F9:0E:34:8A:A0, try count now: 1
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): do fake peer & start
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Connect to fake peer: B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:58.110Z SendDataConnector.js: Start called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:01:58.111Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:01:58.111Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: B0:C5:59:3F:75:69, name: null,
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at B0:C5:59:3F:75:69,
I/jxcore-log( 3200): 2015-11-26T07:01:58.121Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Round of send data to peer 7C:F9:0E:34:8A:A0 done with result: DATA-TIMEOUT", source: file:///android_asset/www/js/thali_main.js (63),
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0xa):jv handle:0x0 not FOUND
,I/art     (  820): Explicit concurrent mark sweep GC freed 29800(1282KB) AllocSpace objects, 8(410KB) LOS objects, 31% free, 34MB/50MB, paused 1.892ms total 81.808ms
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3928): [1] 5.onFinished: Scheduling replication attempt 4.
,W/bt-btif ( 3260): invalid rfc slot id: 39
I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT2102
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt in
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT2102
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/jxcore-log( 3200): 2015-11-26T07:02:01.192Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f825d4 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4e current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4e
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x4  CID 0x42
,E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:42, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3260): invalid rfc slot id: 42
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T07:02:03.251Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:02:03.251Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:03.252Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: S5-1,
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): invalid rfc slot id: 40
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4166
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T07:02:04.143Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4f
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,W/bt-btif ( 3260): info:x10,
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 7 peers.
,I/SS      ( 3200): Peer(1): XT1039_8c05 f4:f1:e1:5c:43:c8,
,I/SS      ( 3200): Peer(2): Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
,I/SS      ( 3200): Peer(3): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3200): Peer(4): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(5): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(7): G4-1 a2:39:f7:6f:c9:5d
,D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag,
D/BluetoothMapService( 3260): onReceive
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Note3-1
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-LG-H815_PT5432
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:02:08.241Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:08.252Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:08.253Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69,
I/jxcore-log( 3200): 
,I/        ( 3200): Started service discovery
,I/jxcore-log( 3200): 2015-11-26T07:02:08.650Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:08.669Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:08.761Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:08.766Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:08.771Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: Note3-1, WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3200): we got incoming connection
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2102","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3200): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT2102
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT2102
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/jxcore-log( 3200): 2015-11-26T07:02:12.914Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:02:13.257Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:13.257Z SendDataConnector.js: Connect (retry count 1) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:02:13.258Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:13.258Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: B0:C5:59:3F:75:69, name: null
I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at B0:C5:59:3F:75:69
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/jxcore-log( 3200): 2015-11-26T07:02:13.331Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:13.402Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:13.473Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:13.549Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:13.686Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:13.822Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=0a:ec:a9:50:76:28,
,I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=a2:39:f7:6f:c9:5d
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3200): we got incoming connection,
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/        ( 3200): Cleared service requests
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/        ( 3200): Started peer discovery
,I/BTListenerThread( 3200): got MESSAGE_READ 82 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
I/HS      ( 3200): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT4166
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, samsung-SM-N9005_PT4166
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:02:15.745Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:16.190Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:16.195Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:16.199Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:16.207Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:16.220Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:16.227Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): invalid rfc slot id: 41
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT5432
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/jxcore-log( 3200): 2015-11-26T07:02:18.900Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 3928): [1] 5.onFinished: Scheduling replication attempt 5.
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x46 current:0x0
W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x46
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 8 peers.
,I/SS      ( 3200): Peer(1): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3200): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(3): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(4): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3200): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3200): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3200): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,W/bt-btif ( 3260): invalid rfc slot id: 43
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT2102
I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtToSocketBase( 3200): Close bt socket
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T07:02:23.692Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4688): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x47 current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x47
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): invalid rfc slot id: 44
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4166
,I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4166
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/jxcore-log( 3200): 2015-11-26T07:02:26.421Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x49 current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x49
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT811, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT811, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag,
,D/BluetoothMapService( 3260): onReceive,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21,
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Note3-1
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT4327","ra":"7C:F9:0E:37:96:AB"} -- peerIdentifier:7C:F9:0E:37:96:AB, peerName: samsung-SM-A500FU_PT4327, peerAddress: 7C:F9:0E:37:96:AB
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:37:96:AB, Name: samsung-SM-A500FU_PT4327, WifiDirectName: , WifiDirect Address: 7e:f9:0e:37:96:ac, peerId: 7C:F9:0E:37:96:AB
,W/bt-btif ( 3260): info:x10,
D/        ( 3260): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,D/btif_config( 3260): btif_get_device_type: Device [f8:95:c7:87:3c:51] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 1
E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 10 NewState: 11
I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:3C:51 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: F8:95:C7:87:3C:51
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:F8:95:C7:87:3C:51 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State,
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
,I/BTListenerThread( 3200): we got incoming connection,
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started,
,I/BTListenerThread( 3200): got MESSAGE_READ 77 bytes.,
I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3200): Incoming connection Hand Shake finished for : LGE-LG-H815_PT5432
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:02:32.402Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:32.838Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:32.849Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:32.855Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:32.867Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:32.923Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [58:2a:f7:ed:96:be]: 6, 10f, 608
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 80 bytes.
I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2102","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.,
I/HS      ( 3200): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT2102
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
,I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT2102
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
,I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177,
I/jxcore-log( 3200): 2015-11-26T07:02:35.682Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:02:36.035Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:36.174Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:36.233Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:36.243Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:36.247Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:36.269Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): ,
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,W/bt-btif ( 3260): info:x10,
D/        ( 3260): remote version info [e0:db:10:1f:c9:5e]: 7, f, 6109
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Note3-1
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
,I/BTListenerThread( 3200): waiting to accept incoming Connection
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 82 bytes.,
I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}����������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3200): Incoming connection Hand Shake finished for : samsung-SM-N9005_PT4166
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, samsung-SM-N9005_PT4166
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtToRequestSocket( 3200): --DoOneRunRound started
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
I/jxcore-log( 3200): 2015-11-26T07:02:37.854Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:38.305Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:38.309Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:38.316Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:38.320Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:38.328Z SendDataTCPServer.js: TCP/IP server has received 8192 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:38.336Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
,E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 849672, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 851241, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 45155(2MB) AllocSpace objects, 13(1433KB) LOS objects, 37% free, 27MB/43MB, paused 2.180ms total 59.544ms
,D/Finsky  ( 3928): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 3928): [1] 5.onFinished: Giving up after 6 failures.
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 8 peers.
,I/SS      ( 3200): Peer(1): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3200): Peer(2): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(3): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3200): Peer(4): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3200): Peer(5): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3200): Peer(6): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(7): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3200): Peer(8): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3260): invalid rfc slot id: 46
I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :LGE-LG-H815_PT5432
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
,I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T07:02:43.109Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=1
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x40 current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x40
,W/bt-sdp  ( 3260): SDP - Rcvd conn cnf with error: 0x22  CID 0x45
,E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:45, failed to find channle,                                       status:1, scn:0
W/bt-btif ( 3260): invalid rfc slot id: 45
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3200): 2015-11-26T07:02:44.484Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:44.485Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:44.486Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3200): Found Service, :{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT2627","ra":"44:80:EB:7B:5A:05"} -- peerIdentifier:44:80:EB:7B:5A:05, peerName: motorola-XT1072_PT2627, peerAddress: 44:80:EB:7B:5A:05
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 44:80:EB:7B:5A:05, Name: motorola-XT1072_PT2627, WifiDirectName: , WifiDirect Address: 44:80:eb:7b:5a:07, peerId: 44:80:EB:7B:5A:05
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82b2c rs_disc_pending=0
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): invalid rfc slot id: 47
I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT2102
,I/BtToSocketBase( 3200): Stop ReceivingThread,
I/BtToSocketBase( 3200): Stop SendingThread
,I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
,I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
,I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T07:02:46.549Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): ,
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x48 current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x48
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82244 rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: G4-1
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82b2c rs_disc_pending=1
W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-btif ( 3260): invalid rfc slot id: 48
,I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :samsung-SM-N9005_PT4166
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in,
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
I/jxcore-log( 3200): 2015-11-26T07:02:48.327Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82964 rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4a current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4a
,I/jxcore-log( 3200): 2015-11-26T07:02:49.487Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
,I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:02:49.488Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:1F:C9:5E, alias=null, name=Note3-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Note3-1
,I/jxcore-log( 3200): 2015-11-26T07:02:54.491Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:54.492Z SendDataConnector.js: Connect (retry count 2) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:02:54.493Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:54.494Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: B0:C5:59:3F:75:69, name: null
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at B0:C5:59:3F:75:69
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3260): No ag scb for peer addr
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [58:2a:f7:ed:96:be]: 7, f, 6109
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/SS      ( 3200): Found 9 peers.
I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(2): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3200): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3200): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3200): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:255
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:255
,W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTListenerThread( 3200): we got incoming connection
I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTListenerThread( 3200): waiting to accept incoming Connection
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTListenerThread( 3200): got MESSAGE_READ 80 bytes.
,I/BTListenerThread( 3200): Got JSON from encryption:{"pi":"58:2A:F7:ED:96:BE","pn":"HUAWEI-ALE-L21_PT2102","ra":"58:2A:F7:ED:96:BE"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTListenerThread( 3200): MESSAGE_WRITE 82 bytes.
,I/HS      ( 3200): Incoming connection Hand Shake finished for : HUAWEI-ALE-L21_PT2102
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : true, HUAWEI-ALE-L21_PT2102
,I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BTConnectedThread
I/BtConnectorHelper( 3200): Server socket is using : 0, and is now connected.
,I/BtToRequestSocket( 3200): --DoOneRunRound started
,I/BtToRequestSocket( 3200): LocalHost address: localhost/127.0.0.1, port: 41177
,I/BtToRequestSocket( 3200): --DoOneRunRound ended
,I/jxcore-log( 3200): 2015-11-26T07:02:57.078Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:57.450Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:57.453Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:57.489Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:57.529Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:02:57.533Z SendDataTCPServer.js: TCP/IP server has received 10000 bytes of data
I/jxcore-log( 3200): 
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3200): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,W/bt-btif ( 3260): invalid rfc slot id: 49
I/BtToSocketBase( 3200): ReceivingThread thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtConnectorHelper( 3200): Disconnect:::Stop : mBtToServerSocket :HUAWEI-ALE-L21_PT2102
,I/BtToSocketBase( 3200): Stop ReceivingThread
,I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
,I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt socket
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.net.SocketException: Socket closed
I/BtConnectorHelper( 3200): BT Disconnected with error : disconnected: java.net.SocketException: Socket closed
,I/jxcore-log( 3200): 2015-11-26T07:03:07.697Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 3200): 
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Started peer discovery
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82b2c rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
,W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,W/bt-rfcomm( 3260): rfc_find_lcid_mcb LCID reused LCID:0x4f current:0x0
,W/bt-rfcomm( 3260): RFCOMM_DisconnectInd LCID:0x4f
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=58:2A:F7:ED:96:BE, alias=null, name=ALE-L21, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: ALE-L21
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 10 peers.
,I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(2): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3200): Peer(3): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(4): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(5): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(6): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3200): Peer(7): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(8): Note3-1 ea:50:8b:de:28:a3
I/SS      ( 3200): Peer(9): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(10): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/wpa_supplicant( 4688): P2P-DEVICE-LOST p2p_dev_addr=ea:50:8b:de:28:a3
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4688): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4688): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3200): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3200): Cleared service requests
F/libc    ( 4688): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 4688 (wpa_supplicant)
,I/libc    ( 4688): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,D/WifiHW  (  820): 'P2P_FIND 120' command timed out.
,I/        ( 3200): Starting peer discovery failed, error code 0
E/WifiStateMachine(  820): Connection lost, restart supplicant
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): failed to set BSSID: any
E/native  (  820): do suspend true
,W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1483): Read error: ssl=0x9d0e3e00: I/O error during system call, Connection timed out
,I/jxcore-log( 3200): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): The Coordinator has disconnected!
I/jxcore-log( 3200): 
V/NativeCrypto( 1483): SSL shutdown failed: ssl=0x9d0e3e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 103] got DISCONNECTED, was satisfying 2
E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  820): Unexpected BatchedScanResults :null
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 103]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/RttService(  820): SCAN_AVAILABLE : 1
,D/RttService(  820): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
I/        ( 3200): Discovery state changed to Stopped.
I/WB      ( 3200): Wifi is DISABLED !!
I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
I/        ( 3200): Stopping services
,I/        ( 3200): Stop Bluetooth
I/        ( 3200): Stop Bluetooth
I/BTListenerThread( 3200): Stopped
,E/bt-btif ( 3260): SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:50, channel:-1
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/SS      ( 3200): We got empty peers list
I/        ( 3200): Starting peer discovery failed, error code 2
I/        ( 3200): Clearing local services failed, error code 2
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3200): 2015-11-26T07:03:32.715Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:32.715Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:32.715Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/        ( 3200): Clearing service requests failed, error code 2
I/        ( 3200): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 103]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 103](  820): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 6
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=false
,E/ConnectivityService(  820): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/Tethering(  820): MasterInitialState.processMessage what=3
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
,D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1782): onCreate
,E/GpsLocationProvider(  820): No APN found to select.
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1782): num queued entries: 0
,I/iu.UploadsManager( 1782): num updated entries: 0
,I/iu.SyncManager( 1782): NEXT; no task
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599980 ms
,I/Babel   ( 2640): connection state changed from CONNECTED to DISCONNECTED
,D/SystemUpdateService( 1782): onDestroy
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599988 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy,
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,D/WifiService(  820): setWifiEnabled: false pid=3200, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  820): setWifiEnabled: true pid=3200, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  820): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 480ms
,I/jxcore-log( 3200): Wifi toggled for connection repairment
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  820): DEFERRED_TOGGLE handled
,D/SoftapController(  354): Softap fwReload - Ok,
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/Tethering(  820): InitialState.processMessage what=4
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false,
,E/WifiHW  (  820): Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory,
,I/wpa_supplicant( 4994): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 4994): rfkill: Cannot open RFKILL control device,
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 4994): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 4994): Could not read interface p2p-dev-wlan0 flags: No such device
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@33e79fbb}
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiNative-HAL(  820): Setting external_sim to 1
D/WifiStateMachine(  820): Setting OUI to 92-68-C3
,I/WifiNative-HAL(  820): startHal
,D/wifi    (  820): setting scan oui 0xb4bbad18
D/WifiHAL (  820): Sending mac address OUI
,E/native  (  820): do suspend true
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiScanningService(  820): SCAN_AVAILABLE : 3
,D/RttService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  820): DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4bbad18
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
D/CommandListener(  354): Setting iface cfg
E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '140 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 140 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,I/WB      ( 3200): Wifi is now enabled !
I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
,I/        ( 3200): Starting All
I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, org.thaliproject.p2p.btconnectorlib.BTConnectorSettings@6b82210
I/        ( 3200): Stopping services
I/        ( 3200): Starting services address: {"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}
D/WifiNative-HAL(  820): p2pGetDeviceAddress
,I/        ( 3200): Add local service :{"pi":"F8:CF:C5:D9:E5:61","pn":"motorola-Nexus 6_PT2145","ra":"F8:CF:C5:D9:E5:61"}, length : 82
I/        ( 3200): peerDiscoveryTimer timeout value:7870
,D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
I/        ( 3200): Stop Bluetooth
I/        ( 3200): StartBluetooth listener
,I/        ( 3200): StartBluetooth listener
D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/BTListenerThread( 3200): starting to listen
,I/BTListenerThread( 3200): waiting to accept incoming Connection
I/        ( 3200): Discovery state changed to Stopped.
,I/wpa_supplicant( 4994): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/        ( 3200): Added local service
,I/        ( 3200): Cleared service requests
,I/        ( 3200): Stopped peer discovery
I/        ( 3200): Started peer discovery
I/        ( 3200): Discovery state changed to Started.
I/        ( 3200): Started peer discovery
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63),
,I/wpa_supplicant( 4994): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000,
E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/jxcore-log( 3200): 2015-11-26T07:03:37.716Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:37.717Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4994): wlan0: Trying to associate with SSID 'NG7005g'
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,I/art     (  820): Explicit concurrent mark sweep GC freed 56424(2MB) AllocSpace objects, 4(252KB) LOS objects, 31% free, 34MB/50MB, paused 1.569ms total 85.661ms
,I/wpa_supplicant( 4994): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 4994): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 4994): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 5
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -44
E/WifiStateMachine(  820):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=170 rx_time=418 scan_time=0
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/wpa_supplicant( 4994): P2P-FIND-STOPPED 
,I/        ( 3200): Discovery state changed to Stopped.
,I/        ( 3200): Starting peer discovery failed, error code 2
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 2 peers.
I/SS      ( 3200): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
,I/SS      ( 3200): Peer(2): Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/        ( 3200): Added service request
,I/dhcpcd  ( 5005): version 5.5.6 starting
,I/dhcpcd  ( 5005): wlan0: rebinding lease of 192.168.1.110
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@33e79fbb}
,I/        ( 3200): Starting service discovery failed, error code 2
,I/        ( 3200): Cleared service requests
,I/dhcpcd  ( 5005): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 5005): wlan0: leased 192.168.1.110 for 86400 seconds
,E/native  (  820): do suspend true
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 104
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 104
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 104
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 104
,D/ConnectivityService(  820): Setting Dns servers for network 104 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 104]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 104]
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 104]
,D/ConnectivityService(  820):    accepting network in place of null
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{104}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 104]
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 104] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 2
,E/GpsLocationProvider(  820): No APN found to select.
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1782): num queued entries: 0
,I/iu.UploadsManager( 1782): num updated entries: 0
I/ValidateNoPeople(  820): skipping global notification
,I/iu.SyncManager( 1782): NEXT; no task,
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599973 ms,
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 26 Nov 2015 07:03:42 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448521422324], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448521422306]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): Validated
,D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null,
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 104]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 104],
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 104] was already satisfying request 1. No change.
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 104]
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
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 940605, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/Herrevad( 1782): NQAS connected
,I/Babel   ( 2640): connection state changed from DISCONNECTED to CONNECTED
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/SS      ( 3200): Found 3 peers.
I/SS      ( 3200): Peer(1): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(2): G4-1 a2:39:f7:6f:c9:5d
,I/SS      ( 3200): Peer(3): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/jxcore-log( 3200): 2015-11-26T07:03:42.721Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:03:42.722Z SendDataConnector.js: Connect (retry count 3) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:42.722Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): 2015-11-26T07:03:42.723Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: B0:C5:59:3F:75:69, name: null,
,I/BTConnectToThread( 3200): Starting to connect,
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at B0:C5:59:3F:75:69
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:53, failed to find channle,                                       status:2, scn:-90363730
W/bt-btif ( 3260): invalid rfc slot id: 53
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T07:03:42.746Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:42.746Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:03:42.747Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,D/GCM     ( 1483): Connected
,D/GCM     ( 1483): Message class com.google.f.a.a.p
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 103] cleared because we found a replacement network
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect called
,I/jxcore-log( 3200): 
I/jxcore-log( 3200): Coordinator is now connected to the server!
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback connected to server", source: file:///android_asset/www/js/thali_main.js (63)
I/wpa_supplicant( 4994): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 52:55:27:f0:fd:0b p2p_dev_addr=52:55:27:f0:fd:0b pri_dev_type=10-0050F204-5 name='Android_8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND ee:1f:72:18:8b:78 p2p_dev_addr=ee:1f:72:18:8b:78 pri_dev_type=10-0050F204-5 name='Thali Test (Galaxy S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 52:55:27:f0:ff:f0 p2p_dev_addr=52:55:27:f0:ff:f0 pri_dev_type=10-0050F204-5 name='Android_2dc2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/jxcore-log( 3200): 2015-11-26T07:03:47.764Z SendDataConnector.js: re-try now : B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:03:47.765Z SendDataConnector.js: ReStart called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 0a:ec:a9:50:75:42 p2p_dev_addr=0a:ec:a9:50:75:42 pri_dev_type=10-0050F204-5 name='A3-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,I/        ( 3200): Found Service, :{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT621","ra":"08:EC:A9:50:75:41"} -- peerIdentifier:08:EC:A9:50:75:41, peerName: samsung-SM-A300FU_PT621, peerAddress: 08:EC:A9:50:75:41
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 08:EC:A9:50:75:41, Name: samsung-SM-A300FU_PT621, WifiDirectName: A3-1, WifiDirect Address: 0a:ec:a9:50:75:42, peerId: 08:EC:A9:50:75:41
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT811, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT811, WifiDirectName: , WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: , WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: , WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2
,I/        ( 3200): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: , WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/jxcore-log( 3200): 2015-11-26T07:03:52.769Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:52.770Z SendDataConnector.js: Connect (retry count 4) to peer B0:C5:59:3F:75:69 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:52.770Z SendDataConnector.js: doConnect called with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): ,
I/jxcore-log( 3200): 2015-11-26T07:03:52.771Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: B0:C5:59:3F:75:69, name: null
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at B0:C5:59:3F:75:69
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:54, failed to find channle,                                       status:2, scn:-90363730
W/bt-btif ( 3260): invalid rfc slot id: 54
I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/jxcore-log( 3200): 2015-11-26T07:03:52.795Z SendDataConnector.js: CLIENT connected to -1, error: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:52.796Z SendDataConnector.js: CLIENT Can not Connect: Connection to B0:C5:59:3F:75:69 failed
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:03:52.800Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:03:52.805Z SendDataConnector.js: Mobile.Disconnect() callback with peer B0:C5:59:3F:75:69
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): ---- round done--------
I/jxcore-log( 3200): 
I/jxcore-log( 3200): ---- gotta redo : B0:C5:59:3F:75:69, try count now: 1
I/jxcore-log( 3200): 
I/jxcore-log( 3200): do fake peer & start
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): Connect to fake peer: 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:52.808Z SendDataConnector.js: Start called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:52.809Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:03:52.809Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/        ( 3200): Connecting to null, at 7C:F9:0E:51:18:22
I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Round of send data to peer B0:C5:59:3F:75:69 done with result: Connection to B0:C5:59:3F:75:69 failed", source: file:///android_asset/www/js/thali_main.js (63)
I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:55, failed to find channle,                                       status:2, scn:-90363730
W/bt-btif ( 3260): invalid rfc slot id: 55
,I/BTConnectToThread( 3200): socket connect failed: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/CONNEC  ( 3200): Error: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/jxcore-log( 3200): 2015-11-26T07:03:52.820Z SendDataConnector.js: CLIENT connected to -1, error: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:52.821Z SendDataConnector.js: CLIENT Can not Connect: Connection to 7C:F9:0E:51:18:22 failed
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:03:52.821Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 02:ee:bd:dd:33:d2 p2p_dev_addr=02:ee:bd:dd:33:d2 pri_dev_type=10-0050F204-5 name='Android_d8c3' config_methods=0x188 dev_capab=0x25 group_capab=0x0
,E/bt-btif ( 3260): DISCOVERY_COMP_EVT slot id:50, failed to find channle,                                       status:1, scn:0
,W/bt-btif ( 3260): invalid rfc slot id: 50
,I/        ( 3200): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/jxcore-log( 3200): 2015-11-26T07:03:57.822Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:03:57.823Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 36:fc:ef:de:0a:e2 p2p_dev_addr=36:fc:ef:de:0a:e2 pri_dev_type=10-0050F204-5 name='Thali Test's G2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/jxcore-log( 3200): 2015-11-26T07:04:02.828Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:02.829Z SendDataConnector.js: Connect (retry count 1) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:02.829Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:02.830Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 7C:F9:0E:51:18:22, name: null
,I/BTConnectToThread( 3200): Starting to connect
W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to null, at 7C:F9:0E:51:18:22
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,W/bt-btif ( 3260): info:x10
,D/        ( 3260): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3
E/BluetoothRemoteDevices( 3260): aclStateChangeCallback: Device is NULL
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,D/btif_config( 3260): btif_get_device_type: Device [7c:f9:0e:51:18:22] type 1
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 1
,E/bt-btif ( 3260): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 10 NewState: 11
,I/BluetoothBondStateMachine( 3260): Entering PendingCommandState State
,I/BluetoothBondStateMachine( 3260): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:51:18:22 newState: 0
,D/BluetoothAdapterProperties( 3260): Failed to remove device: 7C:F9:0E:51:18:22
,I/BluetoothBondStateMachine( 3260): Bond State Change Intent:7C:F9:0E:51:18:22 OldState: 11 NewState: 10
,I/BluetoothBondStateMachine( 3260): StableState(): Entering Off State
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
,W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5029","ra":"7C:F9:0E:51:18:22"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : samsung-SM-A500FU_PT5029
I/HS      ( 3200): Hand Shake finished outgoing for : samsung-SM-A500FU_PT5029
,I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, samsung-SM-A500FU_PT5029
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 59487
I/BtConnectorHelper( 3200): Request socket is using : 59487
I/BtToRequestSocket( 3200): Now accepting connections
,I/        ( 3200): Cleared service requests
,I/wpa_supplicant( 4994): p2p-dev-wlan0: P2P: Reject scan trigger since one is already pending
I/        ( 3200): Started peer discovery
,I/        ( 3200): Discovery state changed to Started.
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :59487
,I/jxcore-log( 3200): 2015-11-26T07:04:04.080Z SendDataConnector.js: CLIENT connected to 59487, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:04.080Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 59487
,I/BtToRequestSocket( 3200): Set local streams
,I/BtToRequestSocket( 3200): rin ended ---------------------------;
I/jxcore-log( 3200): 2015-11-26T07:04:04.093Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 3200): 
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND 02:f4:6f:30:e0:6d p2p_dev_addr=02:f4:6f:30:e0:6d pri_dev_type=10-0050F204-5 name='S5mini-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8736
,I/SS      ( 3200): Found 11 peers.
,I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
I/SS      ( 3200): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(4): G3s-1 a2:39:f7:70:12:80
,I/SS      ( 3200): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(6): A3-1 0a:ec:a9:50:75:42
I/SS      ( 3200): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
,I/SS      ( 3200): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/jxcore-log( 3200): 2015-11-26T07:04:04.605Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:18184
,I/jxcore-log( 3200): 2015-11-26T07:04:04.650Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:04.676Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 3200): 
,D/        ( 3260): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8284
,I/jxcore-log( 3200): 2015-11-26T07:04:04.766Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:04.815Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:04.849Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:04.895Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:04.970Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:05.053Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 3200): 
,I/        ( 3200): Started service discovery
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82ebc rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/        ( 3200): Found Service, :{"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"E0:DB:10:1F:C9:5E","pn":"samsung-SM-N9005_PT4166","ra":"E0:DB:10:1F:C9:5E"} -- peerIdentifier:E0:DB:10:1F:C9:5E, peerName: samsung-SM-N9005_PT4166, peerAddress: E0:DB:10:1F:C9:5E
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : E0:DB:10:1F:C9:5E, Name: samsung-SM-N9005_PT4166, WifiDirectName: , WifiDirect Address: ea:50:8b:de:28:a3, peerId: E0:DB:10:1F:C9:5E
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0,
,W/bt-btif ( 3260): dm_pm_timer expires
,W/bt-btif ( 3260): dm_pm_timer expires 0
W/bt-btif ( 3260): proc dm_pm_timer expires
,I/        ( 3200): Found Service, :{"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"}, typeCordovap2p._tcp.local.:,
I/        ( 3200): JsonLine: {"ra":"F4:F1:E1:5C:3B:E2","pi":"F4:F1:E1:5C:3B:E2","pn":"motorola-XT1039_PT186"} -- peerIdentifier:F4:F1:E1:5C:3B:E2, peerName: motorola-XT1039_PT186, peerAddress: F4:F1:E1:5C:3B:E2
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F4:F1:E1:5C:3B:E2, Name: motorola-XT1039_PT186, WifiDirectName: XT1039_8c05, WifiDirect Address: f4:f1:e1:5c:43:c8, peerId: F4:F1:E1:5C:3B:E2,
,I/        ( 3200): Found Service, :{"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"50:2E:6C:AC:21:50","pn":"HTC-HTC One_M8_PT6155","ra":"50:2E:6C:AC:21:50"} -- peerIdentifier:50:2E:6C:AC:21:50, peerName: HTC-HTC One_M8_PT6155, peerAddress: 50:2E:6C:AC:21:50
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 50:2E:6C:AC:21:50, Name: HTC-HTC One_M8_PT6155, WifiDirectName: Android_d8c3, WifiDirect Address: 02:ee:bd:dd:33:d2, peerId: 50:2E:6C:AC:21:50
,I/        ( 3200): Found Service, :{"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"ra":"34:FC:EF:9D:93:0B","pi":"34:FC:EF:9D:93:0B","pn":"LGE-LG-D802_PT944"} -- peerIdentifier:34:FC:EF:9D:93:0B, peerName: LGE-LG-D802_PT944, peerAddress: 34:FC:EF:9D:93:0B
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 34:FC:EF:9D:93:0B, Name: LGE-LG-D802_PT944, WifiDirectName: Thali Test's G2, WifiDirect Address: 36:fc:ef:de:0a:e2, peerId: 34:FC:EF:9D:93:0B
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT811","ra":"F8:95:C7:87:85:54"} -- peerIdentifier:F8:95:C7:87:85:54, peerName: LGE-LG-D722_PT811, peerAddress: F8:95:C7:87:85:54
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:85:54, Name: LGE-LG-D722_PT811, WifiDirectName: G3s-1, WifiDirect Address: a2:39:f7:70:12:80, peerId: F8:95:C7:87:85:54
,I/jxcore-log( 3200): 2015-11-26T07:04:15.052Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:15.053Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:15.054Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:15.055Z SendDataConnector.js: tryAgain afer: 5000 ms.
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:15.056Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
I/BtConnectorHelper( 3200): Disconnect outgoing peer: samsung-SM-A500FU_PT5029
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
,I/BtToSocketBase( 3200): Close bt out
,I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x15):jv handle:0x0 not FOUND
,I/        ( 3200): Found Service, :{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"}, typeCordovap2p._tcp.local.:
I/        ( 3200): JsonLine: {"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT5166","ra":"7C:F9:0E:34:8A:A0"} -- peerIdentifier:7C:F9:0E:34:8A:A0, peerName: samsung-SM-G900F_PT5166, peerAddress: 7C:F9:0E:34:8A:A0
,I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : 7C:F9:0E:34:8A:A0, Name: samsung-SM-G900F_PT5166, WifiDirectName: S5-1, WifiDirect Address: ee:1f:72:63:11:86, peerId: 7C:F9:0E:34:8A:A0
,I/        ( 3200): Found Service, :{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT8112","ra":"B0:C5:59:3F:75:69"} -- peerIdentifier:B0:C5:59:3F:75:69, peerName: samsung-SM-G900F_PT8112, peerAddress: B0:C5:59:3F:75:69
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : B0:C5:59:3F:75:69, Name: samsung-SM-G900F_PT8112, WifiDirectName: Thali Test (Galaxy S5), WifiDirect Address: ee:1f:72:18:8b:78, peerId: B0:C5:59:3F:75:69
,I/        ( 3200): Found Service, :{"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"}, typeCordovap2p._tcp.local.:
,I/        ( 3200): JsonLine: {"pi":"F8:95:C7:87:3C:51","pn":"LGE-LG-H815_PT5432","ra":"F8:95:C7:87:3C:51"} -- peerIdentifier:F8:95:C7:87:3C:51, peerName: LGE-LG-H815_PT5432, peerAddress: F8:95:C7:87:3C:51
I/BtConnectorHelper( 3200): PeerDiscovered BtAddress : F8:95:C7:87:3C:51, Name: LGE-LG-H815_PT5432, WifiDirectName: G4-1, WifiDirect Address: a2:39:f7:6f:c9:5d, peerId: F8:95:C7:87:3C:51
,I/jxcore-log( 3200): 2015-11-26T07:04:20.055Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:20.056Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/jxcore-log( 3200): 2015-11-26T07:04:25.060Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:25.061Z SendDataConnector.js: Connect (retry count 2) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:25.061Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:25.062Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,I/        ( 3200): Selected device address: 7C:F9:0E:51:18:22, name: Thali Test (Galaxy A5)
,I/BTConnectToThread( 3200): Starting to connect
,W/BluetoothAdapter( 3200): getBluetoothService() called with no BluetoothManagerCallback
,I/        ( 3200): Connecting to Thali Test (Galaxy A5), at 7C:F9:0E:51:18:22
,I/        ( 3200): Cleared service requests
,D/BTIF_SOCK( 3260): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,I/        ( 3200): Started peer discovery
,W/bt-btif ( 3260): info:x10
D/        ( 3260): remote version info [7c:f9:0e:51:18:22]: 7, 1d, 7d3,
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Thali Test (Galaxy A5)
,W/bt-sdp  ( 3260): process_service_search_attr_rsp
,W/bt-btif ( 3260): new conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 3260): bta_dm_pm_ssr:2, lat:1200
I/BTConnectToThread( 3200): Starting to Handshake
,I/BTHandshakeSocketThread( 3200): Creating BTHandshakeSocketThread
I/BTConnectToThread( 3200): MESSAGE_WRITE 82 bytes.
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread started
,I/BTConnectToThread( 3200): got MESSAGE_READ 83 bytes.
I/BTConnectToThread( 3200): Got JSON from encryption:{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT5029","ra":"7C:F9:0E:51:18:22"}��������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������������
,I/BTConnectToThread( 3200): HandshakeOk : samsung-SM-A500FU_PT5029
,I/HS      ( 3200): Hand Shake finished outgoing for : samsung-SM-A500FU_PT5029
I/BTHandshakeSocketThread( 3200): BTHandshakeSocketThread fully stopped
I/BtConnectorHelper( 3200): Starting the connected thread incoming : false, samsung-SM-A500FU_PT5029
I/BtToSocketBase( 3200): BtToSocketBase BtConnectedRequestSocket
I/BtToRequestSocket( 3200): Creating BtConnectedRequestSocket
,I/BtToRequestSocket( 3200): mHTTPPort  set to : 34749
,I/BtConnectorHelper( 3200): Request socket is using : 34749
I/BtToRequestSocket( 3200): Now accepting connections
,I/BtConnectorHelper( 3200): Calling ConnectionStatusUpdate with port :34749
,I/jxcore-log( 3200): 2015-11-26T07:04:25.588Z SendDataConnector.js: CLIENT connected to 34749, error: null
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:25.592Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 3200): 
,I/BtToRequestSocket( 3200): incoming data from: /127.0.0.1, port: 34749
,I/BtToRequestSocket( 3200): Set local streams,
I/BtToRequestSocket( 3200): rin ended ---------------------------;
I/jxcore-log( 3200): 2015-11-26T07:04:25.602Z SendDataConnector.js: CLIENT now sending 10000 bytes of data,
I/jxcore-log( 3200): 
,D/btif_config_util( 3260): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 3260): dm_pm_timer expires
,W/bt-btif ( 3260): dm_pm_timer expires 0
,W/bt-btif ( 3260): proc dm_pm_timer expires
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND f4:f1:e1:5c:43:c8 p2p_dev_addr=f4:f1:e1:5c:43:c8 pri_dev_type=10-0050F204-5 name='XT1039_8c05' config_methods=0x188 dev_capab=0x21 group_capab=0x0
,I/SS      ( 3200): Found 11 peers.
I/SS      ( 3200): Peer(1): S5-1 ee:1f:72:63:11:86
I/SS      ( 3200): Peer(2): Android_d8c3 02:ee:bd:dd:33:d2
,I/SS      ( 3200): Peer(3): Thali Test's G2 36:fc:ef:de:0a:e2
I/SS      ( 3200): Peer(4): G3s-1 a2:39:f7:70:12:80
I/SS      ( 3200): Peer(5): Android_2dc2 52:55:27:f0:ff:f0
I/SS      ( 3200): Peer(6): A3-1 0a:ec:a9:50:75:42
,I/SS      ( 3200): Peer(7): G4-1 a2:39:f7:6f:c9:5d
I/SS      ( 3200): Peer(8): XT1039_8c05 f4:f1:e1:5c:43:c8
I/SS      ( 3200): Peer(9): S5mini-1 02:f4:6f:30:e0:6d
I/SS      ( 3200): Peer(10): Thali Test (Galaxy S5) ee:1f:72:18:8b:78
I/SS      ( 3200): Peer(11): Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pManager( 3200): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/        ( 3200): Added service request
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/        ( 3200): Started service discovery
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND ee:1f:72:63:11:86 p2p_dev_addr=ee:1f:72:63:11:86 pri_dev_type=10-0050F204-5 name='S5-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1,
I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:70:12:80 p2p_dev_addr=a2:39:f7:70:12:80 pri_dev_type=10-0050F204-5 name='G3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,I/wpa_supplicant( 4994): P2P-DEVICE-FOUND a2:39:f7:6f:c9:5d p2p_dev_addr=a2:39:f7:6f:c9:5d pri_dev_type=10-0050F204-5 name='G4-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1
,F/libc    ( 4994): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xc in tid 4994 (wpa_supplicant)
I/libc    ( 4994): Suppressing debuggerd output because prctl(PR_GET_DUMPABLE)==0
,I/        ( 3200): Cleared service requests
,E/bt-btm  ( 3260): tBTM_SEC_DEV:0xa2f82ebc rs_disc_pending=0
,W/bt-btif ( 3260): bta_dm_check_av:0
W/bt-btif ( 3260): btif_dm_cback : unhandled event (14)
,I/jxcore-log( 3200): 2015-11-26T07:04:35.679Z SendDataConnector.js: Receiving data timeout now
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:35.680Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:35.681Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:35.681Z SendDataConnector.js: tryAgain afer: 5000 ms.,
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:35.683Z SendDataConnector.js: ----------------- closeClientSocket
I/jxcore-log( 3200): 
I/BtToSocketBase( 3200): SendingThread thread got error: input stream got -1 on read
,I/BtConnectorHelper( 3200): Disconnect outgoing peer: samsung-SM-A500FU_PT5029
I/BtToSocketBase( 3200): Stop ReceivingThread
I/BtToSocketBase( 3200): Stop SendingThread
I/BtToSocketBase( 3200): Close local in
I/BtToSocketBase( 3200): Close LocalOutputStream
I/BtToSocketBase( 3200): Close localHostSocket
,I/BtToSocketBase( 3200): Close bt in
I/BtToSocketBase( 3200): Dunno which thread got error: disconnected: java.io.IOException: bt socket closed, read return: -1
I/BtToSocketBase( 3200): Close bt out
I/BtToSocketBase( 3200): Close bt socket
I/BtToRequestSocket( 3200): Close server socket
,W/bt-btif ( 3260): bta_jv_rfc_port_to_cb(port_handle:0x16):jv handle:0x0 not FOUND,
,E/bt-btm  ( 3260): btm_sec_disconnected - Clearing Pending flag
,D/BluetoothMapService( 3260): onReceive
,I/BTConnectionReceiver( 1511): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:51:18:22, alias=null, name=Thali Test (Galaxy A5), majorDeviceClass=512, deviceClass=524],
,I/BluetoothClassifier( 1511): Bluetooth Device Name: Thali Test (Galaxy A5)
,I/jxcore-log( 3200): 2015-11-26T07:04:40.683Z SendDataConnector.js: re-try now : 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/jxcore-log( 3200): 2015-11-26T07:04:40.684Z SendDataConnector.js: ReStart called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 974891, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  820): Explicit concurrent mark sweep GC freed 52165(2MB) AllocSpace objects, 5(174KB) LOS objects, 31% free, 34MB/50MB, paused 2.391ms total 82.671ms
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1000731, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/WifiHW  (  820): 'P2P_FIND 120' command timed out.
,I/        ( 3200): Starting peer discovery failed, error code 0
,E/WifiStateMachine(  820): Connection lost, restart supplicant
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): failed to set BSSID: any
,E/native  (  820): do suspend true
,W/Settings( 1747): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,I/jxcore-log( 3200): DBG, CoordinatorConnector disconnect called
I/jxcore-log( 3200): 
V/NativeCrypto( 1483): Read error: ssl=0xaecfda00: I/O error during system call, Connection timed out
I/jxcore-log( 3200): The Coordinator has disconnected!
I/jxcore-log( 3200): 
,V/NativeCrypto( 1483): SSL shutdown failed: ssl=0xaecfda00: I/O error during system call, Broken pipe
,E/WifiStateMachine(  820): WifiStateMachine: Leaving Connected state
,E/WifiStateMachine(  820): Unexpected BatchedScanResults :null
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 104] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 104] got DISCONNECTED, was satisfying 2
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 104]) by 10011
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,D/WifiScanningService(  820): SCAN_AVAILABLE : 1
D/WifiScanningService(  820): StartedState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState
D/RttService(  820): SCAN_AVAILABLE : 1
,D/RttService(  820): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  820): NetworkAgent: NetworkAgent channel lost
I/        ( 3200): Discovery state changed to Stopped.
I/WB      ( 3200): Wifi is DISABLED !!
I/        ( 3200): Stoping All
I/        ( 3200): Stopping services
I/        ( 3200): Stopping services
I/        ( 3200): Stop Bluetooth
I/        ( 3200): Stop Bluetooth
I/BTListenerThread( 3200): Stopped
,I/        ( 3200): Starting peer discovery failed, error code 2
I/        ( 3200): Clearing local services failed, error code 2
I/        ( 3200): Clearing service requests failed, error code 2
I/        ( 3200): Stopping peer discovery failed, error code 2
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService(  820): notifyType LOST for NetworkAgentInfo [WIFI () - 104]
D/CSLegacyTypeTracker(  820): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 104] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524292
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): OfflineState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 104](  820): Disconnected - quitting
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  820): MasterInitialState.processMessage what=3
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  820): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 6
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     ( 1272): Explicit concurrent mark sweep GC freed 40801(2MB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 23MB/38MB, paused 634us total 25.695ms
,E/GpsLocationProvider(  820): No APN found to select.
,I/SystemUpdateService( 1782): active receiver: enabled
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,I/SystemUpdateService( 1782): showing system update notification
,E/GpsLocationProvider(  820): No APN found to select.
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1782): num queued entries: 0
,I/iu.UploadsManager( 1782): num updated entries: 0
,I/iu.SyncManager( 1782): NEXT; no task
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599974 ms
,D/SystemUpdateService( 1782): onDestroy
,I/Babel   ( 2640): connection state changed from CONNECTED to DISCONNECTED
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) },
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599981 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms,
,D/SystemUpdateService( 1782): onDestroy
,I/jxcore-log( 3200): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 3200): 
I/jxcore-log( 3200): Error type "connect_error" when connecting to the test server
I/jxcore-log( 3200): 
,D/WifiService(  820): setWifiEnabled: false pid=3200, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiService(  820): setWifiEnabled: true pid=3200, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,D/WifiController(  820): WifiController msg { when=0 what=155656 target=com.android.internal.util.StateMachine$SmHandler } deferred for 483ms
,I/jxcore-log( 3200): Wifi toggled for connection repairment
I/jxcore-log( 3200): 
,I/chromium( 3200): [INFO:CONSOLE(63)] "logCallback Error type "connect_error" when connecting to the test server", source: file:///android_asset/www/js/thali_main.js (63)
,D/WifiController(  820): DEFERRED_TOGGLE handled
,D/SoftapController(  354): Softap fwReload - Ok
,D/CommandListener(  354): Setting iface cfg
D/CommandListener(  354): Trying to bring down wlan0
,D/Tethering(  820): InitialState.processMessage what=4
D/CommandListener(  354): Clearing all IP addresses on wlan0
,D/Tethering(  820): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/wpa_supplicant( 5106): Successfully initialized wpa_supplicant
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 5106): rfkill: Cannot open RFKILL control device
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/wpa_supplicant( 5106): rfkill: Cannot open RFKILL control device
,E/wpa_supplicant( 5106): Could not read interface p2p-dev-wlan0 flags: No such device
,I/jxcore-log( 3200): 2015-11-26T07:04:45.686Z SendDataConnector.js: Mobile.Disconnect() callback with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:45.690Z SendDataConnector.js: Connect (retry count 3) to peer 7C:F9:0E:51:18:22 with availability status: true
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:45.691Z SendDataConnector.js: doConnect called with peer 7C:F9:0E:51:18:22
I/jxcore-log( 3200): 
I/jxcore-log( 3200): 2015-11-26T07:04:45.691Z SendDataConnector.js: do connect now
I/jxcore-log( 3200): 
,D/AndroidRuntime( 3200): Shutting down VM
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@28944b46}
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  820): Setting external_sim to 1
W/Settings( 2640): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xb4bbad18
D/WifiHAL (  820): Sending mac address OUI
,E/native  (  820): do suspend true,
,W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device),
D/CommandListener(  354): Setting iface cfg
D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  820): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): getting scan capabilities on interface[0] = 0xb4bbad18
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '168 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 168 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,D/WifiNative-HAL(  820): p2pGetDeviceAddress
,D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,I/wpa_supplicant( 5106): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,I/wpa_supplicant( 5106): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 5106): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 5106): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 5106): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 5106): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 105] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg,
E/WifiStateMachine(  820): Start Dhcp Watchdog 6
,E/WifiStateMachine(  820):  WifiLinkLayerStats: ,
E/WifiStateMachine(  820):  my bss beacon rx: 2
E/WifiStateMachine(  820):  RSSI mgmt: -44
E/WifiStateMachine(  820):  BE :  rx=0 tx=2 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  on_time : 0 tx_time=66 rx_time=201 scan_time=0
,E/native  (  820): do suspend false,
,E/WifiStateMachine(  820): scanCount==0 - aborting,
,I/dhcpcd  ( 5113): version 5.5.6 starting
,I/dhcpcd  ( 5113): wlan0: rebinding lease of 192.168.1.110
,I/dhcpcd  ( 5113): wlan0: acknowledged 192.168.1.110 from 192.168.1.1
,I/dhcpcd  ( 5113): wlan0: leased 192.168.1.110 for 86400 seconds,
,E/native  (  820): do suspend true
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 105] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 105
E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 105
,D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 105
,D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 105
,D/ConnectivityService(  820): Setting Dns servers for network 105 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 105]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 105]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 105]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 105](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 105](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 105](  820): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 105](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{105}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.110/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 105]
,D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 105] isDefaultNetwork=true
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,I/NetworkMonitor( 3445): type=WIFI subType= reason=null isConnected=true
,D/NetworkChangeNotifierAutoDetect( 1511): Network connectivity changed, type is: 2
,V/MusicLeanback( 3445): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1272): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
D/TelephonyManager(  820): getDataEnabled: retVal=false
,D/SprintDMReceiver( 4396): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,E/GpsLocationProvider(  820): No APN found to select.
,D/SprintDMHelper( 4396): simOperator:  IMSI: null
,D/SprintDMReceiver( 4396): Not Sprint UICC, don't do anything.
,I/SystemUpdateService( 1782): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/SystemUpdateService( 1782): onCreate
,D/SystemUpdateService( 1782): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1782): active receiver: enabled
,I/SystemUpdateService( 1782): showing system update notification
,I/iu.Environment( 1782): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1782): num queued entries: 0
,I/iu.UploadsManager( 1782): num updated entries: 0
,I/iu.SyncManager( 1782): NEXT; no task
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/ValidateNoPeople(  820): skipping global notification
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 105](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 26 Nov 2015 07:04:50 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1448521490590], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1448521490569]}
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 105](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 105]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 105]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 105] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 105]
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1059): CM callback handler got msg 524290
,V/SystemUpdateService( 1782): retry (wakeup: false) in 3599973 ms
,D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1782): onDestroy
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Herrevad( 1782): NQAS connected
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
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
,I/Babel   ( 2640): connection state changed from DISCONNECTED to CONNECTED
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@28944b46}
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
,E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,D/GCM     ( 1483): Connected
,D/GCM     ( 1483): Message class com.google.f.a.a.p,
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1003925, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  820): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 104] cleared because we found a replacement network
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/ClientConnectionOperation( 1782): Handling authorization failure,
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	,at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442),
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): ,	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
,E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
,E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	,at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): ,	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	,at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	,at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/art     (  820): Explicit concurrent mark sweep GC freed 67313(3MB) AllocSpace objects, 9(426KB) LOS objects, 31% free, 34MB/50MB, paused 3.053ms total 80.710ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1033400, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1043111, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 52177(2MB) AllocSpace objects, 8(882KB) LOS objects, 36% free, 27MB/43MB, paused 1.522ms total 80.797ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>],
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1067278, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/art     ( 4206): Explicit concurrent mark sweep GC freed 19331(2MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 23MB/31MB, paused 310us total 25.090ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1095496, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/GoogleAuthProtoRequest( 3277): [341] a.<init>: mAccountName set to: thalitester@gmail.com
,V/GoogleAuthProtoRequest( 3277): [342] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 3277): [341] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3277): [341] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,W/ExperimentUpdateService( 3277): [342] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3277): [342] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3277): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3277): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3277): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3277): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3277): 	at com.a.a.k.run(SourceFile:110)
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native,
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1123383, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1127283, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/art     (  820): Explicit concurrent mark sweep GC freed 39313(1748KB) AllocSpace objects, 9(332KB) LOS objects, 31% free, 34MB/50MB, paused 2.379ms total 96.775ms
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
,W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1187974, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,I/UsageStatsService(  820): User[0] Flushing usage stats to disk
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4168): Finished books sync,
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1213618, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 17 more
E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): 	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686)
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1281513, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 55632(3MB) AllocSpace objects, 15(1653KB) LOS objects, 36% free, 27MB/43MB, paused 1.174ms total 54.444ms
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1342967, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1364326, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,W/bt-btm  ( 3260): Stopping oneshot timer
,I/art     (  820): Explicit concurrent mark sweep GC freed 41445(1844KB) AllocSpace objects, 13(585KB) LOS objects, 31% free, 34MB/50MB, paused 1.364ms total 82.535ms
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/HttpOperation( 4133): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
,E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at blb.a(PG:3937)
E/HttpOperation( 4133): 	at czp.a(PG:18188)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77)
E/HttpOperation( 4133): 	... 12 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089)
E/HttpOperation( 4133): 	... 14 more
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4133): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4133): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4133): 	at jdm.a(PG:82)
E/HttpOperation( 4133): 	at jcs.o(PG:406)
E/HttpOperation( 4133): 	at jcn.a(PG:1379)
E/HttpOperation( 4133): 	at jcs.i(PG:143)
E/HttpOperation( 4133): 	at hec.a(PG:42)
E/HttpOperation( 4133): 	at hee.a(PG:102)
E/HttpOperation( 4133): 	at czr.a(PG:65)
E/HttpOperation( 4133): 	at kka.a(PG:108)
E/HttpOperation( 4133): 	at czp.a(PG:19176)
E/HttpOperation( 4133): 	at czp.a(PG:9081)
E/HttpOperation( 4133): 	at czq.run(PG:1686)
E/HttpOperation( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4133): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587),
E/HttpOperation( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4133): 	at jdj.a(PG:4091)
E/HttpOperation( 4133): 	at jdj.a(PG:1125)
E/HttpOperation( 4133): 	at jdm.a(PG:77),
E/HttpOperation( 4133): 	... 15 more
E/HttpOperation( 4133): Caused by: faj: BadAuthentication
E/HttpOperation( 4133): 	at fal.a(PG:38)
E/HttpOperation( 4133): 	at jdj.a(PG:4089),
E/HttpOperation( 4133): 	... 17 more
E/ExperimentLoader( 4133): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4133): 	,at jdm.a(PG:82)
E/ExperimentLoader( 4133): 	at jcs.o(PG:406)
E/ExperimentLoader( 4133): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4133): 	at jcs.i(PG:143)
E/ExperimentLoader( 4133): 	at hec.a(PG:42)
E/ExperimentLoader( 4133): 	at hee.a(PG:102)
E/ExperimentLoader( 4133): ,	at czr.a(PG:65)
E/ExperimentLoader( 4133): 	at kka.a(PG:108)
E/ExperimentLoader( 4133): 	at czp.a(PG:19176)
E/ExperimentLoader( 4133): 	at czp.a(PG:9081)
E/ExperimentLoader( 4133): 	at czq.run(PG:1686),
E/ExperimentLoader( 4133): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4133): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4133): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4133): 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4133): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4133): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4133): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4133): 	at jdj.a(PG:1125)
,E/ExperimentLoader( 4133): 	at jdm.a(PG:77)
E/ExperimentLoader( 4133): 	... 15 more
E/ExperimentLoader( 4133): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4133): 	at fal.a(PG:38)
,E/ExperimentLoader( 4133): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4133): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1560081, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,V/KeepSync( 4206): Connecting to GoogleApiClient
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1782): Handling authorization failure,
E/ClientConnectionOperation( 1782): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1782): 	,at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1782): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1782): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1782): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1782): 	,at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1782): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1782),: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1782): 	... 7 more
V/KeepSync( 4206): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4206): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4206): IOException
E/KeepSync( 4206): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4206): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4206): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4206): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4206): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4206): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4206): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4206): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4206): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4206): 	... 10 more
W/KeepSync( 4206): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1623121, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/BooksSync( 4168): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 4168): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4168): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4168): Soft error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4168): Sync error
E/BooksSync( 4168): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4168): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 4168): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1635482, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,I/ProcessStatsService(  820): Prepared write state in 17ms
,I/ProcessStatsService(  820): Pruning old procstats: /data/system/procstats/state-2015-11-25-09-28-25.bin
,I/EventLogService( 1782): Opted in for usage reporting
,I/EventLogService( 1782): Aggregate from 1448520631063 (log), 1448520291069 (data)
,W/EventLogAggregator( 1782): Unknown tag: snet_gcore
W/EventLogAggregator( 1782): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1782): dumping service [account]
,I/GLSUser ( 1483): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1483): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1483): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1483): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1483): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1483): Explicit concurrent mark sweep GC freed 61252(3MB) AllocSpace objects, 12(1323KB) LOS objects, 36% free, 27MB/43MB, paused 1.317ms total 44.146ms
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/GCM     ( 1483): Message class com.google.f.a.a.i
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3260): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5378): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 5378): CheckJNI is OFF
D/AndroidRuntime( 5378): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3200:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
W/PackageSettings(  820): Skipping PackageSetting{2f8d60a8 com.example.hello/10272} due to missing metadata
I/WindowState(  820): WIN DEATH: Window{11c476e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/WifiService(  820): Client connection lost with reason: 4
E/libprocessgroup(  820): failed to kill 1 processes for processgroup 3200
W/ActivityManager(  820): Force removing ActivityRecord{261c0668 u0 com.test.thalitest/.MainActivity t24}: app died, no saved state
V/ActivityManager(  820): Display changed displayId=0
I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
W/ActivityManager(  820): Spurious death for ProcessRecord{521319c 3200:com.test.thalitest/u0a265}, curProc for 3200: null
D/TaskPersister(  820): removeObsoleteFile: deleting file=24_task.xml
D/BuaReceiver( 3067): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1272): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Keyboard.Facilitator( 1208): resetDictionaries() : en_US
I/art     ( 1059): Explicit concurrent mark sweep GC freed 104471(4MB) AllocSpace objects, 0(0B) LOS objects, 17% free, 76MB/92MB, paused 1.041ms total 43.365ms
I/ActivityManager(  820): Start proc 5394:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
I/Keyboard.Facilitator.DecoderInitializer( 1208): run()
D/VoicemailCleanupService( 4107): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1208): createOrResetDecoder
I/art     (  820): Explicit concurrent mark sweep GC freed 44087(2MB) AllocSpace objects, 15(701KB) LOS objects, 31% free, 34MB/50MB, paused 2.038ms total 105.137ms
I/art     (  820): WaitForGcToComplete blocked for 91.784ms for cause Explicit
I/art     ( 1511): Explicit concurrent mark sweep GC freed 57123(2MB) AllocSpace objects, 12(212KB) LOS objects, 22% free, 27MB/35MB, paused 456us total 130.124ms
I/ConfigService( 1483): onCreate
I/ActivityManager(  820): Start proc 5417:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3200 uid 10265
I/Keyboard.Facilitator( 1208): onFinishInput()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1208): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
W/ContextImpl( 5417): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = history
D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Loading LM = user
W/LocationOracleImpl( 1511): Best location was null
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1208): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1208): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1208): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1208): run()
I/StatsUtilsManager( 1208): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1208): shouldRecordStats() = Too Soon
I/HotwordRecognitionRnr( 1511): Starting hotword detection.
I/MicrophoneInputStream( 1511): mic_starting com.google.android.apps.gsa.speech.audio.u@39607d63
E/NetworkScheduler.SchedulerReceiver( 1483): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1483): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/AudioFlinger(  358): AudioFlinger's thread 0xb40a3000 ready to run
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/art     ( 1300): Explicit concurrent mark sweep GC freed 12171(691KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 2.045ms total 37.176ms
D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
I/MicrophoneInputStream( 1511): mic_started com.google.android.apps.gsa.speech.audio.u@39607d63
D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
D/PackageBroadcastService( 1782): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1782): Module APK com.google.android.play.games already loaded
W/LocationOracleImpl( 1511): Best location was null
D/ChimeraCfgMgr( 1782): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1782): Module APK com.google.android.play.games already loaded
D/AccountUtils( 1782): Clearing selected account for com.test.thalitest
I/UpdateIcingCorporaServi( 1511): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/LocationOracleImpl( 1511): Best location was null
I/LocationSettingsChecker( 1782): Removing dialog suppression flag for package com.test.thalitest
W/Launcher( 1300): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2fc99417 new=com.google.android.velvet.VelvetApplication@2fc99417
D/GOOGLEHELP_CompatibleDatabase( 1782): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1782): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1782): 0 metrics were deleted when clearing package com.test.thalitest.
D/GOOGLEHELP_CompatibleDatabase( 1782): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1782): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1782): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1782): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1782): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1782): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/GOOGLEHELP_CompatibleDatabase( 1782): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1782): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1782): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1782): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  820): Start proc 5460:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
D/Launcher.Workspace( 1300): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1300): 11683562 - stripEmptyScreens()
I/HotwordWorker( 1511): onReady
I/ConfigFetchService( 1782): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1782): service connected
I/PeopleContactsSync( 1782): CP2 sync disabled
I/Icing   ( 1782): doRemovePackageData com.test.thalitest
I/UpdateIcingCorporaServi( 1511): UpdateCorporaTask done [took 83 ms] updated apps [took 83 ms] 
W/BaseAppContext( 1782): Using Auth Proxy for data requests.
W/BaseAppContext( 1782): Using Auth Proxy for data requests.
I/art     (  820): Explicit concurrent mark sweep GC freed 12155(573KB) AllocSpace objects, 1(110KB) LOS objects, 31% free, 34MB/50MB, paused 2.936ms total 265.921ms
I/art     ( 1747): Explicit concurrent mark sweep GC freed 18256(1011KB) AllocSpace objects, 8(128KB) LOS objects, 37% free, 26MB/42MB, paused 930us total 23.892ms
E/DataBuffer( 1747): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33214919)
D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@1ab916d9}
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=1.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-127
E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=21.25 rxSuccessRate=190.25 targetRoamBSSID=any RSSI=-127
I/art     ( 5378): System.exit called, status: 0
I/AndroidRuntime( 5378): VM exiting with result code 0.
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660839187
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
I/kickstart(  871): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
I/kickstart(  871): STATUS: Wrote to /sys/power/wake_lock
E/kickstart(  871): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  871): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
I/GAv4    ( 5460): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5460):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5460):   adb logcat -s GAv4
W/GAv4    ( 5460): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5460): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5460): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/AnalyticsTrackerProxyImpl( 5460): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/SQLiteDatabase( 5460): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5460): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5460): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5460): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5460): 	at gir$c.run(Unknown Source)
E/GAv4    ( 5460): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5460): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5460): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5460): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5460): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5460): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5460): 	at gir$c.run(Unknown Source)
E/GAv4    ( 5460): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5460): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5460): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5460): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5460): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5460): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5460): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5460): 	at aen.run(PG:536)
E/SQLiteDatabase( 5460): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5460): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5460): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5460): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5460): 	at aej.c(PG:139)
E/SQLiteDatabase( 5460): 	at aej.b(PG:398)
E/SQLiteDatabase( 5460): 	at agf.f(PG:417)
E/SQLiteDatabase( 5460): 	at oe.run(PG:1112)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5460): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 5460): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 5460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 5460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 5460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 5460): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 5460): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 5460): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 5460): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 5460): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 5460): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 5460): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 5460): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 5460): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 5460): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 5460): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 5460): 	at java.lang.Thread.run(Thread.java:818)
W/GAv4    ( 5460): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5460): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5460): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5460): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5460): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5460): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5460): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5460): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5460): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/CAKEMIX_CRASHED( 5460): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 5460): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 5460): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 5460): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 5460): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 5460): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 5460): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 5460): 	at aen.run(PG:536)
E/SharedPreferencesImpl( 5460): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/ResourcesManager( 5460): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5460): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  820): Start proc 5500:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{37f4c66f token=Token{1a68d54e ActivityRecord{d006849 u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t25}}} to stack=1 task=25 at 0
I/ActivityManager(  820): Killing 4307:com.android.settings/1000 (adj 15): empty #17
I/HotwordDetector( 1511): Closing mic
I/MicrophoneInputStream( 1511): mic_close com.google.android.apps.gsa.speech.audio.u@39607d63
I/Process ( 5460): Sending signal. PID: 5460 SIG: 9
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1511): Hotword detection finished
I/HotwordRecognitionRnr( 1511): Stopping hotword detection.
E/lowmemorykiller(  256): Error opening /proc/5460/oom_score_adj; errno=2
W/ActivityManager(  820): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  820): android.os.DeadObjectException
W/ActivityManager(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  820): 	at android.app.ApplicationThreadProxy.scheduleLaunchActivity(ApplicationThreadNative.java:797)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.realStartActivityLocked(ActivityStackSupervisor.java:1181)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1281)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:1891)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1455)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2473)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.completePauseLocked(ActivityStack.java:998)
W/ActivityManager(  820): 	at com.android.server.am.ActivityStack.activityPausedLocked(ActivityStack.java:896)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.activityPaused(ActivityManagerService.java:6311)
W/ActivityManager(  820): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:512)
W/ActivityManager(  820): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2208)
W/ActivityManager(  820): 	at android.os.Binder.execTransact(Binder.java:446)
I/ActivityManager(  820): Start proc 5518:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  820): Spurious death for ProcessRecord{24a03038 5518:com.google.android.apps.docs/u0a46}, curProc for 5460: null
W/OpenGLRenderer( 1300): Incorrectly called buildLayer on View: ew, destroying layer...
E/SQLiteDatabase( 5500): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 5500): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5500): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5500): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5500): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5500): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 5500): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 5500): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 5500): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 5500): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 5500): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 5500): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 5500): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 5500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5500): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5500): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 5500): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 5500): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 5500): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 5500): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/AndroidRuntime( 5500): Shutting down VM
I/ActivityManager(  820): Killing 3445:com.google.android.music:main/u0a66 (adj 15): empty #17
E/AndroidRuntime( 5500): FATAL EXCEPTION: main
E/AndroidRuntime( 5500): Process: com.android.documentsui, PID: 5500
E/AndroidRuntime( 5500): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5500): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 5500): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 5500): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 5500): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5500): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5500): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 5500): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 5500): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 5500): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 5500): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 5500): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5500): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 5500): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5500): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5500): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 5500): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 5500): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 5500): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 5500): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 5500): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 5500): 	... 9 more
E/native  ( 1208): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1208): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
I/ActivityManager(  820): Start proc 5541:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
I/Icing   ( 1782): Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
D/ExternalStorage( 5541): After updating volumes, found 1 active roots
E/Icing   ( 1782): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1782): Could not init tag ds.tag.deleted
E/Icing   ( 1782): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1782): Could not init tag ds.tag.deleted
E/native  ( 1208): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1208): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
I/OpenGLRenderer(  820): Initialized EGL, version 1.4
I/GAv4    ( 5518): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5518):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5518):   adb logcat -s GAv4
D/OpenGLRenderer(  820): Enabling debug mode 0
W/GAv4    ( 5518): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/native  ( 1208): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1208): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1208): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1208): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
I/ActivityManager(  820): Killing 4396:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
W/GAv4    ( 5518): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5518): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5518): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5518): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5518): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5518): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5518): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5518): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5518): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5518): 	at gir$c.run(Unknown Source)
E/GAv4    ( 5518): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 5518): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5518): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5518): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 5518): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 5518): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5518): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 5518): 	at gir$c.run(Unknown Source)
W/AnalyticsTrackerProxyImpl( 5518): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
E/GAv4    ( 5518): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5518): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 5518): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5518): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 5518): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5518): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5518): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5518): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5518): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5518): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5518): 	at aen.run(PG:536)
E/kickstart(  871): ERROR: function: rx_data:267 Timeout Occured, No response or command came from the target!
I/kickstart(  871): WARNING: function: sahara_start:892 Retrying memory read request
E/SQLiteDatabase( 5518): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 5518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 5518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5518): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 5518): 	at ael.a(PG:1521)
E/SQLiteDatabase( 5518): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 5518): 	at aej.c(PG:139)
E/SQLiteDatabase( 5518): 	at aej.b(PG:398)
E/SQLiteDatabase( 5518): 	at agf.f(PG:417)
E/SQLiteDatabase( 5518): 	at oe.run(PG:1112)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5518): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5518): 	at java.lang.Thread.run(Thread.java:818)
E/AbstractDatabaseInstance( 5518): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 5518): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 5518): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 5518): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 5518): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 5518): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 5518): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 5518): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 5518): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 5518): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 5518): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 5518): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 5518): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 5518): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 5518): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 5518): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 5518): 	at java.lang.Thread.run(Thread.java:818)
I/Icing   ( 1782): Indexing done 0A4562BF807829C124E952811A67787B55D6217E
W/ResourcesManager( 5518): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5518): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/ErrorNotificationActivity( 5518): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
V/JNIHelp ( 5518): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/OpenGLRenderer( 5518): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 5518): Validating map...
V/WindowManager(  820): Adding window Window{205d5a74 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 3 of 9 (after Window{2866641b u0 com.android.chrome/org.chromium.chrome.browser.document.DocumentActivity})
V/WindowManager(  820): Adding window Window{27f7f812 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 3 of 10 (before Window{205d5a74 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
I/ProviderInstaller( 5518): Installed default security provider GmsCore_OpenSSL
W/GAv4    ( 5518): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 5518): Job execution failed: android.database.sqlite.SQLiteException: Database open failed

```
