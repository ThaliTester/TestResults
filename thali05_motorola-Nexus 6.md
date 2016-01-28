#### Test 573480789efee08_thali05_motorola-Nexus 6 Logs


```
--------- beginning of main
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 2691): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 2691): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 2691): [1] 5.onFinished: Scheduling replication attempt 3.
D/AndroidRuntime( 3116): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
D/AndroidRuntime( 3116): CheckJNI is OFF
D/AndroidRuntime( 3116): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  820): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/WindowManager(  820): addAppToken: AppWindowToken{16f99775 token=Token{2485ceac ActivityRecord{3c46145f u0 com.test.thalitest/.MainActivity t28}}} to stack=1 task=28 at 0
D/AndroidRuntime( 3116): Shutting down VM
I/MicrophoneInputStream( 1509): mic_close com.google.android.apps.gsa.speech.audio.u@2025bc5
I/HotwordDetector( 1509): Closing mic
V/WindowManager(  820): Adding window Window{215195d6 u0 Starting com.test.thalitest} at 2 of 7 (after Window{675cb93 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
I/ActivityManager(  820): Start proc 3130:com.test.thalitest/u0a265 for activity com.test.thalitest/.MainActivity
D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
I/HotwordRecognitionRnr( 1509): Hotword detection finished
I/HotwordRecognitionRnr( 1509): Stopping hotword detection.
I/ActivityManager(  820): Killing 2782:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1660216595
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,I/kickstart(  870): STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,I/kickstart(  870): STATUS: Wrote to /sys/power/wake_lock
,I/WebViewFactory( 3130): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3130): Time to load native libraries: 3 ms (timestamps 3721-3724)
,I/LibraryLoader( 3130): Expected native library version number "",actual native library version number ""
E/kickstart(  870): ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
I/kickstart(  870): STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,V/WebViewChromiumFactoryProvider( 3130): Binding Chromium to main looper Looper (main, tid 1) {3bde02f4}
,I/LibraryLoader( 3130): Expected native library version number "",actual native library version number ""
I/chromium( 3130): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3130): Initializing chromium process, singleProcess=true
,W/art     ( 3130): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3130): ApplicationContext is null in ApplicationStatus
,W/chromium( 3130): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 3130): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 3130): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3130): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno  ( 3130): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/BluetoothManagerService(  820): Message: 20
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17d92086:true
,D/BluetoothAdapter( 3130): 364963806: getState() :  mService = null. Returning STATE_OFF
,I/art     (  820): Explicit concurrent mark sweep GC freed 21233(942KB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 1.743ms total 75.292ms
,W/art     ( 3130): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 3130): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3130): CordovaWebView is running on device made by: motorola
,W/art     ( 3130): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3130): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 3130): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,D/Atlas   ( 3130): Validating map...
,V/WindowManager(  820): Adding window Window{2c70b736 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{215195d6 u0 Starting com.test.thalitest})
,W/chromium( 3130): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 3130): Initialized EGL, version 1.4
,D/OpenGLRenderer( 3130): Enabling debug mode 0
,I/Keyboard.Facilitator( 1215): onFinishInput()
,I/ActivityManager(  820): Displayed com.test.thalitest/.MainActivity: +894ms
,W/BindingManager( 3130): Cannot call determinedVisibility() - never saw a connection for the pid: 3130
,D/JsMessageQueue( 3130): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3130): JniHelper::setJavaVM(0xb489d200), pthread_self() = -1576275456
,I/chromium( 3130): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/kickstart(  870): STATUS: Received file 'm9kefs2'
I/kickstart(  870): STATUS: 950272 bytes transferred in 0.986250 seconds
I/kickstart(  870): STATUS: Successfully downloaded files from target 
I/kickstart(  870): STATUS: Wrote to /sys/power/wake_unlock
,I/kickstart(  870): STATUS: Sahara protocol completed
,I/art     ( 3130): Background sticky concurrent mark sweep GC freed 64314(6MB) AllocSpace objects, 14(2MB) LOS objects, 18% free, 29MB/36MB, paused 1.448ms total 107.370ms
,W/jxcore-log( 3130): Initializing JXcore engine
W/jxcore-log( 3130): JXcore engine is ready
,W/Thread-322( 3186): type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10654]" dev="sockfs" ino=10654 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-322( 3186): type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-322( 3186): type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10796]" dev="sockfs" ino=10796 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-322( 3186): type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[19247]" dev="sockfs" ino=19247 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 3130): Starting JXcore engine
,W/jxcore-log( 3130): Platform android
W/jxcore-log( 3130): 
W/jxcore-log( 3130): Process ARCH arm
W/jxcore-log( 3130): 
,I/jxcore-log( 3130): JXcore Cordova bridge is ready!
I/jxcore-log( 3130): 
W/jxcore-log( 3130): JXcore engine is started
,I/jxcore-log( 3130): Toggling radios to true
,I/jxcore-log( 3130): 
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothManagerService(  820): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  820): Message: 1
D/BluetoothManagerService(  820): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  820): New client listening to asynchronous messages
,D/WifiService(  820): setWifiEnabled: true pid=3130, uid=10265,
E/WifiService(  820): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 3130): Radios toggled
I/jxcore-log( 3130): 
D/SoftapController(  354): Softap fwReload - Ok
,I/jxcore-log( 3130): My device name is: motorola-Nexus 6
I/jxcore-log( 3130): 
,D/CommandListener(  354): Setting iface cfg
,D/CommandListener(  354): Trying to bring down wlan0
,D/CommandListener(  354): Clearing all IP addresses on wlan0
,E/WifiMonitor(  820): killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,I/ActivityManager(  820): Start proc 3190:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,W/ResourcesManager( 3190): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/wpa_supplicant( 3207): Successfully initialized wpa_supplicant
,D/WifiMonitor(  820): startMonitoring(wlan0) with mConnected = false
,I/wpa_supplicant( 3207): rfkill: Cannot open RFKILL control device
,I/ActivityManager(  820): Start proc 3208:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,D/AdapterServiceConfig( 3190): Adding HeadsetService
D/AdapterServiceConfig( 3190): Adding A2dpService
D/AdapterServiceConfig( 3190): Adding HidService
D/AdapterServiceConfig( 3190): Adding HealthService
,D/AdapterServiceConfig( 3190): Adding PanService
D/AdapterServiceConfig( 3190): Adding GattService
,D/AdapterServiceConfig( 3190): Adding BluetoothMapService
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothAdapterState( 3190): make
D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@173fe54b:true
,I/bluedroid( 3190): init
I/BluetoothAdapterState( 3190): Entering OffState
,I/bte_conf( 3190): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3190): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 3190): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3190): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,I/bluedroid( 3190): get_profile_interface socket
I/GKI_LINUX( 3190): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 3190): get_profile_interface map_client
,D/BluetoothAdapterProperties( 3190): Address is:F8:CF:C5:D9:E5:61
D/BluetoothAdapterProperties( 3190): Name is: Nexus 6
D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  820): Message: 40
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bluedroid( 3190): config_hci_snoop_log
D/BluetoothManagerService(  820): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  820): Broadcasting onBluetoothServiceUp() to 7 receivers.
D/BluetoothAdapterState( 3190): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 3190): Setting state to 11
I/BluetoothAdapterState( 3190): Bluetooth adapter state changed: 10-> 11
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 10 -> 11
D/BluetoothBondStateMachine( 3190): make
I/BluetoothBondStateMachine( 3190): StableState(): Entering Off State
I/BluetoothAdapterState( 3190): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
D/HeadsetService( 3190): Received start request. Starting profile...
I/BluetoothHeadsetServiceJni( 3190): classInitNative: succeeds
D/HeadsetStateMachine( 3190): make
D/HeadsetStateMachine( 3190): max_hf_connections = 1
I/bluedroid( 3190): get_profile_interface handsfree
D/HeadsetStateMachine( 3190): Enter Disconnected: -2, size: 0
D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
D/BluetoothA2dp(  820): Proxy object connected
D/BluetoothA2dp( 1068): Proxy object connected
D/A2dpService( 3190): Received start request. Starting profile...
I/BluetoothAvrcpServiceJni( 3190): classInitNative: succeeds
I/bluedroid( 3190): get_profile_interface avrcp
,E/RemoteController( 3190): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 3190): classInitNative: succeeds
D/A2dpStateMachine( 3190): make
,I/bluedroid( 3190): get_profile_interface a2dp
I/GKI_LINUX( 3190): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/A2dpStateMachine( 3190): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 3190): classInitNative: succeeds
D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
,D/BluetoothInputDevice( 1068): Proxy object connected
,D/HidService( 3190): Received start request. Starting profile...
I/bluedroid( 3190): get_profile_interface hidhost
I/BluetoothHealthServiceJni( 3190): classInitNative: succeeds
D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
D/HealthService( 3190): Received start request. Starting profile...
I/bluedroid( 3190): get_profile_interface health
I/BluetoothPanServiceJni( 3190): classInitNative(L105): succeeds
D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
,D/BluetoothPan( 1068): BluetoothPAN Proxy object connected
,D/PanService( 3190): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3190): initializeNative(L110): pan
,I/bluedroid( 3190): get_profile_interface pan
I/BtGatt.JNI( 3190): classInitNative(L873): classInitNative: Success!
,D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
D/BtGatt.DebugUtils( 3190): handleDebugAction() action=null
D/BtGatt.GattService( 3190): Received start request. Starting profile...
D/BtGatt.GattService( 3190): start()
I/bluedroid( 3190): get_profile_interface gatt
D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
D/BtGatt.AdvertiseManager( 3190): advertise manager created
,D/BluetoothAdapterService( 3190): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1f25ca1d
D/BluetoothMap( 1068): Proxy object connected
,D/BluetoothMapService( 3190): Received start request. Starting profile...
D/BluetoothMapService( 3190): start()
,D/BluetoothMapEmailSettingsLoader( 3190): Found 0 applications
,D/BluetoothMapEmailAppObserver( 3190): createReceiver()
D/BluetoothMapEmailAppObserver( 3190): initObservers()
D/BluetoothMapEmailAppObserver( 3190): getEnabledAccountItems()
,D/HeadsetStateMachine( 3190): Proxy object connected,
D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 3190): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5,
D/HeadsetStateMachine( 3190): Disconnected process message: 11, size: 0
,D/BluetoothAdapterState( 3190): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3190): enable
I/bt_hci_bdroid( 3190): init
I/GKI_LINUX( 3190): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 3190): btu_task pending for preload complete event
,I/bt_vendor( 3190): init
I/bt_vnd_conf( 3190): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 3190): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3190): userial_init
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 25086(1344KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 25MB/41MB, paused 761us total 30.841ms
,I/ActivityManager(  820): Start proc 3253:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,I/ActivityManager(  820): Killing 2650:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,I/bt_userial_vendor( 3190): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 3190): device fd = 53 open
D/bt_userial( 3190): Entering userial_read_thread()
,I/bt_hwcfg( 3190): bt vendor lib: set UART baud 3000000
,D/bt_hwcfg( 3190): Chipset BCM4354A2
D/bt_hwcfg( 3190): Target name = [BCM4354A2]
I/bt_hwcfg( 3190): Found patchfile: /vendor/firmware//bcm4354A2.hcd
,D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
,W/ProcessCpuTracker(  820): Skipping unknown process pid 3273
,I/ActivityManager(  820): Start proc 3277:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,I/ActivityManager(  820): Killing 2816:com.google.android.apps.messaging/u0a75 (adj 15): empty #17
,D/Tethering(  820): sendTetherStateChangedBroadcast 1, 0, 0
,I/ActivityManager(  820): Killing 2749:com.google.android.gm/u0a78 (adj 15): empty #17
,I/wpa_supplicant( 3207): rfkill: Cannot open RFKILL control device
E/wpa_supplicant( 3207): Could not read interface p2p-dev-wlan0 flags: No such device
,I/bt_hwcfg( 3190): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 3190): Settlement delay -- 100 ms
I/bt_hwcfg( 3190): Setting fw settlement delay to 100 
,I/bt_hwcfg( 3190): bt vendor lib: set UART baud 3000000
I/bt_hwcfg( 3190): Setting local bd addr to F8:CF:C5:D9:E5:61
,I/bt_hwcfg( 3190): vendor lib fwcfg completed
I/bt-btu  ( 3190): btu_task received preload complete event
,I/        ( 3190): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 3190): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3190): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3190): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3190): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3190): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3190): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3190): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3190): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3190): BTE_InitTraceLevels -- TRC_PAN
,I/        ( 3190): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3190): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3190): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3190): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3190): BTE_InitTraceLevels -- TRC_BTIF
,D/WifiConfigStore(  820): Loading config and enabling all networks 
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@cdbcea3}
,E/WifiConfigStore(  820): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-HAL(  820): Setting external_sim to 1
D/WifiStateMachine(  820): Setting OUI to 92-68-C3
I/WifiNative-HAL(  820): startHal
D/wifi    (  820): setting scan oui 0xae884970
D/WifiHAL (  820): Sending mac address OUI
,W/Settings( 2619): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/WifiStateMachine(  820): cancelDelayedScan -> 1
,D/WifiScanningService(  820): SCAN_AVAILABLE : 3
D/RttService(  820): SCAN_AVAILABLE : 3
D/WifiScanningService(  820): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL(  820): startHal
D/RttService(  820): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  820): getting scan capabilities on interface[0] = 0xae884970
D/WifiHAL (  820): Creating message to get scan capablities; iface = 5
D/WifiHAL (  820): In GetCapabilities::handleResponse
W/CommandListener(  354): Failed to retrieve HW addr for p2p0 (No such device)
D/WifiHAL (  820): Id = 0, subcmd = 0, len = 28, expected len = 32
D/WifiScanningService(  820): StartedState
D/CommandListener(  354): Setting iface cfg
,E/WifiP2pService(  820): Unable to change interface settings: java.lang.IllegalStateException: command '28 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 28 Failed to set address (No such device)'
D/WifiMonitor(  820): startMonitoring(p2p0) with mConnected = true
,I/ActivityManager(  820): Killing 2344:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/wpa_supplicant( 3207): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,D/WifiNative-HAL(  820): p2pGetDeviceAddress
,D/WifiNative-HAL(  820): p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,E/bt-btm  ( 3190): BTM_SecRegister:p_cb_info->p_le_callback == 0xaf003085 
E/bt-btm  ( 3190): BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf003085 
,E/native  (  820): do suspend false
,I/ActivityManager(  820): Start proc 3296:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,D/BluetoothAdapterProperties( 3190): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3190): Calling BTA_HhEnable
,E/bt-btif ( 3190): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 3190): Address is:F8:CF:C5:D9:E5:61
,D/BluetoothAdapterProperties( 3190): Name is: Nexus 6
D/BluetoothManagerService(  820): Bluetooth Adapter name changed to Nexus 6
D/BluetoothManagerService(  820): Stored Bluetooth name: Nexus 6
W/bt-btm  ( 3190): Stopping oneshot timer
,D/BluetoothAdapterProperties( 3190): Scan Mode:20
,D/BluetoothAdapterProperties( 3190): Discoverable Timeout:120
,D/bte_conf( 3190): Device ID record 1 : primary
,D/bte_conf( 3190):   vendorId            = 000f
,D/bte_conf( 3190):   vendorIdSource      = 0001,
,D/bte_conf( 3190):   product             = 1200
D/bte_conf( 3190):   version             = 1436
D/bte_conf( 3190):   clientExecutableURL = 
,D/bte_conf( 3190):   serviceDescription  = 
,D/bte_conf( 3190):   documentationURL    = 
D/bte_conf( 3190): bte_load_did_conf no section named DID2.
,D/BluetoothAdapterState( 3190): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,D/BluetoothAdapterProperties( 3190): ScanMode =  20
D/BluetoothAdapterProperties( 3190): State =  11
D/BluetoothAdapterProperties( 3190): Setting state to 12
I/BluetoothAdapterState( 3190): Bluetooth adapter state changed: 11-> 12,
D/BluetoothManagerService(  820): Message: 60
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  820): Broadcasting onBluetoothStateChange(true) to 13 receivers.
D/BluetoothPanServiceJni( 3190): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
I/BluetoothAdapterState( 3190): Entering On State
,D/BluetoothHeadset( 1068): onBluetoothStateChange: up=true
D/BluetoothManagerService(  820): Creating new ProfileServiceConnections object for profile: 1,
D/BluetoothPan( 1068): onBluetoothStateChange(on) call bindService
D/BluetoothAdapterProperties( 3190): Scan Mode:21
D/BluetoothAdapterProperties( 3190): Discoverable Timeout:120
,D/BluetoothInputDevice( 1068): onBluetoothStateChange: up=true
D/BluetoothAvrcpController( 1068): onBluetoothStateChange: up=true
E/BluetoothAvrcpController( 1068): Could not bind to Bluetooth AVRCP Controller Service with Intent { act=android.bluetooth.IBluetoothAvrcpController }
,D/BluetoothMap( 1068): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothA2dp( 1068): onBluetoothStateChange: up=true
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothA2dpSink( 1068): onBluetoothStateChange: up=true
E/BluetoothA2dpSink( 1068): Could not bind to Bluetooth A2DP Service with Intent { act=android.bluetooth.IBluetoothA2dpSink }
D/BluetoothHeadset(  820): onBluetoothStateChange: up=true
D/BluetoothHeadsetClient( 1068): onBluetoothStateChange: up=true
E/BluetoothHeadsetClient( 1068): Could not bind to Bluetooth Headset Client Service with Intent { act=android.bluetooth.IBluetoothHeadsetClient }
,D/BluetoothA2dp(  820): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1260): onBluetoothStateChange: up=true
D/BluetoothManagerService(  820): Bluetooth State Change Intent: 11 -> 12
D/BluetoothMapService( 3190): onReceive
D/BluetoothMapService( 3190): STATE_ON
D/BluetoothManagerService(  820): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  820): Message: 40
D/BluetoothManagerService(  820): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapMasInstance( 3190): Map Service startRfcommSocketListener
D/BluetoothMapMasInstance( 3190): MAS initSocket()
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
W/BluetoothAdapter( 3190): getBluetoothService() called with no BluetoothManagerCallback
E/bt_h4   ( 3190): vendor lib postload completed
,D/BluetoothMapMasInstance( 3190): Accepting socket connection...
,D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 1068): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset(  820): Proxy object connected
D/BluetoothManagerService(  820): Message: 400
,D/BluetoothHeadset( 1260): Proxy object connected
,D/StrictMode( 3296): StrictMode policy violation; ~duration=243 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3296): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3296): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3296): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3296): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3296): 	at android.content.ContextWrapper.getFilesDir(ContextWrapper.java:202)
D/StrictMode( 3296): 	at com.google.android.libraries.stitch.incompat.missinglibs.a.a(PG:31)
D/StrictMode( 3296): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=242 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 3296): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3296): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3296): 	at com.google.android.libraries.stitch.incompat.b.a(PG:116)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:510)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3296): StrictMode policy violation; ~duration=240 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
,D/StrictMode( 3296): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3296): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
,D/StrictMode( 3296): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3296): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3296): ,	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3296): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:182)
D/StrictMode( 3296): ,	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:81)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:524)
,D/StrictMode( 3296): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151),
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102),
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
,D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
,D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3296): StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at android.app.SharedPreferencesImpl.awaitLoadedLocked(SharedPreferencesImpl.java:202),
D/StrictMode( 3296): 	at android.app.SharedPreferencesImpl.getBoolean(SharedPreferencesImpl.java:259)
D/StrictMode( 3296): 	at android.preference.PreferenceManager.setDefaultValues(PreferenceManager.java:481)
,D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.b.a.a(PG:938)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364),
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
,D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): ,	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698),
D/StrictMode( 3296): StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3296): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 3296): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 3296): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 3296): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 3296): 	at java.lang.System.loadLibrary(System.java:988)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:42)
,D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.<clinit>(PG:80)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	,at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=287 violation=2
D/StrictMode( 3296): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteConnection.applyBlockGuardPolicy(SQLiteConnection.java:1041)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:842)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
D/StrictMode( 3296): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
D/StrictMode( 3296): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
D/StrictMode( 3296): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
,D/StrictMode( 3296): 	at android.os.Binder.execTransact(Binder.java:446)
D/StrictMode( 3296): # via Binder call with stack:
D/StrictMode( 3296): android.os.StrictMode$LogStackTrace
D/StrictMode( 3296): 	at android.os.StrictMode.readAndHandleBinderCallViolations(StrictMode.java:1717)
D/StrictMode( 3296): 	at android.os.Parcel.readExceptionCode(Parcel.java:1527)
D/StrictMode( 3296): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:134)
D/StrictMode( 3296): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:421)
D/StrictMode( 3296): 	at android.content.ContentResolver.query(ContentResolver.java:478)
D/StrictMode( 3296): 	at android.content.ContentResolver.query(ContentResolver.java:422)
,D/StrictMode( 3296): 	at com.google.android.c.c.a(PG:87)
D/StrictMode( 3296): 	at com.google.android.c.c.a(PG:107)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.s.a(PG:325)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.s.a(PG:175)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.o.a(PG:134)
D/StrictMode( 3296): 	at com.google.b.a.by.a(PG:125)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540),
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	,at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
,D/StrictMode( 3296): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 3296): 	at java.io.File.exists(File.java:363)
D/StrictMode( 3296): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:995)
D/StrictMode( 3296): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1018)
D/StrictMode( 3296): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:960)
D/StrictMode( 3296): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): ,	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	,at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 3296): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 3296): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3296): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3296): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): 	,at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
D/StrictMode( 3296): StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 3296): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 3296): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 3296): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:961)
D/StrictMode( 3296): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:176)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.c.h.a(PG:149)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,D/StrictMode( 3296): StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 3296): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 3296): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 3296): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 3296): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 3296): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 3296): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 3296): 	at com.google.p.j.c(PG:1152)
D/StrictMode( 3296): 	at com.google.p.j.a(PG:121)
D/StrictMode( 3296): 	at com.google.t.b.a.dr.<init>(PG:24)
D/StrictMode( 3296): 	at com.google.t.b.a.ds.a(PG:61)
D/StrictMode( 3296): 	at com.google.p.e.a(PG:170)
D/StrictMode( 3296): 	at com.google.p.e.b(PG:21)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.c.h.a(PG:150)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.shared.net.a.b.a(PG:587)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.map.n.f.a(PG:323)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.d.<init>(PG:540)
D/StrictMode( 3296): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:84)
D/StrictMode( 3296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1012)
D/StrictMode( 3296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4553)
D/StrictMode( 3296): 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
D/StrictMode( 3296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1364)
D/StrictMode( 3296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 3296): 	at android.os.Looper.loop(Looper.java:135)
D/StrictMode( 3296): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 3296): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
D/StrictMode( 3296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,W/com.google.a.a.a.b.a( 3296): Application name is not set. Call Builder#setApplicationName.
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1be5e1ce:true
,I/ActivityManager(  820): Killing 2113:com.android.defcontainer/u0a7 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1477): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/ContextImpl( 3277): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  820): Message: 20
,D/BluetoothManagerService(  820): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c069601:true
,D/LocalBluetoothProfileManager( 3277): Adding local A2DP profile
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3277): Adding local HEADSET profile
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,W/BluetoothAdapter( 3190): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  820): Message: 30
,D/AuthorizationBluetoothService( 1477): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3277): Adding local MAP profile
D/BluetoothMap( 3277): Create BluetoothMap proxy object
,D/BluetoothManagerService(  820): Message: 30
,D/BluetoothManagerService(  820): Message: 30
,D/LocalBluetoothProfileManager( 3277): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 3277): finishStartingService: stopping service
,D/BluetoothManagerService(  820): checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,D/BluetoothA2dp( 3277): Proxy object connected
W/BluetoothAdapter( 3190): getBluetoothService() called with no BluetoothManagerCallback
,I/BtOppRfcommListener( 3190): Accept thread started.
D/A2dpProfile( 3277): Bluetooth service connected
,D/BluetoothInputDevice( 3277): Proxy object connected
,D/HidProfile( 3277): Bluetooth service connected
,D/BluetoothPan( 3277): BluetoothPAN Proxy object connected
,D/PanProfile( 3277): Bluetooth service connected
D/BluetoothMap( 3277): Proxy object connected
,D/MapProfile( 3277): Bluetooth service connected
D/BluetoothMap( 3277): getConnectedDevices()
,D/BluetoothPbap( 3277): Proxy object connected
D/PbapServerProfile( 3277): Bluetooth service connected
,D/BluetoothManagerService(  820): Message: 400
D/BluetoothHeadset( 3277): Proxy object connected
,D/HeadsetProfile( 3277): Bluetooth service connected
,I/wpa_supplicant( 3207): p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,E/WifiStateMachine(  820): WifiStateMachine shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
E/WifiConfigStore(  820):  rewrite network history for "NG700"WPA_PSK
E/WifiConfigStore(  820):  rewrite network history for "NG7005g"WPA_PSK
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiConfigStore(  820): writeKnownNetworkHistory write linked 1
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT will save config -> "NG7005g" nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,E/WifiStateMachine(  820): CMD_AUTO_CONNECT did save config ->  nid=0
,E/WifiConfigStore(  820): will read network variables netId=0
,I/wpa_supplicant( 3207): wlan0: Trying to associate with SSID 'NG7005g'
,I/wpa_supplicant( 3207): wlan0: Associated with c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 3207): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3207): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:4a completed [id=0 id_str=]
,D/ConnectivityService(  820): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,E/WifiConfigStore(  820): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,D/CommandListener(  354): Setting iface cfg
,E/WifiStateMachine(  820): Start Dhcp Watchdog 1
,E/WifiStateMachine(  820):  WifiLinkLayerStats: 
E/WifiStateMachine(  820):  my bss beacon rx: 1
E/WifiStateMachine(  820):  RSSI mgmt: -49
E/WifiStateMachine(  820):  BE :  rx=0 tx=3 lost=0 retries=0
E/WifiStateMachine(  820):  BK :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VI :  rx=0 tx=0 lost=0 retries=0
E/WifiStateMachine(  820):  VO :  rx=2 tx=0 lost=0 retries=0
,E/WifiStateMachine(  820):  on_time : 0 tx_time=57 rx_time=173 scan_time=0
,D/ConnectivityService(  820): updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,E/native  (  820): do suspend false
,E/WifiStateMachine(  820): scanCount==0 - aborting
,I/dhcpcd  ( 3337): version 5.5.6 starting
,I/dhcpcd  ( 3337): wlan0: rebinding lease of 192.168.1.122
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js,
I/jxcore-log( 3130): 
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 3130): 
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 3130): 
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js,
I/jxcore-log( 3130): 
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 3130): 
,I/dhcpcd  ( 3337): wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 3130): 
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 3130): 
,I/jxcore-log( 3130): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 3130): 
,I/dhcpcd  ( 3337): wlan0: leased 192.168.1.122 for 86400 seconds
,D/ConnectivityService(  820): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/ConnectivityService(  820): Adding iface wlan0 to network 100
,E/WifiStateMachine(  820): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  820): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  820): Adding Route [fe80::/64 -> :: wlan0] to network 100
D/ConnectivityService(  820): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
D/ConnectivityService(  820): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
D/ConnectivityService(  820): Setting Dns servers for network 100 to [/192.168.1.1]
,D/ConnectivityService(  820): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820):    accepting network in place of null
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Connected
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/ConnectivityService(  820): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
D/ConnectivityService(  820): Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/CSLegacyTypeTracker(  820): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1068): CM callback handler got msg 524290
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/Tethering(  820): MasterInitialState.processMessage what=3
,V/BackupManagerService(  820): Scheduling immediate backup pass
V/BackupManagerService(  820): Running a backup pass
V/BackupManagerService(  820): clearing pending backups
,I/NetworkMonitor( 2852): type=WIFI subType= reason=null isConnected=true
,D/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
,E/PhoneInterfaceManager( 1260): [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
,V/MusicLeanback( 2852): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/TelephonyManager(  820): getDataEnabled: retVal=false
,V/PerformBackupTask(  820): Beginning backup of 14 targets
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,E/GpsLocationProvider(  820): No APN found to select.
,V/BackupServiceBinder(  820): doBackup() invoked
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,D/AlarmManagerService(  820): Setting time of day to sec=1453981612
W/AlarmManagerService(  820): Unable to set rtc to 1453981612: Invalid argument
,I/BackupRestoreController(  820): Getting widget state for user: 0
,I/ActivityManager(  820): Start proc 3378:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 11:46:52 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453981612760], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453981612744]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): rematching NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  820): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  820): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 400us total 35.717ms
,D/ConnectivityManager.CallbackHandler( 1068): CM callback handler got msg 524290
,D/ConnectivityService(  820): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 392us total 14.198ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 742us total 15.228ms
,D/GpsLocationProvider(  820): NTP server returned: 1453981612732 (Thu Jan 28 12:46:52 GMT+01:00 2016) reference: 132800 certainty: 9 system time offset: -129
,I/art     (  820): Explicit concurrent mark sweep GC freed 48485(2MB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.388ms total 79.848ms
,I/GoogleURLConnFactory( 1477): Using platform SSLCertificateSocketFactory
,I/ConfigFetchService( 1750): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1750): running network task: configservice_periodic
,I/ConfigService( 1477): onCreate
,E/WakeLock( 1750): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1750): launchTask
,D/SprintDMReceiver( 3378): Received intent: android.net.conn.CONNECTIVITY_CHANGE
,D/SprintDMHelper( 3378): simOperator:  IMSI: null
D/SprintDMReceiver( 3378): Not Sprint UICC, don't do anything.
,W/GmsBackupTransport( 1708): Unknown package in backup request: @pm@
V/GmsBackupTransport( 1708): starting performBackup for @pm@
,E/Auth.Api.Credentials( 1750): [CredentialSyncAdapter] Unknown sync event.
,V/GmsBackupTransport( 1708): performBackup done for @pm@
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 14969(815KB) AllocSpace objects, 2(32KB) LOS objects, 38% free, 25MB/41MB, paused 975us total 23.637ms
,W/GLSActivity( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1477): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1477): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ConfigFetchService( 1750): service connected
,W/GmsBackupTransport( 1708): Error sending final backup to server: 
W/GmsBackupTransport( 1708): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1708): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1708): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1708): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1708): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1708): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1708): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1708): 	... 1 more
W/DriveInitializer( 1750): Background init thread started
D/BackupManagerService(  820): Now staging backup of com.google.android.talk
,I/SystemUpdateService( 1750): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,D/ConfigFetchService( 1750): ConfigApi connection successful.
D/SystemUpdateService( 1750): onCreate
,D/SystemUpdateService( 1750): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/BackupManagerService(  820): Now staging backup of com.google.android.dialer
,D/BackupManagerService(  820): Now staging backup of com.android.providers.settings
,D/BackupManagerService(  820): Now staging backup of com.android.sharedstoragebackup
,I/SystemUpdateService( 1750): active receiver: enabled
,D/BackupManagerService(  820): Now staging backup of com.google.android.gm
,D/BackupManagerService(  820): Now staging backup of com.android.providers.userdictionary
,I/iu.SyncManager( 1750): SYNC; picasa accounts
,W/DriveInitializer( 1750): Background init thread ended
,D/NetworkLogImpl( 1750): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1750): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/BackupManagerService(  820): Now staging backup of com.android.nfc
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/iu.UploadsManager( 1750): num queued entries: 0
,I/iu.UploadsManager( 1750): num updated entries: 0
I/iu.SyncManager( 1750): NEXT; no task
,I/CheckinService( 1750): Checking schedule, now: 1453981613199 next: 1453944162248
I/CheckinService( 1750): active receiver: enabled
D/BackupManagerService(  820): Now staging backup of com.google.android.apps.genie.geniewidget
,D/BackupManagerService(  820): Now staging backup of com.google.android.marvin.talkback
,D/BackupManagerService(  820): Now staging backup of com.google.android.inputmethod.latin
,D/BackupManagerService(  820): Now staging backup of com.google.android.calendar
,D/BackupManagerService(  820): Now staging backup of com.android.vending
,D/BackupManagerService(  820): Now staging backup of android
,I/SystemUpdateService( 1750): showing system update notification
,I/CheckinService( 1750): Preparing to send checkin request
I/EventLogService( 1750): Accumulating logs since 1453979880209
,D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
I/GcmGroups( 1750): Failed to subscribe to group.
I/GcmGroups( 1750): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1750): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1750): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1750): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1750): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1750): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1750): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1750): 	at android.os.Looper.loop(Looper.java:135)
I/GcmGroups( 1750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/GcmGroups( 1750): Groups upload failed, retrying in 24000:00:00
,I/GmsBackupTransport( 1708): Next backup will happen in 43199853 millis.
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BackupManagerService(  820): Backup pass finished.
,I/EventLogService( 1750): Opted in for usage reporting
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1750): retry (wakeup: false) in 3599879 ms
,I/ActivityManager(  820): Start proc 3443:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,D/SystemUpdateService( 1750): onDestroy
,E/HttpOperation( 3026): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3026): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3026): 	at jdm.a(PG:82)
E/HttpOperation( 3026): 	at jcs.o(PG:406)
E/HttpOperation( 3026): 	at jcn.a(PG:1379)
E/HttpOperation( 3026): 	at jcs.i(PG:143)
E/HttpOperation( 3026): 	at blb.a(PG:3937)
E/HttpOperation( 3026): 	at czp.a(PG:18188)
E/HttpOperation( 3026): 	at czp.a(PG:9081)
E/HttpOperation( 3026): 	at czq.run(PG:1686)
E/HttpOperation( 3026): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3026): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3026): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3026): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3026): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3026): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3026): 	at jdj.a(PG:4091)
E/HttpOperation( 3026): 	at jdj.a(PG:1125)
E/HttpOperation( 3026): 	at jdm.a(PG:77)
E/HttpOperation( 3026): 	... 12 more
E/HttpOperation( 3026): Caused by: faj: BadAuthentication
E/HttpOperation( 3026): 	at fal.a(PG:38)
E/HttpOperation( 3026): 	at jdj.a(PG:4089)
E/HttpOperation( 3026): 	... 14 more
,I/Babel   ( 2619): connection state changed from DISCONNECTED to CONNECTED
,D/GCM     ( 1477): Connected
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1477): Message class com.google.f.a.a.p
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 3026): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3026): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3026): 	at jdm.a(PG:82)
E/HttpOperation( 3026): 	at jcs.o(PG:406)
E/HttpOperation( 3026): 	at jcn.a(PG:1379)
E/HttpOperation( 3026): 	at jcs.i(PG:143)
E/HttpOperation( 3026): 	at hec.a(PG:42)
E/HttpOperation( 3026): 	at hee.a(PG:102)
E/HttpOperation( 3026): 	at czr.a(PG:65)
E/HttpOperation( 3026): 	at kka.a(PG:108)
E/HttpOperation( 3026): 	at czp.a(PG:19176)
E/HttpOperation( 3026): 	at czp.a(PG:9081)
E/HttpOperation( 3026): 	at czq.run(PG:1686)
E/HttpOperation( 3026): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 3026): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 3026): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 3026): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 3026): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 3026): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 3026): 	at jdj.a(PG:4091)
E/HttpOperation( 3026): 	at jdj.a(PG:1125)
E/HttpOperation( 3026): 	at jdm.a(PG:77)
E/HttpOperation( 3026): 	... 15 more
E/HttpOperation( 3026): Caused by: faj: BadAuthentication
E/HttpOperation( 3026): 	at fal.a(PG:38)
E/HttpOperation( 3026): 	at jdj.a(PG:4089)
E/HttpOperation( 3026): 	... 17 more
E/ExperimentLoader( 3026): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3026): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3026): 	at jdm.a(PG:82)
E/ExperimentLoader( 3026): 	at jcs.o(PG:406)
E/ExperimentLoader( 3026): 	at jcn.a(PG:1379)
E/ExperimentLoader( 3026): 	at jcs.i(PG:143)
E/ExperimentLoader( 3026): 	at hec.a(PG:42)
E/ExperimentLoader( 3026): 	at hee.a(PG:102)
E/ExperimentLoader( 3026): 	at czr.a(PG:65)
E/ExperimentLoader( 3026): 	at kka.a(PG:108)
E/ExperimentLoader( 3026): 	at czp.a(PG:19176)
E/ExperimentLoader( 3026): 	at czp.a(PG:9081)
E/ExperimentLoader( 3026): 	at czq.run(PG:1686)
E/ExperimentLoader( 3026): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 3026): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 3026): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 3026): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 3026): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 3026): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 3026): 	at jdj.a(PG:4091)
E/ExperimentLoader( 3026): 	at jdj.a(PG:1125)
E/ExperimentLoader( 3026): 	at jdm.a(PG:77)
E/ExperimentLoader( 3026): 	... 15 more
E/ExperimentLoader( 3026): Caused by: faj: BadAuthentication
E/ExperimentLoader( 3026): 	at fal.a(PG:38)
E/ExperimentLoader( 3026): 	at jdj.a(PG:4089)
E/ExperimentLoader( 3026): 	... 17 more
,V/GoogleAuthProtoRequest( 3208): [322] a.<init>: mAccountName set to: thalitester@gmail.com
,W/Kids    ( 1750): [AccountUtils] Account not ready
W/Kids    ( 1750): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1750): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1750): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1750): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1750): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1750): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1750): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1750): 	at java.lang.Thread.run(Thread.java:818)
,W/EventLogAggregator( 1750): Unknown tag: snet_gcore
,W/EventLogAggregator( 1750): Unknown tag: snet_launch_service
,I/CheckinRequestBuilder( 1750): Checkin reason type: 12 attempt count: 1
,D/WifiService(  820): New client listening to asynchronous messages
,E/ActivityThread( 1750): Failed to find provider info for com.google.android.wearable.settings
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 38552, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Start proc 3474:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/ExperimentUpdateService( 3208): [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 3208): [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3208): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3208): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3208): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3208): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3208): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3208): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3208): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3208): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3208): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3208): 	at com.a.a.k.run(SourceFile:110)
,I/GAv4    ( 3443): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3443):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3443):   adb logcat -s GAv4
V/KeepSync( 3253): Connecting to GoogleApiClient
,W/GAv4    ( 3443): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3443): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3443): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  820): Start proc 3496:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/ResourcesManager( 3496): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3496): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  820): Explicit concurrent mark sweep GC freed 32943(1535KB) AllocSpace objects, 5(122KB) LOS objects, 32% free, 33MB/49MB, paused 3.128ms total 56.077ms
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 32596(1859KB) AllocSpace objects, 4(87KB) LOS objects, 37% free, 26MB/42MB, paused 1.067ms total 140.909ms
,V/JNIHelp ( 3496): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1750): Handling authorization failure
E/ClientConnectionOperation( 1750): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1750): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1750): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1750): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1750): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1750): 	... 7 more
,V/KeepSync( 3253): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 3253): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 3253): (284) automatic index on blob_node(is_deleted)
E/SQLiteLog( 3253): (284) automatic index on blob_node(is_deleted)
,I/ProviderInstaller( 3496): Installed default security provider GmsCore_OpenSSL
,I/WebViewFactory( 3443): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 3443): Time to load native libraries: 3 ms (timestamps 4112-4115)
I/LibraryLoader( 3443): Expected native library version number "",actual native library version number ""
,E/YouTube MDX( 3496): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,V/WebViewChromiumFactoryProvider( 3443): Binding Chromium to main looper Looper (main, tid 1) {2cecf6a1}
,I/LibraryLoader( 3443): Expected native library version number "",actual native library version number ""
I/chromium( 3443): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3443): Initializing chromium process, singleProcess=true
,W/art     ( 3443): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 3443): ApplicationContext is null in ApplicationStatus
,W/chromium( 3443): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/GAV2    ( 3474): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/libEGL  ( 3443): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3443): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno  ( 3443): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/dex2oat ( 3554): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1259068041.jar --oat-fd=30 --oat-location=/data/data/com.google.android.youtube/cache/ads1259068041.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/BooksApp( 3474): Created application version: 3.6.8 (30608)
,I/art     ( 1750): Explicit concurrent mark sweep GC freed 12685(1037KB) AllocSpace objects, 14(224KB) LOS objects, 35% free, 29MB/45MB, paused 1.140ms total 101.966ms
,I/dex2oat ( 3554): dex2oat took 73.191ms (threads: 4) arena alloc=71KB java alloc=12KB native alloc=716KB free=7MB
,W/AudioManagerAndroid( 3443): Requires BLUETOOTH permission
,W/InstanceID/Rpc( 3496): Found 10011
,I/NSApplication( 3443): Starting up...
,I/BooksSync( 3474): Starting books sync for 61035162, extras: ade
I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 3614:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Killing 2940:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,E/KeepSync( 3253): IOException
E/KeepSync( 3253): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 3253): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 3253): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 3253): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 3253): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 3253): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 3253): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 3253): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 3253): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 3253): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 3253): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 3253): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 3253): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 3253): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 3253): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 3253): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 3253): 	... 10 more
W/KeepSync( 3253): Sync result 2
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 38557, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 3474): GmsCore Version = 7.8.99 (2134222-430)
,W/CheckinRequestBuilder( 1750): awaiting user notification for token
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Start proc 3655:com.google.android.gms.unstable/u0a11 for service com.google.android.gms/.droidguard.DroidGuardService
,I/GoogleURLConnFactory( 1750): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 3655): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3655): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MultiDex( 3655): VM with version 2.1.0 has multidex support
I/MultiDex( 3655): install
I/MultiDex( 3655): VM has multidex support, MultiDex support library is disabled.
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 3474): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 3474): Soft error
E/BooksSync( 3474): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3474): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 3474): Sync error
E/BooksSync( 3474): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 3474): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 3474): Finished books sync
,V/JNIHelp ( 3655): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/GLSActivity( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1477): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1477): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,W/SubscribedFeeds( 1750): Hard error
,I/ActivityManager(  820): Killing 2960:com.android.musicfx/u0a18 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38558, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ProviderInstaller( 3655): Installed default security provider GmsCore_OpenSSL
,I/art     (  820): Explicit concurrent mark sweep GC freed 17641(737KB) AllocSpace objects, 3(142KB) LOS objects, 31% free, 34MB/50MB, paused 1.217ms total 52.218ms
,I/ActivityManager(  820): Killing 2987:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 43631, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 166475, reason: Periodic
,I/ActivityManager(  820): Start proc 3678:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
I/ActivityManager(  820): Killing 1361:android.process.acore/u0a5 (adj 15): empty #17
,I/ActivityManager(  820): Start proc 3696:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,D/WVCdm   (  358): Instantiating CDM.
E/SQLiteLog( 3696): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
,I/PeopleSync( 1750): onPerformSync() [5005f081]
,W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/GoogleURLConnFactory( 3655): Using platform SSLCertificateSocketFactory
,I/AnalyticsLogBase( 3696): PlayLogger.onLoggerConnected
I/AnalyticsLogBase( 3696): PlayLogger.onLoggerConnected
,W/ResourcesManager( 3696): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3696): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/PeopleDatabaseHelper( 1750): cleanUpNonGplusAccounts done.
,V/JNIHelp ( 3696): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 3696): Installed default security provider GmsCore_OpenSSL
W/AbstractGoogleClient( 3696): Application name is not set. Call Builder#setApplicationName.
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 19460(1068KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 27MB/43MB, paused 725us total 51.201ms
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4424000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4424000
,D/DrmLibTime(  317): got the req here! ret=0
D/DrmLibTime(  317): command id, time_cmd_id = 770
D/DrmLibTime(  317): time_getutcsec starts!
D/DrmLibTime(  317): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  317): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  317): QSEE Time Listener: seconds: 1453981615
D/DrmLibTime(  317): QSEE Time Listener: nano seconds: 718135519
D/DrmLibTime(  317): time_getutcsec returns 0, sec = 1453981615; nsec = 718135519
D/DrmLibTime(  317): time_getutcsec finished! 
D/DrmLibTime(  317): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  317): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xb3e03940
D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb58765b0, dataLength=8
D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4011000, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb583d340, idLength=0xb2fb6710
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
D/WVCdm   (  358): PrepareKeyRequest: nonce=4213974272
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4022200
D/DrmWidevineDash(  358): message_length=1599, signature=0xb40653c0, signature_length=3002820340
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
,I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
,D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0,
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,I/PeopleSync( 1750): Setting subscription: result=true [5005f081]
,I/PeopleSync( 1750): Starting sync, feed=null [5005f081]
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,E/CalendarSyncAdapter( 3696): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 3696): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 3696): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 3696): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 3696): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 3696): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 3696): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 3696): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 3696): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2382)
E/CalendarSyncAdapter( 3696): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1850)
E/CalendarSyncAdapter( 3696): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:1733)
E/CalendarSyncAdapter( 3696): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:503)
E/CalendarSyncAdapter( 3696): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:392)
E/CalendarSyncAdapter( 3696): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 3696): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 3696): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 3696): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 3696): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 3696): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 3696): 	... 12 more
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,I/PeopleSync( 1750): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 43882, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 167652, reason: Periodic
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PeopleSync( 1750): Sync finished, successful=false, took 89ms
,I/ActivityManager(  820): Killing 1779:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,I/PeopleSync( 1750): Cannot authenticate [5005f081]
I/PeopleSync( 1750): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1750): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1750): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1750): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1750): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1750): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1750): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1750): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1750): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1750): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1750): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1750): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1750): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/WVCdm   (  358): CdmEngine::OpenSession
I/WVCdm   (  358): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  358): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x11
D/DrmWidevineDash(  358): Service_Initialize: starts!
D/QSEECOMAPI: (  358): QSEECom_get_handle sb_length = 0x19000
D/QSEECOMAPI: (  358): App is not loaded in QSEE
,I/GCoreUlr( 1708): Uploading GCM registration ID for account#2#
,I/ActivityManager(  820): Start proc 3735:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,I/ActivityManager(  820): Killing 2691:com.android.vending/u0a19 (adj 15): empty #17
,D/TimeService( 3735): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1453981616371
D/        ( 3735): TimeServiceNative: User Time to be set is 1453981616371
D/QC-time-services( 3735): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3735): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3735): Lib:time_genoff_operation: pargs->ts_val = 1453981616371
D/QC-time-services(  373): Daemon: Connection accepted:time_genoff
D/QC-time-services(  373): Daemon:Received base = 2, unit = 1, operation = 0,value = 1453981616371
D/QC-time-services(  373): Daemon:genoff_opr: Base = 2, val = 1453981616371, operation = 0
D/QC-time-services(  373): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS5/15/70 7:59:22
D/QC-time-services(  373): Daemon:Value read from RTC seconds = 14284762000
D/QC-time-services(  373): Daemon:new time 1453981616371 
D/QC-time-services(  373): Daemon: delta 1439696854371 genoff 1439696854371 
D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696854371 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
D/QC-time-services( 3735): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  373): Updating the TOD offset
,D/QC-time-services(  373): Daemon:genoff_persistent_update: Writing genoff = 1439696854371 to memory
D/QC-time-services(  373): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  373): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  373): Daemon:Update to modem bit set
D/QC-time-services(  373): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  373): Daemon: Base = 2, Value being sent to MODEM = 1138016816371
E/QC-time-services( 3735): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QSEECOMAPI: (  358): Loaded image: APP id = 3
,D/DrmWidevineDash(  358): Service_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4424000
E/DrmWidevineDash(  358): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb4424000
,D/DrmLibTime(  317): got the req here! ret=0
D/DrmLibTime(  317): command id, time_cmd_id = 770
D/DrmLibTime(  317): time_getutcsec starts!
D/DrmLibTime(  317): QSEE Time Listener: time_getutcsec
D/DrmLibTime(  317): QSEE Time Listener: get_utc_seconds
D/DrmLibTime(  317): QSEE Time Listener: seconds: 1453981616
D/DrmLibTime(  317): QSEE Time Listener: nano seconds: 425740206
D/DrmLibTime(  317): time_getutcsec returns 0, sec = 1453981616; nsec = 425740206
D/DrmLibTime(  317): time_getutcsec finished! 
D/DrmLibTime(  317): iotcl_continue_command finished! and return 0 
D/DrmLibTime(  317): before calling ioctl to read the next time_cmd
,D/DrmWidevineDash(  358): OEMCrypto_Initialize: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
,D/DrmWidevineDash(  358): hlos api version =  9
,D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: starts!
,D/DrmWidevineDash(  358): OEMCrypto_IsKeyboxValid: ends! returns 0
,D/WVCdm   (  358): OEMCrypto_Initialize Level 1 success. I will use level 1.
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: starts! SID=0xb3f01940
E/QC-time-services(  373): Daemon: Time-services: Waiting to acceptconnection
D/DrmWidevineDash(  358): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  358): OEMCrypto_OpenSession: ends! returns 0
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: starts! randomData=0xb4c4e230, dataLength=8
,D/DrmWidevineDash(  358): OEMCrypto_GetRandom: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb4d2b000, wrapped_rsa_key_length=1280
D/DrmWidevineDash(  358): OEMCrypto_LoadDeviceRSAKey: ends! returns 0
I/WVCdm   (  358): CdmEngine::QueryKeyControlInfo
E/QC-time-services(  373): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,W/WVCdm   (  358): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  358): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  358): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: starts! deviceID=0xb583d380, idLength=0xbed5e2f0
,I/ActivityManager(  820): Killing 3277:com.android.settings/1000 (adj 15): empty #17
,D/DrmWidevineDash(  358): OEMCrypto_GetDeviceID: ends! returns 0
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: starts!
,D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: is_supported = 1
,D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: wv_app_version = 21
D/DrmWidevineDash(  358): OEMCrypto_SupportsUsageTable: ends! returns 0x0
,D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: starts!
D/DrmWidevineDash(  358): OEMCrypto_GetHDCPCapability: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: starts!
D/DrmWidevineDash(  358): hlos api version =  9
D/DrmWidevineDash(  358): tz api version =  9
D/DrmWidevineDash(  358): OEMCrypto_APIVersion: ends! returns version 9
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_GenerateNonce: ends! returns 0
D/WVCdm   (  358): PrepareKeyRequest: nonce=2856869236
D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb4023e00
D/DrmWidevineDash(  358): message_length=1634, signature=0xb4065140, signature_length=3201688276
,D/DrmWidevineDash(  358): OEMCrypto_GenerateRSASignature returns 0
,W/BaseAppContext( 1708): Using Auth Proxy for data requests.
,I/PeopleSync( 1750): ***Sync finished***, duration: 1235 [5005f081]
,I/GLSUser ( 1708): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 1708): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 43744, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 169492, reason: Periodic
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 3760:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GCoreUlr( 1708): 
E/GCoreUlr( 1708): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1708): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1708): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1708): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1708): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1708): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1708): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1708): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1708): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1708): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1708): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1708): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1708): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1708): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1708): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1708): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 43922, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 167281, reason: Periodic
,I/GAv4    ( 3760): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3760):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3760):   adb logcat -s GAv4
,I/ActivityManager(  820): Start proc 3779:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,W/GAv4    ( 3760): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  358): CdmEngine::CloseSession
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: starts! SID=1
D/DrmWidevineDash(  358): OEMCrypto_CloseSession: ends! returns 0
I/WVCdm   (  358): L3 Terminate.
D/DrmWidevineDash(  358): OEMCrypto_Terminate: starts!
D/DrmWidevineDash(  358): Service_Uninitialize: starts!
D/QSEECOMAPI: (  358): QSEECom_dealloc_memory 
D/QSEECOMAPI: (  358): QSEECom_shutdown_app, app_id = 3
D/DrmWidevineDash(  358): Service_Uninitialize: ends! returns 0x0
D/DrmWidevineDash(  358): OEMCrypto_Terminate: ends! returns 0
,W/GAv4    ( 3760): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3760): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dex2oat ( 3800): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/Gmail   ( 3779): getAccountsCursor
,I/dex2oat ( 3800): dex2oat took 34.112ms (threads: 4) arena alloc=113KB java alloc=18KB native alloc=1125KB free=6MB
,I/Adreno  ( 3655): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,I/art     (  820): Explicit concurrent mark sweep GC freed 26160(1127KB) AllocSpace objects, 7(489KB) LOS objects, 32% free, 33MB/49MB, paused 1.230ms total 54.206ms
,D/ActivityThread( 3779): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Start proc 3813:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,I/art     (  369): Explicit concurrent mark sweep GC freed 703(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 1.559ms total 11.236ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 3(96B) AllocSpace objects, 0(0B) LOS objects, 39% free, 21MB/36MB, paused 201us total 9.623ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 7(224B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 194us total 8.103ms
,I/ActivityManager(  820): Start proc 3831:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,I/Adreno  ( 3655): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,W/GAV2    ( 3779): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  820): Killing 3296:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,I/ContactLocale( 3831): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/ActivityManager(  820): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 3813): EasService.onCreate
,V/Herrevad( 1750): NQAS connected
,D/GCM     ( 1477): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/Exchange( 3813): RestartPingTask
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@cdbcea3}
,I/[@@    ] SyncAdapterProxy( 1477): Delagator disabled, using the (deprecated) GData sync adapter
,I/EventLogService( 1750): Opted in for usage reporting
,D/GCM     ( 1477): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Gmail   ( 3779): Observing account changes for notifications
,I/Gmail   ( 3779): getAccountsCursor
,W/Gmail   ( 3779): Sync started for account: account:61035162
,D/AuthorizationBluetoothService( 1477): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1750): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/PlayLogIntentService( 1477): Cannot perform this operation because the connection pool has been closed.
E/PlayLogIntentService( 1477): java.lang.IllegalStateException: Cannot perform this operation because the connection pool has been closed.
E/PlayLogIntentService( 1477): 	at android.database.sqlite.SQLiteConnectionPool.throwIfClosedLocked(SQLiteConnectionPool.java:962)
E/PlayLogIntentService( 1477): 	at android.database.sqlite.SQLiteConnectionPool.waitForConnection(SQLiteConnectionPool.java:599)
E/PlayLogIntentService( 1477): 	at android.database.sqlite.SQLiteConnectionPool.acquireConnection(SQLiteConnectionPool.java:348)
E/PlayLogIntentService( 1477): 	at android.database.sqlite.SQLiteSession.acquireConnection(SQLiteSession.java:894)
E/PlayLogIntentService( 1477): 	at android.database.sqlite.SQLiteSession.executeForLong(SQLiteSession.java:650)
E/PlayLogIntentService( 1477): 	at android.database.sqlite.SQLiteStatement.simpleQueryForLong(SQLiteStatement.java:107)
E/PlayLogIntentService( 1477): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:825)
E/PlayLogIntentService( 1477): 	at android.database.DatabaseUtils.longForQuery(DatabaseUtils.java:813)
E/PlayLogIntentService( 1477): 	at com.google.android.gms.playlog.store.g.c(SourceFile:86)
E/PlayLogIntentService( 1477): 	at com.google.android.gms.playlog.store.g.b(SourceFile:79)
E/PlayLogIntentService( 1477): 	at com.google.android.gms.playlog.service.PlayLogIntentService.a(SourceFile:23)
E/PlayLogIntentService( 1477): 	at com.google.android.gms.playlog.service.c.a(SourceFile:103)
E/PlayLogIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/PlayLogIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 14673(850KB) AllocSpace objects, 11(1212KB) LOS objects, 37% free, 26MB/42MB, paused 1.489ms total 26.030ms
,I/ActivityManager(  820): Start proc 3876:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,D/LocationInitializer( 1750): Restart initialization of location
,I/Exchange( 3813): RestartPingsTask did not start any pings.
I/Exchange( 3813): PSS stopIfIdle
I/Exchange( 3813): PSS has no active accounts; stopping service.
I/art     ( 1750): Explicit concurrent mark sweep GC freed 17628(1128KB) AllocSpace objects, 12(192KB) LOS objects, 35% free, 29MB/45MB, paused 4.179ms total 111.325ms
,I/Exchange( 3813): onDestroy
,W/ResourcesManager( 3876): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3876): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3876): VM with version 2.1.0 has multidex support
I/MultiDex( 3876): install
I/MultiDex( 3876): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3876): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 3779): (283) recovered 86 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ProviderInstaller( 3876): Installed default security provider GmsCore_OpenSSL
,V/GoogleAuthProtoRequest( 3208): [323] a.<init>: mAccountName set to: thalitester@gmail.com
,D/WearableService( 3876): callingUid 10011, callindPid: 3876
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/MDM     ( 1708): [125] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 2619): UserRecoverableAuthException.
E/Babel   ( 2619): eei: BadAuthentication
E/Babel   ( 2619): 	at eeg.a(Unknown Source)
E/Babel   ( 2619): 	at eeg.a(Unknown Source)
E/Babel   ( 2619): 	at eeg.a(Unknown Source)
E/Babel   ( 2619): 	at g.a(Unknown Source)
E/Babel   ( 2619): 	at cae.a(SourceFile:3089)
E/Babel   ( 2619): 	at cae.a(SourceFile:1131)
E/Babel   ( 2619): 	at cws.a(SourceFile:4333)
E/Babel   ( 2619): 	at cws.a(SourceFile:1419)
E/Babel   ( 2619): 	at crl.a(SourceFile:492)
E/Babel   ( 2619): 	at crl.a(SourceFile:1468)
E/Babel   ( 2619): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2619): 	at cas.b(SourceFile:106)
E/Babel   ( 2619): 	at cap.d(SourceFile:335)
E/Babel   ( 2619): 	at caq.run(SourceFile:81)
E/Babel   ( 2619): Error getting auth token
E/Babel   ( 2619): dvm
E/Babel   ( 2619): 	at g.a(Unknown Source)
E/Babel   ( 2619): 	at cae.a(SourceFile:3089)
E/Babel   ( 2619): 	at cae.a(SourceFile:1131)
E/Babel   ( 2619): 	at cws.a(SourceFile:4333)
E/Babel   ( 2619): 	at cws.a(SourceFile:1419)
E/Babel   ( 2619): 	at crl.a(SourceFile:492)
E/Babel   ( 2619): 	at crl.a(SourceFile:1468)
E/Babel   ( 2619): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2619): 	at cas.b(SourceFile:106)
E/Babel   ( 2619): 	at cap.d(SourceFile:335)
E/Babel   ( 2619): 	at caq.run(SourceFile:81)
,W/GLSActivity( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1477): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1477): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ContactsSyncAdapter( 1477): innerSync failed
D/ContactsSyncAdapter( 1477): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1477): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1477): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1477): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1477): 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:123)
D/ContactsSyncAdapter( 1477): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1477): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1477): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1477): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
D/ContactsSyncAdapter( 1477): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1477): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
D/ContactsSyncAdapter( 1477): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,I/Gmail   ( 3779): notifyAccountChanged
,E/Babel   ( 2619): Account registration failed 1-Redacted-21
E/Babel   ( 2619): cyp: null -- null
E/Babel   ( 2619): 	at cae.a(SourceFile:3121)
E/Babel   ( 2619): 	at cae.a(SourceFile:1131)
E/Babel   ( 2619): 	at cws.a(SourceFile:4333)
E/Babel   ( 2619): 	at cws.a(SourceFile:1419)
E/Babel   ( 2619): 	at crl.a(SourceFile:492)
E/Babel   ( 2619): 	at crl.a(SourceFile:1468)
E/Babel   ( 2619): 	at cqu.a(SourceFile:4416)
E/Babel   ( 2619): 	at cas.b(SourceFile:106)
E/Babel   ( 2619): 	at cap.d(SourceFile:335)
E/Babel   ( 2619): 	at caq.run(SourceFile:81)
,I/art     ( 2619): Note: end time exceeds epoch: 
,I/Gmail   ( 3779): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/GCM     ( 1477): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Gmail   ( 3779): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/AuthorizationBluetoothService( 1477): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 44076, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,V/GmsCoreStatsServiceLauncher( 1750): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 170271, reason: Periodic
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3779): notifyAccountChanged
,I/Gmail   ( 3779): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3779): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/MDM     ( 1708): [128] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1750): Restart initialization of location
,W/ExperimentUpdateService( 3208): [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
W/ExperimentUpdateService( 3208): [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3208): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3208): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 3208): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 3208): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 3208): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 3208): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 3208): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 3208): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 3208): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 3208): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  820): Killing 2852:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/art     (  820): Explicit concurrent mark sweep GC freed 19981(929KB) AllocSpace objects, 1(110KB) LOS objects, 32% free, 33MB/49MB, paused 1.710ms total 78.115ms
,W/ResourcesManager( 1477): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/Babel   ( 2619): Unexpected exception while authenticating.
E/Babel   ( 2619): eej: User intervention required. Notification has been pushed.
E/Babel   ( 2619): 	at eeg.b(Unknown Source)
E/Babel   ( 2619): 	at eeg.b(Unknown Source)
E/Babel   ( 2619): 	at g.a(Unknown Source)
E/Babel   ( 2619): 	at cae.b(SourceFile:1146)
E/Babel   ( 2619): 	at dcg.run(SourceFile:5617)
E/Babel   ( 2619): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 2619): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 2619): 	at java.lang.Thread.run(Thread.java:818)
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Ads     ( 1750): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3779): getAccountsCursor
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3779): getAccountsCursor
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 26120(1449KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 905us total 23.507ms
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=56.41 rxSuccessRate=59.56 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 2, 4 -> obsolete
,I/Gmail   ( 3779): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,I/CheckinTask( 1750): Sending checkin request (9760 bytes)
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 3779): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3779): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ReminderSync( 1750): AuthError [T SyncAdapterThread-1:id=232:priority=5:group=main]
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 44101, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 169281, reason: Periodic
,V/JNIHelp ( 3779): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/SyncAdapterService( 3443): Ignoring sync request for non-current account
,I/ProviderInstaller( 3779): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=56.41 rxSuccessRate=59.56 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 3, 4 -> obsolete
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DelayedSyncController( 3614): Delaying sync.
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/GLSActivity( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1477): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1477): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,W/GLSActivity( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1477): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1477): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,W/BaseAppContext( 1750): Using Auth Proxy for data requests.
,I/Gmail   ( 3779): notifyAccountChanged
,I/Gmail   ( 3779): getAccountsCursor
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/jxcore-log( 3130): Test app app.js loaded
I/jxcore-log( 3130): 
,I/chromium( 3130): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 3130): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 3130): BLE advertisement is supported
I/jxcore-log( 3130): 
,I/ActivityManager(  820): Start proc 3932:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,I/Gmail   ( 3779): notifyAccountChanged
,W/Gmail   ( 3779): Sync complete for account: account:61035162
,I/Gmail   ( 3779): getAccountsCursor
,I/ActivityManager(  820): Killing 3378:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 44025, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 170090, reason: Periodic
,I/MusicStore( 3932): Database version: 120
,I/CheckinResponseProcessor( 1750): From server: 1 gservices updates and 1 deletes
,I/ActivityManager(  820): Start proc 3955:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,W/ResourcesManager( 3932): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3932): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3932): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 3932): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 3932): GMSCore installation verified
,I/ConfigStore( 3932): Config Database version: 1
,I/CertBlacklister(  820): Certificate blacklist changed, updating...
,I/CertBlacklister(  820): Certificate blacklist updated
,I/GservicesProvider( 1477): main difference update completed
,I/ActivityManager(  820): Start proc 3977:com.google.android.partnersetup/u0a16 for broadcast com.google.android.partnersetup/.GservicesChangedReceiver
,I/CheckinRequestBuilder( 1750): Checkin reason type: 12 attempt count: 1
,I/MediaRouter( 3932): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,E/ActivityThread( 1750): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  820): Explicit concurrent mark sweep GC freed 26306(1149KB) AllocSpace objects, 4(158KB) LOS objects, 32% free, 33MB/49MB, paused 1.694ms total 58.198ms
,I/ActivityManager(  820): Start proc 3995:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,I/GHttpClientFactory( 3932): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3932): Using platform SSLCertificateSocketFactory
W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/NetworkMonitor( 3932): type=WIFI subType= reason=null isConnected=true
I/art     ( 1477): Explicit concurrent mark sweep GC freed 20351(1064KB) AllocSpace objects, 6(661KB) LOS objects, 37% free, 26MB/42MB, paused 945us total 25.984ms
,I/Babel_telephony( 2619): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
W/Babel   ( 2619): BAM#gBA: invalid account id: -1
W/Babel   ( 2619): BAM#gBA: invalid account id: -1
I/Babel_telephony( 2619): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,I/MusicLifecycle( 3932): Sync started
,I/com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter( 3955): Sync request not initiated by GCP app. Dropping
,I/NetworkMonitor( 3932): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 3932): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 3932): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  820): Start proc 4026:com.google.android.configupdater/u0a42 for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver
,I/ActivityManager(  820): Killing 1509:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,D/WifiService(  820): Client connection lost with reason: 4
,I/ActivityManager(  820): Killing 3026:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,I/GAV2    ( 3474): Thread[GAThread,5,main]: No campaign data found.,
,E/UpdateRequestReceiver( 4026): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4026): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4026): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 4026): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  820): Killing 3474:com.google.android.apps.books/u0a34 (adj 15): empty #17
,E/Auth.Api.Credentials( 1750): [CredentialSyncAdapter] Unknown sync event.
,I/SystemUpdateService( 1750): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 1750): onCreate
,D/SystemUpdateService( 1750): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,D/GCM     ( 1477): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 5596(239KB) AllocSpace objects, 5(551KB) LOS objects, 37% free, 26MB/42MB, paused 1.563ms total 30.865ms
,I/ActivityManager(  820): Killing 3496:com.google.android.youtube/u0a86 (adj 15): empty #17
,I/art     ( 1708): Explicit concurrent mark sweep GC freed 13563(796KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 1.292ms total 31.655ms
,E/DataBuffer( 1708): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ddcbb88)
,I/art     ( 1750): Explicit concurrent mark sweep GC freed 25646(2MB) AllocSpace objects, 9(143KB) LOS objects, 35% free, 29MB/45MB, paused 1.662ms total 81.779ms
,D/SystemEventReceiver( 1750): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 1750): Updating ocr activity enabled=false
,I/GCoreUlr( 1708): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1708): DispatchingService.onCreate()
,I/SystemUpdateService( 1750): active receiver: enabled
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1477): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1477): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,I/SystemUpdateService( 1750): showing system update notification
,I/ValidateNoPeople(  820): skipping global notification
,V/SystemUpdateService( 1750): retry (wakeup: false) in 3599879 ms
,I/art     (  820): Explicit concurrent mark sweep GC freed 12803(571KB) AllocSpace objects, 4(346KB) LOS objects, 32% free, 33MB/49MB, paused 1.404ms total 59.846ms
,I/MusicLifecycle( 3932): Sync ended
W/MusicSyncAdapter( 3932): Sync failed due to an authentication issue.
,I/ActivityManager(  820): Killing 3253:com.google.android.keep/u0a79 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 44173, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager(  820): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 172389, reason: Periodic
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1708): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 7872(412KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.389ms total 45.586ms
,I/GAV2    ( 3696): Thread[GAThread,5,main]: No campaign data found.
,W/CheckinRequestBuilder( 1750): awaiting user notification for token
,I/GCoreUlr( 1708): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1708): Unbound from all location providers
,I/GCoreUlr( 1708): DispatchingService.onDestroy()
,D/SystemUpdateService( 1750): onDestroy
,I/GCoreUlr( 1708): Unbound from all location providers
,I/EventLogService( 1750): Opted in for usage reporting
,I/CheckinTask( 1750): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1750): Checking schedule, now: 1453981620714 next: 1454022763695
I/CheckinService( 1750): active receiver: disabled
,I/art     ( 1750): Explicit concurrent mark sweep GC freed 9449(607KB) AllocSpace objects, 8(128KB) LOS objects, 35% free, 29MB/45MB, paused 1.821ms total 77.147ms
,I/CheckinService( 1750): Checking schedule, now: 1453981620776 next: 1454022763695
I/CheckinService( 1750): active receiver: disabled
,I/ActivityManager(  820): Start proc 4077:com.google.android.googlequicksearchbox:search/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 4297(178KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.108ms total 22.071ms
,I/GservicesUpdateTask( 4077): Updating Gservices keys
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/MusicLeanback( 3932): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3932): Stop autocaching.
,D/GCM     ( 1477): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1750): [AccountUtils] Account not ready
W/Kids    ( 1750): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1750): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1750): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1750): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1750): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1750): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1750): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1750): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1750): 	at java.lang.Thread.run(Thread.java:818)
,E/GmsUtils( 3932): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3932): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  820): Killing 3735:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/GAV2    ( 3779): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  820): Killing 3760:com.google.android.deskclock/u0a44 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3813:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3208:com.google.android.apps.gcs/u0a89 (adj 15): empty #17
,V/ConfigFetchTask( 1750): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XTqQBKMVv3O0XkrVqCsJnlv5RAGr8sdfmqFFHfZ3cigNVzjnk4brxvFUkzgMIJEMDtw9IWfUdj0pvnTdMwMI7KfWxQfnoUUmJ6MlPYVU04jKvI4k9fwuL8meeKit6Bn-89b50S-uodoUp4-g3Rcb867jgX8weWqOyLzEaHMK2aekahOaFbUGb46NqhP-EJnW4sCgeT8Z6aVukKvuJ5BcUVyVbeCT6k-1OJy0ArVe2MAcoDe_w
,I/GoogleURLConnFactory( 1750): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  820): Start proc 4131:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,D/Finsky  ( 4131): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4131): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ConfigFetchTask( 1750): updating config table for com.google.android.gms
,I/ActivityManager(  820): Start proc 4168:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,I/ConfigFetchService( 1750): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/ConfigFetchService( 1750): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1750): GmsCore config value changed; rescheduling
W/Settings( 4131): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4131): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ConfigFetchService( 1750): fetch service done; releasing wakelock
,I/ConfigFetchService( 1750): self-hosted config:fetch_interval = 43200
,I/ConfigFetchService( 1750): stopping self
,W/ResourcesManager( 4168): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/Finsky  ( 4131): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
W/ResourcesManager( 4168): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 4131): [1] 2.run: Finished loading 1 libraries.
,I/MultiDex( 4168): VM with version 2.1.0 has multidex support
I/MultiDex( 4168): install
I/MultiDex( 4168): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 4131): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4131): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/JNIHelp ( 4168): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/VacuumService( 1477): Vacuum at: now=1453981623589 tag=VacuumService
,I/GoogleURLConnFactory( 1477): Using platform SSLCertificateSocketFactory
,I/ProviderInstaller( 4168): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1477): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1477): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1750): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/Uploader( 1477): No account for auth token provided
,I/art     (  820): Explicit concurrent mark sweep GC freed 19586(927KB) AllocSpace objects, 4(64KB) LOS objects, 32% free, 33MB/49MB, paused 1.372ms total 78.738ms
,E/MDM     ( 1708): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1750): Restart initialization of location
,V/Finsky  ( 4131): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4131): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4131): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4131): [1] 5.onFinished: Scheduling replication attempt 4.
,I/MusicLeanback( 3932): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 3932): Stop autocaching.
,E/GmsUtils( 3932): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 3932): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/ActivityManager(  820): Killing 3831:android.process.acore/u0a5 (adj 15): empty #17
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1477): No account for auth token provided
,D/Finsky  ( 4131): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1477): No account for auth token provided
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4131): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 38414(2MB) AllocSpace objects, 6(538KB) LOS objects, 36% free, 27MB/43MB, paused 1.375ms total 49.610ms
,W/Uploader( 1477): No account for auth token provided
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4131): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Uploader( 1477): No account for auth token provided
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Uploader( 1477): No account for auth token provided
,W/Finsky  ( 4131): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4131): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4131): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4131): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1708): client connected with version: 7571000
,W/Uploader( 1477): No account for auth token provided
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550),
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	,at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477):  no longer exists, so no auth token.
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): ,	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235),
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ConfigService( 1477): onDestroy,
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/art     (  820): Explicit concurrent mark sweep GC freed 23186(1037KB) AllocSpace objects, 3(330KB) LOS objects, 31% free, 34MB/50MB, paused 1.386ms total 54.645ms
,I/ActivityManager(  820): Killing 2619:com.google.android.talk/u0a61 (adj 15): empty #17
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  820): Killing 2198:com.android.providers.calendar/u0a3 (adj 15): empty #17
,W/PackageSettings(  820): Skipping PackageSetting{2b5a22b0 com.example.hello/10273} due to missing metadata
,E/Uploader( 1477): Failed to get auth token: User intervention required. Notification has been pushed.,
E/Uploader( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1477): 	at com.google.android.gms.auth.p.c(SourceFile:550)
,E/Uploader( 1477): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
,E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1477): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1477): 	,at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,W/Uploader( 1477): No account for auth token provided
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  820): Start proc 4220:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver
,I/art     (  369): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 203us total 10.999ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 197us total 8.897ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 199us total 8.803ms
W/ResourcesManager( 4220): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GmsNetworkLocationProvi( 1708): DISABLE
,D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  820): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  820): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/GmsNetworkLocationProvi( 1708): onSetRequest: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  820): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  820): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@31089279
,V/GmsNetworkLocationProvi( 1708): ENABLE
V/GmsNetworkLocationProvi( 1708): SET-REQUEST
,V/GmsNetworkLocationProvi( 1708): in Handler: ProviderRequestUnbundled, reportLocation is true and interval is 86400000
,V/BackupManagerService(  820): Scheduling immediate backup pass
,V/BackupManagerService(  820): Running a backup pass
,V/BackupManagerService(  820): clearing pending backups
,V/PerformBackupTask(  820): Beginning backup of 14 targets
,D/PerformBackupTask(  820): invokeAgentForBackup on @pm@
,I/Launcher( 1279): Deferring update until onResume
,V/BackupServiceBinder(  820): doBackup() invoked
,I/PMBA    (  820): Previous metadata 1570415 mismatch vs 1743759 - rewriting
,I/BackupRestoreController(  820): Getting widget state for user: 0
,W/GmsBackupTransport( 1708): Unknown package in backup request: @pm@
,V/GmsBackupTransport( 1708): starting performBackup for @pm@
,V/GmsBackupTransport( 1708): performBackup done for @pm@
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel_SMS( 4220): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4220): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4220): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,I/Babel_SMS( 4220): MmsConfig.loadFromDatabase
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GLSActivity( 1477): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1477): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1477): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1477): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1477): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GmsBackupTransport( 1708): Error sending final backup to server: 
W/GmsBackupTransport( 1708): com.google.android.gms.backup.d.d: Can not get client auth token
W/GmsBackupTransport( 1708): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
W/GmsBackupTransport( 1708): 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
W/GmsBackupTransport( 1708): 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
W/GmsBackupTransport( 1708): 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
W/GmsBackupTransport( 1708): 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
W/GmsBackupTransport( 1708): 	at android.os.Binder.execTransact(Binder.java:446)
W/GmsBackupTransport( 1708): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
W/GmsBackupTransport( 1708): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
W/GmsBackupTransport( 1708): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
W/GmsBackupTransport( 1708): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
W/GmsBackupTransport( 1708): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
W/GmsBackupTransport( 1708): 	... 1 more
D/BackupManagerService(  820): Now staging backup of com.google.android.talk
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
E/Babel_SMS( 4220): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4220): MmsConfig.loadFromResources
E/Babel_SMS( 4220): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4220): MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
D/BackupManagerService(  820): Now staging backup of com.google.android.googlequicksearchbox
,I/GmsBackupTransport( 1708): Next backup will happen in 43199965 millis.
,I/BackupManagerService(  820): Backup pass finished.
,W/Settings( 4220): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4220): startup - clean
,I/Babel   ( 4220): deleted: false for 0
,I/Babel_telephony( 4220): TeleModule.launchCompleted
,W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/Babel_telephony( 4220): TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,W/Babel   ( 4220): BAM#gBA: invalid account id: -1
,W/Babel   ( 4220): BAM#gBA: invalid account id: -1
I/Babel_telephony( 4220): TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
W/Telecom (  820): TelecomServiceImpl: null is not visible for the calling user
,I/ActivityManager(  820): Start proc 4251:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,W/VideoCapabilities( 4220): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 4220): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4220): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4220): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4220): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4220): Unrecognized profile 2130706433 for video/avc
,D/PackageBroadcastService( 1750): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1750): Null package name or gms related package.  Ignoreing.
,I/UpdateIcingCorporaServi( 4077): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/Launcher( 1279): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d7c8dbf new=com.google.android.velvet.VelvetApplication@3d7c8dbf
,I/vclib   ( 4220): onServiceConnected
,I/Icing   ( 1750): updateResources: need to parse f{com.google.android.gms}
W/Babel   ( 4220): Attempted to change video mute state without an active call.
,W/ResourcesManager( 4220): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4220): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  820): Start proc 4278:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/ContactLocale( 4251): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/ResourcesManager( 4278): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 4220): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/UpdateIcingCorporaServi( 4077): UpdateCorporaTask done [took 96 ms] updated apps [took 96 ms] 
,I/ProviderInstaller( 4220): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  820): Killing 3443:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=36.39 rxSuccessRate=24.61 targetRoamBSSID=any RSSI=-49
,E/WifiStateMachine(  820): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/ActivityManager(  820): Killing 3614:com.android.chrome/u0a40 (adj 15): empty #17
,I/ActivityManager(  820): Killing 3779:com.google.android.gm/u0a78 (adj 15): empty #17
,I/PowerManagerService(  820): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno  (  820): EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,D/PermissionCache(  261): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (275 us)
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4131): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 4131): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4131): [1] 5.onFinished: Scheduling replication attempt 5.
,I/DisplayManagerService(  820): Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  261): Set power mode=0, type=0 flinger=0xb6482000
V/ActivityManager(  820): Display changed displayId=0
D/qdhwcomposer(  261): hwc_setPowerMode: Setting mode 0 on display: 0
,I/qdhwcomposer(  261): handle_blank_event: dpy:0 panel power state: 0
,D/qdhwcomposer(  261): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl(  820): Excessive delay in setPowerMode(): 270ms
,I/DreamManagerService(  820): Entering dreamland.
,I/DreamController(  820): Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,I/PowerManagerService(  820): Dozing...
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=on
,D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=on
,E/WifiStateMachine(  820): cancelDelayedScan -> 6
,E/native  (  820): do suspend false
,I/Keyboard.Facilitator( 1215): onFinishInput()
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@26325d71}
,E/WifiStateMachine(  820): cancelDelayedScan -> 8
,E/native  (  820): do suspend true
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
,D/audio_hw_primary(  358): adev_set_parameters: enter: screen_state=off
D/mot_vr_audio_hw(  358): adev_set_parameters: screen_state=off
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.00 rxSuccessRate=0.00 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,I/art     (  820): Explicit concurrent mark sweep GC freed 38843(2MB) AllocSpace objects, 19(1152KB) LOS objects, 31% free, 34MB/50MB, paused 1.800ms total 90.249ms
,D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@26325d71}
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 83763(4MB) AllocSpace objects, 21(1388KB) LOS objects, 36% free, 28MB/44MB, paused 1.303ms total 44.631ms
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=0.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-49
E/WifiStateMachine(  820): WifiStateMachine L2Connected CMD_START_SCAN source -2 5, 8 -> obsolete
,D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Start proc 4318:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,I/ActivityManager(  820): Start proc 4335:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,W/ResourcesManager( 4335): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4335): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 4335): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProviderInstaller( 4335): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 4131): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 4131): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 4131): [1] 5.onFinished: Giving up after 6 failures.
,V/GoogleAuthProtoRequest( 4318): [465] a.<init>: mAccountName set to: thalitester@gmail.com
,I/dex2oat ( 4372): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1259068041.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads1259068041.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 4335): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 4372): dex2oat took 38.862ms (threads: 4) arena alloc=88KB java alloc=12KB native alloc=966KB free=7MB
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4318): [465] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4318): [465] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4318): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4318): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4318): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4318): 	at com.a.a.k.run(SourceFile:110)
,W/InstanceID/Rpc( 4335): Found 10011
,V/GoogleAuthProtoRequest( 4318): [466] a.<init>: mAccountName set to: thalitester@gmail.com
,I/ActivityManager(  820): Killing 3696:com.google.android.calendar/u0a37 (adj 15): empty #17
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4318): [466] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4318): [466] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4318): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4318): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4318): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4318): 	at com.a.a.k.run(SourceFile:110)
,I/ActivityManager(  820): Killing 3995:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
,I/ActivityManager(  820): Start proc 4434:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,W/GAV2    ( 4434): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 4434): Created application version: 3.6.8 (30608)
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4278): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4278): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4278): 	at jdm.a(PG:82)
E/HttpOperation( 4278): 	at jcs.o(PG:406)
E/HttpOperation( 4278): 	at jcn.a(PG:1379)
E/HttpOperation( 4278): 	at jcs.i(PG:143)
E/HttpOperation( 4278): 	at blb.a(PG:3937)
E/HttpOperation( 4278): 	at czp.a(PG:18188)
E/HttpOperation( 4278): 	at czp.a(PG:9087)
E/HttpOperation( 4278): 	at czq.run(PG:1686)
E/HttpOperation( 4278): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4278): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4278): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4278): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4278): 	at jdj.a(PG:4091)
E/HttpOperation( 4278): 	at jdj.a(PG:1125)
E/HttpOperation( 4278): 	at jdm.a(PG:77)
E/HttpOperation( 4278): 	... 12 more
E/HttpOperation( 4278): Caused by: faj: BadAuthentication
E/HttpOperation( 4278): 	at fal.a(PG:38)
E/HttpOperation( 4278): 	at jdj.a(PG:4089)
E/HttpOperation( 4278): 	... 14 more
,I/BooksSync( 4434): Starting books sync for 61035162, extras: ade
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4278): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4278): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4278): 	at jdm.a(PG:82)
E/HttpOperation( 4278): 	at jcs.o(PG:406)
E/HttpOperation( 4278): 	at jcn.a(PG:1379)
E/HttpOperation( 4278): 	at jcs.i(PG:143)
E/HttpOperation( 4278): 	at blb.a(PG:3937)
E/HttpOperation( 4278): 	at czp.a(PG:18188)
E/HttpOperation( 4278): 	at czp.a(PG:9081)
E/HttpOperation( 4278): 	at czq.run(PG:1686)
E/HttpOperation( 4278): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4278): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4278): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4278): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4278): 	at jdj.a(PG:4091)
E/HttpOperation( 4278): 	at jdj.a(PG:1125)
E/HttpOperation( 4278): 	at jdm.a(PG:77)
E/HttpOperation( 4278): 	... 12 more
E/HttpOperation( 4278): Caused by: faj: BadAuthentication
E/HttpOperation( 4278): 	at fal.a(PG:38)
E/HttpOperation( 4278): 	at jdj.a(PG:4089)
E/HttpOperation( 4278): 	... 14 more
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/BooksConfig( 4434): GmsCore Version = 7.8.99 (2134222-430)
,E/HttpOperation( 4278): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4278): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4278): 	at jdm.a(PG:82)
E/HttpOperation( 4278): 	at jcs.o(PG:406)
E/HttpOperation( 4278): 	at jcn.a(PG:1379)
E/HttpOperation( 4278): 	at jcs.i(PG:143)
E/HttpOperation( 4278): 	at hec.a(PG:42)
E/HttpOperation( 4278): 	at hee.a(PG:102)
E/HttpOperation( 4278): 	at czr.a(PG:65)
E/HttpOperation( 4278): 	at kka.a(PG:108)
E/HttpOperation( 4278): 	at czp.a(PG:19176)
E/HttpOperation( 4278): 	at czp.a(PG:9081)
E/HttpOperation( 4278): 	at czq.run(PG:1686)
E/HttpOperation( 4278): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4278): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4278): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4278): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4278): 	at jdj.a(PG:4091)
E/HttpOperation( 4278): 	at jdj.a(PG:1125)
E/HttpOperation( 4278): 	at jdm.a(PG:77)
E/HttpOperation( 4278): 	... 15 more
E/HttpOperation( 4278): Caused by: faj: BadAuthentication
E/HttpOperation( 4278): 	at fal.a(PG:38)
E/HttpOperation( 4278): 	at jdj.a(PG:4089)
E/HttpOperation( 4278): 	... 17 more
E/ExperimentLoader( 4278): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4278): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4278): 	at jdm.a(PG:82)
E/ExperimentLoader( 4278): 	at jcs.o(PG:406)
E/ExperimentLoader( 4278): 	at jcn.a(PG:1379)
E/ExperimentLoader( 4278): 	at jcs.i(PG:143)
E/ExperimentLoader( 4278): 	at hec.a(PG:42)
E/ExperimentLoader( 4278): 	at hee.a(PG:102)
E/ExperimentLoader( 4278): 	at czr.a(PG:65)
E/ExperimentLoader( 4278): 	at kka.a(PG:108)
E/ExperimentLoader( 4278): 	at czp.a(PG:19176)
E/ExperimentLoader( 4278): 	at czp.a(PG:9081)
E/ExperimentLoader( 4278): 	at czq.run(PG:1686)
E/ExperimentLoader( 4278): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/ExperimentLoader( 4278): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4278): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4278): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4278): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4278): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4278): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4278): 	at jdj.a(PG:1125)
E/ExperimentLoader( 4278): 	at jdm.a(PG:77)
E/ExperimentLoader( 4278): 	... 15 more
E/ExperimentLoader( 4278): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4278): 	at fal.a(PG:38)
E/ExperimentLoader( 4278): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4278): 	... 17 more
,I/art     (  820): Explicit concurrent mark sweep GC freed 30275(1337KB) AllocSpace objects, 3(236KB) LOS objects, 32% free, 33MB/49MB, paused 1.647ms total 85.532ms
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 133667, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  820): Start proc 4471:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 25329(1551KB) AllocSpace objects, 19(2MB) LOS objects, 37% free, 26MB/42MB, paused 959us total 24.897ms
,E/BooksAccountManager( 4434): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4434): Soft error
E/BooksSync( 4434): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4434): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 4434): Sync error
E/BooksSync( 4434): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4434): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4434): Finished books sync,
,I/ActivityManager(  820): Killing 3955:com.google.android.apps.cloudprint:sync/u0a41 (adj 15): empty #17
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 166032, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,V/KeepSync( 4471): Connecting to GoogleApiClient
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1750): Handling authorization failure
E/ClientConnectionOperation( 1750): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249),
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1750): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1750): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1750): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1750): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1750): 	,... 7 more
,V/KeepSync( 4471): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4471): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4471): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4471): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,E/KeepSync( 4471): IOException
E/KeepSync( 4471): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4471): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4471): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4471): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4471): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4471): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4471): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4471): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4471): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4471): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4471): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4471): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4471): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4471): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4471): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4471): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4471): 	... 10 more
W/KeepSync( 4471): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 167249, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager(  820): Killing 4026:com.google.android.configupdater/u0a42 (adj 15): empty #17
,I/GAV2    ( 4434): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 4131): [429] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 4131): [429] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,I/EventLogService( 1750): Opted in for usage reporting
I/EventLogService( 1750): Aggregate from 1453981613497 (log), 1453979880209 (data)
,W/EventLogAggregator( 1750): Unknown tag: snet_gcore
,W/EventLogAggregator( 1750): Unknown tag: snet_launch_service
,I/ServiceDumpSys( 1750): dumping service [account]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1215): run()
I/Keyboard.Facilitator( 1215): flushDynamicLanguageModels()
,I/ConfigService( 1477): onCreate
,I/ConfigService( 1477): onDestroy
,D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4278): [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 4278): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4278): 	at jdm.a(PG:82),
E/HttpOperation( 4278): 	at jcs.o(PG:406)
E/HttpOperation( 4278): 	at jcn.a(PG:1379)
E/HttpOperation( 4278): 	at jcs.i(PG:143)
E/HttpOperation( 4278): ,	at blb.a(PG:3937)
E/HttpOperation( 4278): 	at czp.a(PG:18188)
E/HttpOperation( 4278): 	,at czp.a(PG:9081)
E/HttpOperation( 4278): 	at czq.run(PG:1686)
,E/HttpOperation( 4278): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4278): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4278): 	at java.lang.Thread.run(Thread.java:818),
E/HttpOperation( 4278): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4278): 	at jdj.a(PG:4091)
E/HttpOperation( 4278): 	at jdj.a(PG:1125)
,E/HttpOperation( 4278): 	at jdm.a(PG:77)
E/HttpOperation( 4278): 	... 12 more
E/HttpOperation( 4278): Caused by: faj: BadAuthentication
E/HttpOperation( 4278): ,	at fal.a(PG:38)
E/HttpOperation( 4278): 	at jdj.a(PG:4089)
E/HttpOperation( 4278): 	... 14 more
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/HttpOperation( 4278): [getmobileexperiments] Unexpected exception
E/HttpOperation( 4278): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 4278): 	at jdm.a(PG:82)
E/HttpOperation( 4278): 	at jcs.o(PG:406)
E/HttpOperation( 4278): 	at jcn.a(PG:1379)
E/HttpOperation( 4278): 	at jcs.i(PG:143)
E/HttpOperation( 4278): 	at hec.a(PG:42)
E/HttpOperation( 4278): 	at hee.a(PG:102)
E/HttpOperation( 4278): 	at czr.a(PG:65)
E/HttpOperation( 4278): 	at kka.a(PG:108)
E/HttpOperation( 4278): 	at czp.a(PG:19176)
E/HttpOperation( 4278): 	at czp.a(PG:9081)
E/HttpOperation( 4278): 	at czq.run(PG:1686)
E/HttpOperation( 4278): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/HttpOperation( 4278): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/HttpOperation( 4278): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/HttpOperation( 4278): 	at java.lang.Thread.run(Thread.java:818)
E/HttpOperation( 4278): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/HttpOperation( 4278): 	at jdj.a(PG:4091)
E/HttpOperation( 4278): 	at jdj.a(PG:1125)
E/HttpOperation( 4278): 	at jdm.a(PG:77)
E/HttpOperation( 4278): 	... 15 more
E/HttpOperation( 4278): Caused by: faj: BadAuthentication
E/HttpOperation( 4278): 	at fal.a(PG:38)
E/HttpOperation( 4278): 	at jdj.a(PG:4089)
E/HttpOperation( 4278): 	... 17 more
,E/ExperimentLoader( 4278): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4278): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 4278): 	at jdm.a(PG:82)
E/ExperimentLoader( 4278): 	at jcs.o(PG:406)
E/ExperimentLoader( 4278): ,	at jcn.a(PG:1379)
E/ExperimentLoader( 4278): 	at jcs.i(PG:143)
E/ExperimentLoader( 4278): 	at hec.a(PG:42)
E/ExperimentLoader( 4278): 	at hee.a(PG:102)
,E/ExperimentLoader( 4278): 	at czr.a(PG:65)
E/ExperimentLoader( 4278): 	at kka.a(PG:108)
E/ExperimentLoader( 4278): 	at czp.a(PG:19176)
E/ExperimentLoader( 4278): 	at czp.a(PG:9081)
E/ExperimentLoader( 4278): 	at czq.run(PG:1686)
E/ExperimentLoader( 4278): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422),
E/ExperimentLoader( 4278): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ExperimentLoader( 4278): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ExperimentLoader( 4278): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ExperimentLoader( 4278): 	at java.lang.Thread.run(Thread.java:818)
E/ExperimentLoader( 4278): Caused by: android.accounts.AuthenticatorException: Recoverable error
E/ExperimentLoader( 4278): 	at jdj.a(PG:4091)
E/ExperimentLoader( 4278): ,	at jdj.a(PG:1125)
E/ExperimentLoader( 4278): 	at jdm.a(PG:77)
E/ExperimentLoader( 4278): 	... 15 more
E/ExperimentLoader( 4278): Caused by: faj: BadAuthentication
E/ExperimentLoader( 4278): 	at fal.a(PG:38)
E/ExperimentLoader( 4278): 	at jdj.a(PG:4089)
E/ExperimentLoader( 4278): 	... 17 more
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 226131, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 18140(1025KB) AllocSpace objects, 3(330KB) LOS objects, 37% free, 26MB/42MB, paused 1.337ms total 64.411ms
,V/GoogleAuthProtoRequest( 4318): [467] a.<init>: mAccountName set to: thalitester@gmail.com
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ExperimentUpdateService( 4318): [467] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,W/ExperimentUpdateService( 4318): [467] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): 	at com.a.a.a.k.a(SourceFile:117)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.k.get(SourceFile:97)
W/ExperimentUpdateService( 4318): 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
W/ExperimentUpdateService( 4318): 	at com.google.android.gms.gcm.c.run(Unknown Source)
W/ExperimentUpdateService( 4318): Caused by: com.a.a.a: User needs to (re)enter credentials.
W/ExperimentUpdateService( 4318): 	at com.google.android.flib.a.a.a(SourceFile:167)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.g.a(SourceFile:79)
W/ExperimentUpdateService( 4318): 	at com.a.a.a.a.a(SourceFile:93)
W/ExperimentUpdateService( 4318): 	at com.a.a.k.run(SourceFile:110)
,D/ConnectivityService(  820): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10011
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Forcing reevaluation
D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Checking http://connectivitycheck.android.com/generate_204 on "NG7005g"
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jan 2016 11:49:04 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453981744892], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453981744877]}
,D/NetworkMonitor/NetworkAgentInfo [WIFI () - 100](  820): Validated
D/ConnectivityService(  820): setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
,D/ConnectivityService(  820): Validated NetworkAgentInfo [WIFI () - 100],
,I/art     ( 1708): Explicit concurrent mark sweep GC freed 12487(697KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 1.418ms total 68.566ms
,E/DataBuffer( 1708): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@26a7828d)
,V/Herrevad( 1750): NQAS connected
,D/GCM     ( 1477): Connected
,I/art     (  820): Explicit concurrent mark sweep GC freed 27264(1271KB) AllocSpace objects, 5(80KB) LOS objects, 32% free, 33MB/49MB, paused 1.783ms total 101.694ms
,I/GCM     ( 1750): Message from null null
E/GCM     ( 1750): Dropping message from null
,D/GCM     ( 1477): Message class com.google.f.a.a.p
,I/BooksSync( 4434): Starting books sync for 61035162, extras: ade
,V/KeepSync( 4471): Connecting to GoogleApiClient
,I/BooksConfig( 4434): GmsCore Version = 7.8.99 (2134222-430)
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ClientConnectionOperation( 1750): Handling authorization failure
E/ClientConnectionOperation( 1750): com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClientConnectionOperation( 1750): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClientConnectionOperation( 1750): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClientConnectionOperation( 1750): 	at java.lang.Thread.run(Thread.java:818)
E/ClientConnectionOperation( 1750): Caused by: com.google.android.gms.auth.ad: BadAuthentication
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
E/ClientConnectionOperation( 1750): 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
E/ClientConnectionOperation( 1750): 	... 7 more
,V/KeepSync( 4471): GoogleApiClient failed to connect with error code: 4
,E/SQLiteLog( 4471): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4471): (284) automatic index on blob_node(is_deleted)
,E/SQLiteLog( 4471): (284) automatic index on blob_node(is_deleted)
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 4434): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 4434): Soft error
E/BooksSync( 4434): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4434): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 4434): Sync error
E/BooksSync( 4434): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 4434): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 4434): Finished books sync
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 256068, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/GLSUser ( 1477): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,I/GLSUser ( 1477): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1477): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1477): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1477): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/KeepSync( 4471): IOException
E/KeepSync( 4471): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/KeepSync( 4471): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
E/KeepSync( 4471): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
E/KeepSync( 4471): 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
E/KeepSync( 4471): 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
E/KeepSync( 4471): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
E/KeepSync( 4471): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
E/KeepSync( 4471): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
E/KeepSync( 4471): 	at com.google.android.keep.util.m.a(SourceFile:207)
E/KeepSync( 4471): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
E/KeepSync( 4471): 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
E/KeepSync( 4471): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/KeepSync( 4471): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/KeepSync( 4471): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/KeepSync( 4471): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/KeepSync( 4471): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
E/KeepSync( 4471): 	... 10 more
,W/KeepSync( 4471): Sync result 2
,D/SyncManager(  820): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 259827, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 3190): Disconnected process message: 10, size: 0
,I/jxcore-log( 3130): --= Surplus to requirements =--
I/jxcore-log( 3130): 
I/jxcore-log( 3130): ****TEST TOOK:  ms ****
I/jxcore-log( 3130): 
I/jxcore-log( 3130): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3130): 
,D/AndroidRuntime( 4557): >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,D/AndroidRuntime( 4557): CheckJNI is OFF
,D/AndroidRuntime( 4557): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=-1: uninstall pkg
I/ActivityManager(  820): Killing 3130:com.test.thalitest/u0a265 (adj 0): stop com.test.thalitest
,W/PackageSettings(  820): Skipping PackageSetting{2b5a22b0 com.example.hello/10273} due to missing metadata
,E/libprocessgroup(  820): failed to kill 1 processes for processgroup 3130
,W/ActivityManager(  820): Force removing ActivityRecord{3c46145f u0 com.test.thalitest/.MainActivity t28}: app died, no saved state
E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
,V/ActivityManager(  820): Display changed displayId=0
D/WifiService(  820): Client connection lost with reason: 4
,W/DisplayManagerService(  820): Failed to notify process 3130 that displays changed, assuming it died.
W/DisplayManagerService(  820): android.os.DeadObjectException
W/DisplayManagerService(  820): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService(  820): 	at android.os.BinderProxy.transact(Binder.java:496)
W/DisplayManagerService(  820): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
W/DisplayManagerService(  820): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
W/DisplayManagerService(  820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService(  820): 	at android.os.Looper.loop(Looper.java:135)
W/DisplayManagerService(  820): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService(  820): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/ActivityManager(  820): Force stopping com.test.thalitest appid=10265 user=0: pkg removed
,D/BuaReceiver( 2921): ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
I/Keyboard.Facilitator( 1215): resetDictionaries() : en_US
D/TaskPersister(  820): removeObsoleteFile: deleting file=28_task.xml
,I/InputReader(  820): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1215): run()
I/Decoder ( 1215): createOrResetDecoder
,I/art     ( 1068): Explicit concurrent mark sweep GC freed 55727(2MB) AllocSpace objects, 0(0B) LOS objects, 18% free, 72MB/88MB, paused 741us total 56.436ms
,I/ConfigService( 1477): onCreate
,D/VoicemailCleanupService( 4251): Cleaning up data for package: com.test.thalitest
,D/JobSchedulerService(  820): Receieved: android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  820): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/ActivityManager(  820): Start proc 4575:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
W/InputMethodManagerService(  820): Got RemoteException sending setActive(false) notification to pid 3130 uid 10265
I/Keyboard.Facilitator( 1215): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): run()
,I/art     ( 1279): Explicit concurrent mark sweep GC freed 11833(665KB) AllocSpace objects, 12(1408KB) LOS objects, 31% free, 35MB/51MB, paused 579us total 23.317ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1215): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1215): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1215): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1215): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1215): run()
I/StatsUtilsManager( 1215): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1215): shouldRecordStats() = Too Soon
,I/art     (  820): Explicit concurrent mark sweep GC freed 22614(1299KB) AllocSpace objects, 6(284KB) LOS objects, 32% free, 33MB/49MB, paused 1.385ms total 133.399ms
,I/art     (  820): WaitForGcToComplete blocked for 91.333ms for cause Explicit
,I/ActivityManager(  820): Start proc 4603:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,W/ContextImpl( 4603): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,E/NetworkScheduler.SchedulerReceiver( 1477): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1477): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/art     (  820): Explicit concurrent mark sweep GC freed 4718(249KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 33MB/49MB, paused 1.769ms total 62.518ms
,I/art     ( 4557): System.exit called, status: 0
I/AndroidRuntime( 4557): VM exiting with result code 0.
,I/ActivityManager(  820): Killing 3977:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,D/Launcher.Workspace( 1279): 11683562 - stripEmptyScreens()
D/Launcher.Workspace( 1279): 11683562 - stripEmptyScreens()
,E/SQLiteLog( 1279): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/PackageBroadcastService( 1750): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1750): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1750): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1750): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 1750): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/AccountUtils( 1750): Clearing selected account for com.test.thalitest
,--------- beginning of crash
E/AndroidRuntime( 1750): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1750): Process: com.google.android.gms, PID: 1750
E/AndroidRuntime( 1750): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1750): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1750): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1750): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1750): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1750): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1750): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1750): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1750): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1750): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1750): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:312)
E/AndroidRuntime( 1750): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1750): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
E/AndroidRuntime( 1750): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1750): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
E/AndroidRuntime( 1750): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1750): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1750): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1750): 	at java.lang.Thread.run(Thread.java:818)
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
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
,E/SQLiteLog( 1750): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1750): disk I/O error (code 3850)
E/DriveAsyncService( 1750): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1750): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1750): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1750): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1750): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1750): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1750): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1750): 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
E/DriveAsyncService( 1750): 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
E/DriveAsyncService( 1750): 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
E/DriveAsyncService( 1750): 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
E/DriveAsyncService( 1750): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/DriveAsyncService( 1750): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1750): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1750): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager(  820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/OpenGLRenderer(  820): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   (  820): Validating map...
,I/LocationSettingsChecker( 1750): Removing dialog suppression flag for package com.test.thalitest
,W/LocationOracleImpl( 4077): Best location was null
,I/VS.Container( 4077): create_recognizer
,E/SQLiteDatabase( 1750): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1750): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1750): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1750): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 1750): Couldn't open phenotype.db for writing (will try read-only):,
E/SQLiteOpenHelper( 1750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463),
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
,E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187),
E/SQLiteOpenHelper( 1750): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteOpenHelper( 1750): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1750): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1750): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1750): Opened phenotype.db in read-only mode,
,E/SQLiteDatabase( 1750): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1750): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1750): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1750): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1750): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1750): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1750): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1750): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1750): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1750): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1750): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1750): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1750): 	at com.google.android.g,ms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1750): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1750): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1750): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1750): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1750): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1750): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1750): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/OpenGLRenderer(  820): Initialized EGL, version 1.4
W/SQLiteOpenHelper( 1750): Opened metrics.db in read-only mode
D/GOOGLEHELP_CompatibleDatabase( 1750): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1750): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1750): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/GOOGLEHELP_CompatibleDatabase( 1750): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1750): Sending signal. PID: 1750 SIG: 9
D/OpenGLRenderer(  820): Enabling debug mode 0
,E/Search.SharedPreferencesProto( 4077): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/SQLiteDatabase( 4077): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/jar_store.db'.
E/SQLiteDatabase( 4077): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4077): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteDatabase( 4077): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4077): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,E/SQLiteOpenHelper( 4077): Couldn't open jar_store.db for writing (will try read-only):
E/SQLiteOpenHelper( 4077): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4077): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.k.pj(JarStore.java:893)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.g.pe(JarStore.java:1036)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.f.pb(JarStore.java:173)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.r.gF(VelourReleaseState.java:325)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.r.zd(VelourReleaseState.java:128)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.r.aJp(VelourReleaseState.java:202)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.r.a(VelourReleaseState.java:44)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.velour.s.iq(VelourReleaseState.java:371)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.shared.velour.j.auD(JarObjectLoader.java:185)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.shared.velour.j.call(JarObjectLoader.java:137)
E/SQLiteOpenHelper( 4077): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4077): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4077): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4077): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/SQLiteOpenHelper( 4077): Opened jar_store.db in read-only mode
,W/Launcher( 1279): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3d7c8dbf new=com.google.android.velvet.VelvetApplication@3d7c8dbf
,E/SQLiteLog( 1279): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/WifiService(  820): Client connection lost with reason: 4
,I/HotwordRecognitionRnr( 4077): Starting hotword detection.
,I/ActivityManager(  820): Start proc 4656:com.google.android.apps.docs/u0a46 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/UpdateIcingCorporaServi( 4077): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  820): Process com.google.android.gms (pid 1750) has died
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
,W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 11000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  820): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 11000ms
I/MicrophoneInputStream( 4077): mic_starting com.google.android.apps.gsa.speech.audio.u@1255491a
,I/AudioFlinger(  358): AudioFlinger's thread 0xb40ce000 ready to run
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/MicrophoneInputStream( 4077): mic_started com.google.android.apps.gsa.speech.audio.u@1255491a
,E/SQLiteLog( 4077): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/audio_hw_primary(  358): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  358): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
E/ACDB-LOADER(  358): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  358): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  358): enable_audio_route: apply and update mixer path: audio-record
,W/FileUtils( 4077): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 4077): Failed to write new file: loracle.new
,E/Search.SharedPreferencesProto( 4077): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,I/ActivityManager(  820): Start proc 4677:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,E/SharedPreferencesImpl( 4077): Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
E/AndroidRuntime( 4077): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4077): Process: com.google.android.googlequicksearchbox:search, PID: 4077
E/AndroidRuntime( 4077): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 4077): 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:85)
E/AndroidRuntime( 4077): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:623)
E/AndroidRuntime( 4077): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AndroidRuntime( 4077): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 4077): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 4077): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 4077): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 4077): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 4077): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 4077): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 4077): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4077): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4077): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
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
,I/HotwordDetector( 4077): Closing mic
,I/MicrophoneInputStream( 4077): mic_close com.google.android.apps.gsa.speech.audio.u@1255491a
,W/FileUtils( 4077): Failed to chmod(/data/data/com.google.android.googlequicksearchbox/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/FileBytesWriter( 4077): Failed to write new file: loracle.new
,I/OpenGLRenderer(  820): Initialized EGL, version 1.4
,E/Search.SharedPreferencesProto( 4077): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,D/WifiService(  820): acquireWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3d97691b}
,W/InputMethodManagerService(  820): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1602ab8 attribute=null, token = android.os.BinderProxy@320be882
,W/TRUiThreadExecutor( 4077): Task does not implement UiTask: com.google.common.g.a.p@a8ac035
,E/WifiStateMachine(  820): WifiStateMachine CMD_START_SCAN source 10011 txSuccessRate=0.50 rxSuccessRate=0.50 targetRoamBSSID=any RSSI=-49
,D/audio_hw_primary(  358): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  358): disable_snd_device: snd_device(55: voice-rec-mic)
,I/SoundTriggerHwService::Module(  358): void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,I/HotwordRecognitionRnr( 4077): Stopping hotword detection.
I/HotwordRecognitionRnr( 4077): Hotword detection finished
,I/ActivityManager(  820): Start proc 4704:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,I/art     (  369): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 201us total 10.576ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 215us total 10.718ms
,I/art     (  369): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 797us total 10.095ms
,W/art     ( 4077): Suspending all threads took: 12.434ms
,W/ResourcesManager( 4704): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4704): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/BroadcastQueue(  820): Skipping deliver [background] BroadcastRecord{2ba20494 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{33a19ea6 4077 com.google.android.googlequicksearchbox:search/10028/u0 remote:31d3a001}: process crashing
,W/LocationOracleImpl( 4077): Best location was null
,I/MultiDex( 4704): VM with version 2.1.0 has multidex support
I/MultiDex( 4704): install
I/MultiDex( 4704): VM has multidex support, MultiDex support library is disabled.
,I/WebViewFactory( 4077): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4077): Time to load native libraries: 1 ms (timestamps 9512-9513)
I/LibraryLoader( 4077): Expected native library version number "",actual native library version number ""
,W/art     ( 4077): Attempt to remove local handle scope entry from IRT, ignoring
,E/SQLiteDatabase( 4704): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4704): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1181)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.security.snet.ab.a(SourceFile:1200)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4704): Failed to open database '/data/data/com.google.android.gms/databases/snet_safe_browsing.db'.
E/SQLiteDatabase( 4704): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getWr,itableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.security.snet.aa.b(SourceFile:826)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.security.snet.aa.a(SourceFile:847)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.security.snet.w.doInBackground(SourceFile:133)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4704): 	at java.lang.Thread.run(Thread.java:818)
V/JNIHelp ( 4704): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ProviderInstaller( 4704): Installed default security provider GmsCore_OpenSSL
,W/NativeLibraryUtils( 4704): Failed to open lock file
W/NativeLibraryUtils( 4704): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4704): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/NativeLibraryUtils( 4704): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:117)
W/NativeLibraryUtils( 4704): 	at com.google.android.gms.common.util.ax.a(SourceFile:305)
W/NativeLibraryUtils( 4704): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 4704): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 4704): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 4704): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/NativeLibraryUtils( 4704): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/NativeLibraryUtils( 4704): 	... 3 more
,W/art     ( 4077): Attempt to remove local handle scope entry from IRT, ignoring
,D/WifiService(  820): New client listening to asynchronous messages
,I/GAv4-SVC( 4704): Google Analytics 7.8.99 is starting up.
,W/BroadcastQueue(  820): Skipping deliver [background] BroadcastRecord{2ec1522c u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{2d73dc7e 4077 com.google.android.googlequicksearchbox:search/10028/u0 remote:1a34e39}: process crashing
W/BroadcastQueue(  820): Skipping deliver [background] BroadcastRecord{96194f5 u-1 android.net.wifi.RSSI_CHANGED} to ReceiverList{2d73dc7e 4077 com.google.android.googlequicksearchbox:search/10028/u0 remote:1a34e39}: process crashing
,E/SQLiteDatabase( 4704): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4704): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:884)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.e.k.run(SourceFile:388)
,E/GAv4-SVC( 4704): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 4704): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4704): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4704): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.w.getWritableDatabase(SourceFile:897)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.o(SourceFile:812)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.a(SourceFile:630)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.q(SourceFile:264)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.v.e(SourceFile:274)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.y.e(SourceFile:885)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.y.b(SourceFile:258)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.analytics.internal.ab.run(SourceFile:152)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4704): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.e.k.run(SourceFile:388)
,E/SQLiteDatabase( 4704): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 4704): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteDatabase( 4704): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4704): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4704): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 4704): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4704): 	at java.lang.Thread.run(Thread.java:818)
E/GAv4-SVC( 4704): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4704): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 4704): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4704): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:419)
E/SQLiteOpenHelper( 4704): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteOpenHelper( 4704): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteOpenHelper( 4704): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 4704): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 4704): 	at com.google.android.gms.reminders.a.a.a(SourceFile:71)
E/SQLiteOpenHelper( 4704): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:39)
E/SQLiteOpenHelper( 4704): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteOpenHelper( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 4704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 4704): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 4704): Opened reminders.db in read-only mode
W/GAv4-SVC( 4704): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/GAv4-SVC( 4704): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 4704): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4704): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 4704): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4704): 	at java.lang.Thread.run(Thread.java:818)
,E/SharedPreferencesImpl( 4704): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4704): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4704): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4704): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/AndroidRuntime( 4704): FATAL EXCEPTION: AsyncTask #3
E/AndroidRuntime( 4704): Process: com.google.android.gms, PID: 4704
E/AndroidRuntime( 4704): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4704): 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
E/AndroidRuntime( 4704): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4704): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4704): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4704): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4704): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4704): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 4704): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4704): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4704): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4704): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4704): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
E/AndroidRuntime( 4704): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 4704): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 4704): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/AndroidRuntime( 4704): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4704): 	... 4 more
D/GFEEDBACK_SendErrorReportOperation( 4704): Error doing instant send: java.,io.IOException: failed to create reports directory
E/GFEEDBACK_SendErrorReportOperation( 4704): Error saving report: java.io.IOException: failed to create reports directory
E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
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
I/GAv4    ( 4656): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4656):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4656):   adb logcat -s GAv4
W/GAv4    ( 4656): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4656): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4656): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4656): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,E/SQLiteDatabase( 4656): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4656): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4656): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4656): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4656): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4656): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 4656): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4656): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4656): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4656): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4656): 	at aen.run(PG:536)
,E/SQLiteDatabase( 4656): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4656): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4656): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4656): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4656): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4656): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4656): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4656): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4656): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4656): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4656): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4656): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4656): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4656): 	at aej.c(PG:139)
E/SQLiteDatabase( 4656): 	at aej.b(PG:398)
E/SQLiteDatabase( 4656): 	at agf.f(PG:417)
E/SQLiteDatabase( 4656): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4656): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4656): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4656): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4656): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4656): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4656): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4656): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4656): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4656): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4656): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4656): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4656): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4656): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4656): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4656): 	at java.lang.Thread.run(Thread.java:818)
,W/GAv4    ( 4656): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4656): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4656): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4656): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4656): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4656): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4656): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4656): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4656): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
,E/SharedPreferencesImpl( 4656): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4656): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4656): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4656): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4656): 	at aen.run(PG:536)
,W/ResourcesManager( 4656): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4656): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  820): Start proc 4767:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver
,I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,V/WindowManager(  820): addAppToken: AppWindowToken{2f8c1063 token=Token{334ffe92 ActivityRecord{1d391c1d u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}}} to stack=1 task=29 at 0
,I/Process ( 4656): Sending signal. PID: 4656 SIG: 9
,E/lowmemorykiller(  258): Error writing /proc/4656/oom_score_adj; errno=22
,E/JavaBinder(  820): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  820): Exception when starting activity com.google.android.apps.docs/.app.ErrorNotificationActivity
W/ActivityManager(  820): android.os.TransactionTooLargeException
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
,E/native  ( 1215): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1215): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,I/ActivityManager(  820): Start proc 4784:com.google.android.apps.docs/u0a46 for activity com.google.android.apps.docs/.app.ErrorNotificationActivity
,W/ActivityManager(  820): Spurious death for ProcessRecord{3e82a565 4784:com.google.android.apps.docs/u0a46}, curProc for 4656: null
,W/OpenGLRenderer( 1279): Incorrectly called buildLayer on View: ew, destroying layer...
,E/native  ( 1215): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
E/native  ( 1215): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,E/native  ( 1215): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1215): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1215): dynamic-lm.cc:266 Cannot open fd for /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
E/native  ( 1215): dynamic-lm.cc:257 Cannot write DynamicLm to /data/data/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,E/SQLiteDatabase( 4767): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4767): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4767): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 4767): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 4767): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/SQLiteDatabase( 4767): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/SQLiteDatabase( 4767): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 4767): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/SQLiteDatabase( 4767): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/SQLiteDatabase( 4767): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/SQLiteDatabase( 4767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4767): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 4767): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/SQLiteDatabase( 4767): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4767): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/SQLiteDatabase( 4767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
,I/ActivityManager(  820): Killing 3678:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,D/AndroidRuntime( 4767): Shutting down VM
,E/AndroidRuntime( 4767): FATAL EXCEPTION: main
E/AndroidRuntime( 4767): Process: com.android.documentsui, PID: 4767
E/AndroidRuntime( 4767): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4767): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
E/AndroidRuntime( 4767): 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
E/AndroidRuntime( 4767): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
E/AndroidRuntime( 4767): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4767): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 4767): 	at android.app.ActivityThread.main(ActivityThread.java:5254)
E/AndroidRuntime( 4767): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4767): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4767): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
E/AndroidRuntime( 4767): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
E/AndroidRuntime( 4767): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 4767): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AndroidRuntime( 4767): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4767): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4767): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 4767): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 4767): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/AndroidRuntime( 4767): 	at android.content.ContentResolver.call(ContentResolver.java:1372)
E/AndroidRuntime( 4767): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 4767): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
E/AndroidRuntime( 4767): 	... 9 more
,E/Search.SharedPreferencesProto( 4077): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
E/Search.SharedPreferencesProto( 4077): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/DropBoxManagerService(  820): Can't write: system_app_crash
E/DropBoxManagerService(  820): java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  820): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  820): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  820): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  820): 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
E/DropBoxManagerService(  820): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  820): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  820): ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  820): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  820): 	... 5 more
,I/ActivityManager(  820): Killing 3655:com.google.android.gms.unstable/u0a11 (adj 15): empty #17
,D/GCM     ( 1477): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  820): Start proc 4809:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,I/art     ( 1477): Explicit concurrent mark sweep GC freed 23880(1298KB) AllocSpace objects, 7(394KB) LOS objects, 37% free, 26MB/42MB, paused 1.936ms total 43.582ms
,I/ActivityManager(  820): Killing 3932:com.google.android.music:main/u0a66 (adj 15): empty #17
,I/GAv4    ( 4784): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4784):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4784):   adb logcat -s GAv4
,I/art     (  820): Explicit concurrent mark sweep GC freed 18732(1043KB) AllocSpace objects, 2(220KB) LOS objects, 31% free, 34MB/50MB, paused 1.557ms total 86.965ms
,D/ExternalStorage( 4809): After updating volumes, found 1 active roots
,D/AuthorizationBluetoothService( 1477): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/GAv4    ( 4784): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/GmsCoreStatsServiceLauncher( 4704): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4784): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4784): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4784): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4784): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4784): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4784): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4784): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4784): Opening the database failed, dropping the table and recreating it
,E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4784): Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4784): 	at fdw$a.getWritableDatabase(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdw.g(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdw.a(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdw.e(Unknown Source)
E/SQLiteDatabase( 4784): 	at fdy.b(Unknown Source)
E/SQLiteDatabase( 4784): 	at feb.run(Unknown Source)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4784): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 4784): 	at gir$c.run(Unknown Source)
E/GAv4    ( 4784): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 4784): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/GAv4    ( 4784): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 4784): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,D/WearableService( 3876): callingUid 10011, callindPid: 3876
,E/MDM     ( 1708): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/SQLiteDatabase( 4784): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4784): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4784): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4784): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4784): 	at aen.run(PG:536)
,D/LocationInitializer( 4704): Restart initialization of location
,E/SQLiteDatabase( 4784): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4784): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4784): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4784): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4784): 	at aej.c(PG:139)
E/SQLiteDatabase( 4784): 	at aej.b(PG:398)
E/SQLiteDatabase( 4784): 	at agf.f(PG:417)
E/SQLiteDatabase( 4784): 	at oe.run(PG:1112)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4784): 	at java.lang.Thread.run(Thread.java:818)
,E/AbstractDatabaseInstance( 4784): Failed to delete from CachedSearch133
E/AbstractDatabaseInstance( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AbstractDatabaseInstance( 4784): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4784): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4784): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4784): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4784): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4784): 	at aej.b(PG:398)
E/AbstractDatabaseInstance( 4784): 	at agf.f(PG:417)
E/AbstractDatabaseInstance( 4784): 	at oe.run(PG:1112)
E/AbstractDatabaseInstance( 4784): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/AbstractDatabaseInstance( 4784): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AbstractDatabaseInstance( 4784): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AbstractDatabaseInstance( 4784): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AbstractDatabaseInstance( 4784): 	at java.lang.Thread.run(Thread.java:818)
,W/ResourcesManager( 4784): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4784): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/SQLiteDatabase( 1477): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1477): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1477): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 1477): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1477): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1477): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteDatabase( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteDatabase( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteDatabase( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteDatabase( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 1477): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1477): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1477): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteOpenHelper( 1477): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1477): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 1477): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1477): 	at android.databa,se.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:99)
E/SQLiteOpenHelper( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/SQLiteOpenHelper( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/SQLiteOpenHelper( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/SQLiteOpenHelper( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 1477): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1477): Opened phenotype.db in read-only mode
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ErrorNotificationActivity( 4784): Google Drive has stopped unexpectedly. Please provide additional details to help us diagnose the issue.
,E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
,D/OpenGLRenderer( 4784): Use EGL_SWAP_BEHAVIOR_PRESERVED: true
D/Atlas   ( 4784): Validating map...
V/WindowManager(  820): Adding window Window{1f6b1d97 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 10 (after Window{675cb93 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
V/JNIHelp ( 4784): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/WindowManager(  820): Adding window Window{e260f6d u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity} at 2 of 11 (before Window{1f6b1d97 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity})
,I/ProviderInstaller( 4784): Installed default security provider GmsCore_OpenSSL
,W/GAv4    ( 4784): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4784): Job execution failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 4784): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4784): 	,at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4784): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4784): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4784): 	at aej.c(PG:139)
E/SQLiteDatabase( 4784): 	at aej.a(PG:358)
E/SQLiteDatabase( 4784): 	at aej.a(PG:345)
E/SQLiteDatabase( 4784): 	at agf.d(PG:281)
E/SQLiteDatabase( 4784): 	at agf.b(PG:312)
E/SQLiteDatabase( 4784): 	at agf.a(PG:221)
E/SQLiteDatabase( 4784): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/SQLiteDatabase( 4784): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/SQLiteDatabase( 4784): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/SQLiteDatabase( 4784): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/SQLiteDatabase( 4784): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4784): 	at android.os.Binder.execTransact(Binder.java:446)
E/AbstractDatabaseInstance( 4784): Failed to query Account133 object
E/AbstractDatabaseInstance( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
,E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AbstractDatabaseInstance( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/AbstractDatabaseInstance( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AbstractDatabaseInstance( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AbstractDatabaseInstance( 4784): 	at aev.getWritableDatabase(PG:238)
E/AbstractDatabaseInstance( 4784): 	at ael.a(PG:1521)
E/AbstractDatabaseInstance( 4784): 	at hix$a.a(PG:125)
E/AbstractDatabaseInstance( 4784): 	at aej.c(PG:139)
E/AbstractDatabaseInstance( 4784): 	at aej.a(PG:358)
E/AbstractDatabaseInstance( 4784): 	at aej.a(PG:345)
E/AbstractDatabaseInstance( 4784): 	at agf.d(PG:281)
E/AbstractDatabaseInstance( 4784): 	at agf.b(PG:312)
E/AbstractDatabaseInstance( 4784): 	at agf.a(PG:221)
E/AbstractDatabaseInstance( 4784): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/AbstractDatabaseInstance( 4784): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/AbstractDatabaseInstance( 4784): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/AbstractDatabaseInstance( 4784): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/AbstractDatabaseInstance( 4784): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/AbstractDatabaseInstance( 4784): 	at android.os.Binder.execTransact(Binder.java:446)
,E/DatabaseUtils( 4784): Writing exception to parcel
E/DatabaseUtils( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/DatabaseUtils( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/DatabaseUtils( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/DatabaseUtils( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/DatabaseUtils( 4784): 	at aev.getWritableDatabase(PG:238)
E/DatabaseUtils( 4784): 	at ael.a(PG:1521)
E/DatabaseUtils( 4784): 	at hix$a.a(PG:125)
E/DatabaseUtils( 4784): 	at aej.c(PG:139)
E/DatabaseUtils( 4784): 	at aej.a(PG:358)
E/DatabaseUtils( 4784): 	at aej.a(PG:345)
E/DatabaseUtils( 4784): 	at agf.d(PG:281)
E/DatabaseUtils( 4784): 	at agf.b(PG:312)
E/DatabaseUtils( 4784): 	at agf.a(PG:221)
E/DatabaseUtils( 4784): 	at com.google.android.apps.docs.storagebackend.StorageBackendContentProvider.queryRoots(PG:291)
E/DatabaseUtils( 4784): 	at android.provider.DocumentsProvider.query(DocumentsProvider.java:480)
E/DatabaseUtils( 4784): 	at android.content.ContentProvider.query(ContentProvider.java:966)
E/DatabaseUtils( 4784): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:211)
E/DatabaseUtils( 4784): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 4784): 	at android.os.Binder.execTransact(Binder.java:446)
,W/GAv4    ( 4784): Error opening database: android.database.sqlite.SQLiteException: Database open failed
W/GAv4    ( 4784): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/GAv4    ( 4784): Failed to commit local dispatch transaction: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4784): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4    ( 4784): Sync local dispatch failed: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/GAv4    ( 4784): Error opening database: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
W/Documents( 4767): Failed to load some roots from com.google.android.apps.docs.storage: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/Documents( 4767): Update found 6 roots in 914ms
,E/GAv4    ( 4784): syncDispatchLocalHits failed: java.util.concurrent.ExecutionException: android.database.sqlite.SQLiteException: Database open failed
E/SharedPreferencesImpl( 4784): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/CAKEMIX_CRASHED( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/CAKEMIX_CRASHED( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/CAKEMIX_CRASHED( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/CAKEMIX_CRASHED( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/CAKEMIX_CRASHED( 4784): 	at aev.getWritableDatabase(PG:238)
E/CAKEMIX_CRASHED( 4784): 	at ael.a(PG:1521)
E/CAKEMIX_CRASHED( 4784): 	at hix$a.a(PG:125)
E/CAKEMIX_CRASHED( 4784): 	at aen.run(PG:536),
,E/SQLiteDatabase( 4784): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4784): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 4784): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
E/SQLiteDatabase( 4784): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4784): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4784): 	at aev.getWritableDatabase(PG:238)
E/SQLiteDatabase( 4784): 	at ael.a(PG:1521)
E/SQLiteDatabase( 4784): 	at hix$a.a(PG:125)
E/SQLiteDatabase( 4784): 	at aej.c(PG:139)
E/SQLiteDatabase( 4784): 	at aej.a(PG:358)
E/SQLiteDatabase( 4784): 	at aej.a(PG:345)
E/SQLiteDatabase( 4784): 	at agf.c(PG:884)
E/SQLiteDatabase( 4784): 	at aii.doInBackground(PG:1063)
E/SQLiteDatabase( 4784): 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4784): 	,at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4784): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4784): 	at java.lang.Thread.run(Thread.java:818)
I/ActivityManager(  820): START u0 {act=android.intent.action.BUG_REPORT flg=0x10000000 cmp=com.google.android.apps.docs/.app.ErrorNotificationActivity (has extras)} from uid 10046 on display 0
,I/Process ( 4784): Sending signal. PID: 4784 SIG: 9
,W/InputDispatcher(  820): channel '1f6b1d97 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  820): channel '1f6b1d97 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  820): channel 'e260f6d com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  820): channel 'e260f6d com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,I/WindowState(  820): WIN DEATH: Window{e260f6d u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity},
,W/InputDispatcher(  820): Attempted to unregister already unregistered input channel 'e260f6d com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
I/ActivityManager(  820): Process com.google.android.apps.docs (pid 4784) has died
W/ActivityManager(  820): Force removing ActivityRecord{1d391c1d u0 com.google.android.apps.docs/.app.ErrorNotificationActivity t29}: app died, no saved state
,I/WindowState(  820): WIN DEATH: Window{1f6b1d97 u0 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity},
W/InputDispatcher(  820): Attempted to unregister already unregistered input channel '1f6b1d97 com.google.android.apps.docs/com.google.android.apps.docs.app.ErrorNotificationActivity (server)'
,E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
D/WifiService(  820): releaseWifiLockLocked: WifiLock{NlpWifiLock type=2 binder=android.os.BinderProxy@3d97691b}
,E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
,E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505),
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
,E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 1477): (8) statement aborts at 1: [BEGIN EXCLUSIVE;] attempt to write a readonly database
E/ClearcutLoggerIntentService( 1477): attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearcutLoggerIntentService( 1477): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.phenotype.service.a.f.a(SourceFile:102)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:540)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.clearcut.service.a.a(SourceFile:153)
E/ClearcutLoggerIntentService( 1477): 	at com.google.android.gms.common.service.g.run(SourceFile:178)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1477): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1477): 	at java.lang.Thread.run(Thread.java:818)
,I/ConfigService( 1477): onDestroy
,E/Search.SharedPreferencesProto( 4077): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,W/WindowManager(  820): App freeze timeout expired.
,E/QMI_FW  (  820): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660216595
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,E/QMI_FW  (  820): xport_send: Sendto failed for port 4608,
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 11, ind.status = -1660216595
,E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching ,
E/QMI_FW  (  820): xport_send: Sendto failed for port 4608
,E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_IzatApiV02(  820): E/virtual int izat_core::IzatApiV02::injectLocation(GpsExtLocation):857]: error! inject position failed
E/QMI_FW  (  820): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
E/LocSvc_ApiV02(  820): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
E/QMI_FW  (  820): xport_send: Sendto failed for port 4608
E/LocSvc_api_v02(  820): E/locClientSendReq:2446]: send_msg_sync error: -1
,E/LocSvc_ApiV02(  820): E/virtual loc_api_adapter_err LocApiV02::injectPosition(double, double, float):565]: error! status = eLOC_CLIENT_FAILURE_INTERNAL, inject_pos_ind.status = eQMI_LOC_SUCCESS_V02
I/qdhwcomposer(  261): handle_blank_event: dpy:0 panel power state: 0
E/kickstart(  870): ERROR: function: rx_data:288 Read/Write File descriptor returned error: No such device, error code -1
,E/kickstart(  870): ERROR: function: sahara_main:1143 Sahara protocol error
E/kickstart(  870): ERROR: function: main:268 Uploading  Image using Sahara protocol failed

```
